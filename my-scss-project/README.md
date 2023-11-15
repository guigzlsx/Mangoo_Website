# My SCSS Project

This project uses the 7-1 architecture pattern for organizing SCSS files. The structure is modular and easy to maintain, making it ideal for large projects.

## Project Structure

The project is structured as follows:

- `abstracts`: This directory contains all the Sass variables and mixins that are used throughout the project.
- `base`: This directory contains the base styles for the project, including a CSS reset and typography styles.
- `components`: This directory contains the styles for individual components, such as buttons.
- `layout`: This directory contains the styles for larger layout components, such as the header and footer.
- `pages`: This directory contains the styles specific to individual pages.
- `themes`: This directory contains the styles for different themes.
- `vendors`: This directory contains any third-party styles, such as Bootstrap.
- `main.scss`: This is the main Sass file that imports all the other Sass files.

## Usage

To use this project, import the `main.scss` file into your project. This file will import all the other necessary files.

## Customization

You can customize the project by modifying the variables in the `abstracts/_variables.scss` file and the mixins in the `abstracts/_mixins.scss` file. You can also add your own styles to the `components`, `layout`, `pages`, and `themes` directories.

## Dependencies

This project uses Bootstrap for some styles. You can find the Bootstrap styles in the `vendors/_bootstrap.scss` file.