Visit URL: https://sadekmia24845.github.io/Front-End-Design-With-API/

Visit URL: https://genuine-cranachan-86d577.netlify.app/

Phone Explorer - Device Specification Finder

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![REST API](https://img.shields.io/badge/REST-API-005571?logo=api&logoColor=white)](https://restfulapi.net/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Overview

Phone Explorer is a lightweight, fully responsive front-end web application that allows users to search for mobile phones and view their core technical specifications instantly. Built with pure Vanilla JavaScript, it demonstrates seamless REST API integration, dynamic DOM manipulation, and an intuitive modal-based UI for displaying detailed device information.

This project is perfect for developers looking to understand how to fetch data from an API, handle user events (including keyboard shortcuts), and render dynamic content without any external frameworks.

---

Key Features

- Smart Search: Search for any phone by name or keyword.
- Keyboard Shortcut: Press the `Enter` key directly from the search bar to trigger a search (improves UX).
- Dynamic Card Listing: Displays search results in a clean, grid-based card layout showing the phone's image and name.
- Detailed Modal View: Click the "Details" button to open a beautifully styled modal that displays:
  - Brand
  - Storage capacity
  - Display size
  - Chipset / Processor
  - Release date
- Graceful Fallbacks: Automatically displays `"Not Available"` or `"No release date found"` when API data is missing.
- Clean UI: Modern, distraction-free interface optimized for both desktop and mobile screens.

---

Tech Stack

| Category | Technology |
| :--- | :--- |
| Markup | HTML5 |
| Styling | CSS3 (Custom) |
| Logic | Vanilla JavaScript (ES6+) |
| HTTP Requests | Fetch API |
| Data Format | JSON (RESTful API) |

---

Project Structure

The project follows a simple and straightforward file structure:

```text
FRONT-END-DESIGN/
├── index.html               # Main HTML entry point
├── style.css                # All custom styles (layout, cards, modal styling)
├── js/
│   └── script.js            # Core JavaScript (Search, API calls, Modal logic)
├── Iphone 17 pro max.png    # Static image asset
└── iphone.png               # Static image asset
