**Title: JSON and Its Grammar**

---

## 1. Concept of JSON

1. **Define JSON as lightweight data interchange format**  
    JSON (JavaScript Object Notation) is a text-based format used for storing and exchanging data between systems.
    
2. **Represent structured data using key-value pairs**  
    It organizes data in a structured form using objects and arrays, making it easy to read and write.
    
3. **Enable data exchange between client and server**  
    JSON is widely used in web applications to transmit data between client-side and server-side programs.
    

**Recall Chain:**  
**Define → Represent → Enable**

---

## 2. Grammar of JSON Data Format

4. **Specify objects using curly braces structure**  
    A JSON object is enclosed in `{}` and contains key-value pairs separated by commas.
    
5. **Declare arrays using square brackets notation**  
    A JSON array is enclosed in `[]` and stores an ordered list of values.
    
6. **Assign values using key colon value syntax**  
    Each key is a string followed by a colon `:` and its corresponding value.
    

**Recall Chain:**  
**Specify → Declare → Assign**

---

## 3. JSON Data Types and Rules

7. **Define allowed data types in JSON format**  
    JSON supports string, number, boolean, null, object, and array data types.
    
8. **Enforce double quotes for keys and strings**  
    All keys and string values must be enclosed in double quotes to maintain valid syntax.
    
9. **Restrict trailing commas and undefined values**  
    JSON does not allow trailing commas or undefined values, ensuring strict data structure.
    

**Recall Chain:**  
**Define → Enforce → Restrict**

---

**Total Points: 9**


**Title: JSON Object and Array Structures**

---

## 1. JSON Object Structure

1. **Define object as collection of key-value pairs**  
    A JSON object is an unordered set of key-value pairs enclosed within curly braces `{}`.
    
2. **Organize data using string keys with values**  
    Each key is a string followed by a colon `:` and mapped to a value such as string, number, or another object.
    
3. **Demonstrate object structure through example representation**  
    Example:
    

```json
{
  "name": "Rahul",
  "age": 20,
  "isStudent": true
}
```

**Recall Chain:**  
**Define → Organize → Demonstrate**

---

## 2. JSON Array Structure

4. **Define array as ordered list of values**  
    A JSON array is a collection of values arranged in a specific order and enclosed in square brackets `[]`.
    
5. **Store multiple elements separated by commas**  
    Values in an array can be of any valid JSON data type and are separated by commas.
    
6. **Illustrate array structure using example representation**  
    Example:
    

```json
["Apple", "Banana", "Mango"]
```

**Recall Chain:**  
**Define → Store → Illustrate**

---

## 3. Combined Object and Array Usage

7. **Embed arrays within objects for complex data**  
    JSON allows arrays to be used as values inside objects to represent grouped data.
    
8. **Nest objects inside arrays for structured records**  
    Arrays can contain multiple objects to represent collections of similar entities.
    
9. **Present combined structure through integrated example**  
    Example:
    

```json
{
  "students": [
    { "name": "Rahul", "age": 20 },
    { "name": "Amit", "age": 22 }
  ]
}
```

**Recall Chain:**  
**Embed → Nest → Present**

---

**Total Points: 9**

**Title: Values Supported by JSON**

---

## 1. Primitive Values in JSON

1. **Define string values using double-quoted text**  
    Strings in JSON are sequences of characters enclosed in double quotes, representing textual data.
    
2. **Represent numeric values without quotes or formatting**  
    Numbers include integers and floating-point values written without quotes.
    
3. **Express logical values using boolean literals**  
    Boolean values are represented as `true` or `false` to indicate logical states.
    

**Recall Chain:**  
**Define → Represent → Express**

---

## 2. Special Value in JSON

4. **Include null value to represent empty data**  
    The `null` value is used to indicate the absence of a value or an empty field.
    

**Recall Chain:**  
**Include**

---

## 3. Structured Values in JSON

5. **Define object values using key-value structure**  
    Objects are collections of key-value pairs enclosed in curly braces `{}`.
    
6. **Organize array values as ordered collections**  
    Arrays are ordered lists of values enclosed in square brackets `[]`.
    
7. **Combine structures to represent complex data forms**  
    Objects and arrays can be nested to create complex hierarchical data.
    

