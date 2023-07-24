# CLX
A high-level data-sorting library using complex algorithms.

# HOW TO USE
CLX is simple!
All you have to do is install the library:
```
npm install clx
```
Import the desired functions:
```javascript
const { // e.g. bubbleSort, mergeSort } = require('./clx')
// or
import { '', '' } from 'clx'
```

And your good to go! Otherwise, if your stil stuck, here is some example usage to help you grasp it.
'''javascript
// Import bubbleSort method
import bubbleSort from 'clx'

// Declare our array
const arr = [1, 3, 2, 5, 6, 8, 4, 9, 10, 7];

// Print our new sorted array!
console.log(bubbleSort(arr));
```
Output:
```
[
  1, 2, 3, 4,  5,
  6, 7, 8, 9, 10
]
```
