Here at whatfix we want to recreate a 3rd party website's dom structure in our graph database.
We have a global click listener attached to the document.
Whenever a user clicks on an element, we get the element that was clicked on.
We want to explore the dom structure around the clicked element and store it in our graph database.

create a function that takes in an element and a threshold and returns an array of all the elements that are threshold levels deep from the clicked element.

![dom](./assets/image_2.png)

```js
const exploreOut = (element, threshold) => {
	return [];
};
```
