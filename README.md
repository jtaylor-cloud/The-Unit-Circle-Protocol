🏭 Mr. Fraction Factory
An Interactive Fraction Learning Website for Middle School Students

What Is This?
Mr. Fraction Factory is a single-file static HTML website built for middle school students to explore, practice, and understand fractions through interactive visuals and guided lessons. It's themed as an industrial fraction factory, guided by the character Mr. Fraction — a bearded, goggle-wearing inventor who shows students the ropes.
The site is designed with dyslexia-friendly principles: clear sans-serif fonts, high contrast, generous spacing, and visual-first explanations.

Features
The landing page gives students four stations to choose from:
StationWhat It Does📘 Fraction LessonAnimated intro explaining what fractions are, their parts, and how they work — with pizza and pie visuals✂️ Simplify FractionsStudents enter a fraction and get step-by-step simplification using the Euclidean Algorithm, with circle and bar models⚙️ Operate FractionsInteractive addition, subtraction, multiplication, and division with rectangle/grid visual models🔄 Convert FractionsLive conversion between fractions, decimals, and percentages with pie charts, number lines, and bar models

File Structure
/
├── index.html                        ← Main hub page (the factory entrance)
├── fraction_simplifier.html          ← Simplify Fractions station
├── fraction_tool_v14__1_.html        ← Operate Fractions station
├── fraction-converter__1_.html       ← Convert Fractions station
├── Mr__Fraction_Front.png            ← Mr. Fraction facing forward
├── Mr__Fraction_Left_Side.png        ← Mr. Fraction (left profile, working)
├── Mr__Fraction_Right_Side.png       ← Mr. Fraction (right profile, thinking)
├── Mr__Fraction_Back.png             ← Mr. Fraction from behind (pointing)
├── Mr__Fraction_Ladder.png           ← Mr. Fraction climbing a ladder
├── Mr__Fraction_GIF.gif              ← Animated Mr. Fraction
├── Gear.png                          ← Decorative factory gear
├── Pizza.png                         ← Pizza (fraction visual aid)
└── Pie.png                           ← Pie (fraction visual aid)

Note: All files must stay in the same folder for images and navigation links to work correctly. Do not move HTML files into subfolders without updating the src and href paths.


How to Use

Open index.html in any modern web browser (Chrome, Firefox, Edge, Safari).
No internet connection required — except for Google Fonts, which load from the web. Offline fallback fonts are used automatically if unavailable.
No server, build tools, or installation needed. Just open and go.


Design Principles
Dyslexia-Friendly

Uses Atkinson Hyperlegible and Nunito — fonts specifically designed for readability
Large font sizes (minimum 16px body text)
High contrast color themes with clear visual hierarchy
Short sentences and chunked explanations
Visuals paired with every concept

Factory Theme

Warm industrial colors: amber, rust, brown, steel
Animated spinning gears in the background
Mr. Fraction appears throughout to guide and react
Conveyor belt metaphor for moving between topics
Station-based navigation (like factory workstations)


Technical Notes

Pure static HTML/CSS/JS — no frameworks, no dependencies, no build step
Each tool page is self-contained — can be used independently if needed
The main index.html acts as a hub with navigation cards to each station
Animations use CSS keyframes only (no JavaScript animation libraries)
Visual models (pies, bars, grids) are drawn with HTML Canvas or SVG


Customization
Changing Colors
Each page uses CSS custom properties (variables) at the top of the <style> block. Edit those to retheme quickly.
Adding Mr. Fraction Images
Drop new PNG files into the same folder and reference them in the HTML <img src="filename.png">. All images use mix-blend-mode: multiply or transparent backgrounds to blend with the factory theme.
Adding a New Station

Create a new HTML file following the same layout and CSS variable conventions
Add a new station card to index.html linking to it
Add a "Back to Factory" nav link in the new file


Browser Support
Works in all modern browsers. No polyfills needed. Tested in:

Chrome 120+
Firefox 120+
Safari 17+
Edge 120+


Credits

Mr. Fraction character art and all PNG/GIF assets — original illustrations provided by the project creator
Atkinson Hyperlegible font — Braille Institute (free, open license)
Nunito / Fredoka One fonts — Google Fonts (free, open license)
Fraction tool logic adapted from original interactive HTML prototypes


License
This project is intended for educational use. Assets (Mr. Fraction character art) are the property of Jon Taylor and should not be redistributed without permission.
