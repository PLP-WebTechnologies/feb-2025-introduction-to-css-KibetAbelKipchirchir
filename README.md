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

Happy Coding! 💻✨\
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Styled Page</title>
  <!-- Link to external CSS file -->
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1 class="main-header">Welcome to My Styled Page</h1>
  </header>

  <section id="about">
    <h2>About Me</h2>
    <p class="description">This is a paragraph describing the purpose of the page. It's styled with a custom font and padding.</p>
    <img src="https://via.placeholder.com/300" alt="Placeholder Image" class="styled-image">
  </section>

  <section id="contact">
    <h2>Contact Information</h2>
    <ul>
      <li class="contact-item">Email: example@example.com</li>
      <li class="contact-item">Phone: 123-456-7890</li>
      <li class="contact-item">Address: 123 Main St, City, Country</li>
    </ul>
  </section>
</body>
</html>


/* General Styles */
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  background-color: #f0f8ff;
  color: #333;
}

/* Styling Header */
.main-header {
  text-align: center;
  font-size: 2.5rem;
  margin: 20px;
  color: #4a90e2;
}

/* Styling Sections */
#about, #contact {
  padding: 20px;
  margin: 20px;
  border: 2px solid #4a90e2;
  border-radius: 10px;
  background-color: #ffffff;
}

/* Image Styling */
.styled-image {
  display: block;
  margin: 20px auto;
  border: 5px solid #4a90e2;
  border-radius: 15px;
}

/* List Styling */
.contact-item {
  font-size: 1.2rem;
  margin: 5px 0;
  color: #555;
}

