**Title: jQuery and Its Key Features**

---

## 1. Concept of jQuery

1. **Define jQuery as lightweight JavaScript library**  
    jQuery is a fast and lightweight JavaScript library designed to simplify HTML document traversal, event handling, and animation.
    
2. **Simplify complex JavaScript operations using abstraction**  
    It reduces the need for writing lengthy JavaScript code by providing easy-to-use methods and functions.
    
3. **Enable cross-browser compatible scripting easily**  
    jQuery ensures that code works consistently across different web browsers without additional effort.
    

**Recall Chain:**  
**Define → Simplify → Enable**

---

## 2. Key Features of jQuery

4. **Provide concise syntax for DOM manipulation**  
    jQuery uses short and simple syntax to select and modify HTML elements, making code more readable and efficient.
    
5. **Support powerful event handling mechanisms**  
    It offers methods to easily handle events such as clicks, key presses, and mouse actions.
    
6. **Enable dynamic effects and animations support**  
    jQuery provides built-in functions for animations like fading, sliding, and toggling elements.
    

**Recall Chain:**  
**Provide → Support → Enable**

---

## 3. Advanced Capabilities of jQuery

7. **Facilitate AJAX operations for asynchronous communication**  
    jQuery simplifies AJAX calls, allowing data exchange with servers without reloading the page.
    
8. **Offer cross-browser compatibility without extra coding**  
    It handles browser differences internally, ensuring consistent behavior across platforms.
    
9. **Extend functionality through plugins and utilities**  
    jQuery supports plugins that add additional features and enhance development efficiency.
    

**Recall Chain:**  
**Facilitate → Offer → Extend**

---

**Total Points: 9**


**Title: Adding jQuery into a Web Page**

---

## 1. Adding jQuery Using CDN (Content Delivery Network)

1. **Include jQuery via external CDN link source**  
    jQuery can be added by linking to a hosted version using a CDN in the HTML file.
    
2. **Load library directly from remote server**  
    The browser fetches jQuery from an online server, reducing load time and improving performance.
    
3. **Demonstrate CDN integration through script example**  
    Example:
    

```html
<script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>
```

**Recall Chain:**  
**Include → Load → Demonstrate**

---

## 2. Adding jQuery Using Local File

4. **Download jQuery file for local usage**  
    The jQuery library can be downloaded and stored within the project directory.
    
5. **Reference local file through script tag path**  
    The downloaded file is linked using the `<script>` tag with its relative path.
    
6. **Illustrate local integration using example code**  
    Example:
    

```html
<script src="js/jquery-3.6.0.min.js"></script>
```

**Recall Chain:**  
**Download → Reference → Illustrate**

---

## 3. Adding jQuery Using Package Managers (Advanced)

7. **Install jQuery using package manager tools**  
    jQuery can be installed using tools like npm or yarn in modern development environments.
    
8. **Manage dependencies within project environment**  
    The library becomes part of the project dependencies and is managed automatically.
    
9. **Show installation and usage through example commands**  
    Example:
    

```bash
npm install jquery
```

**Recall Chain:**  
**Install → Manage → Show**

---

**Total Points: 9**


**Title: Comparison of jQuery Traversal Methods**

---

## 1. `parent()` vs `parents()`

1. **Select immediate parent using parent() method**  
    The `parent()` method retrieves only the direct parent element of the selected element.
    
2. **Traverse all ancestors using parents() method**  
    The `parents()` method moves upward through all ancestor elements up to the root.
    
3. **Differentiate single-level access with multi-level traversal**  
    Thus, `parent()` returns one level up, while `parents()` returns multiple ancestor levels.
    

**Recall Chain:**  
**Select → Traverse → Differentiate**

---

## 2. `children()` vs `find()`

4. **Retrieve direct child elements using children() method**  
    The `children()` method selects only the immediate child elements of the selected element.
    
5. **Search all descendant elements using find() method**  
    The `find()` method selects all matching descendants at any depth within the element.
    
