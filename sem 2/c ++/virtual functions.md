**Title: Rules of Virtual Function in C++**

---

## 1. Declaration Rules

1. **Declare virtual function using virtual keyword in base class**  
    A function must be declared with the `virtual` keyword in the base class to enable dynamic binding.
    
2. **Ensure function belongs to class and not static**  
    Virtual functions must be non-static member functions of a class.
    
3. **Allow overriding in derived class with identical signature**  
    Derived classes must use the same function name, return type, and parameters.
    

**Recall Chain:**  
**Declare → Ensure → Allow**

---

## 2. Invocation and Binding Rules

4. **Invoke virtual function through base class pointer reference**  
    Virtual functions are called using base class pointers or references.
    
5. **Resolve function call at runtime using dynamic binding**  
    The compiler delays binding until execution to select correct function.
    
6. **Select derived class function based on actual object type**  
    The function executed depends on the object type, not pointer type.
    

**Recall Chain:**  
**Invoke → Resolve → Select**

---

## 3. Constraints and Special Rules

7. **Avoid declaring constructors as virtual functions**  
    Constructors cannot be virtual because object creation is incomplete.
    
8. **Support virtual destructors for proper object cleanup**  
    Destructors should be virtual in base classes for safe deletion.
    
9. **Ensure pointer of base refers to derived object**  
    Runtime polymorphism works only when base pointer points to derived instance.
    

**Recall Chain:**  
**Avoid → Support → Ensure**

---

**Total Points: 9**


**Title: Virtual Function in C++ with Example**

---

## 1. Concept of Virtual Function

1. **Define virtual function as function resolved at runtime**  
    A virtual function is a member function whose call is resolved during runtime.
    
2. **Associate function execution with actual object type**  
    The function executed depends on the type of object, not the pointer.
    
3. **Establish role in enabling runtime polymorphism behavior**  
    Virtual functions support dynamic binding in object-oriented programming.
    

**Recall Chain:**  
**Define → Associate → Establish**

---

## 2. Working Mechanism

4. **Declare virtual function using virtual keyword in base class**  
    The base class function must be declared with the `virtual` keyword.
    
5. **Override function in derived class using same signature**  
    The derived class redefines the function with identical parameters.
    
6. **Invoke function using base class pointer reference**  
    A base class pointer calls the derived class function at runtime.
    

**Recall Chain:**  
**Declare → Override → Invoke**

---

## 3. Example of Virtual Function

7. **Create base and derived classes demonstrating virtual behavior**  
    Example:
    

```cpp
#include<iostream>
using namespace std;

class Base {
public:
  virtual void show() {
    cout << "Base class show\n";
  }
};

class Derived : public Base {
public:
  void show() {
    cout << "Derived class show\n";
  }
};
```

8. **Assign derived object to base class pointer reference**  
    Example:
    

```cpp
int main() {
  Base* b;
  Derived d;
  b = &d;
```

9. **Observe runtime call of derived class function**  
    Example:
    

```cpp
  b->show();  // Calls Derived version
  return 0;
}
```

**Recall Chain:**  
**Create → Assign → Observe**

---

**Total Points: 9**


**Title: Limitations of Virtual Functions in C++**

---

## 1. Performance and Execution Overhead

1. **Introduce runtime overhead due to dynamic binding mechanism**  
    Virtual functions are resolved at runtime, causing slight performance delay.
    
2. **Increase memory usage because of virtual table storage**  
    Each class with virtual functions maintains a vtable, consuming extra memory.
    
3. **Affect execution speed compared to compile-time binding**  
    Dynamic binding is slower than static binding used in normal functions.
    

**Recall Chain:**  
**Introduce → Increase → Affect**

---

## 2. Structural and Usage Constraints

4. **Restrict use of virtual functions in constructors context**  
    Constructors cannot be declared virtual as object initialization is incomplete.
    
5. **Limit usage with static functions and static binding cases**  
    Static member functions cannot be virtual.
    
6. **Require base class pointer for proper runtime polymorphism**  
    Virtual functions work effectively only with base class pointers or references.
    

**Recall Chain:**  
**Restrict → Limit → Require**

---

## 3. Design and Maintenance Issues

7. **Complicate program design due to indirect function calls**  
    Understanding flow becomes harder because calls are resolved at runtime.
    
8. **Reduce readability when excessive virtual functions are used**  
    Too many virtual functions can make code complex.
    
9. **Demand careful implementation to avoid unexpected behavior**  
    Incorrect use may lead to bugs like improper overriding or memory issues.
    

