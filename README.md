# Web-Dev
It contains HTML5 , Normal CSS, Normal JS complete


# HTML5, CSS & JavaScript Complete Course Syllabus

## Week 1: HTML5 Fundamentals

### Class 1 (Saturday) - HTML5 Basics (2.5 hours)
- HTML5 document structure and DOCTYPE declaration
- Document head: `<title>`, `<meta>`, `<link>`, `<style>`, `<script>`
- Semantic HTML5 elements: `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<aside>`, `<footer>`
- Text elements: `<h1>-<h6>`, `<p>`, `<span>`, `<div>`
- Text formatting: `<strong>`, `<em>`, `<mark>`, `<small>`, `<del>`, `<ins>`, `<sub>`, `<sup>`
- Lists: `<ul>`, `<ol>`, `<li>`, `<dl>`, `<dt>`, `<dd>`
- Links: `<a>` tag with href, target, title, download attributes
- Images: `<img>` with src, alt, width, height, loading attributes
- Comments in HTML
- HTML validation and best practices

### Class 2 (Sunday) - Advanced HTML5 Elements (2.5 hours)
- **Form Elements Complete:**
  - `<form>` with action, method, enctype, target attributes
  - `<input>` types: text, email, password, number, tel, url, search, date, time, datetime-local, month, week, color, range, file, hidden, checkbox, radio, submit, reset, button
  - `<textarea>` with cols, rows, placeholder, maxlength
  - `<select>`, `<option>`, `<optgroup>` for dropdowns
  - `<button>` types: submit, reset, button
  - `<label>` for accessibility
  - `<fieldset>` and `<legend>` for grouping
  - `<datalist>` for autocomplete suggestions
- **Form Attributes:**
  - Validation: required, pattern, min, max, step, minlength, maxlength
  - User experience: placeholder, autofocus, disabled, readonly
  - Form validation and error handling
- **Media Elements:**
  - `<audio>` with controls, autoplay, loop, muted, preload
  - `<video>` with controls, autoplay, loop, muted, poster, preload
  - `<source>` for multiple formats
  - `<track>` for subtitles and captions
- **Table Elements:**
  - `<table>`, `<caption>`, `<thead>`, `<tbody>`, `<tfoot>`
  - `<tr>`, `<th>`, `<td>` with colspan, rowspan
  - Table accessibility with scope attribute
- **Other Elements:**
  - `<canvas>` for graphics
  - `<svg>` for scalable vector graphics
  - `<iframe>` for embedding content
  - `<embed>`, `<object>` for plugins
- **Test:** HTML5 fundamentals and forms (30 min)

## Week 2: Advanced HTML5 & CSS Fundamentals

### Class 3 (Saturday) - HTML5 APIs & CSS Introduction (2.5 hours)
- **HTML5 Advanced Features:**
  - Custom data attributes (data-*)
  - Microdata and structured data basics
  - HTML5 APIs overview: Geolocation, Local Storage, Session Storage, Web Workers
  - Progressive web app basics: manifest.json, service workers introduction
- **Accessibility (A11Y):**
  - ARIA labels, roles, and properties
  - Alt text best practices
  - Keyboard navigation and focus management
  - Screen reader considerations
- **SEO and Meta Tags:**
  - Meta description, keywords, author
  - Open Graph tags for social media
  - Twitter Card tags
  - Viewport meta tag for responsive design
- **CSS Introduction:**
  - CSS syntax: selectors, properties, values
  - CSS integration: inline, internal, external stylesheets
  - CSS comments and organization
  - Cascade, specificity, and inheritance
  - CSS reset and normalize concepts

### Class 4 (Sunday) - CSS Fundamentals & Box Model (2.5 hours)
- **CSS Selectors Complete:**
  - Element, class, ID selectors
  - Attribute selectors: [attr], [attr=value], [attr~=value], [attr|=value]
  - Pseudo-classes: :hover, :focus, :active, :visited, :first-child, :last-child, :nth-child(), :not()
  - Pseudo-elements: ::before, ::after, ::first-line, ::first-letter
  - Combinators: descendant, child (>), adjacent sibling (+), general sibling (~)
