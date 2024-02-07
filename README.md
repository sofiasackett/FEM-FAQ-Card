# FEM-FAQ-Card
FAQ Card challenge by Frontend Mentor

# Frontend Mentor - FAQ accordion card solution

This is a solution to the [FAQ accordion card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/faq-accordion-card-XlyjD0Oam). Frontend Mentor challenges help you to improve your coding skills by building realistic projects. 

## Table of contents

  - [The challenge](#the-challenge)
  - [Links](#links)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)

The following screenshot is the design that I was attempting to reproduce. 

![active-states](https://user-images.githubusercontent.com/43033791/111329942-e521e000-8645-11eb-8bb0-fd56166a906e.jpg)

The following screenshot is my replication of the design.
![Screenshot (1)](https://user-images.githubusercontent.com/43033791/111329713-b4da4180-8645-11eb-80d9-333c398add97.png)

### The challenge

Users should be able to:

- View the optimal layout for the component depending on their device's screen size
- See hover states for all interactive elements on the page
- Hide/Show the answer to a question when the question is clicked

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- JavaScript

### What I learned

This is the first challenge that I have ever completed from Frontend Mentor, and the first tangible product I have been able to create using frontend development tools and languages. This project reinforced my ancient HTML and CSS knowledge as well as allowed me to try out some JavaScript for the FAQ accordion. 

### Continued development

I know that this project is full of dirty code, and I hope to come back in the future and remedy it, but for now I want to focus on other projects and try to solve new problems.

Two main issues I have with my solution is that the accordion expands outside of the card because I was unable to figure out how to collapse all other accordion items when one is opened. The second issue I have is that I feel as though too many elements are positioned relative and given exact coordinates, which is not particularly responsive or mobile-friendly. When the window is resized smaller, the box illustration with the '@' symbol stays in the exact same position while the rest of the card moves as one. However, the card does not automatically resize for smaller screens, which will need to be addressed in the future. 

One small issue that I need to fix is the spacing between the answers and the border line before the following question. I played around a lot with padding of the accordion itself as well as each panel and what you see is about as good as I was able to get it right now.

