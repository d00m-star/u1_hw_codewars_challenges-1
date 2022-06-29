## Return Negative!

```js
function makeNegative(num) {
  return num > 0 ? -num : num
}
```

## Sum of Positive

```js
function positiveSum(arr) {
  let sum = 0
  for (i = 0; i < arr.length; i++) {
    if (arr[i] > 0) {
      sum += arr[i]
    }
  }
  return sum
}
```

## Function 2

```js
function square(num) {
  return num ** 2
}
```

## Sum Arrays

```js
function sum(numbers) {
  let total = 0
  for (i = 0; i < numbers.length; i++) {
    total += numbers[i]
  }
  return total
}
```

## Reversed Strings

```js
function solution(str) {
  let newStr = ''
  for (i = str.length - 1; i >= 0; i--) {
    newStr += str[i]
  }
  return newStr
}
```
