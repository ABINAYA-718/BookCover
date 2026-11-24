Ex.05 Book Cover Page Design
Date:
AIM:
To design a book back cover page using HTML and CSS.

DESIGN STEPS:
Step 1:
Create a Django Admin project.

Step 2:
Create an app in the Django interface.

Step 3:
Create a folder named 'static' in the app folder.

Step 4:
Create a new HTML file in the static folder.

Step 5:
Write the HTML code with relevant CSS properties.

Step 6:
Choose the appropriate style and color scheme.

Step 7:
Insert the images in their appropriate places.

Step 8:
Publish the website in the LocalHost.

PROGRAM:
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Book Back Cover</title>
  <link rel="stylesheet" href="{% static 'style.css' %}">
</head>
<body>
  <div class="cover">
    <h1>WHAT SILENCE LEFT BEHIND</h1>
    <p class="quote">"A story that stays with you long after the last page."</p>
    <img src="{% static 'cover.jpg' %}" alt="Book image">
    <p class="summary">
      Follow Arun as he leaves his village to chase a dream. Along the way
      he meets friends, faces hard choices, and discovers that the quietest
      journeys change us the most.
    </p>
    <h3>About the Author</h3>
    <p class="author">Written by ABINAYA.</p>
    <div class="footer">
      <span>Price: ₹499</span>
      <span class="barcode">| || ||| | ||</span>
    </div>
  </div>
</body>
</html>
```
OUTPUT:
<img width="1920" height="1080" alt="Screenshot (54)" src="https://github.com/user-attachments/assets/8c15b51f-e079-45d6-aac7-468199d5d047" />

RESULT:
The program for designing book back cover page using HTML and CSS is completed successfully.
