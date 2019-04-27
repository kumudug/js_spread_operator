# js_spread_operator
Spread operator on arrays and objects

### Spread on object

```javascript
const person = {
  name: 'Max',
  age: 29,
  greet() {
    console.log('Hi, I am ' + this.name);
  }
};

const copiedPerson = { ...person };
```

### Spread on array

```javascript
const hobbies = ['Sports', 'Cooking'];

const copiedArray = [...hobbies];
```

### Rest operator [When you use thie syntax to merge items into an array]

```javascript
const toArray = (...args) => {
  return args;
};

console.log(toArray(1, 2, 3, 4));
```
