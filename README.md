# array-methods

### A cheat sheet of array methods:

#### [To add/remove elements](https://javascript.info/array-methods#add-remove-items):
- push(...items) – adds items to the end,
- pop() – extracts an item from the end,
- shift() – extracts an item from the beginning,
- unshift(...items) – adds items to the beginning.
- [splice](https://javascript.info/array-methods#splice)(pos, deleteCount, ...items) – at index pos deletes deleteCount elements and inserts items.
- [slice](https://javascript.info/array-methods#slice)(start, end) – creates a new array, copies elements from index start till end (not inclusive) into it.
- [concat](https://javascript.info/array-methods#concat)(...items) – returns a new array: copies all members of the current one and adds items to it. If any of items is an array, then its elements are taken.

#### To search among elements:
- [indexOf/lastIndexOf](https://javascript.info/array-methods#indexof-lastindexof-and-includes)(item, pos) – look for item starting from position pos, return the index or -1 if not found.
- [includes](https://javascript.info/array-methods#indexof-lastindexof-and-includes)(value) – returns true if the array has value, otherwise false.
- [find/filter](https://javascript.info/array-methods#find-and-findindex-findlastindex)(func) – filter elements through the function, return first/all values that make it return true.
- findIndex is like find, but returns the index instead of a value.

#### To iterate over elements:
- forEach(func) – calls func for every element, does not return anything.
        
#### To transform the array:
- map(func) – creates a new array from results of calling func for every element.
- sort(func) – sorts the array in-place, then returns it.
- reverse() – reverses the array in-place, then returns it.
- split/join – convert a string to array and back.
- reduce/reduceRight(func, initial) – calculate a single value over the array by calling func for each element and passing an intermediate result between the calls.

#### Additionally:
- Array.isArray(value) checks value for being an array, if so returns true, otherwise false.

Please note that methods sort, reverse and splice modify the array itself.
