# HTML & CSS — Navigation Bar and Card Design

## Student Information

| | |
|---|---|
| Name | *[Bibek Yadav  Hajara]* |
| Student ID | *[2602412292]* |
| Course / Module | *[Bsc(Hons) Software Engineering]* |
| Level | *[Level-4]* |
| Assignment | HTML & CSS Practical Assignment: Navigation Bar and Responsive Card Layout |

## Project Description

LearnLoop Academy is a small one-page website for a fictional online coding school. It has a sticky navigation bar with a mobile hamburger menu, an introduction section, a grid of six course cards, and a footer. The navbar, card component and card layout (Parts A to C) are combined into one page (Part D).

## Technologies Used

- HTML5 (semantic elements)
- CSS3 (custom properties, transitions, media queries)
- CSS Flexbox (navbar, inside each card)
- CSS Grid (card layout)
- Responsive CSS

## Project Structure

```
html-css-assignment/
├── index.html
├── css/style.css
├── images/            (6 SVG course illustrations)
├── screenshots/
└── README.md
```

## Learning Resources

> Fill this in with the resources you really used. Replace each row with your own words and delete rows for resources you did not use.

| No. | Resource | Topic Learned | What I Learned | How I Applied It |
|---|---|---|---|---|
| 1 | Teacher's lecture | HTML Structure | I learned how HTML elements are used to structure a webpage.| I used headings, paragraphs, sections, navigation and footer elements.  |
| 2 | Teacher's Material | CSS Selectors| I learned how element, class and ID selectors target HTML elements. | I used class selectors for cards and an ID selector for the website brand. |
| 3 | MDN Web Docs |  CSS Box Model |  I learned how margin, padding and borders affect the size and spacing of elements. |  I applied margin and padding to sections and cards. |
| 4 | W3Schools|  CSS Hover | I learned how the `:hover` pseudo-class changes an element when the mouse moves over it. |  I used hover effects on navigation links and buttons.|

## Key Concepts Used in the Code

- **Semantic HTML:** `<header>`, `<nav>`, `<main>`, `<section>`, `<article>` and `<footer>` describe what each part is, which helps screen readers, search engines and anyone reading the code. Each card is an `<article>` because it is a self-contained item.
- **Selectors:** class selectors (`.card`, `.btn`, `.tag`), the universal selector (`*`) for the reset, descendant selectors (`.nav-links a`), the `:hover` pseudo-class, and the sibling combinators `~` and `+`.
- **Box model:** `box-sizing: border-box` makes padding and borders count inside an element's width. Margin and padding set spacing outside and inside elements.
- **Flexbox:** the navbar uses `display: flex` with `justify-content: space-between` and `align-items: center`. Inside each card, a column flex layout with `margin-top: auto` on the button keeps buttons aligned at the bottom.
- **Grid:** `.card-grid` uses `grid-template-columns: repeat(3, 1fr)` and `gap`. Grid suits this layout because it controls rows and columns together, so all cards get equal widths.
- **Typography:** one font family, a clear size hierarchy (h1, h2, h3, body, small meta text), and comfortable `line-height`.
- **Hover effects:** nav links change background colour; cards lift with `transform: translateY(-6px)` and a stronger shadow; buttons darken. All use `transition` for smoothness.
- **Responsive design:** `@media` queries change the grid to 2 columns at 900px and 1 column at 600px. At 600px the nav links collapse into a hamburger menu built with a hidden checkbox and `:checked`, with no JavaScript.

## Challenges and Solutions
## Challenge 1: Creating spacing between navigation links

At first, the navigation links were too close together.
### Solution

I studied margin and padding and used padding and margin on the navigation links to create appropriate spacing.

## Challenge 2: Making all cards look consistent

The cards initially had different sizes and spacing.
### Solution

I created a common `.course-card` class and applied the same width, height, margin, padding and border styles to all cards.
## Challenge 3: Creating multiple cards without Flexbox or Grid

The assignment does not require Flexbox or CSS Grid.
### Solution

I used `display: inline-block` and vertical alignment to place the cards next to each other.

## AI Usage Disclosure

I used ChatGPT as a learning assistant while completing this assignment..

### What I asked AI for

I asked ChatGPT for help understanding:

- HTML structure
- CSS selectors
- CSS box model
- Navigation bar styling
- Card styling
- Hover effects
- Organizing the project files

### What I learned

I learned how different HTML elements and CSS properties work together to create a webpage.

I also learned how classes can be reused to apply the same design to multiple cards.
### What I implemented myself

I reviewed and understood the generated examples and adapted the HTML and CSS to create my own webpage structure, content and design.

I am responsible for understanding and explaining the final code.
# Conclusion

This assignment helped me understand how HTML and CSS can be used to create a structured webpage.

I practiced HTML elements, CSS selectors, colors, typography, spacing, borders, images, buttons and hover effects.

I also learned how to document my learning process and organize a web project for submission through GitHub.