**Recall Chain:**  
**Define → Organize → Combine**

---

## 4. Syntax Rules for JSON Values

8. **Enforce double quotes for string representation**  
    All string values must be enclosed in double quotes to maintain valid JSON syntax.
    
9. **Restrict unsupported types like undefined or functions**  
    JSON does not support values such as `undefined`, functions, or comments.
    

**Recall Chain:**  
**Enforce → Restrict**

---

**Total Points: 9**


**Title: Escape Sequence Characters in JSON Strings**

---

## 1. Purpose of Escape Sequences

1. **Define escape sequences for special character representation**  
    Escape sequences in JSON are used to include special or non-printable characters within strings.
    
2. **Handle reserved characters without breaking syntax**  
    They allow characters like quotes and backslashes to be safely included in JSON strings.
    
3. **Ensure valid string formatting during data exchange**  
    Using escape sequences maintains proper JSON syntax and prevents parsing errors.
    

**Recall Chain:**  
**Define → Handle → Ensure**

---

## 2. Common Escape Sequence Characters

4. **Represent quotation mark using backslash quote sequence**  
    The `\"` escape sequence is used to include double quotes inside a JSON string.
    
5. **Include backslash character using double backslash sequence**  
    The `\\` escape sequence represents a single backslash character.
    
6. **Insert newline character using backslash n sequence**  
    The `\n` escape sequence is used to create a new line within a string.
    

**Recall Chain:**  
**Represent → Include → Insert**

---

## 3. Additional Escape Sequences

7. **Add tab space using backslash t sequence**  
    The `\t` escape sequence inserts a horizontal tab in the string.
    
8. **Embed carriage return using backslash r sequence**  
    The `\r` escape sequence represents a carriage return character.
    
9. **Encode unicode characters using backslash u notation**  
    The `\uXXXX` format is used to represent Unicode characters in hexadecimal form.
    

**Recall Chain:**  
**Add → Embed → Encode**

---

**Total Points: 9**


**Title: JSON Tokens with Examples**

---

## 1. Structural Tokens in JSON

1. **Define braces token for object representation**  
    Curly braces `{ }` are used to define JSON objects containing key-value pairs.  
    Example:
    

```json
{ "name": "Rahul" }
```

2. **Represent brackets token for array structure**  
    Square brackets `[ ]` are used to define JSON arrays containing ordered values.  
    Example:
    

```json
[1, 2, 3]
```

3. **Separate elements using comma delimiter token**  
    The comma `,` is used to separate key-value pairs in objects or elements in arrays.  
    Example:
    

```json
{ "name": "Rahul", "age": 20 }
```

**Recall Chain:**  
**Define → Represent → Separate**

---

## 2. Naming and Assignment Tokens

4. **Specify key strings using double quotes token**  
    Keys in JSON must be strings enclosed in double quotes.  
    Example:
    

```json
{ "city": "Mumbai" }
```

5. **Assign values using colon separator token**  
    The colon `:` separates a key from its corresponding value.  
    Example:
    

```json
{ "age": 25 }
```

6. **Combine key-value pairs for structured data**  
    Multiple key-value pairs together form structured JSON objects.  
    Example:
    

```json
{ "name": "Amit", "age": 22 }
```

**Recall Chain:**  
**Specify → Assign → Combine**

---

## 3. Value Tokens in JSON

7. **Define string token for textual values**  
    Strings represent text data enclosed in double quotes.  
    Example:
    

```json
{ "name": "John" }
```

8. **Represent number and boolean tokens appropriately**  
    Numbers and booleans (`true`, `false`) represent numeric and logical values.  
    Example:
    

```json
{ "age": 30, "isStudent": false }
```

9. **Include null token for empty value representation**  
    The `null` token represents the absence of a value.  
    Example:
    

```json
{ "middleName": null }
```

**Recall Chain:**  
**Define → Represent → Include**

---

**Total Points: 9**


**Title: Comparison Between JSON and XML**

---

## 1. Data Representation Approach

1. **Define JSON as lightweight key-value format**  
    JSON represents data using simple key-value pairs and arrays, making it concise and easy to read.
    
2. **Describe XML as tag-based markup language**  
    XML represents data using custom tags and nested elements, resulting in a more verbose structure.
    
