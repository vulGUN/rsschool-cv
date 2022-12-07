# Max Likhachev

## Contacts:

-   **E-mail**: likha.max@gmail.com
-   **Phone**: +7 (995) 177-44-20
-   **Telegram**: [Max Likhachev](https://t.me/maxbny)
-   **GitHub**: [vulGUN](https://github.com/vulGUN/)

## About me:

I am considering a career change towards front-end development.
Completed online courses in HTML / CSS, currently taking a course in JavaScript + React and looking for an opportunity to apply knowledge in practice.
Ready to take a test task to demonstrate the level of skills.

## Skils:

##### HTML

-   studied basic HTML tags;
-   I know the difference between block and inline elements;
-   use HTML tags according to their semantics.

##### CSS

-   I can create adaptive layout using media expressions;
-   using flexbox model / bootstrap grid;
-   I know how to use pseudo-classes / pseudo-elements;
-   Working with SASS / SCSS preprocessors;

##### JavaScript

-   studied what variables and data types are;
-   conversion of data types;
-   basic operators, logical operators;
-   conditional branching: if, else, '?';
-   cycles;
-   conditions;
-   functions;
-   little experience in using the jQuery library.

##### Git / GitHub

-   know basic git commands;
-   I can create/delete commits;
-   I can push a project to github;

##### Tools

-   I use Windows 11 as a working OS;
-   I have experience using Figma with design layouts;
-   I use the Visual Studio Code editor with add-ons (Emmet, Prettier, etc.) for more comfortable coding;
-   Familiar with the Gulp task scheduler. I use it to trigger server startup, compile SASS/SCSS files to style.min.css;

## Code Examples:

```javascript
function tribonacci(signature, n) {
    let arr = [...signature];
    if (n === 0) return [];
    else if (n === 1) return [arr[0]];
    else if (n === 2) return [arr[0], arr[1]];
    for (let i = 0; i < n - 3; i++) {
        arr.push(arr[i] + arr[i + 1] + arr[i + 2]);
    }
    return arr;
}
```

```javascript
function persistence(num) {
    let arr = num.toString().split(''),
        length = arr.length,
        count = 0;
    for (let i = 0; i <= length; i++) {
        if (arr.length > 1) {
            arr = arr
                .reduce((a, b) => a * b)
                .toString()
                .split('');
            count++;
        }
    }
    return count;
}
```

## Education:

-   Voronezh State University of Architecture and Civil Engineering;
-   Course on the Udemi platform "Professional HTML and CSS";
-   Course on the Udemi platform "Full Course in JavaScript + React" (in progress...).

## English:

Level A2, elementary. I read technical documentation, occasionally using Google Translate.
