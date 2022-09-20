# Frontend Mentor - Advice generator app solution

This is a solution to the [Advice generator app challenge on Frontend Mentor](https://www.frontendmentor.io/profile/nishantdev365). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the app depending on their device's screen size
- See hover states for all interactive elements on the page
- Generate a new piece of advice by clicking the dice icon

### Screenshot

![Design preview for the Advice generator app coding challenge](./design/advice%20generator.png)

### Links

- Solution URL: [Add solution URL here](https://www.frontendmentor.io/solutions/advice-generator-app-J_ynFvMccs)
- Live Site URL: [Add live site URL here](https://nishantdev365.github.io/advice-generator/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

I learnt how to use asyn await function effectively

```API
async function advice() {
  const response = await fetch(URL);
  const data = await response.json();
  const { id, advice } = data.slip;
  adviceText.innerHTML = `<h1 class="advice__heading">Advice # ${id}</h1>
        <p class="advice__text">
      " ${advice} "
        </p>`;
}
advice();
```

## Author

- Frontend Mentor - Nishant Kumar