3. **Differentiate compact representation with verbose tagging**  
    Thus, JSON is more compact, whereas XML requires more space due to opening and closing tags.
    

**Recall Chain:**  
**Define → Describe → Differentiate**

---

## 2. Syntax and Readability

4. **Highlight JSON syntax as simple and minimal**  
    JSON uses fewer symbols such as `{}`, `[]`, and `:` which makes it easier to understand.
    
5. **Explain XML syntax as structured but complex**  
    XML uses nested tags and attributes, increasing complexity in writing and reading.
    
6. **Contrast readability based on syntax simplicity**  
    Thus, JSON is more readable for developers, while XML is comparatively complex.
    

**Recall Chain:**  
**Highlight → Explain → Contrast**

---

## 3. Data Handling and Usage

7. **Support data exchange efficiently using JSON format**  
    JSON is widely used in web applications for fast data exchange between client and server.
    
8. **Utilize XML for document storage and configuration**  
    XML is commonly used for document representation, configuration files, and legacy systems.
    
9. **Relate modern usage preference with performance benefits**  
    Thus, JSON is preferred for web APIs due to speed, while XML is used where structured documents are needed.
    

**Recall Chain:**  
**Support → Utilize → Relate**

---

**Total Points: 9**

**Title: JSON Data Types**

---

## 1. Primitive Data Types

1. **Define string type using double-quoted characters**  
    A string in JSON is a sequence of characters enclosed in double quotes, used to represent textual data.
    
2. **Represent number type without quotes formatting**  
    Numbers include integers and floating-point values written without quotes.
    
3. **Express boolean type using true or false**  
    Boolean values represent logical states and are written as `true` or `false`.
    

**Recall Chain:**  
**Define → Represent → Express**

---

## 2. Special Data Type

4. **Include null type for absence of value**  
    The `null` type is used to represent an empty or missing value in JSON.
    

**Recall Chain:**  
**Include**

---

## 3. Structured Data Types

5. **Define object type using key-value pairs**  
    Objects are collections of key-value pairs enclosed within curly braces `{}`.
    
6. **Organize array type as ordered collection**  
    Arrays are ordered lists of values enclosed within square brackets `[]`.
    
7. **Combine structures for representing complex data**  
    Objects and arrays can be nested to represent hierarchical data structures.
    

**Recall Chain:**  
**Define → Organize → Combine**

---

## 4. Data Type Rules and Constraints

8. **Enforce strict syntax for valid JSON values**  
    All strings must use double quotes and follow strict formatting rules.
    
9. **Restrict unsupported types like functions and undefined**  
    JSON does not support functions, `undefined`, or comments, ensuring standardization.
    

**Recall Chain:**  
**Enforce → Restrict**

---

**Total Points: 9**

**Title: Creating a JSON Object and Google JSON Style Guidelines**

---

## 1. Creating a JSON Object

1. **Define JSON object using curly brace structure**  
    A JSON object is created using `{}` containing key-value pairs representing structured data.
    
2. **Assign values using key colon value format**  
    Each key is a string followed by a colon `:` and mapped to a valid JSON value.
    
3. **Construct object through practical example representation**  
    Example:
    

```json
{
  "name": "Rahul",
  "age": 21,
  "isStudent": true
}
```

**Recall Chain:**  
**Define → Assign → Construct**

---

## 2. Google JSON Style Guidelines

4. **Enforce meaningful and descriptive key naming conventions**  
    Keys should be clear, descriptive, and follow consistent naming such as camelCase.
    
5. **Maintain consistent structure and formatting practices**  
    Objects should follow a uniform structure with proper indentation and spacing for readability.
    
6. **Avoid unnecessary nesting and redundant data fields**  
    Deep nesting should be minimized to keep JSON simple and easy to parse.
    

**Recall Chain:**  
**Enforce → Maintain → Avoid**

---

## 3. Additional Best Practices

7. **Use standard data types for interoperability**  
    Only valid JSON data types like string, number, boolean, array, object, and null should be used.
    
8. **Ensure consistency in key usage across objects**  
    Similar objects should use the same keys to maintain uniformity.
    
