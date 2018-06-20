## HOW TO USE
Given an HTML element that you want to scroll to like this:
```
<div id="someid"></div>
```

Add for instance a button, and call the function with parameters inside the onclick-property:
```
<button onclick="scrollToSmoothly('someid', 3000)">someText</button>
```

The number 3000 is the number of milliseconds it should take, the default is 2500, so calling it just as "scrollToSmoothly('someid)" works fine.

Remember to include the script in your head tag like this:
```
<head>
    <!-- ... other stuff ... -->
    <script type="text/javascript" src="someLocation/someOtherLocation/scrollToSmoothly.js"></script>
</head>
```

## OTHER STUFF
Inside the file you can also change the update rate, and you can replace the mathematical function at the bottom if you want different type of movement.
