### promise

```js
const asyncTest = async () => {
	const result = await new Promise((resolve, reject) => {
		setTimeout(() => {
			console.log("before resolve");
			resolve(3 + 5);
		}, 100);
	});

	console.log("after result resolve", result);
	return result;
};
const result = asyncTest();
console.log("after function", result);
```