6. **Contrast immediate selection with deep-level searching**  
    Thus, `children()` works one level down, while `find()` searches through all nested levels.
    

**Recall Chain:**  
**Retrieve → Search → Contrast**

---

## 3. `next()` vs `nextAll()`

7. **Access next sibling element using next() method**  
    The `next()` method selects only the immediately following sibling of the selected element.
    
8. **Collect all following siblings using nextAll() method**  
    The `nextAll()` method selects all subsequent sibling elements after the selected element.
    
9. **Relate single sibling access with multiple sibling retrieval**  
    Thus, `next()` returns one next element, while `nextAll()` returns all next siblings.
    

**Recall Chain:**  
**Access → Collect → Relate**

---

**Total Points: 9**


**Title: jQuery Selectors**

---

## 1. Concept of jQuery Selectors

1. **Define selectors as element targeting expressions**  
    jQuery selectors are used to select and access HTML elements based on their attributes, types, or relationships.
    
2. **Identify elements within DOM using patterns**  
    They use CSS-style syntax to locate elements efficiently within the document structure.
    
3. **Enable manipulation of selected elements dynamically**  
    Once selected, elements can be modified, styled, or used for event handling.
    

**Recall Chain:**  
**Define → Identify → Enable**

---

## 2. ID Selector in jQuery

4. **Select unique element using hash ID selector**  
    The ID selector uses `#id` to select a single element with a specific unique identifier.
    
5. **Access element directly for precise manipulation**  
    Since IDs are unique, this selector targets only one element in the DOM.
    
6. **Demonstrate ID selection through example code**  
    Example:
    

```javascript
$("#title").hide();
```

This hides the element with id **title**.

**Recall Chain:**  
**Select → Access → Demonstrate**

---

## 3. Class Selector in jQuery

7. **Target grouped elements using dot class selector**  
    The class selector uses `.class` to select all elements sharing the same class name.
    
8. **Retrieve multiple elements for collective operations**  
    It allows applying changes to multiple elements simultaneously.
    
9. **Illustrate class selection using practical example**  
    Example:
    

```javascript
$(".menu").css("color", "red");
```

This changes the text color of all elements with class **menu**.

**Recall Chain:**  
**Target → Retrieve → Illustrate**

---

**Total Points: 9**


**Title: Event Handling in jQuery**

---

## 1. Concept of Event Handling

1. **Define event handling as response mechanism**  
    Event handling is the process of detecting user or browser actions and executing corresponding functions.
    
2. **Recognize events as triggers for interaction logic**  
    Events such as clicks, key presses, and mouse movements initiate program execution.
    
3. **Enable dynamic behavior through programmed responses**  
    Event handling allows web pages to respond interactively to user actions.
    

**Recall Chain:**  
**Define → Recognize → Enable**

---

## 2. Process of jQuery Event Handling

4. **Select target element using jQuery selector syntax**  
    The element on which the event will occur is first selected using jQuery selectors.
    
5. **Attach event method to selected element**  
    An event method such as `click()`, `dblclick()`, or `hover()` is used to bind the event.
    
6. **Execute callback function when event occurs**  
    A function is defined that runs automatically when the specified event is triggered.
    

**Recall Chain:**  
**Select → Attach → Execute**

---

## 3. Example of jQuery Event Handling

7. **Illustrate event binding using click method example**  
    A click event can be attached to a button using jQuery.
    
8. **Define function to perform action on event**  
    The function specifies what action should occur when the button is clicked.
    
9. **Demonstrate complete event handling code snippet**  
    Example:
    

```javascript
$(document).ready(function() {
  $("#btn").click(function() {
    alert("Button clicked");
  });
});
```

**Recall Chain:**  
**Illustrate → Define → Demonstrate**

---

**Total Points: 9**

**Title: Question 6**