9. **Validate JSON structure for correctness and parsing**  
    JSON data should be validated to ensure it follows proper syntax and avoids errors.
    

**Recall Chain:**  
**Use → Ensure → Validate**

---

**Total Points: 9**


**Title: Creating a JSON Object Using `stringify()` Method**

---

## 1. Concept of `stringify()` Method

1. **Define stringify() as object to JSON converter**  
    The `JSON.stringify()` method converts a JavaScript object into a JSON-formatted string.
    
2. **Transform structured data into transferable format**  
    It prepares data for transmission or storage by converting it into text form.
    
3. **Enable interoperability between systems using JSON**  
    The generated JSON string can be easily sent between client and server.
    

**Recall Chain:**  
**Define → Transform → Enable**

---

## 2. Process of Creating JSON Object

4. **Create JavaScript object with key-value pairs**  
    A normal JavaScript object is first defined with properties and values.
    
5. **Apply stringify() method to convert object**  
    The `JSON.stringify()` function is called on the object to generate a JSON string.
    
6. **Store or transmit converted JSON string data**  
    The resulting string can be stored in files or sent over a network.
    

**Recall Chain:**  
**Create → Apply → Store**

---

## 3. Example of stringify() Usage

7. **Construct object for conversion demonstration purpose**  
    A sample object is created with properties like name and age.
    
8. **Convert object into JSON string using method**  
    The `JSON.stringify()` method is applied to produce the JSON representation.
    
9. **Display resulting JSON string as output**  
    The output shows the object in valid JSON string format.
    

Example:

```javascript
let obj = {
  name: "Rahul",
  age: 21
};

let jsonString = JSON.stringify(obj);
console.log(jsonString);
```

**Recall Chain:**  
**Construct → Convert → Display**

---

**Total Points: 9**


**Title: Sending HTML Data to a JSON File**

---

## 1. Capturing Data from HTML

1. **Identify input elements using DOM selection methods**  
    HTML form elements are accessed using JavaScript methods like `getElementById()` or jQuery selectors.
    
2. **Extract user-entered values from form fields**  
    Values are retrieved from inputs such as text boxes using the `.value` property or `.val()` in jQuery.
    
3. **Organize extracted data into structured format**  
    The collected values are prepared for conversion into a structured object.
    

**Recall Chain:**  
**Identify → Extract → Organize**

---

## 2. Converting Data into JSON Format

4. **Create JavaScript object using collected values**  
    A JavaScript object is formed using key-value pairs representing the captured data.
    
5. **Apply stringify method to convert into JSON**  
    The `JSON.stringify()` method converts the object into a JSON string.
    
6. **Prepare JSON data for transmission or storage**  
    The generated JSON string becomes ready to be sent to a server or saved.
    

**Recall Chain:**  
**Create → Apply → Prepare**

---

## 3. Sending Data to Server (JSON File)

7. **Initiate AJAX request to server endpoint**  
    An AJAX call is used to send the JSON data to a server where it can be stored.
    
8. **Transmit JSON string using POST method request**  
    The JSON data is sent using HTTP POST to a backend script that writes to a file.
    
9. **Store received data into JSON file on server**  
    The server processes the request and saves the data into a `.json` file.
    

Example:

```javascript
let data = {
  name: $("#name").val(),
  age: $("#age").val()
};

$.ajax({
  url: "save.php",
  type: "POST",
  data: JSON.stringify(data),
  contentType: "application/json",
  success: function(response) {
    console.log("Data saved");
  }
});
```

**Recall Chain:**  
**Initiate → Transmit → Store**

---

**Total Points: 9**


**Title: Converting JSON String into JavaScript Object using `parse()`**

---

## 1. Concept of `parse()` Method

1. **Define parse() as JSON to object converter**  
    The `JSON.parse()` method converts a JSON-formatted string into a JavaScript object.
    
2. **Interpret string data into structured format**  
    It reads the JSON string and reconstructs it into usable JavaScript data structures.
    
3. **Enable programmatic access to parsed data**  
    After parsing, the data can be accessed and manipulated using object properties.
    

**Recall Chain:**  
**Define → Interpret → Enable**

---

## 2. Process of Conversion Using `parse()`

