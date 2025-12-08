### Directory Overview

This directory contains a collection of static HTML/CSS/JS web pages that form a "Cyber Productivity Hub". The main entry point is `index.html`, which serves as a dashboard linking to various tools. The project is written in French and has a consistent "cyberpunk" aesthetic. All styling and scripts are embedded directly within the HTML files; there is no build system or package management.

### Key Files

*   `index.html`: The main dashboard and entry point for the productivity hub. It displays a clock, a list of long-term goals, and a grid of links to the other tool pages.
*   `todo app.html`: A to-do list application with features for adding, editing, deleting, reordering, and importing tasks. It uses Supabase for backend data storage.
*   `meteo.html`: A weather application that displays current weather and a 24-hour forecast. It can use the user's current location or a pre-defined list of locations and fetches data from the Open-Meteo API.
*   `rss.html`: An RSS feed reader that aggregates articles from several tech news websites. It features infinite scroll and a native share button.
*   `AGENTS.md`: A file that outlines the coding conventions and guidelines used in the project.
*   Other `.html` files: Each file provides a specific tool or utility, such as a Pomodoro timer, a Tabata workout timer, a simple tab page, etc.

### Usage

The contents of this directory are intended to be used as a personal, web-based productivity dashboard. To use it, simply open the `index.html` file in a web browser. From there, you can navigate to the various tools and applications. Since the files are all static, they can be hosted on any web server that can serve HTML files, or used directly from the local filesystem. The `todo app.html` requires an internet connection to connect to its Supabase backend.
