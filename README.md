# @mimo-org/input

A simple, synchronous input function for Node to read from stdin, inspired by Python's `input()`.

## Installation

```bash
npm install @mimo-org/input
```

## Usage

```javascript
const input = require('@mimo-org/input');

const name = input('Enter your name: ');
console.log(`Hello, ${name}!`);
```
