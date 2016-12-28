# Callback Function in Javascript

1. A callback function is a function that is passed to another function as a parameter.

2. The callback function is called (or executed) inside the another function.

3. Pass anonymous function(i.e. callback function) as a parameter to other functions or methods.

4. The callback function is not executed immediately. It is “called back” (hence the name) at some specified point inside the   containing function’s body.

5. The callback is a closure and as we know, closures have access to the containing function’s scope, so the callback function can access the containing    functions’ variables, and even the variables from the global scope.


Example:
```Javascript
  var friends = ["India", "UK", "USA", "Japan"];
	friends.forEach(function (MyName, Myindex){
	console.log(Myindex + 1 + ". " + MyName); // 1. India, 2. UK, 3. USA, 4. Japan
	});
  ```
