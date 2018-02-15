# isNullOrEmpty
Basic helper function which determines if something is null or empty

```
import isNullOrEmpty from 'isNullOrEmpty'

console.log(isNullOrEmpty('')) // true
console.log(isNullOrEmpty(null)) // true
console.log(isNullOrEmpty(undefined)) // true
console.log(isNullOrEmpty([])) // true
console.log(isNullOrEmpty('Example')) // false
```