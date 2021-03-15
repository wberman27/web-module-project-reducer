# Understanding Questions:
1. What are the steps of execution from the pressing of the 1 button to the rendering of our updated value? List what part of the code excutes for each step.

* The user presses the 1 button.
...

* The onClick function is invoked.
* The handler takes in that event and invokes addOne with a value of 1. 
* The addOne function returns type ADD_ONE to the reducer via dispatch, 
* and the reducer adds one to the total.

...

* TotalDisplay shows the total plus 1.
