# JavaScript Pattern

## Pattern 1
```javascript
let string = '';
for (let i = 1; i <= 5; i++) {
   for (let j = 1; j <= i; j++) {
      string += j;
   }
   string += '\n';
}
console.log(string);


output
1
12
123
1234
12345
```