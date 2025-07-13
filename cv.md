# Tetenkin Evgeniy

![Tetenkin Evgeniy](https://avatars.githubusercontent.com/Evgesha675)

## Contacts
- **Phone:** +7 914 921 1234  
- **Email:** tetenkinevgenij@gmail.com  
- **Discord:** @Evgesh_ochka  
- **Telegram:** [@Evgesh_ochka](https://t.me/Evgesh_ochka)  
- **GitHub:** [https://github.com/Evgesha675](https://github.com/Evgesha675)  

---

## Briefly About Myself
My name is Tetenkin Evgeniy, i'm newcomer web-designer. I study HTML, CSS, JS and Vue.js.

---

## Skills
- HTML, CSS  
- JS  
- Vue.js  
- GitHub  
- Figma  

---

## Sample Code

> Well met with Fibonacci bigger brother, AKA Tribonacci.  
>  
> As the name may already reveal, it works basically like a Fibonacci, but summing the last 3 (instead of 2) numbers of the sequence to generate the next. And, worse part of it, regrettably I won't get to hear non-native Italian speakers trying to pronounce it :(  
>  
> So, if we are to start our Tribonacci sequence with [1, 1, 1] as a starting input (AKA signature), we have this sequence:  
>  
> `[1, 1 ,1, 3, 5, 9, 17, 31, ...]`  
>  
> But what if we started with [0, 0, 1] as a signature? As starting with [0, 1] instead of [1, 1] basically shifts the common Fibonacci sequence by once place, you may be tempted to think that we would get the same sequence shifted by 2 places, but that is not the case and we would get:  
>  
> `[0, 0, 1, 1, 2, 4, 7, 13, 24, ...]`  
>  
> Well, you may have guessed it by now, but to be clear: you need to create a fibonacci function that given a signature array/list, returns the first n elements - signature included of the so seeded sequence.  
>  
> Signature will always contain 3 numbers; n will always be a non-negative number; if n == 0, then return an empty array (except in C return NULL) and be ready for anything else which is not clearly specified ;)

---
```
function tribonacci(signature, n) {
  let result = new Array(n); 

  for (let i = 0; i < n && i < 3; i++) {
    result[i] = signature[i];
  }
  
  for (let i = 3; i < n; i++) {
    result[i] = result[i - 1] + result[i - 2] + result[i - 3];
  }
  return result;
}
```

## Work Experience
absent

---

## Education
Student ISU - Applied Computer Science in Design

---

## English Level
B2
