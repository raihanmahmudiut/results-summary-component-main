# Frontend Mentor - Results summary component solution

This is a solution to the [Results summary component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/results-summary-component-CE_K6s0maV). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

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
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page

### Screenshot

![](./screenshot.jpg)

<!-- Add a screenshot of your solution. The easiest way to do this is to use Firefox to view your project, right-click the page and select "Take a Screenshot". You can choose either a full-height screenshot or a cropped one based on how long the page is. If it's very long, it might be best to crop it.

Alternatively, you can use a tool like [FireShot](https://getfireshot.com/) to take the screenshot. FireShot has a free option, so you don't need to purchase it.

Then crop/optimize/edit your image however you like, add it to your project, and update the file path in the image above. -->

<!-- ### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com) -->

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

I learned a lot about custom properties in CSS and how to use these variable values with hsl and reuse them in different classes without having to change them in every place. I can simply change it at the root.

```css
:root {
	--clr-primary-hsl-400: 940, 100%, 67%;
	--clr-primary-hsl-500: 956, 50%, 37%;
	--clr-secondary-hsl-400: 941, 81%, 54%;
	--clr-secondary-hsl-500: 941, 50%, 54%;

	--clr-neutral-hsl-100: 0, 0%, 100%;
	--clr-neutral-hsl-200: 221, 100%, 96%;
	--clr-neutral-hsl-300: 241, 100%, 89%;
	--clr-neutral-hsl-700: 224, 30%, 27%;

	--clr-neutral-100: hsl(var(--clr-neutral-hsl-100));
	--clr-neutral-200: hsl(var(--clr-neutral-hsl-200));
	--clr-neutral-300: hsl(var(--clr-neutral-hsl-300));
	--clr-neutral-700: hsl(var(--clr-neutral-hsl-700));

	--clr-primary-400: hsl(var(--clr-primary-hsl-400));
	--clr-primary-500: hsla(var(--clr-primary-hsl-500));
	--clr-secondary-400: hsl(var(--clr-secondary-hsl-400));

	--gradient-primary: linear-gradient(
		var(--clr-primary-400),
		var(--clr-secondary-400)
	);

	--gradient-to-transparent: linear-gradient(
		var(--clr-primary-500),
		hsl(var(--clr-secondary-hsl-500), 0)
	);

	--clr-accent-1: 321, 100%, 67%;
	--clr-accent-2: 411, 100%, 56%;
	--clr-accent-3: 566, 100%, 37%;
	--clr-accent-4: 134, 85%, 45%;

	--font-family-default: "HankenGrotesk", sans-serif;

	--fw-regular: 500;
	--fw-bold: 700;
	--fw-black: 800;

	--fs-400: 1.125rem;
	--fs-500: 1.25rem;
	--fs-600: 1.5rem;
	--fs-700: 1.75rem;
	--fs-800: 2rem;
	--fs-900: 5rem;
}
```

If you want more help with writing markdown, we'd recommend checking out [The Markdown Guide](https://www.markdownguide.org/) to learn more.

### Continued development

Use this section to outline areas that you want to continue focusing on in future projects. These could be concepts you're still not completely comfortable with or techniques you found useful that you want to refine and perfect.

I plan to continue learning about CSS custom properties and reducing the complexity of changing design patterns by using them. I also want to learn more about intuitive semantic html.

### Useful resources

- [Example resource 1](https://www.scottohara.me/blog/2017/04/14/inclusively-hidden.html) - This helped me for handling desktop and mobile designs. I really liked this pattern and will use it going forward.
- [Example resource 2](https://www.joshwcomeau.com/css/custom-css-reset/) - This is an amazing article which helped me finally understand css custom reset. I'd recommend it to anyone still learning this concept.

## Author

- Website - [Add your name here](https://www.your-site.com)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/raihanmahmudiut)
- Twitter - [@DaccanMullah](https://www.twitter.com/DaccanMullah)

## Acknowledgments

I used a lot of techniques from the CSS Maestroes Kevin Powell and Josh Comeau.
