# Photo Gallery

This is a simple HTML file for creating a photo gallery using CSS flexbox.

## Table of Contents

- [Description](#description)
- [Usage](#usage)
- [License](#license)

## Description

This HTML file provides the basic structure for creating a photo gallery using CSS flexbox. It includes a header with a title and a div element to display a collection of images. Each image is loaded from a remote source.

## Usage

1. Clone or download the repository to your local machine.

2. Open the `index.html` file in your web browser.

3. You should see a header with the title "css flexbox photo gallery" and a grid of images displayed on the page.

4. You can customize the gallery by modifying the image sources and styles in the HTML and CSS files.

## License

This code is distributed under the [MIT License](LICENSE). Feel free to use and modify it as needed for your projects.
# CSS Styles for Photo Gallery

This code provides CSS styles for creating a photo gallery with a header and a grid of images using CSS flexbox.

## Styles

```css
{
    margin: 0;
    box-sizing: border-box;
}

.header
{
    text-align: center;
    text-transform: uppercase;
    padding: 32px;
    background-color: #0a0a23;
    color: #fff;
    border-bottom: 4px solid #fdb347;
}

.gallary
{
    display: flex;
    flex-direction: row;
    flex-wrap: wrap;
    justify-content: center;
    align-items: center;
    gap: 16px;
    max-width: 1400px;
    margin: 0 auto;
    padding: 20px 10px;
}

img
{
    width: 100%;
    max-width: 350px;
    height: 300px;
    object-fit: cover;
    border-radius: 10px ;
}
