# Scavenger-Hunt-Task-3

# Personal Portfolio Website 

This README file will guide you through the process of creating and deploying your own personal portfolio website using GitHub Pages. A portfolio website is a great way to showcase your skills, projects, and achievements to potential employers, clients, and collaborators.

## Table of Contents
1. [Introduction](#introduction)
2. [Prerequisites](#prerequisites)
3. [Getting Started](#getting-started)
4. [Customizing Your Portfolio](#customizing-your-portfolio)
5. [Adding Your Projects](#adding-your-projects)
6. [Deploying to GitHub Pages](#deploying-to-github-pages)
7. [Domain Setup (Optional)](#domain-setup-optional)
8. [Conclusion](#conclusion)

## Introduction

This repository will serve as the foundation for your personal portfolio website. It includes a basic structure and styling that you can customize to match your personal brand. We will use GitHub Pages to host and publish your portfolio website online.

## Prerequisites

Before you begin, make sure you have the following:

1. **GitHub Account**: You need a GitHub account to host your repository.
2. **Git**: Install Git on your computer to manage version control.
3. **Code Editor**: Choose a code editor like Visual Studio Code, Sublime Text, or Atom.
4. **Basic HTML and CSS knowledge**: Familiarity with HTML and CSS will be helpful for customization.

## Getting Started

1. **Fork the Repository**: Click the "Fork" button at the top right corner of this repository to create your own copy.

2. **Clone the Repository**: Open your terminal or command prompt and navigate to a directory where you want to store your project. Run the following command to clone your forked repository:
   
   ```bash
   git clone https://github.com/yourusername/your-portfolio.git
   ```
   
3. **Navigate to the Project Directory**: Move into the project directory:
   
   ```bash
   cd your-portfolio
   ```

4. **Install Dependencies**: If there are any dependencies listed (usually in a `package.json` file), install them using the appropriate package manager (e.g., npm or yarn).
   
   ```bash
   npm install
   ```

## Customizing Your Portfolio

Open the project folder in your chosen code editor. Here are a few files you might want to customize:

- `index.html`: Update your name, tagline, and other introductory information.
- `assets/css/style.css`: Modify the CSS to match your desired style and layout.

## Adding Your Projects

You'll likely want to showcase your projects on your portfolio. Create a new HTML file for each project in the `projects` directory. You can use the provided `project-template.html` as a starting point.

Remember to link to your project pages from your main `index.html` or any other relevant sections.

## Deploying to GitHub Pages

1. **Create a GitHub Repository**: Go to your GitHub account and create a new repository named `yourusername.github.io`, where `yourusername` is your actual GitHub username. This repository will host your portfolio.

2. **Configure Remote Origin**: In your local project directory, configure Git to point to your GitHub repository:

   ```bash
   git remote set-url origin https://github.com/yourusername/yourusername.github.io.git
   ```

3. **Commit and Push**: Commit your changes and push them to the `main` branch of your GitHub repository:

   ```bash
   git add .
   git commit -m "Initial commit"
   git push origin main
   ```

4. **Visit Your Portfolio**: After a few moments, your portfolio will be accessible at `https://yourusername.github.io`.

## Domain Setup (Optional)

If you have a custom domain, you can set it up for your GitHub Pages portfolio. Follow GitHub's guide on [setting up a custom domain](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site).

## Conclusion

Congratulations! You now have your personal portfolio website up and running on GitHub Pages. Regularly update your portfolio with new projects and achievements to keep it fresh and engaging for visitors. Happy coding!

If you have any further questions or need more advanced customization, refer to GitHub's official documentation or explore more about web development using HTML, CSS, and JavaScript.

## Final step:
To complete the third task of scavenger hunt, you need to make a Pull Request in this repository having the link of your personal portfolio website. 
All the best!!✨
