---
Title: '.lastIndexOf()'
Description: 'Searches a string for a given value and returns the index of the last occurence if found. Returns -1 if not found.'
Subjects:
  - 'Web Development'
  - 'Computer Science'
Tags:
  - 'Strings'
  - 'Methods'
CatalogContent:
  - 'introduction-to-javascript'
  - 'paths/front-end-engineer-career-path'
---

Searches a string for a given value and returns the index of the last occurence if found. Returns `-1` if not found.

## Syntax

```js
string.lastIndexOf(value, startSearch);
```

- `value` is the value to search for in a string.
- `startSearch` (optional), indicates the index to start the search at. The default value is the string length.

## Examples

Find the last occurrence of a string:

```js
const baseballChant =
  'Hey batter, batter, batter, batter, batter! Swing, batter!';

const lastBatter = baseballChant.lastIndexOf('batter');

console.log(lastBatter);
// Output: 51
```

Use second parameter to start search later in string:

```js
const baseballChant =
  'Hey batter, batter, batter, batter, batter! Swing, batter!';

const latterBatter = baseballChant.lastIndexOf('batter', 18);

console.log(latterBatter);
// Output: 12
```

Return `-1` if not found:

```js
const people = ['Dominic', 'Marshawn', 'Alexis', 'Shannon'];

const didYouFindWaldo = people.lastIndexOf('Waldo');

console.log(didYouFindWaldo);
// Output: -1
```
