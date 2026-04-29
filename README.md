# Color Fundamentals for Painters

An interactive, client side web application for exploring color theory concepts through real time visualization and simulation. The system is designed around the traditional RYB color model used in painting rather than RGB, providing a more accurate representation of pigment based color behavior.

---

## Overview

This project implements a modular single page web application that enables users to explore relationships between colors, simulate pigment mixing, and understand theoretical concepts through interactive UI components.

The application focuses on bridging visual design, perceptual psychology, and computational modeling by translating abstract color theory into dynamic, user driven interactions.

---

## System Architecture

The application follows a client side component based structure implemented in vanilla JavaScript.

- Single HTML entry point (index.html)  
- Inline CSS for styling and layout  
- Modular JavaScript logic for interaction and rendering  

There is no backend dependency. All computations and state management are handled in the browser.

---

## Core Functional Modules

### 1. Color Wheel Engine

- Implements RYB to HSL hue mapping  
- Uses canvas rendering for interactive input  
- Supports dynamic generation of:
  - Complementary  
  - Analogous  
  - Triadic  
  - Tetradic  
  - Split complementary  
  - Square palettes  
- Provides real time updates based on user interaction (drag events)  

---

### 2. Pigment Mixing System

- Simulates subtractive color mixing behavior  
- Uses predefined pigment data mapped to realistic outputs  

Features:
- Target color preview  
- Step by step mixing instructions  
- Contextual mixing tips  

---

### 3. Concept Rendering Engine

- Collapsible UI blocks for structured learning  
- Dynamically injects content into the DOM  
- Organized by topic hierarchy aligned with course structure  

---

### 4. Harmony Testing Tool

- Accepts user defined color input (HEX or color picker)  
- Converts and normalizes color values  
- Computes multiple harmony schemes simultaneously  

Displays:
- Visual swatches  
- Color metadata  
- Explanatory descriptions  

---

### 5. Visual Glossary

- Searchable and filterable dataset  
- Categorized terminology such as hue, chroma, and value  
- Dynamic filtering based on user input  

---

## Color Modeling Approach

Unlike typical web applications that rely on RGB, this system prioritizes artist oriented color logic.

- Custom mapping between RYB and HSL color spaces  
- Emphasis on perceptual accuracy over digital precision  

Supports simulation of:
- Hue relationships  
- Saturation shifts  
- Value adjustments  
- Neutralization using complementary colors  

---

## Technologies

- HTML5 for semantic structure  
- CSS3 for layout, responsive design, and styling  
- JavaScript (ES6) for application logic and interactivity  
- Canvas API for color wheel rendering  

No external libraries or frameworks are used.

---

## Live Demo

https://shovkatzeynal.github.io/color_fundamentals/

---

## Design Considerations

- No framework dependency, making the project lightweight and portable  
- Immediate feedback loops to improve user learning  
- Minimal UI to reduce cognitive load  
- Interactive first approach to prioritize exploration over static content  

---

## Limitations

- Color mixing is approximated and not physically exact  
- No persistence layer, state resets on refresh  
- Not optimized for color vision deficiencies  

---

## Future Improvements

- Add CIELAB based color modeling for improved perceptual accuracy  
- Introduce state persistence using localStorage  
- Improve accessibility including contrast and colorblind modes  
- Modularize into a component based framework such as React  
- Add backend support for saving palettes  

---

## License

This project is intended for educational and portfolio use.
