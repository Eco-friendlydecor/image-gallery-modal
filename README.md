# Image Gallery with Modal 🖼️  
Day 14 – 20 Days 20 Projects Challenge

A responsive and interactive Image Gallery built using HTML, CSS, and Vanilla JavaScript.  
This project displays images in a grid layout and opens them in a modal/lightbox view with smooth navigation and keyboard accessibility.

The gallery supports mouse clicks, keyboard navigation (Left / Right arrows), and closing the modal using the Escape key or by clicking outside the image. It is fully responsive and works well on both desktop and mobile devices.

---

Project Overview

This project demonstrates how to build a modern image gallery with a modal (lightbox) without using any external libraries or frameworks. Images are displayed as thumbnails in a responsive grid, and clicking any image opens a larger preview inside a modal overlay.

The project focuses on DOM manipulation, event handling, modal state management, accessibility features, and keyboard interactions using pure JavaScript.

---

Features

- Responsive image grid layout using CSS Grid  
- Click any image to open it in a modal / lightbox  
- Next and Previous navigation inside the modal  
- Keyboard controls:
  - Left Arrow → Previous image
  - Right Arrow → Next image
  - Esc → Close modal
- Click outside the image or on close button to close modal  
- Image captions displayed inside modal  
- Lazy loading for thumbnails  
- Accessible modal with ARIA attributes  
- Mobile-friendly and fully responsive design  

---

Technologies Used

- HTML5 – Structure and semantic markup  
- CSS3 – Styling, layout, responsive design  
- JavaScript (Vanilla) – DOM manipulation, events, modal logic  

---

Project Structure

image-gallery-modal/
│
├── index.html   (Main HTML file)
├── styles.css   (All styling and layout)
└── script.js    (Gallery and modal logic)

---

How It Works

1. Images are stored in a JavaScript array with source URLs and captions  
2. JavaScript dynamically renders image thumbnails into a grid  
3. Clicking a thumbnail opens the modal with the selected image  
4. Modal navigation updates the image source and caption  
5. Keyboard events handle navigation and closing the modal  
6. Clicking the overlay or close button closes the modal  
7. Lazy loading improves performance for thumbnails  

---

How to Run the Project

1. Download or clone the repository  
2. Open the project folder in VS Code  
3. Open index.html in your browser  

OR  

4. Use the Live Server extension in VS Code for best experience  

---

Concepts Learned

- DOM traversal and manipulation  
- Event delegation  
- Modal / lightbox implementation  
- Keyboard event handling  
- Accessibility basics (ARIA roles, focus handling)  
- Responsive design using CSS Grid  
- Lazy loading images  

---

Future Improvements

- Add zoom-in / zoom-out feature  
- Add slideshow autoplay mode  
- Fetch images dynamically from an API  
- Add image categories or filters  
- Dark / Light theme toggle  

---

Author

Chetan Sahu  
Aspiring Full Stack Developer  

GitHub: https://github.com/Eco-friendlydecor  
LinkedIn: https://www.linkedin.com/in/chetan-sahu-247644296/  

---

License

This project is open-source and created for learning and educational purposes.
