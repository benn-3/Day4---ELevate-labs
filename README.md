# DevOps Internship Task 4 – Version-Controlled Web Pages

## Description
This project demonstrates Git version control best practices by managing a simple HTML & CSS website. The goal was to practice branching, merging, pull requests, and tagging in Git/GitHub.

## Branching Workflow
- **feature/webpage**: Development branch where the HTML & CSS web pages were created.
- **dev**: Testing/staging branch, receives merged features from `feature/webpage`.
- **main**: Production branch, contains the final stable version of the project.

## Web Pages
- `index.html` – Home page
- `about.html` – About page
- `contact.html` – Contact page
- `styles.css` – Styling for all pages

## Git Workflow Used
1. Initialize repository and create `feature/webpage` branch
2. Commit HTML & CSS files
3. Push feature branch to GitHub
4. Merge feature branch into `dev` (staging/testing)
5. Merge `dev` into `main` (production)
6. Create a version tag `v1.0` for the release

## Version
- **v1.0** – Initial release with all web pages

## How to View
Open `index.html` in any web browser to view the website.

## Tools & Technologies
- Git & GitHub for version control
- HTML & CSS for web pages
