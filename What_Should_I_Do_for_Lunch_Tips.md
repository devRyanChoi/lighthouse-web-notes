### Tips

Try experimenting with the comparison operators (`<`, `>`, `===`, etc.) in the node REPL, which you can launch using the `node` command in Vagrant.

Work on your code iteratively – that means in small pieces. 

To help you figure out how to use `hungry` and `availableTime` inside your function, try outputting their values to the Terminal as follows.

```javascript
const whatToDoForLunch = function(hungry, availableTime) {
  let availableTime = "";
  if(hungry === true) {
    if (availableTime < 20) {
      console.log(`I'm hungry and I have +${availableTime} minutes for lunch.`)
      console.log("I don't know what to do!") 
    } else if (availableTime >= 20 && availableTime <30 ) {
      console.log(`I'm hungry and I have +${availableTime} minutes for lunch.`)
      console.log("I don't know what to do!") 
    } else if (availableTime > 30) {
      console.log(`I'm hungry and I have +${availableTime} minutes for lunch.`)
      console.log("I don't know what to do!") 
    }
  } else {
    console.log(`I'm not hungry and I have + ${availableTime} + minutes for lunch.`) 
    console.log("I don't know what to do!") 
  }  
}
```

