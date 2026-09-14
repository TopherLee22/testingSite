---
layout: page
theme: jekyll-theme-Midnight
---
<style>
body 
  {
  background-color: #69655d;
}
</style>
<head>
  <meta charset="UTF-8">
 
  <!-- Fix 1: Link stylesheets inside <head>, compiled to CSS -->
  <link rel="stylesheet" href="styles.scss">
</head>

<html lang="en">
<body>
  <p1>
     <form action="/action_page.php" class = "right">
    <input type="file" accept=".mp3,audio/mpeg" id="myFile" name="filename">
    <input type="submit">
    </form>
  </p1>
 
  <p2>
   <form form onsubmit="return handleYoutubeSubmit(event)" class = "right">
      <label for="lname">Youtube link:</label>
      <input type="text" id="lname" name="lname"><br><br>
      <input type="submit" value="Submit">
    </form>
  </p2>

  <div class = "leftAlign">
    <p> Playlists:</p>
  </div>

  <div class = "center-wrap">
  <iframe width="420" height="315" class ="center" src="https://www.youtube.com/embed/jNQXAC9IVRw"></iframe>
  </div>

 </body>


<script>
  async function checkRust(e)
  {
    const url = document.getElementById('videoUrl').value;
    const embedCode = convertYoutubeToEmbed(url);
  
    document.getElementById('videoContainer').innerHTML = embedCode;
  }
</script>
