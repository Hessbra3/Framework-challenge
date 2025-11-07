# Dropbox iPad Case Project

This project is designed to create a visually appealing and functional iPad case for Dropbox using Bootstrap. The project includes various components such as a header, footer, case preview, and a gallery to showcase the product.

## Project Structure

```
dropbox-ipad-case
├── src
│   ├── index.html          # Main entry point for the application
│   ├── components          # Contains reusable HTML components
│   │   ├── header.html     # Header section with navigation
│   │   ├── footer.html     # Footer section with copyright info
│   │   ├── case-preview.html # Preview of the iPad case design
│   │   └── gallery.html    # Gallery of images for the iPad case
│   ├── css
│   │   └── styles.css      # Custom CSS styles
│   ├── scss
│   │   └── _variables.scss  # SCSS variables for easy customization
│   └── assets
│       ├── fonts           # Custom font files
│       └── svgs            # SVG files for icons and illustrations
├── package.json            # npm configuration file
├── .gitignore              # Files and directories to ignore by Git
└── README.md               # Project documentation
```

## Setup Instructions

1. **Clone the repository**:
   ```bash
   git clone <repository-url>
   cd dropbox-ipad-case
   ```

2. **Install dependencies**:
   ```bash
   npm install
   ```

3. **Run the project**:
   You can use a local server to view the project. For example, you can use the `live-server` package:
   ```bash
   npx live-server src/index.html
   ```

## Features

- Responsive design using Bootstrap
- Custom styles for the iPad case
- Image gallery to showcase different designs
- Easy navigation with a header and footer

## Usage Guidelines

- Modify the SCSS variables in `_variables.scss` to customize the design.
- Update the HTML components in the `components` directory as needed.
- Add any custom fonts to the `assets/fonts` directory and reference them in `styles.css`.

Feel free to contribute to the project by submitting issues or pull requests!