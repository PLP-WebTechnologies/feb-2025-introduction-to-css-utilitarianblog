# Introduction to CSS

## Objectives
Link an external CSS file to an HTML document.
Apply basic styling using selectors.
Use colors, fonts, and spacing effectively.

## Instructions

Create a style.css file.
Apply CSS to a HTML page.
Style elements using:
Classes and IDs.
Color and typography.
Margins, paddings, and borders.

>[!NOTE]
>  - Include at least:
>  - Use of 3 selectors
>  - Style an image
>  - Margin, Padding & Borders
>  - Different font

# Tasks
 - Link an external CSS file.
 - Apply at least 3 different selectors.
 - Improve readability and aesthetics.

Happy Coding! 💻✨
# Solution

### index.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Introduction to CSS</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1 class="title">Welcome to CSS Styling</h1>
    </header>

    <main>
        <section class="content">
            <p id="description">
                CSS (Cascading Style Sheets) is used to style HTML elements. It helps improve readability and aesthetics.
            </p>
            <img src="css-logo.png" alt="CSS Logo" class="styled-image">
        </section>
    </main>

    <footer>
        <p>© 2025 Utilitarian Blog</p>
    </footer>
</body>
</html>

### style.css

/* Apply background color and font */
body {
    font-family: 'Arial', sans-serif;
    background-color: #f4f4f4;
    margin: 0;
    padding: 0;
}

/* Styling the title */
.title {
    text-align: center;
    color: #007bff;
    font-size: 24px;
    margin: 20px;
}

/* Styling the paragraph */
#description {
    font-size: 16px;
    color: #333;
    line-height: 1.6;
    padding: 10px;
    border: 2px solid #007bff;
    border-radius: 5px;
    background-color: #e0f7fa;
}

/* Styling the image */
.styled-image {
    display: block;
    margin: 20px auto;
    border: 3px solid #333;
    border-radius: 10px;
    width: 150px;
    height: auto;
}
