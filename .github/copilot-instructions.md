# AI Coding Agent Instructions for web_project_homeland

## Overview
This project is a web application for the homeland project under TT. It is structured to facilitate easy navigation and maintainability. The main components include:
- **Blocks**: Contains reusable CSS files for different sections of the website (e.g., header, footer, main content).
- **Images**: Stores all image assets used in the project.
- **Pages**: Contains specific styles for different pages.
- **Vendor**: Includes third-party styles and fonts.

## Architecture
- **Component Structure**: The project is organized into distinct folders for blocks, images, pages, and vendor resources. Each folder serves a specific purpose, promoting modularity.
- **CSS Files**: Each block has its own CSS file (e.g., `header.css`, `footer.css`, `main.css`, `page.css`) to manage styles independently.

## Developer Workflows
- **Building**: Ensure all CSS files are linked correctly in the HTML files. Use a local server to view changes in real-time.
- **Testing**: Test the application in multiple browsers to ensure compatibility. Use browser developer tools for debugging CSS issues.
- **Debugging**: Inspect elements using browser tools to identify and fix layout issues. Check console for JavaScript errors if applicable.

## Project Conventions
- **CSS Naming**: Follow BEM (Block Element Modifier) methodology for class naming to maintain clarity and avoid conflicts.
- **File Naming**: Use lowercase and hyphens for file names (e.g., `main.css`, `footer.css`).

## Integration Points
- **External Dependencies**: The project uses Normalize.css for consistent styling across browsers. Ensure it is included in the vendor folder.
- **Cross-Component Communication**: Styles are shared across components through the main CSS files, ensuring a cohesive look and feel.

## Key Files
- **[README.md](README.md)**: Provides an overview of the project.
- **[blocks/](blocks/)**: Contains all block-specific styles.
- **[vendor/](vendor/)**: Includes third-party styles and fonts.

## Conclusion
This document serves as a guide for AI coding agents to understand the structure and workflows of the web_project_homeland. For further details, refer to the specific CSS files and the README.md for project context.