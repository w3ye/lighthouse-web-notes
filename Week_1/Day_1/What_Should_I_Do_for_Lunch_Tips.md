### Tips

Used Comparison operators in the node REPL, which you can launch using the `node` command.

Determine if `hungry` is `true` first, then output according to `availableTime`.

```javascript
const whatToDoForLunch = function(hungry, availableTime) {
  if (!hungry) console.log("Wait until you're hungry");
  if (hungry && availableTime < 20) {
    console.log("Pick something up and eat it back in the Lab");
  }
  if (hungry && (availableTime >= 20 && availableTime < 30)) {
    console.log("You deserve a break, you should try Gastown");
  }
  if (hungry && availableTime >= 30) {
    console.log("This is a bootcamp after all");
  }
```