# Imran Khapsirokov
## Junior Frontend developer
### Contact information

**E-mail:** hapsirokov91@mail.ru
**Telegram:** [ImrKhaps](https://t.me/ImrKhaps)
**Discord:** frostaill#3032

***
### Briefly about myself:
Currently I am a 4th year student at the North Caucasian Federal University majoring in Applied Informatics. 
In my free time I study English, play the guitar and love listening to music.
I am currently taking a course at RS-School and I hope that the school will help me realize my aspirations.
***
### Skills and proficiency:
* Html, CSS3
* Javascript basics
* Git/GitHub basics
* VS Code
***
### Code example:
"Square Every Digit" Kata from Codewars. 

#### Description:   

*Welcome. In this kata, you are asked to square every digit of a number and concatenate them.*

*For example, if we run 9119 through the function, 811181 will come out, because 92 is 81 and 12 is 1.*

*Note: The function accepts an integer and returns an integer*.

#### Solution: 
```javascript
function squareDigits(num){
    let strDigits = num.toString().split('');
    let digits = strDigits.map(Number);
    let arr = [];
    let squareDigit = 0;
    for(let i = 0; i < strDigits.length; i++){
      squareDigit = digits[i] ** 2;
      arr.push(squareDigit);
    }
    let digitJoin = arr.join('');
    let answer = Number(digitJoin);
    return answer;
}
```
***
### Education:
* **North-Caucasus Federal University | Stavropol, Russia**
*Bachelor’s program (Applied Informatics in Economics major)* | *diploma expected 2022* 
* HTML and CSS free course on the stepik.com (completed)
* RS Schools course «JavaScript/Front-end. Stage 1» (in progress)

### Languages:
* English - Intermediate/Upper-intermediate ("C1 Advanced" level according to EFset. [My certificate](https://www.efset.org/cert/U7nSCA).)
* Russian - Native
* Circassian - Native