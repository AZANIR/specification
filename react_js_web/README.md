
# React - JS Web



<style>
  .tabs {
    font-size: 0;
  }

  .tabs>input[type="radio"] {
    display: none;
  }

  .tabs>div {
    /* скрыть контент по умолчанию */
    display: none;
    border: 1px solid #e0e0e0;
    padding: 10px 15px;
    font-size: 16px;
  }

  /* отобразить контент, связанный с вабранной радиокнопкой (input type="radio") */
  #tab-btn-1:checked~#content-1,
  #tab-btn-2:checked~#content-2,
  #tab-btn-3:checked~#content-3,
  #tab-btn-4:checked~#content-4,
  #tab-btn-5:checked~#content-5,
  #tab-btn-6:checked~#content-6
  {
    display: block;
  }

  .tabs>label {
    display: inline-block;
    text-align: center;
    vertical-align: middle;
    user-select: none;
    background-color: #f5f5f5;
    border: 1px solid #e0e0e0;
    padding: 2px 8px;
    font-size: 16px;
    line-height: 1.5;
    transition: color 0.15s ease-in-out, background-color 0.15s ease-in-out;
    cursor: pointer;
    position: relative;
    top: 1px;
  }

  .tabs>label:not(:first-of-type) {
    border-left: none;
  }

  .tabs>input[type="radio"]:checked+label {
    background-color: #fff;
    border-bottom: 1px solid #fff;
  }
</style>

<div class="tabs">
  <input type="radio" name="tab-btn" id="tab-btn-1" value="" checked>
  <label for="tab-btn-1">CODING</label>
  <input type="radio" name="tab-btn" id="tab-btn-2" value="">
  <label for="tab-btn-2">DEVELOPMENT TESTING</label>
  <input type="radio" name="tab-btn" id="tab-btn-3" value="">
  <label for="tab-btn-3">DESIGN</label>
  <input type="radio" name="tab-btn" id="tab-btn-4" value="">
  <label for="tab-btn-4">INFRASTRUCTURE</label>
  <input type="radio" name="tab-btn" id="tab-btn-5" value="">
  <label for="tab-btn-5">ENGINEERING</label>
  <input type="radio" name="tab-btn" id="tab-btn-6" value="">
  <label for="tab-btn-6">EXPERTISE CONTRIBUTION</label>
  <div id="content-1">
    <h2>Language</h2>
    <span >Language competency refers to engineer's ability to use a programming language effectively. This includes skills and knowledge of the syntax and semantics of the language, as well as code debugging and good working experience with the language's features and capabilities.

Language:

- Main language API;
- Packages, libraries and API shipped directly with the language;
- Algorithms and data structure;
- Networking with the language;
- Debugging in language;
- Concurrency in language.</span>

