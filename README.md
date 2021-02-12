# wait-for-time
Delay with a promise.

```javascript
import wait from "wait-for-time";

async function someFunc() {
  console.log("waiting now...");
  await wait(5000); // time in milliseconds
  console.log("wait complete");
}
```
