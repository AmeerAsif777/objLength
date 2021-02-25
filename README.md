# objlength
<br />

>You might wonder, for knowing the length of array, we can do like

```
const a= [1,2,3,4]
console.log(a.length); // Returns length of a
```

>But for object, we can't do like the above way, and we have to suppose do like the below way

```
const a = {name: "ameer", age: 98}
Object.keys(a).length // Returns length of a
```

## To make it easy, follow the below way

```js
import objectLength from 'objlength';

let a = {name: "ameerr", age: 98}
console.log(objectLength(a)); //length of a
```