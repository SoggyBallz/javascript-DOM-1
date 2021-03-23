# DOM Atomic 01: Show One Element

## Questions

---

> If you click the link to reveal more text and then refresh the page, does the text remain revealed, or is it hidden again? Why?

Its hidden, because the page resets and so does the code.

---

> Remove `window.addEventListener("load", function(){` (and the closing `})`) from **global.js**. Does the link still reveal the text? What is the purpose of this code that you've removed?

It doesn't reveal the text anymore. It loads all the code on to the webpage.

---

> Describe the the `addEventListener` method. (Remember that there is a specific, technical, methodical way to describe methods. Your reply should match that format.)

The addEventListener() method attaches an event handler to the specified element.
The addEventListener() method makes it easier to control how the event reacts to bubbling.
