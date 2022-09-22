![Avatar](https://cdn-icons-png.flaticon.com/512/147/147142.png)
# Dmitry Andriyanov
## About me
I am 27 years old, I live in Moscow. I want to learn programming and work in this field. I think this kind of work is very interesting.
## Links
* Discord: Dmitry Andriyanov (@AmIln)
* [Github](https://github.com/AmIln)
## Skills
* HTML
* CSS(sass,scss)
* JavaScript
* GULP
* Photoshop
* Figma
## Code example
*this code from codewars "Roman Numerals Decoder"*
```function solution (roman) {
  let romanNumber = [['I',1],['V',5],['X',10],['L',50],['C',100],['D',500],['M',1000]],
      total = 0;
  function returnValue(simbol) {
    for (let i=0;i<=romanNumber.length-1;i++) {
      if (simbol === romanNumber[i][0]) {
        return romanNumber[i][1]
      }
    }
  }
  for (let i=0;i<=roman.length-1;i++) {
    if (roman[i+1] != undefined) {
      if (returnValue(roman[i])<returnValue(roman[i+1])) {
        total+= returnValue(roman[i+1]) - returnValue(roman[i]);
        i++
      } else {
        total+= returnValue(roman[i]);
      }
    } else {
      total+= returnValue(roman[i]);
    }
  }
  return total
}
```
## Work experience
* [CV#1. Markdown Git](https://github.com/AmIln/rsschool-cv)
## Education
* 2022 - The Rolling Scopes JS/Front-end stage 0
## Language
* English B1