4. **Provide valid JSON string as input data**  
    A correctly formatted JSON string must be supplied to the `JSON.parse()` method.
    
5. **Apply parse() method to transform string**  
    The method processes the string and converts it into a JavaScript object.
    
6. **Store resulting object for further operations**  
    The returned object is stored in a variable for accessing its values.
    

**Recall Chain:**  
**Provide → Apply → Store**

---

## 3. Example of `parse()` Usage

7. **Construct JSON string for demonstration purpose**  
    A sample JSON string is created containing key-value pairs.
    
8. **Convert string into object using parse() method**  
    The `JSON.parse()` method is used to perform the conversion.
    
9. **Access object properties after successful parsing**  
    The parsed object allows direct access to its properties using dot notation.
    

Example:

```javascript
let jsonString = '{"name":"Rahul","age":21}';

let obj = JSON.parse(jsonString);

console.log(obj.name);
```

**Recall Chain:**  
**Construct → Convert → Access**

---

**Total Points: 9**


**Title: Persistence of JSON Objects**

---

## 1. Concept of Persistence

1. **Define persistence as long-term data storage mechanism**  
    Persistence of JSON objects refers to storing JSON data so it remains available beyond program execution.
    
2. **Retain data across sessions and application states**  
    It allows applications to preserve user data, settings, or records between different sessions.
    
3. **Ensure data availability for future retrieval operations**  
    Persistent storage enables JSON data to be accessed and reused whenever required.
    

**Recall Chain:**  
**Define → Retain → Ensure**

---

## 2. Methods of Persisting JSON Data

4. **Store JSON in localStorage for client-side persistence**  
    JSON data can be saved in browser localStorage after converting it into a string using `stringify()`.
    
5. **Save JSON data in files on server-side systems**  
    JSON objects can be written into `.json` files on the server for permanent storage.
    
6. **Insert JSON into databases for structured storage**  
    Databases can store JSON data either as text or native JSON types for efficient querying.
    

**Recall Chain:**  
**Store → Save → Insert**

---

## 3. Retrieval and Maintenance of JSON Data

7. **Retrieve stored JSON using appropriate access methods**  
    Data can be fetched from storage and converted back into objects using `parse()`.
    
8. **Update persistent data by modifying stored values**  
    Existing JSON data can be edited and re-saved to reflect changes.
    
9. **Maintain consistency through validation and synchronization**  
    Proper validation ensures data integrity while synchronization keeps stored data updated.
    

**Recall Chain:**  
**Retrieve → Update → Maintain**

---

**Total Points: 9**


**Title: HTTP Cookie and Its Creation**

---

## 1. Concept of HTTP Cookie

1. **Define HTTP cookie as client-side data storage**  
    An HTTP cookie is a small piece of data stored in the user's browser by a web server.
    
2. **Store session information and user preferences**  
    Cookies hold data such as login status, user settings, and tracking information.
    
3. **Enable state management in stateless HTTP protocol**  
    Since HTTP is stateless, cookies help maintain user sessions across multiple requests.
    

**Recall Chain:**  
**Define → Store → Enable**

---

## 2. Creating an HTTP Cookie

4. **Set cookie using document.cookie property assignment**  
    A cookie is created in JavaScript by assigning a key-value pair to `document.cookie`.
    
5. **Specify attributes like expires and path values**  
    Attributes define the lifetime of the cookie and the scope where it is accessible.
    
6. **Demonstrate cookie creation using example syntax**  
    Example:
    

```javascript
document.cookie = "username=Rahul; expires=Tue, 19 Jan 2038 03:14:07 GMT; path=/";
```

**Recall Chain:**  
**Set → Specify → Demonstrate**

---

## 3. Working of HTTP Cookies

7. **Send cookies automatically with HTTP requests**  
    The browser sends stored cookies to the server with every relevant request.
    
8. **Identify users through stored cookie information**  
    Servers use cookies to recognize returning users and maintain sessions.
    
9. **Maintain communication continuity between client and server**  
    Thus, cookies ensure consistent interaction across multiple page requests.
    

**Recall Chain:**  
**Send → Identify → Maintain**

---

**Total Points: 9**


**Title: Interchanging JSON Data Across Platforms**

---

## 1. Standard Format for Interchange

