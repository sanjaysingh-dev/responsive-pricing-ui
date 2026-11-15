# Responsive Pricing UI

A responsive pricing component built using **HTML5 and CSS3**. This project displays three subscription plans — Basic, Professional, and Master, with a monthly/annual pricing toggle.

This is a frontend demonstration project created to practise HTML and CSS fundamentals, including Flexbox, CSS selectors, combinators, media queries, and transitions.

## Features

- **Three Pricing Plans:** Basic, Professional, and Master.
- **Pricing Toggle:** Switch between monthly and annual pricing using a CSS checkbox.
- **Responsive Layout:** Different layouts for mobile, tablet, and desktop screens.
- **CSS Transitions:** Smooth animation for the pricing toggle.
- **Custom Styling:** Gradient backgrounds, typography, and decorative background images.
- **Google Fonts:** Uses the Montserrat font family.

## Technologies Used

- HTML5
- CSS3
- Flexbox
- CSS Media Queries
- CSS Selectors and Combinators
- CSS Transitions
- Google Fonts

## Project Structure

```text
pricing-html-css/
│
├── index.html
├── style.css
├── README.md
├── style-guide.md
│
└── images/
    ├── bg-top.svg
    ├── bg-bottom.svg
    └── favicon-32x32.png
```

## Getting Started

### 1. Clone the Repository

```bash
git clone <your-repository-url>
```

### 2. Navigate to the Project Directory

```bash
cd pricing-html-css
```

### 3. Run the Project

Open `index.html` in your browser.

Alternatively, use the Live Server extension in VS Code.

## Pricing Plans

| Feature               |  Basic | Professional | Master |
| :-------------------- | -----: | -----------: | -----: |
| Storage               | 500 GB |         1 TB |   2 TB |
| Users Allowed         |      2 |            5 |     10 |
| Maximum File Transfer |   3 GB |        10 GB |  20 GB |

### Pricing Details

| Plan         | Monthly | Annually |
| :----------- | ------: | -------: |
| Basic        |  $19.99 |  $199.99 |
| Professional |  $24.99 |  $249.99 |
| Master       |  $39.99 |  $399.99 |

## Responsive Design

The layout uses CSS media queries to adapt to different screen sizes:

- **Mobile:** Single-column layout.
- **Tablet:** Two-column layout with wrapping.
- **Desktop:** Three-column layout.

## Implementation Notes

- The project uses basic HTML elements and `div` containers for structuring the content. Semantic HTML elements such as `<main>`, `<section>`, and `<article>` have not been implemented.
- The monthly/annual pricing toggle is implemented using a checkbox and CSS selectors, without JavaScript.
- Flexbox is used to arrange and align the pricing cards.
- Media queries are used to adjust the layout across different screen sizes.
- The Learn More buttons are included for demonstration purposes and do not perform any actual action.

## Learning Outcomes

Through this project, I practised:

- Structuring a webpage using HTML.
- Applying styles using external CSS.
- Understanding and implementing Flexbox layouts.
- Creating responsive layouts using CSS media queries.
- Working with CSS selectors and combinators (`+` and `~`).
- Using checkbox states and the `:checked` pseudo-class to create interactive UI elements without JavaScript.
- Applying CSS transitions and gradients.
- Integrating Google Fonts and external image assets.

## Author

**Sanjay Singh**