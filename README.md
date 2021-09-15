# js-notes
language notes

Internationalizing Dates (Intl) - [mdn link](Intl.DateTimeFormat)

Internalization of data (time, currency). User browser language ca be get from `navigator.language`


`??` operator -> [mdn link](https://developer.mozilla.org/ru/docs/Web/JavaScript/Reference/Operators/Nullish_coalescing_operator)

`const foo = null ?? 'default string';
console.log(foo);
// expected output: "default string"

const baz = 0 ?? 42;
console.log(baz);
// expected output: 0`



### array methods

`[[1], [2]].flat($number)` - makes array flat. Example `[[1], [2]]`  =>  `[1,2]`
$number - by default set 1. If you need deeper - paste bigger number.

`.flatMap( function(item) {} )` - same as flat (flats only 1 level arrray. In the callback function - use .map() for arrays


