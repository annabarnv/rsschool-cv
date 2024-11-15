# Anna Baranova #
## Junior-front-end-developer
## Contacts
  * Location: Belgrade, Serbia
  * Phone: +381611735346
  * Email: anna.barnv@gmail.com
  * GitHub: annabarnv

## About me

I am learning front-end development. I love the idea of taking data and convert it into something visually appealing for users to enjoyably digest. I see programming for myself as a form of creativity and self-expression just like in music. My first education was in the theory of music and harmony. In my opinion, coding and music have similarities. Both require large amounts of deliberate practice and are not an innate talent. Well, with the exception of geniuses.


## Skills
  * HTML5, CSS3
  * Vanilla JavaScript
  * Git, GitHub
  * Visual Studio Code
  * Chrome DevTools
  * Figma (for developers)
  * TypeScript (basic)
  * SASS

## Code Example
```
function convert(input, source, target) {
 let s = 0, str = '';
  for(let i = 0; i < input.length; i++) {
    s = s*source.length + source.indexOf(input[i]);
  }
    while (s > 0) {
      str = target[s % target.length] + str;
      s = Math.floor(s/target.length);
    }
  return str ? str : target[0];
}
```

