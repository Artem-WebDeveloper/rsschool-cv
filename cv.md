# Artem Gapich

## Contacts

- Telegram: [@turbo_archy](https://t.me/turbo_archy)
- E-mail: archydemon1@gmail.com
- GitHub: [Artem-WebDeveloper](https://github.com/Artem-WebDeveloper)

## About me

I'm a beginner frontend developer with strong motivation and understanding of modern tools and approaches. I love to learn, understand new technologies, accept challenges and solve complex problems. I am constantly developing, daily studying everything related to web development, automation and optimization.

I dream of joining a team where I can develop as a specialist and bring **real benefit** to projects.

## My Skills

**Programming and Markup Languages**

- JavaScript, HTML, CSS

**Development tools**

- VS Code, npm, DevTools, GIT, Vite, Figma, Photoshop

**Methodologies**

- BEM, Responsive design, Clean code principles, Object-Oriented Programming

**Operating Systems and Environments**

- Windows, basic skills working in a Linux environment via WSL (Windows Subsystem for Linux)
- Confident use of the terminal for navigation, running, and configuring projects

## Example Code

#### Task [Are they the "same"?](https://www.codewars.com/kata/550498447451fbbd7600041c)

_Given two arrays `a` and `b` write a function `comp(a, b)` (or`compSame(a, b)`) that checks whether the two arrays have the "same" elements, with the same *multiplicities* (the multiplicity of a member is the number of times it appears). "Same" means, here, that the elements in `b` are the elements in `a` squared, regardless of the order._

**My Solution:**

```javascript
function comp(array1, array2) {
  if (!Array.isArray(array1) || !Array.isArray(array2)) return false;
  if (array1.length !== array2.length) return false;
  const arr1 = array1.sort((a, b) => a - b).map(el => el ** 2);
  const arr2 = array2.sort((a, b) => a - b);
  for (let i = 0; i < arr1.length; i++) {
    if (arr1[i] !== arr2[i]) return false;
  }
  return true;
}
```
