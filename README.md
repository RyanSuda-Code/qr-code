# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
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

### Screenshot

Desktop
![](./images/Screenshot%202025-10-31%20222905.png)
Mobile
![](./images/Screenshot%202025-10-31%20222918.png)

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

### What I learned


```css
@media (min-width: 500px) {
    .container {
        width: 400px;
    }
}
```
This media query sets the container’s width to 400px when the device screen is 500px or wider.
This limits the image inside the container so it can’t grow larger than 400px.


```css
img {
    max-width: 100%;
}
```
Adding the above snippet within the CSS made the image responsive. The image will shrink if the container becomes smaller, will never exceed the width of its parent (.container), and will maintain its original aspect ratio, meaning it won’t stretch or distort.

Together, these two rules ensure that:

    The container’s width is limited to 400px on larger screens.

    he image automatically scales to fit the container.

    The layout remains responsive and visually balanced across different devices.

⚠️ Note:
When using these snippets, be careful not to set width: 100%; on your original .container, as it can cause the container to ignore padding and touch the sides of the browser instead of resizing properly.


### Continued development

🧭 Future Focus

For future projects, I would like to continue learning and become more confident in using media queries. Working on this project made me realize how powerful and essential media queries are, especially for creating responsive designs that adapt to different screen sizes. They help ensure that users have a comfortable experience and that the design and layout remain consistent across all devices.


## Author

- Website - [Ryan](https://github.com/RyanSuda-Code)