- **CSS Box Model:**
  - Content, padding, border, margin
  - Box-sizing: content-box vs border-box
  - Margin collapsing
  - Border properties: width, style, color, radius
  - Padding and margin shorthand
- **Typography:**
  - Font properties: font-family, font-size, font-weight, font-style, font-variant
  - Text properties: color, text-align, text-decoration, text-transform, line-height, letter-spacing, word-spacing
  - Web fonts: Google Fonts, @font-face
- **Colors and Backgrounds:**
  - Color values: hex, rgb(), rgba(), hsl(), hsla(), named colors
  - Background properties: background-color, background-image, background-repeat, background-position, background-size, background-attachment
  - Linear and radial gradients
- **CSS Units:**
  - Absolute units: px, pt, pc, in, cm, mm
  - Relative units: em, rem, %, vh, vw, vmin, vmax, ch, ex
- **Test:** CSS selectors, box model, and typography (30 min)

## Week 3: Advanced CSS Layout & Effects

### Class 5 (Saturday) - CSS Layout Systems (2.5 hours)
- **Display Property:**
  - block, inline, inline-block, none
  - table, table-cell, table-row
  - Modern values: flex, grid, contents
- **CSS Positioning:**
  - Static, relative, absolute, fixed, sticky positioning
  - Top, right, bottom, left properties
  - Z-index and stacking contexts
- **Flexbox Complete:**
  - Flex container properties: display, flex-direction, flex-wrap, flex-flow, justify-content, align-items, align-content, gap
  - Flex item properties: order, flex-grow, flex-shrink, flex-basis, flex, align-self
  - Practical flexbox layouts and common patterns
- **CSS Grid Complete:**
  - Grid container properties: display, grid-template-columns, grid-template-rows, grid-template-areas, grid-template, grid-column-gap, grid-row-gap, grid-gap, justify-items, align-items, justify-content, align-content
  - Grid item properties: grid-column-start, grid-column-end, grid-column, grid-row-start, grid-row-end, grid-row, grid-area, justify-self, align-self
  - Grid functions: repeat(), minmax(), fit-content(), fr unit
  - Named grid lines and areas
- **Float and Clear (Legacy):**
  - Float: left, right, none
  - Clear: left, right, both, none
  - Clearfix techniques

### Class 6 (Sunday) - Advanced CSS Features & Animations (2.5 hours)
- **CSS Transforms:**
  - 2D transforms: translate(), rotate(), scale(), skew(), matrix()
  - 3D transforms: translate3d(), rotateX(), rotateY(), rotateZ(), perspective
  - Transform-origin property
- **CSS Transitions:**
  - Transition properties: transition-property, transition-duration, transition-timing-function, transition-delay
  - Transition shorthand
  - Timing functions: ease, linear, ease-in, ease-out, ease-in-out, cubic-bezier()
- **CSS Animations:**
  - @keyframes rule
  - Animation properties: animation-name, animation-duration, animation-timing-function, animation-delay, animation-iteration-count, animation-direction, animation-fill-mode, animation-play-state
  - Animation shorthand
  - Multiple animations
- **CSS Variables (Custom Properties):**
  - Defining variables with --property-name
  - Using variables with var() function
  - Variable scope and inheritance
  - Dynamic variables with JavaScript
- **Modern CSS Features:**
  - CSS functions: calc(), min(), max(), clamp()
  - Aspect-ratio property
  - CSS logical properties: margin-inline, padding-block, etc.
  - CSS containment and container queries basics
- **Responsive Design:**
  - Media queries: @media screen, print, all
  - Breakpoints and mobile-first design
  - Flexible images and media
  - Responsive typography with clamp()
- **CSS Preprocessors Introduction:**
  - Sass/SCSS basics: variables, nesting, mixins, functions
  - CSS methodology: BEM, OOCSS, SMACSS
- **Test:** Advanced CSS layout and animations (30 min)

## Week 4: JavaScript Complete Guide

### Class 7 (Saturday) - JavaScript Fundamentals (2.5 hours)
- **JavaScript Basics:**
  - JavaScript syntax and structure
  - Variables: var, let, const declarations
  - Data types: string, number, boolean, undefined, null, symbol, bigint
  - Type conversion and coercion
  - Operators: arithmetic, assignment, comparison, logical, bitwise, ternary
