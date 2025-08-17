# Frontend Mentor - Recipe page solution

This is a solution to the [Recipe page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### Screenshot

![](./design/Screenshot%202025-08-17%20at%2021-47-57%20Frontend%20Mentor%20Recipe%20page.png)


### Links

- Solution URL: 
- Live Site URL: (https://recipe-page-pink-kappa.vercel.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties

### What I learned
I learnt how to create and style a basic table in HTML. I also learnt how to notice the small details in a design to get it looking as close to the solution as possible.


To see how you can add code snippets, see below:

```html
<div class="nutrition">
  <h2>Nutrition</h2>
   <p>The table below shows nutritional values per serving without the additional fillings.</p>
   <table>
     <tr>
      <td>Calories</td>
      <td class="amount">277kcal</td>
     </tr>
     <tr>
      <td>Carbs</td>
      <td class="amount">0g</td>
     </tr>
     <tr>
      <td>Protein</td>
      <td class="amount">20g</td>
     </tr>
     <tr class="last">
      <td>Fat</td>
      <td class="amount">22g</td>
     </tr>
   </table>
 </div>
```
```css
table {
  display: table;
  border-collapse: collapse;
  width: 600px;
}
td {
  padding: 10px 20px;
}
tr {
  border-bottom: 1.5px solid var(--Stone150);
}
.last {
  border: none;
}
ol li::marker {
  color: var(--Brown800);
  font-weight: bold;
  font-family: "Outfit", sans-serif;
}

```

### Continued development

How to style advanced tables and identifying what CSS properties to use


## Author

- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)