**Recall Chain:**  
**Complicate → Reduce → Demand**

---

**Total Points: 9**

**Title: Pure Virtual Function in C++**

---

## 1. Concept of Pure Virtual Function

1. **Define pure virtual function as function without implementation**  
    A pure virtual function is a virtual function that has no definition in the base class.
    
2. **Declare function using equals zero syntax notation**  
    It is declared by assigning `= 0` in the function declaration.
    
3. **Establish role in enforcing method implementation in derived classes**  
    Derived classes must provide implementation for the pure virtual function.
    

**Recall Chain:**  
**Define → Declare → Establish**

---

## 2. Working Mechanism

4. **Create abstract class containing at least one pure virtual function**  
    A class with a pure virtual function becomes an abstract class.
    
5. **Prevent instantiation of abstract class directly in program**  
    Objects of abstract classes cannot be created.
    
6. **Override function in derived class to provide implementation**  
    Derived classes must implement the function to become concrete classes.
    

**Recall Chain:**  
**Create → Prevent → Override**

---

## 3. Example of Pure Virtual Function

7. **Define base class with pure virtual function declaration**  
    Example:
    

```cpp
#include<iostream>
using namespace std;

class Shape {
public:
  virtual void draw() = 0;
};
```

8. **Implement function in derived class with definition**  
    Example:
    

```cpp
class Circle : public Shape {
public:
  void draw() {
    cout << "Drawing Circle\n";
  }
};
```

9. **Instantiate derived object and invoke implemented function**  
    Example:
    

```cpp
int main() {
  Circle c;
  c.draw();
  return 0;
}
```

**Recall Chain:**  
**Define → Implement → Instantiate**

---

**Total Points: 9**


**Title: “this Pointer” and “Abstract Class” in C++**

---

# 1. this Pointer

1. **Define this pointer as pointer to current object**  
    The `this` pointer is an implicit pointer that refers to the calling object of a member function.
    
2. **Access object members explicitly using this pointer**  
    It is used to access data members and member functions of the current object.
    
3. **Resolve ambiguity between local and member variables**  
    It helps distinguish between class variables and function parameters with same names.
    
4. **Return current object to enable method chaining**  
    It can be used to return the object itself for chaining operations.
    

**Recall Chain:**  
**Define → Access → Resolve → Return**

---

# 2. Abstract Class

5. **Define abstract class as class with pure virtual function**  
    An abstract class contains at least one pure virtual function.
    
6. **Prevent direct object creation of abstract class type**  
    Objects of abstract classes cannot be instantiated directly.
    
7. **Force derived classes to implement abstract methods**  
    Derived classes must define all pure virtual functions.
    
8. **Provide base framework for achieving runtime polymorphism**  
    Abstract classes act as a blueprint for derived classes.
    

**Recall Chain:**  
**Define → Prevent → Force → Provide**

---

**Total Points: 8**

**Title: Virtual Destructor in C++ with Example**

---

## 1. Concept of Virtual Destructor

1. **Define virtual destructor as destructor declared with virtual keyword**  
    A virtual destructor is a destructor defined using the `virtual` keyword in a base class.
    
2. **Associate destructor call with correct object type at runtime**  
    It ensures that the appropriate destructor is invoked based on the actual object type.
    
3. **Establish role in safe deletion through base class pointer**  
    It guarantees proper cleanup when deleting derived objects via base class pointers.
    

**Recall Chain:**  
**Define → Associate → Establish**

---

## 2. Working Mechanism

4. **Declare destructor virtual in base class definition**  
    The base class destructor must be declared as `virtual`.
    
5. **Invoke deletion using base class pointer reference**  
    Objects are deleted through a base class pointer.
    
6. **Execute derived then base destructor in correct order**  
    The derived class destructor runs first, followed by the base class destructor.
    

**Recall Chain:**  
**Declare → Invoke → Execute**

---

## 3. Example of Virtual Destructor

7. **Create base and derived classes with destructors defined**  
    Example:
    

```cpp
#include<iostream>
using namespace std;

class Base {
public:
  virtual ~Base() {
    cout << "Base Destructor\n";
  }
};

class Derived : public Base {
public:
  ~Derived() {
    cout << "Derived Destructor\n";
  }
};
```

8. **Assign derived object to base class pointer**  
    Example:
    

```cpp
int main() {
  Base* b = new Derived();
```

9. **Delete object to observe proper destructor execution order**  
    Example:
    

```cpp
  delete b;
  return 0;
}
```

**Recall Chain:**  
**Create → Assign → Observe**

---

**Total Points: 9**