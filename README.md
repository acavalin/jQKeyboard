# jQKeyboard
jQKeyboard is a jQuery plugin that allow you to add a virtual keyboard to input
text field ([view demo](https://acavalin.github.io/jQKeyboard/)).

# Requirement
Include [jQuery](https://jquery.com) and `jQKeyboard.css` in the page.

# Usage

~~~javascript
// show keyboard on click on input field
// HTML: <input type="text" name="q" id="q" class="jQKeyboard">
$('input.jQKeyboard').initKeypad();

// show keyboard on click on button with target
// HTML: <input type="text" name="q" id="q">
//       <button class="jQKeyboardToggle" data-field="#q">Show Keyboard</button>
$('.jQKeyboardToggle').initKeypad();
~~~

# License
Licensed under MIT license.
* Initial version: copyright 2015, [Ho Poi Yee](https://github.com/poiyee/jQKeyboard)
* Responsive B/N screens version: copyright 2023, [acavalin](https://github.com/acavalin/jQKeyboard)