```javascript
$(document).ready(function(){
  // Task 1: Hide paragraphs on button click
  $("button").click(function(){
    $("p").hide();
  });

  // Task 2: Toggle div visibility on link click
  $("a").click(function(event){
    event.preventDefault(); // Prevent default link behavior
    $("#content").toggle();
  });

  // Task 3: Add class to specific elements
  $(".important").addClass("highlight");
});
```


**Title: Question 7**

```javascript
$(document).ready(function(){
  $("#animateBtn").click(function(){
    // Sequentially animate width, height, and opacity
    $("#box")
      .animate({ width: "300px" }, 1000)
      .animate({ height: "200px" }, 1000)
      .animate({ opacity: "0.5" }, 1000);
  });
});
```


**Title: Question 8**

```javascript
$(document).ready(function() {
  $("#registrationForm").submit(function(event) {
    let isValid = true;
    $(".error-msg").remove(); // Clear previous errors

    // Validate empty text field
    if ($("#username").val().trim() === "") {
      $("#username").after('<span class="error-msg">Field cannot be empty</span>');
      isValid = false;
    }

    // Validate email format
    let emailReg = /^[^\s@]+@[^\s@]+\.[^\s@]+$/;
    if (!emailReg.test($("#email").val())) {
      $("#email").after('<span class="error-msg">Enter a valid email</span>');
      isValid = false;
    }

    // Prevent submission if invalid
    if (!isValid) {
      event.preventDefault();
    }
  });
});
```



**Title: Question 9**
```javascript
$(document).ready(function() {
  // 1. Define user data
  const userData = { name: "Alice Smith", role: "Lead Designer", email: "alice@example.com" };

  // 2. Function to render/update card
  function updateCard(data) {
    let template = $("#user-card-template").html();
    
    // Replace placeholders with data
    let rendered = template
      .replace(/{{name}}/g, data.name)
      .replace(/{{role}}/g, data.role)
      .replace(/{{email}}/g, data.email);
    
    $("#card-container").html(rendered);
  }

  // 3. Initial Render
  updateCard(userData);

  // 4. Hover Interactions (Event Delegation)
  $(document).on("mouseenter", ".user-card", function() {
    $(this).addClass("card-hover-active");
  }).on("mouseleave", ".user-card", function() {
    $(this).removeClass("card-hover-active");
  });
});
```



**Title: Question 10**
```javascript
$(document).ready(function() {
  let currentIndex = 0;
  const slides = $(".slide");
  const totalSlides = slides.length;

  // Initialize: Hide all slides and show the first one
  slides.hide().eq(currentIndex).show();

  // Next Button Logic
  $("#nextBtn").click(function() {
    slides.eq(currentIndex).fadeOut(500);
    currentIndex = (currentIndex + 1) % totalSlides; // Loop to start
    slides.eq(currentIndex).fadeIn(500);
  });

  // Previous Button Logic
  $("#prevBtn").click(function() {
    slides.eq(currentIndex).fadeOut(500);
    currentIndex = (currentIndex - 1 + totalSlides) % totalSlides; // Loop to end
    slides.eq(currentIndex).fadeIn(500);
  });
});
```


**Title: Creating a Custom jQuery Plugin for Text Highlighting**

---

## 1. Plugin Design Requirements

1. **Define plugin purpose for dynamic text highlighting**  
    The plugin is designed to search for a term within selected elements and highlight matching text.
    
2. **Specify configurable color option for flexibility**  
    It allows users to customize the highlight color through parameters passed to the plugin.
    
3. **Ensure chaining capability with jQuery methods**  
    The plugin must return the jQuery object to support chaining with other jQuery functions.
    

**Recall Chain:**  
**Define → Specify → Ensure**

---

## 2. Plugin Implementation Structure

4. **Extend jQuery prototype using fn method**  
    A custom plugin is created by extending `$.fn` so it can be used on jQuery-selected elements.
    
5. **Accept search term and color parameters**  
    The plugin function takes the search term and an optional color argument for customization.
    
6. **Iterate elements and apply highlighting logic**  
    Each selected element is processed to replace matching text with styled HTML.
    

**Recall Chain:**  
**Extend → Accept → Iterate**

