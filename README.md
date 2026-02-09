# Frontend Mentor - Results summary component solution

This is a solution to the [Results summary component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/results-summary-component-CE_K6s0maV). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Frontend Mentor - Results summary component solution](#frontend-mentor---results-summary-component-solution)
  - [Table of contents](#table-of-contents)
  - [Overview](#overview)
    - [The challenge](#the-challenge)
    - [Screenshot](#screenshot)
    - [Links](#links)
  - [My process](#my-process)
    - [Built with](#built-with)
    - [What I learned](#what-i-learned)
    - [Continued development](#continued-development)
    - [Useful resources](#useful-resources)
  - [Author](#author)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Your challenge is to build out this results summary component and get it looking as close to the design as possible.

You can use any tools you like to help you complete the challenge. So if you've got something you'd like to practice, feel free to give it a go.

We provide the data for the results in a local `data.json` file. So you can use that to add the results and total score dynamically if you choose. 
Users should be able to:

- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page
- **Bonus**: Use the local JSON data to dynamically populate the content

### Screenshot

![](./screenshot.jpg)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- SCSS

**Note: These are just examples. Delete this note and replace the list above with your own choices**

### What I learned

J'ai appris à travailler avec une approche mobile-first. J'ai également appris à utiliser la norme BEM CSS.
Pour le CSS, j'ai utiliser un préprocesseur (SCSS). Cela permet par exemple de créer des variables.
J'ai également utilisé la notation indenté en CSS. 

Voici un snippet CSS que je n'aurai pas pu comprendre avant le début de ce projet.
Je ne sais pas si c'est réellement une bonne ou mauvaise pratique.

```css
.reaction,
.memory,
.verbal,
.visual {
  > div:nth-child(2) > span:first-child {
    color: $color-navy-950;
  }
}
```


### Continued development

Je dois me perfectionner en approche mobile first. Le plus difficile reste le positionnement des éléments. Comment gérer correctement son espace de travail. C'est mon premier projet en utilisation les convetions de nommages BEM. Je pense que je dois m'améliorer sur la façon de nommer mes classes CSS.

### Useful resources

- [BEM CSS](https://alticreation.com/blog/bem-pour-le-css/) - J'ai appris cette technique que je ne connaissais pas. C'est une convention de nommage.
- [BEM CSS - Documentation officielle](https://getbem.com/) - Ceci est la documentation de référence
- [TESTMUAI](https://www.testmuai.com/lt-browser/) - Une plateforme permettant la gestion multi device. Malheureusement la version gratuite permet très peu de chose.

## Author

- Frontend Mentor - [@bdeweer](https://www.frontendmentor.io/profile/bdeweer)
- Twitter - [@bdeweeronx](https://x.com/bdeweeronx)