1. **Define JSON as platform-independent data format**  
    JSON is a text-based format that can be used across different programming languages and systems.
    
2. **Ensure universal readability using simple syntax rules**  
    Its lightweight structure with key-value pairs makes it easy to parse on any platform.
    
3. **Enable seamless data exchange between heterogeneous systems**  
    Thus, JSON acts as a common language for communication across platforms.
    

**Recall Chain:**  
**Define → Ensure → Enable**

---

## 2. Data Transmission Mechanism

4. **Convert data into JSON string using serialization**  
    Objects are converted into JSON strings using methods like `JSON.stringify()`.
    
5. **Transmit JSON data via HTTP or APIs**  
    The JSON string is sent between client and server using HTTP requests such as GET or POST.
    
6. **Receive JSON data and reconstruct original structure**  
    The receiving system converts the JSON string back into usable data.
    

**Recall Chain:**  
**Convert → Transmit → Receive**

---

## 3. Data Parsing and Utilization

7. **Parse JSON string into native data structures**  
    Functions like `JSON.parse()` convert JSON into objects usable in the target language.
    
8. **Access and manipulate data using program logic**  
    The parsed data can be accessed, modified, or displayed as needed.
    
9. **Maintain compatibility using standard encoding formats**  
    Using UTF-8 encoding ensures consistent interpretation across platforms.
    

**Recall Chain:**  
**Parse → Access → Maintain**

---

**Total Points: 9**

**Title: Format of HTTP Protocol**

---

## 1. Structure of HTTP Request Message

1. **Define request line with method and resource path**  
    The request begins with a request line containing the HTTP method (GET, POST), URL, and protocol version.
    
2. **Include headers to convey client request information**  
    Headers provide additional details such as host, content type, user agent, and cookies.
    
3. **Attach optional body for sending client data**  
    The body carries data in methods like POST or PUT, such as form data or JSON.
    

**Recall Chain:**  
**Define → Include → Attach**

---

## 2. Structure of HTTP Response Message

4. **Specify status line with code and protocol version**  
    The response starts with a status line containing HTTP version, status code, and status message.
    
5. **Provide headers describing server response details**  
    Response headers include information like content type, content length, and server details.
    
6. **Deliver response body containing requested resource**  
    The body contains the actual content such as HTML, JSON, or images returned by the server.
    

**Recall Chain:**  
**Specify → Provide → Deliver**

---

## 3. Overall Message Flow in HTTP

7. **Initiate communication through client request transmission**  
    The client sends an HTTP request to the server to access a resource.
    
8. **Process request and generate appropriate response**  
    The server processes the request and prepares a corresponding response.
    
9. **Complete transaction by returning response to client**  
    The server sends back the response, completing the request-response cycle.
    

**Recall Chain:**  
**Initiate → Process → Complete**

---

**Total Points: 9**


**Title: Types of HTTP Headers**

---

## 1. General Headers

1. **Define general headers for request-response control**  
    General headers apply to both HTTP requests and responses and control overall message handling.
    
2. **Provide metadata independent of specific content**  
    They include information such as caching directives and connection management.
    
3. **Illustrate general headers through common examples**  
    Examples: `Cache-Control`, `Connection`, `Date`.
    

**Recall Chain:**  
**Define → Provide → Illustrate**

---

## 2. Request Headers

4. **Specify request headers for client information transfer**  
    Request headers are sent by the client to provide details about the request.
    
5. **Describe client environment and preferences explicitly**  
    They include browser type, accepted formats, and authentication details.
    
6. **Demonstrate request headers using practical examples**  
    Examples: `User-Agent`, `Accept`, `Authorization`.
    

**Recall Chain:**  
**Specify → Describe → Demonstrate**

---

## 3. Response Headers

7. **Define response headers for server information delivery**  
    Response headers are sent by the server to provide information about the response.
    
8. **Indicate server details and response characteristics**  
    They include server type, content type, and response date.
    
9. **Present response headers through example usage**  
    Examples: `Server`, `Content-Type`, `Set-Cookie`.
    

**Recall Chain:**  
**Define → Indicate → Present**

---

## 4. Entity Headers

10. **Introduce entity headers describing message body content**  
    Entity headers provide details about the body of the request or response.
    