---

## 3. Plugin Example Implementation

7. **Construct highlighting logic using regular expression**  
    A regular expression is used to find the search term within the element content.
    
8. **Apply style with customizable background color**  
    Matched text is wrapped in a `<span>` tag with inline style for the chosen highlight color.
    
9. **Return jQuery object to support chaining**  
    The plugin returns `this` to allow further jQuery methods to be chained.
    

Example:

```javascript
(function($) {
  $.fn.highlightText = function(term, color) {
    color = color || "yellow";
    return this.each(function() {
      let regex = new RegExp("(" + term + ")", "gi");
      let newText = $(this).html().replace(regex,
        '<span style="background-color:' + color + ';">$1</span>');
      $(this).html(newText);
    });
  };
})(jQuery);

// Usage
$("#content").highlightText("JavaScript", "lightgreen").fadeIn();
```

**Recall Chain:**  
**Construct → Apply → Return**

---

**Total Points: 9**



**Title: Using jQuery to Update DOM and Handle Errors**

---

## 1. Updating the DOM with Received Data

1. **Initiate data request using jQuery AJAX method**  
    jQuery uses methods like `$.ajax()` or `$.get()` to request data from a server asynchronously.
    
2. **Receive server response within success callback function**  
    The returned data is handled inside a success function once the request completes successfully.
    
3. **Inject received data into DOM elements dynamically**  
    The data is inserted into HTML elements using methods like `html()` or `text()`.
    

Example:

```javascript
$.ajax({
  url: "data.txt",
  success: function(response) {
    $("#content").html(response);
  }
});
```

**Recall Chain:**  
**Initiate → Receive → Inject**

---

## 2. Adding Error Handlers in jQuery

4. **Attach error callback within AJAX request configuration**  
    An error handler is defined to manage failures during the request process.
    
5. **Detect request failure and capture error details**  
    If the request fails, the error function receives information about the failure.
    
6. **Display error message or perform fallback action**  
    The application can show an alert or update the DOM with an error message.
    

Example:

```javascript
$.ajax({
  url: "data.txt",
  success: function(response) {
    $("#content").html(response);
  },
  error: function() {
    $("#content").html("Error loading data");
  }
});
```

**Recall Chain:**  
**Attach → Detect → Display**

---

**Total Points: 6**



**Title: Debugging Common jQuery Issues**

---

## 1. Click Event Not Working for Dynamically Added Element

1. **Identify direct binding failure on dynamic elements**  
    Using `$('#myButton').click()` fails because the element is added after the event binding occurs.
    
2. **Apply event delegation using on() method**  
    Event delegation attaches the handler to a parent element that exists at load time.
    
3. **Resolve issue by binding through parent selector**  
    Example:
    

```javascript
$(document).on("click", "#myButton", function() {
  alert("Button clicked");
});
```

**Recall Chain:**  
**Identify → Apply → Resolve**

---

## 2. Document Ready Firing Before Images Load

4. **Recognize ready() executes after DOM load only**  
    `$(document).ready()` runs when the DOM is ready, not when all resources like images are fully loaded.
    
5. **Switch to window load event for full loading**  
    The `$(window).on("load")` event ensures all images and resources are completely loaded.
    
6. **Fix timing issue using load event handler**  
    Example:
    

```javascript
$(window).on("load", function() {
  console.log("All resources loaded");
});
```

**Recall Chain:**  
**Recognize → Switch → Fix**

---

## 3. Animation Queue Causing Performance Issues

7. **Detect queue buildup due to repeated animations**  
    Multiple animations stack in the queue when triggered repeatedly, causing slow performance.
    
8. **Use stop() method to clear animation queue**  
    The `stop()` method halts current animations and prevents queue accumulation.
    
9. **Optimize animation execution with controlled calls**  
    Example:
    

```javascript
$("#box").stop(true, true).fadeIn();
```

**Recall Chain:**  
**Detect → Use → Optimize**

---

**Total Points: 9**

