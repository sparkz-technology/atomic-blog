# Atomic Blog

Atomic Blog is a React application that showcases a blog with dynamically generated posts. It utilizes the `@faker-js/faker` library to create random post titles and bodies. The application provides functionality to add posts, clear all posts, and search for specific posts based on title or body content.

## Features

- Randomly generated blog posts with dynamic titles and bodies using the `@faker-js/faker` library.
- Add new posts to the blog.
- Clear all existing posts from the blog.
- Search for specific posts based on the title or body content.

## Usage

To use the Atomic Blog application:

1. Install the required dependencies by running `npm install`.
2. Start the development server by running `npm start`.
3. Open the application in your browser at `http://localhost:3000`.

The application allows you to view the generated blog posts, add new posts, clear existing posts, and search for specific posts using the search bar.

## Customization

You can customize the Atomic Blog application by modifying the following:

- Update the `createRandomPost` function in `PostProvider.js` to generate posts with different content or structure.
- Adjust the styles and layout of the components by modifying the CSS in the respective component files.

Feel free to customize the application according to your own preferences and requirements.

## Dependencies

The application relies on the following dependencies:

- React: A JavaScript library for building user interfaces.
- React DOM: The entry point for interacting with the DOM.
- React Scripts: Configuration and scripts for running the React application.
- @faker-js/faker: A library for generating fake data.

All dependencies are listed in the `package.json` file.
