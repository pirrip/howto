### debounce

어떤 내용을 입력하다가 특정시간동안 대기하고 있으면 마지막에 입력된 내용을 바탕으로 서버요청을 하는 방법
**lodash \_.debounce() 사용**

```js
function debounce(func, delay) {
	let indebound = null;
	return function (...args) {
		console.log(new Date(), func, indebound);
		if (indebound) {
			clearTimeout(indebound);
		}
		indebound = setTimeout(() => func(...args), delay);
	};
}
const run = debounce((val) => console.log(new Date(), val), 1000);
run(5);
setTimeout(function () {
	run(7);
}, 200);

run(9);
```

### throttle
