# InkHollow Studio Portfolio

A responsive, single-page portfolio website for an illustrator, built completely from scratch using HTML5, CSS3, and Vanilla JavaScript. 
The site features a dark, moody theme with a vibrant purple accent, a CSS masonry gallery, smooth scrolling, and custom SVG branding.

## Setup Instructions
Since this project does not rely on any build tools, package managers, or backend servers, setup is instantaneous.

1. Navigate to the project folder.
2. Double-click the `index.html` file to open it in your default web browser.
3. Done! 

*(Optional) You can also use a simple local server like VS Code's "Live Server" extension for a better development experience with hot-reloading.*

## Project Structure
- `index.html` - The semantic HTML5 structure.
- `style.css` - Custom properties, typography, masonry CSS grids, flexbox, and media queries.
- `script.js` - Intersection Observer logic for animations and form handling.
- `assets/logo.svg` - Hand-coded scalable vector graphic logo.

## How to Zip the Project
To bundle the project for delivery, you can use the following PowerShell command in the root folder:

```powershell
Compress-Archive -Path "index.html", "style.css", "script.js", "assets" -DestinationPath "inkhollow-portfolio.zip" -Force
```

## Contact Form
"Contact form. If I fill out my name, email, select 'Character Sheet' from the dropdown, and add a test message..."
*(Fill out form on screen and hit submit)*
"...and submit, you'll see the UI gives feedback. Since there's no backend, if I open the browser DevTools Console..."
*(Open DevTools Console, F12 -> Console)*
"...you can see the form data is neatly intercepted and logged out via JavaScript. And that's the complete responsive single-page portfolio!"
