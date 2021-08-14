# JavaScript Pattern

## Pattern 1
```javascript
let string = '';
for (let i = 1; i <= 5; i++) {
   for (let j = 1; j <= i; j++) {
      string += j+' ';
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

## Pattern 2
```JavaScript
let string = '';
for(i = 1; i <= 5; i++) {
   for(j = 1; j <= i; j++) {
      string += i 
   }
   string += '\n';
}
console.log(string);

output
1
22
333
4444
55555
```

## Pattern 3
```JavaScript
let string = '';
let counter = 1;
for(i = 1; i <= 4; i++) {
   for(j = 1; j <= i; j++) {
      string += counter;
      counter++;
   }
   string += '\n';
}
console.log(string);

output
1
23
456
78910
```