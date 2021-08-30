# What does map() return?  
+ It is a function to which map passes each element of given iterable.  
![img](https://res.cloudinary.com/practicaldev/image/fetch/s--IHKam6vP--/c_limit%2Cf_auto%2Cfl_progressive%2Cq_auto%2Cw_880/https://thepracticaldev.s3.amazonaws.com/i/cp0c15zovhapyiyq13zk.png)  
+ map() function returns a map object of the results after applying the given function to each item of a given iterable in JavaScript iterates through an array and calls a specified function for each of the items. Components in JSX are JS functions.  
For each object in the array, a block of JSX elements is returned.  
Also, data from the object is passed to each block using the JSX handlebars-like curly brackets.  
In the App() component of src/index.js iterate over the imported data


#### Data comes in all shapes and sizes. In JavaScript, an array is how we hold sets of data. For the majority of our site content, we use an array of objects.  
![img](https://i.stack.imgur.com/diYcf.png)  

# Each list item needs a unique key :  
+ When creating a list in the UI from an array with JSX, you should add a key prop to each child and to any of its’ children.  
React uses the key prop create a relationship between the component and the DOM element. The library uses this relationship to determine whether or not the component should be re-rendered.  

#### A key is a special string attribute you need to include when creating lists of elements in React. Keys are used to React to identify which items in the list are changed, updated, or deleted. In other words, we can say that keys are used to give an identity to the elements in the lists.  

![img](https://cmichel.io/static/8b84cc2f38f0ee541e61c9788149e14d/eb2af/react-keys-index.png)  

# Spread operator  
The Spread operator lets you expand an iterable like an object, string, or array into its elements while the Rest operator does the inverse by reducing a set of elements into one array.  
![img](https://media.geeksforgeeks.org/wp-content/uploads/20201221224416/Untitled.png)  

### Spread operator is useful for many different routine tasks in JavaScript, including the following:  
1) Copying an array.  
2) Concatenating or combining arrays.  
3) Using Math functions.  
4) Using an array as arguments.

## Spread operator to combine two arrays.
![img](https://res.cloudinary.com/practicaldev/image/fetch/s--0skPBBtw--/c_limit%2Cf_auto%2Cfl_progressive%2Cq_auto%2Cw_880/https://thepracticaldev.s3.amazonaws.com/i/r96nzfhwc13koyaexs8p.png)  

## Spread operator to add a new item to an array.
![img](https://miro.medium.com/max/1200/1*ck6Fs5k54T8Yv09D2dS0jA.png)  

## Spread operator to combine two objects into one.
![img](https://i.stack.imgur.com/Ghl0a.png)  






