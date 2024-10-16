# JavaScript Array Methods: map(), filter(), and reduce()

### 1. **`map()` Method**  
- Creates a **new array** by applying a function to every element in the original array.

```javascript
const numbers = [1, 2, 3, 4];
const squares = numbers.map(num => num * num);
console.log(squares); // Output: [1, 4, 9, 16]
