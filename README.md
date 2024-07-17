![butan1](https://github.com/user-attachments/assets/eae526f3-aa56-4a7c-9abe-57fa55ec10b3)Explanation:

HTML Structure:
The .slider-container holds the .slider which contains multiple .slide elements, each containing an image.
Navigation buttons .prev and .next are used to move between slides.

CSS (styles.css):
Styles to create a responsive image slider with basic controls.
Uses flexbox for .slider to display slides in a row.
Navigation buttons are positioned absolutely for easy access.

JavaScript (script.js):
slideIndex keeps track of the current slide.
showSlides() hides all slides except the one at slideIndex.
changeSlide(n) updates slideIndex and calls showSlides() to display the new slide.
