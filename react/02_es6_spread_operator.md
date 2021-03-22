### Spread Operator (전개 연산자)

**Array**

```js
const arr1 = [1, 2, 3];
const arr2 = [4, 5, 6];
// old way
const com = [].concat(arr1, arr2);
// spread operator
const arr = [...arr1, ...arr2];
```

**Object**

```js
const obj1 = { one: 1, two: 2, three: 3 };
const obj2 = { four: 4, five: 5, six: 6 };
// old way
const com = Object.assign({}, obj1, obj2);
// spread operator
const cc = {
	...obj1,
	...obj2,
};
```
