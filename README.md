# interview-questions

## HTML

### What is DOCTYPE?

* A keyword that alerts the browser how to process a file
* alerts how to process a document i.e. which version of HTML is being used
* can be used to indicate quirks mode or standard mode
* in HTML 5 doctype is generally vestigial and serves to trigger standard mode by default
* https://en.wikipedia.org/wiki/Document_type_declaration

### What are optional HTML closing tags? Why are they useful?

### What is the data-* attribute?
* composed of a string with format "data-x" where x can be any string with no uppercase letters at least one character long
* stores custom data that is meant to be private on the page or application
* can embed custom data attributes into any HTML elements
* exchanges the data between html and the DOM
* allows regular html elements to become much more powerful by storing data that can be used by scripts
* saves time by minimizing backend interaction

### What is the difference between span and div?
* span is **inline** and usually used for small bits of HTML inside of one line
* div is **block-line** (aka has a break before and after) so is used for large chunks of code
* both should be used sparingly when meaningful tags are not available
* http://htmldog.com/guides/html/intermediate/spandiv/

### What is quirks mode?
* quirks mode allows old, unused, outdated versions etc. of browsers 

### What is ARIA?
* Aria - Accessible Rich Internet Applications - set of accessibility attributes added to HTML for people with disables
* uses **role** attribute 
* https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA

## CSS

### What is the difference between background and background-color
* background color can only impact the color of the background of the elemnt
* background is actually shorthand for all background properties, and using it you can style all aspects of the background at once
* however, usage wise if you expect to change just background color and inherit the rest of the background properties, color is desirable
* https://stackoverflow.com/questions/10205464/what-is-the-difference-between-background-and-background-color

## Javascript

### What is hoisting?
* 'pulls' function above where it is declared if it is called higher in the document
* a variable can be declared after it is used
* only applies to declarations not initilizations
* https://www.w3schools.com/js/js_hoisting.asp


