# Smooth drop-down menu

## Overview
This repository contains a simple HTML/CSS/JavaScript implementation of a smooth drop-down menu. The menu is designed to be responsive and accessible, with a smooth animation when opening and closing.

## Features
- Smooth animation
- Responsive design
- Accessible with keyboard navigation and ARIA attributes
- Easy to customize and style

## Usage
You can use this drop-down menu in your own projects by including the HTML, CSS, and JavaScript files. Here's how:

1. Download the files from this repository or add this repository as a submodule to your project.
2. Include the CSS file (`reset.css` and `style.css`) in the `<head>` section of your HTML file:
   ```html
   <link rel="stylesheet" href="path/to/reset.css">
   <link rel="stylesheet" href="path/to/style.css">
   ```

3. Add the HTML code for the drop-down menu to your HTML file:
   ```html
   <div class="box">
       <button class="button" aria-expanded="false" aria-controls="list">menu</button>
       <ul class="menu" id="list" aria-hidden="true">
           <li class="menu__item">
               <a href="#1" class="menu__link" tabindex="-1">Link 1</a>
           </li>
           <li class="menu__item">
               <a href="#2" class="menu__link" tabindex="-1">Link 2</a>
           </li>
           <!-- Add more menu items as needed -->
       </ul>
   </div>
   ```

4. Include the JavaScript file (`main.js`) just before the closing `</body>` tag:
   ```html
   <script src="path/to/main.js"></script>
   ```

5. Customize the menu items by changing the text and `href` attributes of the `<a>` tags inside the `<li>` elements.
6. Style the menu to match your project's design by modifying the CSS file (`style.css`).

## Demo
You can see a live demo of the drop-down menu [here](https://your-demo-link.com).

## Contributing
Contributions are welcome! If you have any suggestions or improvements, feel free to open a pull request or create an issue.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
