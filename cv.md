# My name is Igor Medvedev


## Contacts:
* __Country__ : Belarus
* __E-mail__ : yoyoyo951@gmail.com
* __Telegram__ : https://t.me/igormdvd
* __GitHub__ : [IamIHAR](https://github.com/IamIHAR)


## Skills:
* HTML
* CSS
* Javascript
* React JS
* Git

## Education
 * __BSUIR__
   * Speciality :  Electronic security systems
### Courses:
 * __IT-school__ _Mela Rossa_
   * Speciality : Front-end development
 * __The Rolling Scopes School__
   * Speciality : JavaScript/Front-end, stage 0 (in progress)
### Self-Education:
* learn.javascript.ru (in progress)
* codewars.com (in progress)
* Books about javascript (in progress)


## Code example:
__Split Strings__ KATA from CODEWARS:
Complete the solution so that it splits the string into pairs of two characters. If the string contains an odd number of characters then it should replace the missing second character of the final pair with an underscore ('_').
```javascript
function solution(str){
  if(str === '') return []
  let arr = str.split('')
  let arr2 = []
  arr.length % 2 !== 0? arr.push('_'): arr;
  arr.map((e,i) => i % 2 !== 0? arr2.push(e + ' '): arr2.push(e))
return arr2.join('').trim().split(' ')
}
```

## Languages:
* Russian - native
* English - A2 (in progress)