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

## Demo Video Script & Walkthrough

If you are recording a 1-2 minute demo video, here is a suggested script to talk through the code and UI:

**[Start recording screen on `index.html` file in editor]**
"Hi, here is the hand-coded portfolio for InkHollow Studio. I started with a clean, semantic HTML5 structure. We have a fixed nav, hero section, a masonry grid for the gallery, and sections for about, pricing, and contact."

**[Switch to `style.css`]**
"In the CSS, I've established a dark theme using CSS variables, picking a punchy neon purple accent color. I achieved the masonry gallery layout purely through CSS `column-count`, making it lightweight. The design is fully responsive with breakpoints at 1200px, 768px, and 480px, dropping down to a single column on mobile."

**[Switch to `script.js`]**
"For the JavaScript, I used the native Intersection Observer API to trigger smooth fade-in animations as the user scrolls, avoiding heavy external animation libraries. I also added a simple event listener to intercept the contact form submission."

**[Switch to Browser - Show Website]**
"Now let's look at the live site. As you can see, the dark, moody aesthetic fits the illustrator persona perfectly. The placeholder images are ultra-lightweight CSS gradients to keep the total page weight well under the 2MB limit."

**[Scroll down slowly]**
"Notice the elements fading in as we scroll. The masonry grid adjusts elegantly, and the hover states use our purple accent color. Here are the pricing tiers, cleanly laid out with flexbox."

**[Scroll to Contact Form]**
"Finally, the contact form. If I fill out my name, email, select 'Character Sheet' from the dropdown, and add a test message..."
*(Fill out form on screen and hit submit)*
"...and submit, you'll see the UI gives feedback. Since there's no backend, if I open the browser DevTools Console..."
*(Open DevTools Console, F12 -> Console)*
"...you can see the form data is neatly intercepted and logged out via JavaScript. And that's the complete responsive single-page portfolio!"
