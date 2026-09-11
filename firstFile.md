---
layout: post
theme: jekyll-theme-Midnight
---


<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Form Page</title>
  <!-- Fix 1: Link stylesheets inside <head>, compiled to CSS -->
  <link rel="stylesheet" href="styles.css">
</head>
<body>

  <form action="/action_page.php">
    <input type="file" accept=".mp3,audio/mpeg" id="myFile" name="filename">
    <input type="submit">
  </form>

  <form action="/action_page.php">
    <label for="lname">Youtube link:</label>
    <input type="text" id="lname" name="lname"><br><br>
    <input type="submit" value="Submit">
  </form>

  <section id="p1">
    <!-- Fix 2: Applied rightAlign class to a valid inline element (p or span) -->
    <div class="right">
      <span class="rightAlign">This div element is right</span>
    </div>
  </section>

</body>

