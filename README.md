# My FizzBuzz solution

```javascript
for (let i = 1; i <= 100; i++) {
              /* 
              Evaluates to either "Fizz", "Buzz" or an empty (falsy) 
              string 
              */
  console.log(((i % 5 === 0 ? "Fizz" : "") + (i % 3 === 0 ? "Buzz" : "")) || i);
}
```