- **Control Structures:**
  - Conditional statements: if, else if, else, switch
  - Loops: for, while, do-while, for...in, for...of
  - Break and continue statements
  - Label statements
- **Functions:**
  - Function declarations vs expressions
  - Arrow functions and their differences
  - Parameters and arguments
  - Return statements
  - Function scope and hoisting
  - Callback functions
  - Higher-order functions
- **Objects and Arrays:**
  - Object creation: literal notation, constructor function, Object.create()
  - Object properties and methods
  - Property access: dot notation vs bracket notation
  - Object methods: Object.keys(), Object.values(), Object.entries()
  - Array creation and manipulation
  - Array methods: push(), pop(), shift(), unshift(), slice(), splice(), concat(), join()
  - Array iteration: forEach(), map(), filter(), reduce(), find(), some(), every()
- **DOM Manipulation Basics:**
  - Document object model understanding
  - Selecting elements: getElementById(), getElementsByClassName(), getElementsByTagName(), querySelector(), querySelectorAll()
  - Element properties: innerHTML, textContent, innerText
  - Attribute manipulation: getAttribute(), setAttribute(), removeAttribute()
  - Style manipulation: element.style property

### Class 8 (Sunday) - Advanced JavaScript & Complete Project (2.5 hours)
- **Advanced JavaScript Concepts:**
  - Scope and closures
  - The 'this' keyword and context
  - Prototypes and inheritance
  - Constructor functions and classes
  - Static methods and properties
- **Asynchronous JavaScript:**
  - Understanding synchronous vs asynchronous
  - Callback functions and callback hell
  - Promises: creation, chaining, error handling
  - Async/await syntax
  - Promise methods: Promise.all(), Promise.race(), Promise.allSettled()
- **DOM Events:**
  - Event handling: addEventListener(), removeEventListener()
  - Event object properties and methods
  - Event types: click, submit, load, resize, scroll, mouseover, keydown, etc.
  - Event delegation and bubbling/capturing
  - Preventing default behavior and event propagation
- **Browser APIs:**
  - Fetch API for HTTP requests
  - Local Storage and Session Storage
  - Geolocation API
  - History API
  - Console API for debugging
- **ES6+ Features:**
  - Template literals and string interpolation
  - Destructuring assignment (arrays and objects)
  - Spread operator and rest parameters
  - Default parameters
  - Modules: import/export statements
  - Classes and inheritance
  - Symbols and iterators
- **Error Handling:**
  - Try/catch/finally blocks
  - Throwing custom errors
  - Error types and debugging
- **Form Validation:**
  - Client-side validation with JavaScript
  - Custom validation functions
  - Real-time validation feedback
  - Form submission handling
- **JavaScript Best Practices:**
  - Code organization and structure
  - Naming conventions
  - Performance considerations
  - Memory management
  - Security considerations (XSS prevention)
- **Complete Project Development:**
  - Building a fully interactive web application
  - Combining HTML5 semantic structure
  - Advanced CSS styling with animations
  - Dynamic JavaScript functionality
  - Form validation and data handling
  - Local storage implementation
  - Responsive design implementation
  - Cross-browser compatibility testing
- **Final Test:** Comprehensive assessment covering HTML5, CSS, and JavaScript (30 min)

## Schedule Details

**Saturday Classes:**
- Class Time: 6:30 PM - 9:00 PM (2.5 hours per Saturday class)

**Sunday Classes:**
- Class Time: 6:30 PM - 9:00 PM (2.5 hours per Sunday class)
- Test Time: 9:00 PM - 9:30 PM (30 minutes maximum)

**Additional Requirements:**
- Code File Submission: At the end of every class
- Doubt Clear Session: Google Form provided for weekly questions
- Saturday Doubt Session: 6:00 PM to 6:30 PM (Starting from 2nd Week)

## Learning Outcomes

By the end of this course, students will be able to:
- Create semantic, accessible HTML5 documents
- Implement modern CSS layouts using Flexbox and Grid
- Build responsive, mobile-first websites
- Develop interactive web applications with JavaScript
- Handle asynchronous operations and API integration
- Implement form validation and user input handling
- Debug and optimize web applications
- Follow web development best practices and standards
