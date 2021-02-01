### Tips

Try experimenting with the comparison operators (`<`, `>`, `===`, etc.) in the node REPL, which you can launch using the `node` command in Vagrant.

Work on your code iteratively – that means in small pieces. 

To help you figure out how to use `hungry` and `availableTime` inside your function, try outputting their values to the Terminal as follows.

```javascript
const whatToDoForLunch = function(hungry, availableTime) {
  if (availableTime < 20 && hungry) {
    console.log("Pick something up and eat it in the lab.");
  } else if (hungry && availableTime >= 20 && availableTime <= 30) {
    console.log("Try a place nearby");
  } else if (availableTime > 30 && hungry) {
    console.log("You're in bootcamp you don't have that much time");
  } else {
    console.log("Get back to work!");
  }
};
```