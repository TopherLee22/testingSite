---
layout: post
theme: jekyll-theme-Midnight
---
<head>
  <meta charset="UTF-8">
  <title>Form Page</title>
  <link rel="stylesheet" href="styles.css">
</head>

<html lang="en">
<body>
  <form action="/action_page.php" class = "right">
    <input type="file" accept=".mp3,audio/mpeg" id="myFile" name="filename">
    <input type="submit">
  </form>
  
  <form action="/action_page.php" class = "right">
    <label for="lname">Youtube link:</label>
    <input type="text" id="lname" name="lname"><br><br>
    <input type="submit" value="Submit">
  </form>

 </body>

