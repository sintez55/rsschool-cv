# Andrey Sinitsyn
## Contacts:

* Location: Pskov, Russia
* Phone: +7 953 231 75 64
* Email: sintezsintez55@gmail.com
* GitHub: [sintez55](https://github.com/sintez55)
* Telegram: https://t.me/andreysin77
___

## About:

I recently started learning HTML and CSS and JS programming. I want to study at RS Shcool and become a junior developer. My education is IT, but programming is difficult. I will try.

## Skills:

* HTML
* CSS
* JavaScript
* Git/GitHub
* Photoshop

## Code example:

Given a string made of digits [0-9], return a string where each digit is repeated a number of times equals to its value.

```
function explode(s) {
  let count = 0;
  let resultStr = "";
   for (let i = 0; i < s.length; i++) {
     count = Number(s[i]);
     for (let j = 0; j < count; j++) {
       resultStr =`${resultStr}${s[i]}`;
       }
     }
     return resultStr;
}

```