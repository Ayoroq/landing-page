# The Odin Project: Landing Page

This project is a solution to the "Landing Page" assignment from [The Odin Project's](https://www.theodinproject.com/lessons/foundations-landing-page) Foundations course. The goal was to build a complete landing page from scratch based on a provided design, demonstrating proficiency in HTML structure and CSS styling, with a strong focus on using Flexbox for layout.

## Screenshot

![Project Screenshot](/images/Landing_Page.jpeg)

## About This README

This README provides an overview of the project, describes the development process, and documents the structure and features of the landing page. It also includes image credits and acknowledgements to ensure proper attribution and transparency. The README is intended to help others understand the approach taken, the tools used, and how to navigate or contribute to the project.

## Features

- A clean, multi-section layout.
- A header with a logo and navigation links.
- A hero section with a title, descriptive text, a call-to-action button, and an image.
- An information section with cards displaying images and text.
- An inspiring quote section.
- A call-to-action banner.
- A simple footer with copyright information.

## Built With

- Semantic HTML5
- CSS3
- Flexbox

## The Process

Building this landing page was a step-by-step process, focusing on structuring the content first and then applying styles.

### 1. HTML Structure (The Skeleton)

The first step was to create the basic HTML structure. I used semantic HTML5 tags to define the different sections of the page for better readability and accessibility:

- `<nav>` for the top navigation bar.
- `<header>` for the main hero section.
- `<section>` for the distinct content areas (information, quote, call-to-action).
- `<footer>` for the bottom of the page.

A general `.container` class was used within each section to maintain a consistent width and center the content on the page.

### 2. CSS Styling (The Skin)

With the HTML structure in place, I moved on to styling with CSS.

- **Initial Setup:** I started with a basic CSS reset (`* { box-sizing: border-box; margin: 0; padding: 0; }`) to ensure consistent behavior across different browsers. I also set up the main font (`Roboto`) and a base `line-height`. The `body` was set to `display: flex` with `flex-direction: column` to allow the footer to stick to the bottom of the page on shorter content pages.

- **Flexbox for Layout:** Flexbox was the primary tool for layout.

  - The `navbar`, `header`, and call-to-action `section` all use `display: flex` on their `.container` to align items horizontally. `justify-content: space-between` or `space-around` and `align-items: center` were used to position the elements correctly.
  - The information section (`.section-1 .boxes`) uses `display: flex` to arrange the information cards in a row.
  - The quote section (`.section-2`) uses `display: flex` with `flex-direction: column` to stack the quote and the author, with `align-self: flex-end` on the author to push it to the right.

- **Styling Sections:** Each section was styled individually to match the design mockup, including background colors, font sizes, colors, and padding. Buttons and links were given `:hover` states for better user interaction.

- **Adjustments From Template**: Some adjustments were made from the  given template such as choosing to use a smaller font size when the one being used in the template was too big.

> [!NOTE]
> This is my first attempt at using flexbox and the code in the css might be a little rough or not up to standard, i really don't know as i'm just practicing and getting familiar with it.
> If you have suggestions, or advice please let me know.

###

## Image Credits

The images used in this project were sourced from various platforms. A huge thank you to the photographers for their beautiful work.

- **Header Bird (`Macaw.jpg`):** By [Europeana](https://unsplash.com/photos/5NqwmKjx6jo) on Unsplash
- **Cockatiel (`Cockatiel.jpg`):** By [David Clode](https://unsplash.com/photos/a-close-up-of-a-bird-on-a-tree-branch-EA0BMEBoWXo) on Unsplash
- **Brahminy Kite (`Brahminy Kite.jpg`):** By [Cade](https://unsplash.com/photos/white-and-brown-bird-on-gray-rock-during-daytime-8zSbmf3pl2Q) on Unsplash
- **Common Wood Pigeon (`Pigeon.jpg`):** By [Jolanda Legeer](https://unsplash.com/photos/a-gray-and-white-bird-sitting-on-top-of-a-tree-Uo2bPl11jn8) on Unsplash
- **Greater Flamingo (`Flamingo.jpg`):** By [Gwen Weustink](https://unsplash.com/photos/close-up-photography-of-a-pink-bird-HvCtRFpxK8s) on Unsplash

## Acknowledgements

- [The Odin Project](https://www.theodinproject.com/) for the curriculum and project inspiration.
- [Unsplash](https://unsplash.com/) and other free image providers for the bird images.

---

## License

This project is for educational purposes only.
