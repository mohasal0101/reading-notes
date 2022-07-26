## [React Docs - lists and keys] (https://reactjs.org/docs/lists-and-keys.html)

1. takes an array of numbers and double their values.

2. The map() method is the most commonly used function to iterate over an array of data in JSX.

3. Id

4. “key” is a special string attribute you need to include when creating lists of elements in React. Keys are used to React to identify which items in the list are changed, updated, or deleted.




## [The Spread Operator](https://medium.com/coding-at-dawn/how-to-use-the-spread-operator-in-javascript-b9e4a8b06fab)

1. The spread operator allows us to quickly copy all or part of an existing array or object into another array or object

2. 

to compute new state without mutating state
to make shallow copies of JS objects.
Using Math functions.
Converting NodeList to an array.

3. two methods :-

const cars = ['🚗', '🚙'];
const trucks = ['🚚', '🚛'];

// Method 1: Concat
const combined1 = [].concat(cars, trucks);

// Method 2: Spread
const combined2 = [...cars, ...trucks];


4.

const array = ['🦊'];
// pushing item into the array :
array.push('🐴');
array.splice(array.length, 0, '🐴');
array[array.length] = '🐴';

// Result
// ['🦊', '🐴']

5. 

let person = { firstName: 'John',

lastName: 'Doe',};

let job = { jobTitle: 'JavaScript Developer',

location: 'USA' };

let employee = { ...person, ...job };
