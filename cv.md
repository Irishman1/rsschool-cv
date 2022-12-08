# [rsschool-cv](https://github.com/Irishman1/rsschool-cv)

# Alexander Vasylenko

### Frontend Developer

## Contacts:

- Location: Kiyv, Ukraine
- Phone: +380962836534
- E-mail:sashaukr1999@gmail.com
- Github: [Irishman1](https://github.com/Irishman1)
- LinkedIn: [Alexander Vasylenko](hhttps://www.linkedin.com/in/alexander-vasylenko-091059182//)

## Summary about myself:

Beginning, but ambitious front end developer with good communication and time management skills. My priorities are experience and knowledge.

I am completely sure that my ability to work hard and passion to learn new technologies will help in my future career as a professional Frontend Developer. That is what keeps me up at night, a never ending thirst to create beautiful, powerful things and share them with the world.

## Skills and Proficiency:

- HTML, CSS(Framework Bootstrap, Preprocessor SASS,SCS; BEM methodology, JQuery).
- JavaScript (Fundamentals,Functional Programming, OOP, Asynchronous JavaScript, ES6+,DOM),JSON.
- React, Redux, NextJS
- Git, GitHub, BitBucket, Agile
- Algorithms
- Module Bundlers: Gulp, Webpack.
- VS Code, Figma

## Code example:

### Binary search implementation

```
function binary_search(list, item) {
  let low = 0;
  let high = list.length - 1;

  while (low <= high) {
    let mid = Math.floor((low + high) / 2);

    let guess = list[mid];

    if (guess === item) {
      return mid;
    }
    if (guess > item) {
      high = mid - 1;
    } else {
      low = mid + 1;
    }
  }

  return null;
}

const my_list = [1, 3, 5, 7, 9];

console.log(binary_search(my_list, 3));
console.log(binary_search(my_list, -1));
```

### Quick array sorting implementation

```
function quicksort(array) {
  if (array.length < 2) return array;

  let pivot = array[0];

  let less = array.slice(1).filter(function (el) {
    return el <= pivot;
  });

  let greater = array.slice(1).filter(function (el) {
    return el > pivot;
  });

  return quicksort(less).concat([pivot], quicksort(greater));
}

console.log(quicksort([10, 5, 2, 3]));
```

## Education:

- Bachelor, NURE, Kharkiv/Ukraine
  - Software engineer
- Courses
  - [Udemy video lectures](https://www.udemy.com/)
  - [CS50 lectures](https://www.youtube.com/channel/UCcabW7890RKJzL968QWEykA)
  - [FreeCodeCamp](https://www.freecodecamp.org/)
  - [HTML Academy](https://htmlacademy.ru/)
- Sololearn
  - HTML, JavaScript, Coding for Marketers, Resposive Web Design
- Books
  - **Grokking Algorithms** by _Aditya Bhargava_
  - **Eloquent JavaScript** by _Marijn Haverbeke_
  - **JavaScript for kids** by _Nick Morgan_
- JavaScript
  - [Learn JavaScript](https://learn.javascript.ru/)

## Experience:

- Copywriter (5 months)
- Writing texts on legal/medical/tourist topics
- JavaScript Developer (6 months)
  - Creating websites using React, Redux, NextJS.

## Languages:

- English - _C1 level of proficiency_
- Polish - _B1 level of proficiency_
- Ukrainian - _Native_
- Russian -_C2 level of proficiency_

---

> “Don't worry if it doesn't work right. If everything did, you'd be out of a job.”
> ― Mosher’s Law of Software Engineering
