```js
function fetchData(name) {
  var obj = {
    "Aasir Valji":
      "I'm currently studying Software Engineering at Western University.",
  };
  return `Hey, my name is ${name}! ${obj[name]}`;
}

console.log(fetchData("Aasir Valji"));
```
