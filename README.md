# ReadMate - Book Tracker
<img width="1920" alt="readmate-rounded" src="https://github.com/ivanstudio/readmate/assets/readmate-image">

This app is a book tracker for tracking the books you read. Built with Astro, it utilizes simple HTML and CSS for design and layout, ensuring simplicity and speed. Ideal for readers looking to manage their reading journey.

## Features

- **No Dependencies**: Apart from Astro, this app does not use any external dependencies.
- **Fully Customizable**: Customize every element of the app including fonts, images, and text by simple edits.
- **Responsive Design**: Ensures your app looks stunning on both desktop and mobile devices.

## Usage

To begin using this app, we recommend taking advantage of the GitHub "Use this template" feature, located above the Clone button. This will allow you to create a separate repository where you can customize the app as you wish.

## Getting Started

1. Create a new repository by clicking "Use this template".
2. Navigate to the project directory and install dependencies with `npm install`.
3. Start the development server with `npm start`.

## Customization Guide

### Content

Edit the frontmatter section at the top of `/src/pages/index.astro` to update the website content, including text and images.

### Styles

All CSS is located in `/src/styles/main.css`. Modify this file to change the look and feel of the site.

### Images

Replace images by uploading new ones to the `/public/images` folder and update the references in the frontmatter of `index.astro`.

### Fonts

Add new font files to `/public/fonts` and reference them in `/src/styles/main.css` to change fonts. For easy integration of Google Fonts into your project, check out [Hermes](https://github.com/cadensstudio/hermes).

## Project Structure

- `/src/pages/index.astro`: The main HTML file for your landing page.
- `/src/styles/main.css`: CSS file for styling your landing page.
- `/public/images`: Directory for storing images.
- `/public/fonts`: Directory for storing fonts.

## Deployment

This app can be deployed on any static site hosting service that supports Astro. Follow the hosting provider's instructions for deploying an Astro project.

To view a live version of this site, see https://readmate.app.
# readmate-landing
