### Tips

Try experimenting with the comparison operators (`<`, `>`, `===`, etc.) in the node REPL, which you can launch using the `node` command in Vagrant.

Work on your code iteratively – that means in small pieces. 

To help you figure out how to use `hungry` and `availableTime` inside your function, try outputting their values to the Terminal as follows.


function whatToDoForLunch(hungry, availableTime) {
  console.log("hungry is", hungry);
  console.log("availableTime is", availableTime);
}


Is it possible to format and highlight it nicely like we are seeing here? Absolutely!

You may have noticed that in the 'Tips' text above, some of the words are wrapped by the backtick (`) character, which makes it look like this. In Markdown, the backtick formats text to look like code. It can be used inline like above, or to create a code block.

We can use backticks to designate a code block like so:

```javascript
function whatToDoForLunch(hungry, availableTime) {
  console.log("hungry is", hungry);
  console.log("availableTime is", availableTime);
}
```
