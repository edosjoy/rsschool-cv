# Eduard Nabiulin

![foto](http://dl4.joxi.net/drive/2022/03/17/0000/1892/14180/80/6b115086df.jpg)

---

## Contacts for communication

* Phone/WhatsApp: **+7 (977) 800-40-91**
* Telegram: [**@edosjoy**](https://t.me/edosjoy)
* Discord: **edosjoy#1476**
* E-mail: [**eduard.nabiulin@gmail.com**](mailto:eduard.nabiulin@gmail.com)

---

## About me

I am currently the head of IT projects. I am responsible for the development of various e-commerce products. Before that, I was engaged in SEO optimization of websites for a long time. I was also engaged in the administration and refinement of sites (sites without CMS, self-written and boxed CMS).

All the time I was attracted to development as a programmer. For the sake of interest, I studied various programming languages. I chose JavaScript, because that's where there is user interaction and a tangible return on your work.

Thanks to my great interest in development, I study with pleasure. And made the final decision to become a JavaScript developer.

As I study JavaScript, I do small projects. I post some of them on my [github account](https://github.com/edosjoy).

## Skils
* HTML, CSS
* JavaScript (basic)
* React (basic)
* Git (githab, gitlab)
* WebStorm, VS Code

## Code examples

Example of a solved task on codewars.com (my nicname *edosjoy*)

**Task**

https://www.codewars.com/kata/556deca17c58da83c00002db

> Well met with Fibonacci bigger brother, AKA Tribonacci.
> 
> As the name may already reveal, it works basically like a Fibonacci, but summing the last 3 (instead of 2) numbers of the sequence to generate the next. And, worse part of it, regrettably I won't get to hear non-native Italian speakers trying to pronounce it :(
>
> So, if we are to start our Tribonacci sequence with [1, 1, 1] as a starting input (AKA signature), we have this sequence:
> 
> [1, 1 ,1, 3, 5, 9, 17, 31, ...]
> 
> But what if we started with [0, 0, 1] as a signature? As starting with [0, 1] instead of [1, 1] basically shifts the common Fibonacci sequence by once place, you may be tempted to think that we would get the same sequence shifted by 2 places, but that is not the case and we would get:
> 
> [0, 0, 1, 1, 2, 4, 7, 13, 24, ...]
> 
> Well, you may have guessed it by now, but to be clear: you need to create a fibonacci function that given a signature array/list, returns the first n elements - signature included of the so seeded sequence.
> 
> Signature will always contain 3 numbers; n will always be a non-negative number; if n == 0, then return an empty array (except in C return NULL) and be ready for anything else which is not clearly specified ;)

**Solution**

```javascript
function tribonacci(signature, n){
  
  if (n === 0) {
    return [];
  }
  
  if (n < 4) {
    let newArr = [];
    for (let i = 0; i < n; i++) {
      newArr.push(signature[i]);
    }
    return newArr;
  }
  
  for (let i = 2; i < n - 1; i++) {
    signature.push(signature[i - 2] + signature[i - 1] + signature[i]);
  }
  
  return signature;
  
}
```

## Education

* Higher education, Faculty of Computer Science and Computer Engineering
* Frontend development courses
  * HTML Academy (https://htmlacademy.ru/)
  * IT Proger (https://itproger.com/)
  * Nova JS (https://novajs.space)
  * Udemy (https://www.udemy.com)

## English language

А2 (Pre-Intermediate)

![stars](http://dl4.joxi.net/drive/2022/03/17/0000/1892/14180/80/afeba12fea.jpg)