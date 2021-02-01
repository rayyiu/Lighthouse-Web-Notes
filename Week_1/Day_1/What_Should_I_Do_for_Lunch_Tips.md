### Tips

Try experimenting with the comparison operators (`<`, `>`, `===`, etc.) in the node REPL, which you can launch using the `node` command in Vagrant.

Work on your code iteratively – that means in small pieces. 

To help you figure out how to use `hungry` and `availableTime` inside your function, try outputting their values to the Terminal as follows.

```javascript 
function whatToDoForLunch (hungry, availableTime) {
    if (hungry) {
    if (availableTime < '20' && hungry === true) {
      return 'find something and eat it in the lab';
    } else if (availableTime >= 20 && availableTime <= 30) {
      return 'try a place nearby';
    } else if (availableTime > 30) {
      return 'think again';
    }
  } else {
    return 'get back to work';
  }
};
```
