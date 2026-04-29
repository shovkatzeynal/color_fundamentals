🎨 Color Fundamentals for Painters
An interactive, client-side web application for exploring color theory concepts through real-time visualization and simulation. The system is designed around the traditional RYB color model used in painting, rather than RGB, providing a more accurate representation of pigment-based color behavior.


Overview
This project implements a modular, single-page web application (SPA) that enables users to explore relationships between colors, simulate pigment mixing, and understand theoretical concepts through interactive UI components.
The application focuses on bridging visual design, perceptual psychology, and computational modeling by translating abstract color theory into dynamic, user-driven interactions.


System Architecture
The application follows a client-side, component-based structure implemented in vanilla JavaScript:
Single HTML entry point (index.html)
Inline CSS for styling and layout
Modular JavaScript logic for interaction and rendering
There is no backend dependency; all computations and state management are handled in the browser.


Core Functional Modules
1. Color Wheel Engine
Implements RYB → HSL hue mapping
Uses canvas rendering for interactive input
Supports dynamic generation of:
Complementary
Analogous
Triadic
Tetradic
Split-complementary
Square palettes
Real-time updates based on user interaction (drag events)
2. 🎨 Pigment Mixing System
Simulates subtractive color mixing behavior
Uses predefined pigment data mapped to realistic outputs
Generates:
Target color preview
Step-by-step mixing instructions
Contextual mixing tips
3. Concept Rendering Engine
Collapsible UI blocks for structured learning
Dynamically injects content into DOM
Organized by topic hierarchy (aligned with course structure)
4. Harmony Testing Tool
Accepts user-defined color input (HEX / picker)
Converts and normalizes color values
Computes multiple harmony schemes simultaneously
Displays results with:
Visual swatches
Color metadata
Explanatory descriptions
5. Visual Glossary
Searchable and filterable dataset
Categorized terminology (e.g., hue, chroma, value)
Dynamic filtering based on user input
Color Modeling Approach

Unlike typical web applications that rely on RGB, this system prioritizes artist-oriented color logic:
Custom mapping between RYB and HSL color spaces
Emphasis on perceptual accuracy over digital precision
Simulation of:
Hue relationships
Saturation shifts
Value adjustments
Neutralization via complementary mixing


🛠️ Technologies
HTML5 – semantic structure
CSS3 – layout, responsive design, custom properties
JavaScript (ES6) – application logic and interactivity
Canvas API – color wheel rendering

No external libraries or frameworks are used.

Getting Started
https://shovkatzeynal.github.io/color_fundamentals/

📈 Design Considerations
No framework dependency → lightweight and portable
Immediate feedback loops → improves user learning
Minimal UI → reduces cognitive load
Interactive-first approach → prioritizes exploration over static content


⚠️ Limitations
Color mixing is approximated, not physically accurate
No persistence layer (state resets on refresh)
Not optimized for color vision deficiencies (future improvement)
Future Improvements
Add CIELAB-based color modeling for perceptual accuracy
Introduce state persistence (localStorage)
Improve accessibility (WCAG contrast + colorblind modes)
Modularize into React or component framework
Add backend for saving palettes

📄 License
This project is intended for educational and portfolio use.
