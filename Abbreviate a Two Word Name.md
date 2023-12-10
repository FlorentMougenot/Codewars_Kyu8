```js
/*
Description:

Write a function to convert a name into initials. This kata strictly takes two words with one space in between them.

The output should be two capital letters with a dot separating them.

It should look like this:

Sam Harris => S.H

patrick feeney => P.F
*/

function abbrevName(name){
let [firstName, lastName] = name.split(' ')
let firstInit = firstName.charAt(0).toUpperCase()
let lastInit = lastName.charAt(0).toUpperCase()
return firstInit + "." + lastInit
}
```