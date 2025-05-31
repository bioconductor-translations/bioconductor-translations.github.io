# Quarto Website

This project is a Quarto-based website that utilizes the `yeti` HTML theme. It includes a homepage, an about page, and a blog section with a welcome post.

## Project Structure

- **_quarto.yml**: Main configuration file for the Quarto website.
- **index.qmd**: Homepage content file.
- **about.qmd**: About page content file.
- **posts/_metadata.yml**: Metadata for the blog posts.
- **posts/welcome/index.qmd**: Welcome post content file.
- **styles.css**: Custom CSS styles for the website.
- **README.md**: Documentation for the project.

## Getting Started

To build and serve the Quarto website, follow these steps:

1. **Install Quarto**: Ensure you have Quarto installed on your system. You can download it from [quarto.org](https://quarto.org).

2. **Clone the Repository**: Clone this repository to your local machine using:
   ```
   git clone <repository-url>
   ```

3. **Navigate to the Project Directory**:
   ```
   cd quarto-website
   ```

4. **Build the Website**: Run the following command to build the website:
   ```
   quarto render
   ```

5. **Serve the Website**: To preview the website locally, use:
   ```
   quarto serve
   ```

## Customization

You can customize the website by modifying the following files:

- **_quarto.yml**: Change the theme or output formats.
- **styles.css**: Add your own styles to override the default `yeti` theme.
- **index.qmd** and **about.qmd**: Update the content as needed.

## Contributing

If you would like to contribute to this project, please fork the repository and submit a pull request with your changes.

## License

This project is licensed under the MIT License. See the LICENSE file for more details.