At Whatfix, we aim to replicate the DOM structure of a third-party website in our graph database. To achieve this, we have a global click listener attached to the document. Whenever a user clicks on an element, we capture the clicked element. Our goal is to explore the surrounding DOM structure relative to the clicked element and store this data in our graph database.

Write a function that takes an element and a threshold as inputs and returns an array of all elements that are exactly the specified threshold levels away from the clicked element in the DOM hierarchy.

![dom](./assets/image_2.png)

```js
const exploreOut = (element, threshold) => {
	return [];
};
```
