# Popup

This Popup app is a simple, responsive web application designed to display a confirmation message after a form submission. The app is built using HTML, CSS, and JavaScript, with a focus on delivering a clean and smooth user experience.

<h2>1. Key Features</h2>

<h3>- Interactive Popup Display</h3>

  Upon clicking the "Submit" button, a popup window appears, providing users with immediate feedback that their details have been successfully submitted. The popup includes a "Thank You" message, a relevant image, and an "OK" button to close the popup.
  
<h3>- Responsive Design</h3>

  The app is designed to be fully responsive, ensuring that the popup and its content are displayed correctly on various devices, from desktop to mobile.

<h3>- Modern UI/UX</h3>

  The app utilizes the "Poppins" font for a clean and modern appearance. The color scheme and layout are designed to be visually appealing and easy to interact with, featuring rounded buttons and smooth animations.

<h2>2. Technical Overview:</h2>

<h3>- HTML Structure</h3>

  The HTML document includes a container that holds the "Submit" button and the hidden popup. The popup contains an image, a heading, a message, and a button to close the popup.
  
<h3>- CSS Styling</h3>

  The CSS handles the visual styling, including layout, colors, fonts, and animations. The popup is initially hidden, positioned off-screen, and scaled down. When triggered, it becomes visible, centered, and smoothly scales up using CSS transitions.

<h3>- JavaScript Functionality</h3>

   The core functionality is implemented with JavaScript, allowing the popup to be displayed and hidden:
   
  <h4>Popup Management</h4>
  
  Functions to show and hide the popup are defined:

      function openPopup() {
        popup.classList.add("open-popup");
      }

      function closePopup() {
        popup.classList.remove("open-popup");
      }

  <h4>Event Handling</h4>

  JavaScript adds interactivity by attaching event listeners to the "Submit" and "OK" buttons, ensuring the popup displays and hides correctly.

  <h2>Summary</h2>
  This Popup app effectively combines modern web technologies to create a straightforward yet elegant user interaction. Its minimalist design, coupled with smooth animations and responsive layout, ensures a seamless experience across different devices.
