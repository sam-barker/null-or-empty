# null-or-empty
Basic helper function which determines if something is null or empty

```
import nullOrEmpty from 'null-or-empty'

console.log(nullOrEmpty('')) // true
console.log(nullOrEmpty(null)) // true
console.log(nullOrEmpty(undefined)) // true
console.log(nullOrEmpty([])) // true
console.log(nullOrEmpty('Example')) // false
```