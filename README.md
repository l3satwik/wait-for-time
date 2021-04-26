# wait-for-time
A npm utility package to delay execution with a promise.

Install:
```yarn add wait-for-time```

Use:
```javascript
import waitFor from "wait-for-time";

async function someFunc() {
  console.log("waiting now...");
  await waitFor(5000); // time in milliseconds
  console.log("wait complete");
}
```