<details><summary>Language</summary>
-----------------
<details><summary>TRAINEE FRONT-END ENGINEER</summary>
    <pre>
    <details><summary><i>Stores data into general composite data type</i></summary>
        <p>Knowledge Description</p><strong>Task Description</strong><p>In JavaScript, composite data types are represented by arrays, and Objects are the structures that allow us to operate on data collection depending on the requirements of the current task. The array is a sequence of elements that can be accessed by their position in the sequence (index). Objects are data structures that maintain a set of objects associated with key-value pairs.</p>
        <p><strong>Task Elements</strong></p><ul><li>Stores different data types into an array</li><li>Stores different data types into Object</li></ul><p><strong>Conceptual Knowledge</strong></p><ul><li>Difference between array and objects in Javascript</li><li>How to access elements in array and object</li><li>Different ways of creating arrays and objects</li></ul>
    </details>
    <details><summary><i>Stores, reuses and operates on language basic data types</i></summary>
        <p>Knowledge Description</p><strong>Task Description</strong><p>Primitive data types are usually implemented on the core of the language and are immutable. There are seven primitive data types: string, number, bigint, boolean, undefined, symbol, and null. First of all, primitive data types could be assigned to the variable for storage and usage of data however, more frequently, when building applications, just storing types like strings or numbers is not enough. There are multiple use cases to change, search and modify strings, do the mathematical operation with the number, make comparisons, etc.</p><p><strong>Task Elements</strong></p><p><strong>&#xFEFF;</strong></p><ul><li>Uses basic strings capability (character access, comparing)</li><li>Uses main string methods (e.g., length, slice, substring, substr)</li><li>Uses main number methods (e.g., toFixed, toString, valueOf)</li><li>Uses boolean based on use cases</li></ul><p><br></p><p><strong>Conceptual Knowledge</strong></p><ul><li>Creating string with String and new String</li><li>Main string prototype methods and when to use them</li><li>Main number specific operation and when to use them (Number.isNaN, isInteger, parseFloat, parseInt)</li><li>Why to use Symbol</li><li>The main use case for Null and Undefined</li><li>What are the main symbol static methods</li></ul>
    </details>
    <details><summary>Uses and maintains language operators and comments</summary>
        <p>Knowledge Description</p><strong>Task Description</strong><p>In JavaScript, operators allow to perform different operations on single or multiple data values to produce a required result, and this could include operations on primitive types, arithmetic, bitwise, logic, comparing and modifying data values. Comments are annotation lines used to bring additional clarity to the code (e.g., get implicit context or clarify intention), specify legal information (e.g., license), generate documentation, or be used for navigation (e.g., "TODO" comments). Also, in JavaScript, the comment's structure could be used to add specific commands such as `use strict`, remove or ignore the linters, and type checking rules.&nbsp;</p><p><strong>Task Elements</strong></p><ul><li>Uses number operators based on use cases (comparison, arithmetic, logical)</li><li>Uses string operators based on use cases (concatenate, comparison, logical)</li><li>Uses conditional and ternary operator</li><li>Creates javaScript comments (single line or multiple line)</li></ul><p><strong>&nbsp;Conceptual Knowledge</strong></p><ul><li>Main compound assignment operators (e.g. x = y, x += y, ….etc.)</li><li>Comparing data in JavaScript (e.g., equal or strict equal, greater and less than...etc.)</li><li>Use cases and how to apply different number operation(e.g., increment, decrement, unary)</li><li>Understanding applicability and scenarios for logical operators such as OR AND NOT&nbsp;</li><li>When to use ternary operators</li><li>Operator and use cases for `in` and `inctanceof`</li></ul>
    </details>
    <details><summary>Uses basic structures for storing and reusing information</summary>
        <p">Knowledge Description</p><strong>Task Description</strong><p>The main structure in JavaScript is variables and functions. Variables are a named data store offendedly defined by the specific keyword for storing and reusing basic data types, primitives, or compound types (Array and Objects). The functions are the main structure and the application's building blocks that allow working with OOP or functional approaches. Functions will enable the creation of highly reusable and scalable structures and provide namespace capability, creating constructors and classes.&nbsp;</p><p><strong>Task Elements</strong></p><ul><li>Uses variables for storing and reusing data (var, let and const)</li><li>Uses function for reusing logic (function, anonymous function, and arrow function)</li></ul><p><strong>Conceptual Knowledge</strong></p><ul><li>Difference between var, let and const</li><li>What is a concept of hoisting and why it’s important</li><li>Different scopes in JavaScript code</li><li>Difference between function, anonymous function, and arrow function</li></ul>
    </details>
    </pre>
</details>

---
<details><summary>JUNIOR FRONT-END ENGINEER</summary>
JUNIOR
</details>

---
<details><summary>MIDDLE FRONT-END ENGINEER</summary>
MIDDLE
</details>

---
<details><summary>SENIOR FRONT-END ENGINEER</summary>
SENIOR
</details>
-----------------
</details>
  </div>
  <div id="content-2">
    Содержимое 2...
  </div>
  <div id="content-3">
    Содержимое 3...
  </div>
  <div id="content-4">
    Содержимое 4...
  </div>
  <div id="content-5">
    Содержимое 5...
  </div>
  <div id="content-6">
    Содержимое 6...
  </div>
</div>