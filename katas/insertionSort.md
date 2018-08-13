# Insertion sort

### Task:
- watch this [video](https://www.youtube.com/watch?v=3k1R_90j6uc&list=PLxc4gS-_A5VDXUIOPkJkwQKYiT2T1t0I8&index=21) on insertion sort
- Implementation a function (`insertionSort(numbers)`) that takes in an array of numbers and returns an array of sorted numbers
- Example:
```js
const numbers = [2,4,3,1]
insertionSort(numbers) // should return [1,2,3,4]
```

### Bonus task:
- Implementation a function (`insertionSortByKey(array, keyToSortBy)`) that takes in an array of objects and a key by which sorting should be done, and returns an array of objects sorted by that key.
- Example:
```js
const people = [
  {
    name: "bob",
    age: 50
  },
  {
    name: "alice",
    age: 20
  },
  {
    name: "june",
    age: 35
  }
];

insertionSortByKey(people, "age");
/*
should return:
[
  {
    name: "alice",
    age: 20
  },
  {
    name: "june",
    age: 35
  }
  {
    name: "bob",
    age: 50
  },
];
*/
```
