# week0.day0.variables

## Variable basics

### 1. Mastering syntax
- Create a file called `basics.js`. 
- In this file, define 3 variables: One should be of type String, another of type Number, and another of type Boolean.
- Print the values of these variables, each on its own line.
- Execute your JavaScript code using `node basics.js` on the command line to see whether everything works.

### 2. Fixing redundancy: StubHub

The following program has a lot of redundant calculations. Use variables to reduce the redundancy in the code.

```
// We bought some tickets to see SZA!
console.log('Face value: ' + (45 * 4 + 75 * 2));
// We're selling them for 50% more lol.
console.log('Selling price: ' + (45 * 4 + 75 * 2) * 1.5);
// But StubHub is charging a 20% seller fee...
console.log('Seller fee: ' + (45 * 4 + 75 * 2) * 1.5 * 0.2);
// So here's our total profit:
console.log('Total profit: ' + ((45 * 4 + 75 * 2) * 1.5  - (45 * 4 + 75 * 2) * 1.5 * 0.2 - (45 * 4 + 75 * 2)));
```

## Variable mysteries

### 1. Variable reassignment

What is the value of `x` after the following code executes?

```
let x = 10;
x = x + 2;
x = x + x;
```

### 2. Copying values

What are the values of `pizza` and `burger` after the following code executes?

```
let pizza = 5;
let burger = 10;
burger = pizza;
pizza = 10;
```

- A. `pizza` is 5; `burger` is 10
- B. `pizza` is 10; `burger` is 10
- C. `pizza` is 10; `burger` is 5
- D. `pizza` is 5; `burger` is 5

### 3. Operators

What are the values of `pizza` and `burger` after the following code executes?

```
let pizza = 5;
let burger = 10;
burger = pizza;
pizza++;
burger--;
pizza /= 2;
```

## Spot the bug

### 1. `const` practice: Anti-aging

Why doesn't this code work?

```
const age = 17;
// I just had my birthday!
age++;
```

### 2. Redeclarations: username

Where is the error in the following snippet of code?

```
const username = 'vrk';
let username = '';
```

### 3. Booleans: yes and no

Where is the error in the following snippet of code?

```
const yes = true;
let no = FALSE;
console.log('no');
```

## Bonuses

### Hard
- Maybe something w/ astral unicode (http://xem.github.io/golfing/#jstweet_en)