11. **Explain content properties such as type and length**  
    They describe attributes like media type, size, and encoding.
    
12. **Exemplify entity headers with relevant fields**  
    Examples: `Content-Type`, `Content-Length`, `Content-Encoding`.
    

**Recall Chain:**  
**Introduce → Explain → Exemplify**

---

**Total Points: 12**


**Title: JSON HTML and Displaying JSON Data**

---

## 1. Concept of JSON HTML

1. **Define JSON HTML as JSON-driven content rendering**  
    JSON HTML refers to using JSON data to dynamically generate and display HTML content in a web page.
    
2. **Represent data separately from presentation layer**  
    JSON stores data while HTML is created dynamically using JavaScript based on that data.
    
3. **Enable dynamic web page updates without reloading**  
    This approach allows updating page content without refreshing the entire webpage.
    

**Recall Chain:**  
**Define → Represent → Enable**

---

## 2. Displaying JSON Data into Web Page

4. **Retrieve JSON data using AJAX or fetch method**  
    JSON data is obtained from a server or local source using asynchronous requests.
    
5. **Parse JSON string into JavaScript object format**  
    The `JSON.parse()` method converts the JSON string into a usable object.
    
6. **Insert parsed data into HTML using DOM methods**  
    The data is displayed using methods like `innerHTML` or jQuery DOM manipulation.
    

Example:

```javascript
fetch("data.json")
  .then(response => response.json())
  .then(data => {
    document.getElementById("demo").innerHTML = data.name;
  });
```

**Recall Chain:**  
**Retrieve → Parse → Insert**

---

## 3. Converting HTML Data into JSON (Vice Versa)

7. **Capture user input from HTML form elements**  
    Values are taken from input fields using JavaScript or jQuery methods.
    
8. **Convert collected data into JSON string format**  
    A JavaScript object is created and converted using `JSON.stringify()`.
    
9. **Send JSON data to server for processing**  
    The JSON string is transmitted via AJAX or form submission for storage or processing.
    

Example:

```javascript
let obj = {
  name: document.getElementById("name").value
};

let jsonData = JSON.stringify(obj);
console.log(jsonData);
```

**Recall Chain:**  
**Capture → Convert → Send**

---

**Total Points: 9**


**Title: JSONP and Displaying PHP Data on Web Page**

---

## 1. Concept of JSONP

1. **Define JSONP as cross-domain data retrieval technique**  
    JSONP (JSON with Padding) is a method used to request data from a server in a different domain.
    
2. **Bypass same-origin policy using script tag loading**  
    It works by dynamically creating a `<script>` tag that fetches data from another domain.
    
3. **Wrap JSON response inside callback function**  
    The server returns data wrapped in a function call, which executes when loaded.
    

Example:

```javascript
function handleData(data) {
  console.log(data);
}
```

Server response:

```javascript
handleData({ "name": "Rahul" });
```

**Recall Chain:**  
**Define → Bypass → Wrap**

---

## 2. Displaying PHP Data on Web Page

4. **Generate data in PHP using server-side script**  
    PHP creates data, often in JSON format, using functions like `json_encode()`.
    
5. **Send JSON data from server to client**  
    The PHP script outputs JSON data which can be accessed via HTTP request.
    
6. **Retrieve PHP data using AJAX or fetch method**  
    JavaScript requests the PHP file to obtain the generated data.
    

Example (PHP):

```php
<?php
$data = array("name" => "Rahul", "age" => 21);
echo json_encode($data);
?>
```

**Recall Chain:**  
**Generate → Send → Retrieve**

---

## 3. Displaying Data in Web Page

7. **Parse received JSON data into JavaScript object**  
    The response is converted into a usable object using `JSON.parse()` or automatic parsing.
    
8. **Access object properties for content extraction**  
    Individual values are accessed using dot notation.
    
9. **Insert data into HTML using DOM manipulation**  
    The extracted data is displayed using methods like `innerHTML`.
    

Example:

```javascript
fetch("data.php")
  .then(res => res.json())
  .then(data => {
    document.getElementById("demo").innerHTML = data.name;
  });
```

**Recall Chain:**  
**Parse → Access → Insert**

---

**Total Points: 9**

