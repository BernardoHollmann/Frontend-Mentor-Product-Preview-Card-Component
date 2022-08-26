# Frontend Mentor - Product preview card component solution

This is a solution to the Product Preview Card Component challenge on Frontend Mentor (https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- Frontend Mentor | Product preview card component challenge
  - The challenge consisted in replicating a perfume card preview page for a desktop and mobile view perspective
  - Here it is two screenshots taken from desktop and mobile perspective;

- My process
  - Built with: HTML + CSS/Bootstrap;
  - As a begginer, this was a tricky one for me. When I first saw the design of the card, imidiatly I thought in using a bootstrap card component to easy up the creating process. However, I am not sure this was the best idea.. First of all, I looked up to the style standars and imported the required fonts from Google Fonts. Then, I copied the CDN link from the Bootsrap website and looked up to the card component documentation. I noticed that there was one of the exemples that shown a very similar design to the pattern I was looking for and copied the code. Then, I implemented it in the HTML section of the index.html file and start customizing it with CSS. At first, I uploaded the given image to the code. As Bootsrap has a class "img-fluid" that adjust the image itself, I thought it was very helpfull for this project. However, after implementing the font and colors with CSS, I struggled in centering the card in the viewport. I had to look for a lot of materials in the internet to find a solution to fit what I was trying to do. Then, after some time, I switched the <main> tag to <div>, because <main> uses display: block as a standard, and used margin, align-items and justify-content to center the card. At the end, after the CSS adjustments, I used a media query in replacing the image content in a <div>. This also took me some time to learn and implement. The result was not 100% accurate, but I think it turned out ok. 

- Author: Bernardo Hollmann

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Links

- https://github.com/BernardoHollmann/Frontend-Mentor-Product-Preview-Card-Component

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Bootstrap
- Border-box / Flex

### What I learned

- I learned how to center a Bootstrap card component and how it can work in different viewports. I also learned how to switch and image in a <img> tag. 

### Continued development

- I would really like to receive feedbacks on it. I am still learning how to better use Bootsrap and all its features. In this project, I had a huge amount of trouble in figuring out how what was the best display parameter to use for centering the card. If someone could explain or inform me where I can learn more about it, I will be very thankfull.
- I know I made several mistakes in this project. Feedbacks would be much appreciated and it will help me keeping improving myself. 

## Author

- Twitter - @bera87 https://twitter.com/bera87