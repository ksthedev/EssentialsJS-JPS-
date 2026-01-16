## Changelog

### v.1.0.0


Compatible with: [JPS 1.2.0](https://github.com/ksthedev/JPS---JavaScript-Plugin-System/blob/main/JPS%20v.1.2.0.rar)


JPS-CLI: [1.0.0](https://github.com/ksthedev/JPS---JavaScript-Plugin-System/blob/main/JPS%20CLI%20v1.0%20for%20v1.2.rar)



```
c.log
c.warn
c.error
c.info

cap
clone
contains
cont
reverse
repeat
rpt

math
rndInt

last
rand
random
rnd
range
shu
uniq
unique

uuid
wait
sleep
```

### Example simple code:


```javascript
const { c, cap, repeat, rndInt, rnd } = require('./js-plugins/essentialsjs/all');

let numbers = [1, 2, 3, 4, 5, 6, "Sorte"]
let randomnumbers = rnd(numbers)

c.log("Hello World");
console.log(cap("hello"));
console.log(repeat("ha", 4, "\n"));
console.log(rndInt(1, 10));
c.log(randomnumbers)
```
