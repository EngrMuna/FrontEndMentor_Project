# Frontend Mentor - Product Preview Card Component Solution

This is my solution to the [Product Preview Card Component Challenge](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa) from Frontend Mentor.  
The challenge helped me practice responsive design using only **HTML and CSS**.

---

## 📸 Overview

### The Challenge
Users should be able to:
- View the optimal layout depending on their device’s screen size.
- See hover and active states for interactive elements.

### Screenshot

#### Desktop Version
![Desktop Design](/images/Desktop_version.jpg)

#### Mobile Version
![Mobile Design](/images/Mobile_version.jpg)

### Links
- **Solution URL:** https://engrmuna.github.io/FrontEndMentor_Project/
- **Live Site URL:** https://engrmuna.github.io/FrontEndMentor_Project/

---

## 🧠 My Process

### Built With
- Semantic **HTML5** markup  
- **CSS Flexbox**  
- **Responsive Design**  
- **Mobile-first workflow**

---

### What I Learned
This project strengthened my understanding of:
- Structuring layouts with Flexbox for both mobile and desktop.
- Using media queries to switch image sources and layout orientation.
- Managing typography and color through reusable CSS variables.
- Setting up Google Fonts and using multiple font families (Montserrat and Fraunces).

Example: Using the `@media` query to change layout and background image:
```css
@media (min-width: 375px) {
  .container {
    flex-direction: row;
  }
  .imgContainer {
    background: url('/images/image-product-desktop.jpg') no-repeat;
    background-size: 100% 100%;
  }
}

Continued Development 
I plan to:

Improve hover and active states for better interactivity.

Experiment with CSS Grid for similar layout challenges.

Add accessibility features like aria-label and semantic buttons.

Useful Resources
W3schools.com - Flexbox Guide

Google Fonts

Frontend Mentor Community

👨‍💻 Author
Name: Munachimso O. Nwosu (Engr)

Frontend Mentor: @EngrMuna

GitHub: @EngrMuna

🎉 Acknowledgments
Thanks to Frontend Mentor for the detailed challenge setup and style guide. It really helped me refine my eye for detail and responsive layout practice.
