# Progress bar component

A simple component that draw a progress bar using native web components syntax - 
previous challenge refactored : ['ecmaloader']('https://github.com/GermanMtzmx/ecmaloader')



### How to call this dude 

```html
	<progress-bar-loader 
		data-stop="40"
		data-time="3"
		data-wait="1"
	>
		
	</progress-bar-loader>
```

## Meaning of attributes

**data-time** is the duration of animation in secs (if data-time is not supplied will take 5 secs)
**data-stop** is the percentaje at progres bar will stop and then load fast (if data-stop is not supplied will take 100%)
**data-wait** is the time in secs that should wait to complete the 100% (if data stop is not supplied will take 0 secs)


