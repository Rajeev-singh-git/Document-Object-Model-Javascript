# Document-Object-Model-Javascript
 ## Explanation of DOM concept 
The Document Object Model (DOM) is a cross-platform and language-independent interface that treats an HTML or XML document as a tree structure wherein each node is an object representing a part of the document. The DOM represents a document with a logical tree.

In JavaScript, the DOM can be accessed using the `document` object. **The `document` object represents the entire HTML document, and it has properties and methods for accessing and manipulating the document's elements.**

Here are some examples of how to use the `document` object to access and manipulate the DOM:

- To get the title of the document, you can use the `document.title` property.
- To get all of the `<p>` elements in the document, you can use the `document.querySelectorAll('p')` method.
- To add a new `<div>` element to the document, you can use the `document.createElement('div')` method.
- To set the text content of a `<p>` element, you can use the `.textContent` property.

  ## DOM Tree Structure

  ![image](https://github.com/Rajeev-singh-git/Document-Object-Model-Javascript/assets/87664048/88bb214c-5647-4573-8ae3-5fff7d05781d)

## DOM ! = = JAVASCRIPT

![image](https://github.com/Rajeev-singh-git/Document-Object-Model-Javascript/assets/87664048/018689c9-9157-4b4e-b47b-64ec5be2d258)

## Handling Click Event

```javascript
 document.querySelector('.check').addEventListener('click', function () {
  const guess = Number(document.querySelector('.guess').value);
  console.log(guess, typeof guess);
});
```

The `addEventListener()` method takes three arguments:

1. The type of event to listen for. In this case, the event is a `click` event.
2. A function to run when the event occurs. This function will be passed an event object as its first argument.
3. A boolean value that indicates whether the event should be handled in the capturing phase or the bubbling phase. In this case, the event will be handled in the bubbling phase.
