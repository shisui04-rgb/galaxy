🌌 Interactive Galaxy Visualization
An immersive, animated, and interactive spiral galaxy rendered entirely in HTML, CSS, and JavaScript (with optional TailwindCSS). It simulates stars, planets, nebulae, and spiral arms with dynamic motion and mouse interaction.

🚀 Features
Animated Spiral Galaxy: Stars rotate around the center simulating spiral arm dynamics.

Realistic Star Field: 2,000 stars of varying brightness, size, and color.

Colorful Nebulae: Glowing, blurred nebula clouds scattered across the galaxy.

Orbiting Planets & Moons: Multiple planets orbit the center, some with animated moons.

Interactive Effects:

Mouse movement distorts the galaxy shape.

Zoom in/out and reset view controls.

Toggle animation on/off.

Custom Design: Clean and cosmic UI with a space-themed font (Space Mono) and glowing visuals.

📂 File Structure
All the code is contained in a single index.html file. It includes:

✅ HTML structure

🎨 CSS styles (including Tailwind and custom fonts)

🧠 JavaScript logic for animation and interactivity

🛠️ How It Works
1. Stars
2000 stars are randomly distributed with density favoring the center.

They rotate at speeds based on their distance from the center.

Twinkling effect is achieved via sinusoidal opacity changes.

2. Spiral Arms
4 arms created using patterned placement of stars.

Arms rotate in opposing directions for dynamic realism.

3. Planets & Moons
8 planets orbit the center with unique speeds and distances.

Random chance to generate moons that orbit around their planets.

4. Nebulae
15 semi-transparent, colored blurred shapes.

Slowly rotate and scale subtly to create a pulsing effect.

5. User Interaction
Mouse movement distorts the positions of stars and arms.

Zoom buttons adjust the scale of the galaxy.

Reset button returns to the default zoom and view.

Pause/Resume button controls animation.

🧰 Technologies Used
Tech	Purpose
HTML5	Page structure
CSS3	Styling, animations
TailwindCSS	Utility-first styling
JavaScript (Vanilla)	Animations and logic
Google Fonts	Space Mono for sci-fi aesthetic
