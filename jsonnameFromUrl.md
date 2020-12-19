```js
var request = require ('request')

request ({
	url: 'https://sites.google.com/view/onlinedatingtipsforwomen/8-steps-to-approach-a-woman-on-the-street',
	json: true
}, (error, response, body) => {
	!error && response.statusCode === 200
		? log (body)
		: log (error)
})
```
