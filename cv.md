# Artem Gapich

## Contacts

- Telegram: [@turbo_archy](https://t.me/turbo_archy)
- E-mail: archydemon1@gmail.com
- GitHub: [Artem-WebDeveloper](https://github.com/Artem-WebDeveloper)

## About me

I'm a beginner frontend developer with strong motivation and understanding of modern tools and approaches. I enjoy learning new technologies, tackling challenges, and solving complex problems. I am committed to continuous improvement, dedicating time daily to studying web development, automation, and optimization.

I dream of joining a team where I can develop as a specialist and bring **real benefit** to projects.

## My Skills

**Programming & Markup Languages**

- JavaScript, HTML, CSS

**Development tools & Technologies**

- VS Code, npm, DevTools, GIT, Vite, Figma, Photoshop

**Methodologies & Principles**

- BEM, Responsive design, SCSS, Clean code principles, Object-Oriented Programming

**Operating Systems & Environments**

- Windows, basic skills working in a Linux environment via WSL (Windows Subsystem for Linux)
- Confident terminal user for navigation, project setup, and configuration

## Example Code

#### Task [Are they the "same"? — Codewars Kata](https://www.codewars.com/kata/550498447451fbbd7600041c)

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

## Work Experience

**Self-learning Project — Browser Card Game "DrunCard"**

**DrunCard** is a dynamic and engaging version of the popular card game "War," designed to be played directly in your browser. The project is implemented using _JavaScript_, _HTML_, and _CSS_ following modern web development standards.

#### Links

- Play the game online: [druncard.netlify.app](https://druncard.netlify.app/)
- Source code repository: [GitHub](https://github.com/Artem-WebDeveloper/druncard)

## Education

**Rostov College of Informatics and Communications**  
Specialization: _Programming in Computer Systems_  
Qualification: _Computer Programming Technician_

**Additional Courses (Udemy):**

- [Build Responsive Real-World Websites with HTML and CSS](https://www.udemy.com/course/design-and-develop-a-killer-website-with-html5-and-css3/)
- [Advanced CSS and Sass: Flexbox, Grid, Animations and More!](https://www.udemy.com/course/advanced-css-and-sass/)
- [The Complete JavaScript Course 2025: From Zero to Expert!](https://www.udemy.com/course/the-complete-javascript-course/)

## Languages

- **Russian** — Native speaker
- **English** — A2 (_actively improving, focusing on technical and conversational English, aiming for B1_)
