📐 Flex Box Layout – HTML & CSS

A simple HTML and CSS Flexbox layout project that demonstrates how to divide a webpage into multiple sections using CSS dimensions, colors, and Flexbox.

The project creates a structured webpage layout containing a header, center section, sidebar, content area, nested sections, and footer.

📸 Project Overview

The webpage is divided into three major sections:

- Header
- Center Content
- Footer

The center section is further divided into:

- Left sidebar
- Right content area

The right content area contains:

- Top section
- Bottom section
  - Bottom Left
  - Bottom Right

Layout Structure

┌─────────────────────────────────────────────┐
│                   HEADER                    │
├───────────┬─────────────────────────────────┤
│           │              TOP                │
│   LEFT    ├─────────────────────────────────┤
│  SIDEBAR  │           BOTTOM                │
│           │     ┌──────────┬──────────┐     │
│           │     │ BOTTOM 1 │ BOTTOM 2 │     │
│           │     └──────────┴──────────┘     │
├───────────┴─────────────────────────────────┤
│                   FOOTER                    │
└─────────────────────────────────────────────┘

🛠️ Technologies Used

- HTML5
- CSS3
- Flexbox

No external libraries or frameworks are required.

📂 Project Structure

flexbox-layout/
│
├── index.html
└── README.md

🎨 CSS Layout

Main Container

.con {
    height: 600px;
    border: 1px solid black;
}

The main container has a fixed height of 600px and a black border.

🟦 Header

The header occupies 20% of the container height:

.header {
    height: 20%;
    background-color: teal;
}

🟨 Center Section

The center section occupies 60% of the container:

.center {
    height: 60%;
    background-color: beige;
    display: flex;
}

The "display: flex" property allows the left and right sections to appear side by side.

🟧 Left Section

The left section works as a sidebar:

.left {
    height: 100%;
    background-color: orange;
    width: 20%;
}

It takes 20% of the center section's width.

🔴 Right Section

The right section takes the remaining 80%:

.right {
    height: 100%;
    background-color: orangered;
    width: 80%;
}

It contains the top and bottom sections.

🟫 Top Section

The top section occupies half of the right section:

.top {
    height: 50%;
    background-color: brown;
}

🔻 Bottom Section

The bottom section also occupies 50% of the right section:

.bottom {
    height: 50%;
    background-color: red;
    display: flex;
}

It uses Flexbox to divide itself into two equal sections.

🟤 Bottom 1

.bottom1 {
    height: 100%;
    width: 50%;
    background-color: chocolate;
}

This section occupies half of the bottom area.

🟡 Bottom 2

.bottom2 {
    height: 100%;
    width: 50%;
    background-color: goldenrod;
}

This section occupies the other half.

🎨 Color Scheme

Section| Background Color
Header| Teal
Center| Beige
Left| Orange
Right| Orangered
Top| Brown
Bottom| Red
Bottom 1| Chocolate
Bottom 2| Goldenrod
Footer| Teal

📊 Layout Distribution

Section| Height| Width
Header| 20%| 100%
Center| 60%| 100%
Left| 100% of center| 20%
Right| 100% of center| 80%
Top| 50% of right| 100%
Bottom| 50% of right| 100%
Bottom 1| 100% of bottom| 50%
Bottom 2| 100% of bottom| 50%
Footer| 20%| 100%

▶️ How to Run

1. Create a folder named "flexbox-layout".
2. Create an "index.html" file.
3. Copy the provided HTML and CSS code into "index.html".
4. Save the file.
5. Open "index.html" in any modern web browser.

🎯 Learning Objectives

This project helps beginners understand:

- CSS Flexbox
- "display: flex"
- Width and height percentages
- Nested "<div>" elements
- Page layout structure
- Horizontal layouts
- Section division
- CSS background colors
- Borders
- Parent-child relationships in CSS

💡 Possible Improvements

The project could be improved by:

- Making the layout responsive
- Using "min-height" instead of fixed heights
- Adding content inside each section
- Adding borders between individual sections
- Adding hover effects
- Using CSS Grid for comparison
- Adding media queries for mobile devices
- Using semantic HTML elements such as "<header>", "<main>", "<aside>", and "<footer>"

👨‍💻 Author

Created as a beginner-friendly HTML & CSS Flexbox Layout project for practicing webpage structure, Flexbox, nested layouts, and CSS styling.# Flex-box
