index.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>If you're reading this it's too late</title>

    <!-- Linking the external CSS file to this HTML document -->
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <!-- Header section containing main-title -->
    <header>
        <h1 class="main-title">When was the last time you smiled?</h1>
    </header>
    
    <!-- Main content section -->
    <section class="content">
        <!-- A paragraph with an ID selector to style it -->
        <p id="description">Please let the people in your life know you love them.</p>
        <br> 
        <!-- An image with a class for styling -->
        <img src="image.jpg" alt="Lebron on the Pat Mcafee show" class="styled-image">
    </section>
    
    <!-- Footer section -->
    <footer>
        <p>© Sports Center 2025, be mindful of our copyright</p>
    </footer>
</body>
</html>

styles.css

header {
    display: block; 
}

body {
    font-family: Arial, sans-serif; /* Sets the font style for the page */
    background-color: #f4f4f4; /* Light gray background color*/
    text-align: center; /* Centers text in the body */
    margin: 20px; /* Adds space around the body */
    padding: 10px; /* Provides some inner spacing in the body */
}


.main-title {
    color: #2c3e50; /* Ensures text is visible */
    font-size: 24px; /* Legible font */
    text-align: center; /* Centers title */
    display: block; /* Display main-title */
    margin: 20px auto; /* Adds space around it */
}


#description {
    font-size: 18px; /* Sets the font size */
    color: #555; /* dark gray text */
    padding: 10px; /* Adds space in the paragraph*/
    border: 2px solid #3498db; /* Blue border around the text */
    border-radius: 5px; /* Rounds the corners of the border */
}


.styled-image {
    width: 300px; /* Sets the image width to 300 pixels */
    height: auto; /* Ensures the image maintains its original aspect ratio */
    border: 5px solid #e74c3c; /* Adds a border around the image */
    margin-top: 15px; /* Creates space above the image to separate it from the text */
    padding: 5px; /* Adds space between the image content and the border */
}

