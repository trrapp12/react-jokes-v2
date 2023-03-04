
# REACT JOKES v2.0 

### NEW AND IMPROVED VERSION

https://user-images.githubusercontent.com/11747875/218291297-69f36beb-ccfd-4657-832b-f80a25814d69.mp4

[![View Project](https://user-images.githubusercontent.com/11747875/141705232-471a0b9c-ca45-4540-a1b6-740c5e1becbe.png)](https://tourmaline-medovik-1e81f3.netlify.app/)


### ORIGINAL VERSION

![screenshot-localhost_3000-2022 03 02-07_54_45](https://user-images.githubusercontent.com/11747875/156386294-0178003b-a2e8-442a-a5e2-59beb3274268.png)

[![View Project](https://user-images.githubusercontent.com/11747875/141705232-471a0b9c-ca45-4540-a1b6-740c5e1becbe.png)](https://trrapp12.github.io/React-Jokes/)

<br/>
<br/>

---

<img align="left" alt="HTML5" width="40px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/html/html.png" />
<img align="left" alt="CSS3" width="40px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/css/css.png" />
<img align="left" alt="JavaScript" width="40px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/javascript/javascript.png" />
<img align="left" alt="Terminal" width="40px" src="https://user-images.githubusercontent.com/11747875/222922644-59ab86f4-e8c5-4e03-9491-0a37eeaf0f46.png" />
<img align="left" alt="Git" width="40px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/git/git.png" />
<img align="left" alt="Terminal" width="40px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/terminal/terminal.png" />
<img align="left" alt="GitHub" width="40px" src="https://raw.githubusercontent.com/github/explore/78df643247d429f6cc873026c0622819ad797942/topics/github/github.png" />

<br>
<br>

---

### Description:


> “A father carries pictures where his money used to be.” – Steve Martin

<br/>
<br/>

Because who doesn't love Dad jokes?  This is a React project I refactored and improved on.  The original was part of a Scrimba Frontend Development course.  However, the complete refactoring was all my own inspiration, creative decision, and coding experimentation. 

THE NEW SITE IMPROVEMENTS INCLUDE

🆕 Static site > DYNAMIC SITE!

🆕 Props only > PROPS, USESTATE(), USEEFFECT()!

🆕 Stuck in a repository (hoping someone would download, build a server, then view) > PUBLISHED ON THE WEB!

🆕 Blah! Monochromatic design with unimpressive hover effects > STRONG COLOR, USE OF SPACE, HIERARCHY, MOVEMENT, AND EVEN TRANSITION EFFECTS THAT INTEGRATE WITH REACT!

🆕 Jokes were presented all at once in an overwhelming list > IMPROVED UI/UX AS PEOPLE CAN NOW CYCLE THROUGH THE JOKES WITH A CLICK INSTEAD OF A SCROLL

<br/>
<br/>

### Project v1.0 demonstrates the following:

- [x] Use of JSX
- [x] Use of basic syntax and architecture of React
- [x] Use of parent > child components
- [x] Use of custom composable, reusable components
- [x] Use of Bable and Webpack through Create React App
- [x] Use of git CLI and GitHub repositories
- [x] Use of CSS and images in React environment
- [x] Use of import and export statements
- [x] Use of local server with webpack

<br/>
<br/>

### CHALLENGES I OVERCAME
---

As far as technical issues most were pretty straightforward, though there were two relatively small hiccups.  

1) I had to move props up to a parent element so that the button that registered the state change could control the state of the joke card (hitting the button cycles the jokes on the card).

2) The fun decoration in the background is all controlled with vanilla JS.  I had originally tried to just add that through a normal script tag in my index.html.  However that created an issue where it would fire the first time the page rendered, but if the state changed and caused a rerender the script tag wouldn't fire again and I would lose the effect of the words inside the decorative ball populating.  So what I had to do to get around that is to creat a function that wrote the same script in my App.js file, and then use a useEffect hook to re-write that script when the page re-rendered.

<br/>
<br/>

### MY OWN PERSONAL CONTRIBUTIONS INCLUDED
---

Basically the original course only took the project up to using props.  Nothing with `useState()` or `useEffect()` were included.  The complete redesign of version 2 was all my own creation.  Once again, these improvements included:

🆕 Static site > DYNAMIC SITE!

🆕 Props only > PROPS, USESTATE(), USEEFFECT()!

🆕 Stuck in a repository (hoping someone would download, build a server, then view) > PUBLISHED ON THE WEB!

🆕 Blah! Monochromatic design with unimpressive hover effects > STRONG COLOR, USE OF SPACE, HIERARCHY, MOVEMENT, AND EVEN TRANSITION EFFECTS THAT INTEGRATE WITH REACT!

🆕 Jokes were presented all at once in an overwhelming list > IMPROVED UI/UX AS PEOPLE CAN NOW CYCLE THROUGH THE JOKES WITH A CLICK INSTEAD OF A SCROLL

<br/>
<br/>

### CREDITS: 
---

Project created by TREVOR RAPP

Original project was inspired by <a href="https://www.linkedin.com/in/bobziroll/">Bob Ziroll's</a> React course, part of the <a href="https://scrimba.com/learn/frontend"> Scrimba's Front End Development Course </a>

<a href="https://www.flaticon.com/free-icons/react" title="react icons">React icons created by Dreamstale - Flaticon</a>

<br/>
<br/>

### YOU CAN FIND ME AT:
---

\**For more information see my [LinkedIn](https://www.linkedin.com/in/trevor-rapp-042a1037) or return to my [Github](https://github.com/trrapp12)*

*This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).*



