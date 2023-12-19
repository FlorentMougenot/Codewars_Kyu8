```js
/*
Description:

Write a function to split a string and convert it into an array of words.
Examples (Input ==> Output):

"Robin Singh" ==> ["Robin", "Singh"]

"I love arrays they are my favorite" ==> ["I", "love", "arrays", "they", "are", "my", "favorite"]
*/

function stringToArray(string){
  let str = ""
  let total = []
  for (i = 0 ; i < string.length; i++){
    if (string[i] !== " "){
     str = str + string[i] 
    }
    else{
      total.push(str)
      str = ""
    }
  }
total.push(str)
  return total
}
```