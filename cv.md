# Bybin Mark

![avatar image](./assets/avatar.jpg)

## Contact information

- Github: [@knifewifealive](https://github.com/knifewifealive)
- Email: bybinmark@yandex.ru
- Discord: [bybinmark(@knifewifealive)](https://discordapp.com/users/292592515398238208/)
- Telegram: [@cagepagerage](https://t.me/cagepagerage)

## Briefly about myself

It is important to me to be inquisitive, seeking answers to complex questions, developing, fun and creative. I completely agree with the statement below:

> “A person’s worth is measured by the worth of what he values.” \
> Marcus Aurelius.

I have four years of experience working with people in the service industry:
* half a year as a waiter (2014 / 2015 summer's)
* a year and a half as a barista (2016 / 2017 summer's, may 2020 - may 2021)
* a year as a cruise travel agent (january 2019 - february 2020)
* a year as a beauty salon receptionist (october 2022 - october 2023)

## Skills and Proficiency:

- HTML5, CSS3
- JavaScript Basics
- Git, GitHub
- VS Code
- Figma

## Code example:

### [Char Code Calculation kata from CodeWars](https://www.codewars.com/kata/57f75cc397d62fc93d000059)

#### Description:

Given a string, turn each character into its ASCII character code and join them together to create a number - let's call this number `total1`:

```
'ABC' --> 'A' = 65, 'B' = 66, 'C' = 67 --> 656667
```

Then replace any incidence of the number `7` with the number `1`, and call this number 'total2':

```
total1 = 656667
              ^
total2 = 656661
              ^
```
Then return the difference between the sum of the digits in total1 and total2:

```
  (6 + 5 + 6 + 6 + 6 + 7)
- (6 + 5 + 6 + 6 + 6 + 1)
-------------------------
                       6
```
#### Solution:

```
function calc(str){
  const amountOfSevens = str.split('')
            .map(item => item.charCodeAt(0))
            .join('')
            .match(/7/g);
  
  return amountOfSevens ? amountOfSevens.length * 6 : 0;
            
}
```
## Projects

1. [CreateX](https://knifewifealive.github.io/createX/), project description and code: <https://github.com/knifewifealive/createX>

1. Deposit calculator, project descriprion and code: <https://github.com/knifewifealive/depositCalculator>

## Education and Courses

- Higher incomplete education, Tyumen Industrial University, Business Informatics and Mathematics, Applied Mathematics and Informatics, 2017 - 2021
- [Aroken Frontend Course](https://youtube.com/playlist?list=PLNaJj8xMY1XQgYzVhLEFD4WSKqEhj4Sx1&si=r2UpvqSj1x2VTj_O) (finished)
- [RS School Stage 0](https://github.com/rolling-scopes-school/tasks/tree/master/stage0) (in progress)

## Languages

- English - Intermediate/Upper-intermediate (according to the online test at www.efset.org)
![Test result](./assets/efset-english-level.jpg)
- Russian - Native