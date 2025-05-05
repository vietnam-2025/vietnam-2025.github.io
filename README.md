# Vietnam Travel Presentation

## Project Purpose

This project is a web-based slide presentation designed to provide a comprehensive overview of Vietnam for potential tourists or interested individuals. It uses a series of linked HTML pages to simulate a slideshow experience.

## Content

The presentation covers a wide range of topics about Vietnam, including:

*   Introduction and Geography (Map, Key Facts)
*   Rich History and Vibrant Culture (Timeline, Festivals, Traditions)
*   Must-See Destinations (North, Central, South)
*   Natural Wonders (Ha Long Bay, Sapa, Caves, etc.)
*   UNESCO World Heritage Sites
*   Adventure and Activities
*   Cuisine Highlights
*   Practical Travel Tips (Visa, Best Time to Visit, Health, Transport, Currency)
*   Itinerary Suggestions

## Technologies Used

*   **HTML5:** For structuring the content of each slide.
*   **CSS3:** For general styling.
*   **Tailwind CSS:** A utility-first CSS framework used for rapid UI development and styling the slides.
*   **JavaScript:** For handling the slide navigation in `index.html` and potentially for interactive elements within slides.
*   **Chart.js:** Used for creating interactive charts (e.g., average temperature graph).
*   **Mermaid.js:** Used for generating diagrams from text (e.g., historical timeline).
*   **Font Awesome:** For incorporating icons throughout the presentation.
*   **Google Fonts:** For custom typography (`Playfair Display` and `Roboto`).

## Structure

*   The core navigation is handled by `index.html`, which acts as a container using an `<iframe>`.
*   Each numbered HTML file (`01.html` through `12.html`) represents an individual slide in the presentation.
*   JavaScript in `index.html` controls loading the appropriate slide file into the iframe based on user navigation (Next/Previous buttons).
*   Shared styling and layout principles are applied across the slides using Tailwind CSS and custom CSS rules defined within each file's `<style>` tags.
*   An `img/` directory stores all the image assets used in the presentation.
