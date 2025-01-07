<!DOCTYPE html>
<html>
<head>
<style>
body {
  display: flex; /* Use flexbox for layout */
  justify-content: space-between; /* Space between text and image */
  align-items: center; /* Center vertically */
  height: 100vh; /* Make the container fill the viewport height */
}

.text-container {
  flex-grow: 1; /* Allow text to grow to fill available space */
  margin-right: 20px; /* Add some margin between text and image */
}

.image-container {
  max-width: 360px; /* Set a maximum width for the image */
}
</style>
</head>
<body>

<div class="text-container">
  <ul>
    <li>📝 Learning Swift & Objective-C</li>
    <li><i>Working with JavaScript, TypeScript, React, and beyond.</i></li>
    <li>🔭 SpaceX enthusiast, fascinated by the cosmos. 🌌</li>
    <li>🛸 Passionate about astrophysics and the mysteries of the universe.</li>
    <li>❤️ Full-stack developer with a love for tackling diverse challenges.</li>
    <li>"Life is an adventure—live it to the fullest!" 🌟</li>
  </ul>
</div>

<div class="image-container">
  <img src="https://raw.githubusercontent.com/rahul-jha98/rahul-jha98/main/techstack.gif" alt="Tech Stack GIF">
</div>

</body>
</html>
