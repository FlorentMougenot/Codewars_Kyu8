```js
/*
Description:

Complete the solution so that it reverses the string passed into it.

'world'  =>  'dlrow'
'word'   =>  'drow'
*/

function solution(str){
  let reversedWord = ""
    for (let i = 0; i < str.length; i++) {
        reversedWord = str[i] + reversedWord;
    }
    return reversedWord;
}

```