```js
var request = require ('request')

request ({
	url: 'https://sites.google.com/view/free-rock-chip-repair-kent-wa/home',
	json: true
}, (error, response, body) => {
	!error && response.statusCode === 200
		? log (body)
		: log (error)
})
```
