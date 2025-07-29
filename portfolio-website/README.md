# Personal UX/UI Designer Portfolio

This is a responsive and accessible personal portfolio website for a UX/UI designer. The website showcases the designer's work, including an overview of projects, a CV, and a contact form.

## Project Structure

The project is organized as follows:

```
portfolio-website
├── src
│   ├── index.html        # Main entry point of the portfolio website
│   ├── about.html        # About Me section
│   ├── cv.html           # Curriculum Vitae
│   ├── contact.html       # Contact form
│   ├── projects
│   │   ├── project1.html # Detailed overview of Project 1
│   │   ├── project2.html # Detailed overview of Project 2
│   │   ├── project3.html # Detailed overview of Project 3
│   │   └── project4.html # Detailed overview of Project 4
│   ├── css
│   │   └── style.css     # Styles for the entire website
│   ├── js
│   │   └── main.js       # JavaScript for scroll behavior and animations
│   └── assets
│       └── fonts         # Custom fonts for typography
├── .github
│   └── workflows
│       └── pages.yml     # GitHub Actions workflow for deployment
├── README.md             # Project documentation
└── package.json          # npm configuration file
```

## Features

- **Responsive Design**: The website is designed to be mobile-friendly and adapts to different screen sizes.
- **Animations**: Smooth scroll behavior and animations enhance user experience.
- **Project Overviews**: Each project has a dedicated page with detailed descriptions and visuals.
- **Contact Form**: Visitors can easily reach out through a simple contact form.

## Setup Instructions

1. Clone the repository to your local machine:
   ```
   git clone https://github.com/yourusername/portfolio-website.git
   ```

2. Navigate to the project directory:
   ```
   cd portfolio-website
   ```

3. Open the `src/index.html` file in your web browser to view the portfolio.

4. To edit content, modify the respective HTML files in the `src` directory.

## Deployment

This portfolio is hosted on GitHub Pages. To deploy your changes, push your updates to the `main` branch of the repository. The GitHub Actions workflow in `.github/workflows/pages.yml` will automatically build and deploy the site.

## Editing Content

- **About Me**: Update `src/about.html` for personal information and design philosophy.
- **CV**: Modify `src/cv.html` to keep your CV up to date.
- **Projects**: Each project overview can be edited in the respective `src/projects/projectX.html` files.
- **Contact**: Adjust the contact form in `src/contact.html` as needed.

## License

This project is licensed under the MIT License. Feel free to use and modify it for your own portfolio.