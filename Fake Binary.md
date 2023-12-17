```js
/*
Description:

Given a string of digits, you should replace any digit below 5 with '0' and any digit 5 and above with '1'. Return the resulting string.

Note: input will never be an empty string
*/

function fakeBin(x){
  let Binary = ""
  for (let i = 0 ; i < x.length ; i++){
    if (Number(x[i]) < 5){
      Binary += 0
    }
    else {
      Binary += 1
    }
  }
return Binary
}
```