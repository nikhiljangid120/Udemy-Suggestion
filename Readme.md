Udemy Homepage with AI-Powered Learning Path Generator
======================================================

This project is a pixel-perfect reproduction of Udemy's homepage, enhanced with an **AI-Powered Personalized Learning Path Generator**. Built for the **Level Up Vibe Coding Hackathon**, it showcases advanced features like dynamic content generation, responsive design, and interactive UI elements---all within a single HTML file.

Features
--------

-   **Pixel-Perfect Udemy Homepage**: Meticulously matches Udemy's design, including header, hero, search bar, course carousel, categories, testimonials, and footer.
-   **AI-Powered Learning Path Generator**: A prominent, always-visible section that generates tailored learning paths based on user inputs (goals, skill level, time, learning style).
    -   **Hardcoded Dataset**: Covers 9 fields/stacks (Java, Python, Full Stack, MERN Stack, Video Editing, Data Science, UI/UX Design, Game Development, Cybersecurity) with detailed steps, Udemy course recommendations, and timelines.
    -   **Personalization**: Paths adapt to user inputs, with a fallback for unrecognized goals.
-   **Interactive UI**: Includes search filtering, category tabs, a smooth carousel, and animated elements (e.g., progress bar, timeline pulses).
-   **Responsive Design**: Fully functional on mobile, tablet, and desktop, using Tailwind CSS for consistency.
-   **Local Storage**: Saves generated learning paths for persistence across sessions.

How to Run
----------

1.  **Open the HTML File**: Simply open `index.html` in any modern browser.
2.  **Explore the Features**:
    -   Use the search bar to filter courses.
    -   Click category tabs to filter the carousel.
    -   Scroll to the AI Learning Path Generator, input your goals (e.g., "Learn MERN Stack"), and submit to see a personalized path.
3.  **No Dependencies**: All assets (Font Awesome, Tailwind CSS) are loaded via CDN.

Technical Details
-----------------

-   **Languages**: HTML, CSS (Tailwind), JavaScript
-   **Key Scripts**:
    -   `learningPaths` object: Contains hardcoded data for 9+ stacks with steps, courses, and timelines.
    -   `displayResults`: Dynamically renders the learning path with animations.
-   **Animations**: CSS-based for performance (e.g., fade-ins, pulses).
-   **Memory Alignment**: Tailored to interests in MERN Stack, full-stack development, and polished UI.

Standout Feature
----------------

The **AI-Powered Learning Path Generator** is the submission's highlight:

-   **Complexity**: Processes user inputs to select and personalize a learning path from a rich dataset, simulating AI behavior without external APIs.
-   **Innovation**: Provides a feature not present in Udemy's original app, enhancing user experience with tailored education plans.
-   **Polish**: Uses Tailwind CSS for a modern, consistent UI with smooth interactions and animations.

This project balances technical precision, creativity, and user-centric design, making it a strong contender in the hackathon.
