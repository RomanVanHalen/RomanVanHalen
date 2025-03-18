<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Chamod's Profile</title>
  <style>
    /* Set the background image */
    body {
      margin: 0;
      padding: 0;
      background-image: url('https://yourimageurl.com/battleground.jpg'); /* Use the URL to your background image */
      background-size: cover;
      background-position: center;
      background-attachment: fixed;
      height: 100vh; /* Full-screen height */
      font-family: Arial, sans-serif;
      color: white;
    }

    /* Add a dark overlay to enhance readability */
    .overlay {
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      background-color: rgba(0, 0, 0, 0.6); /* Semi-transparent black */
    }

    /* Center content */
    .content {
      position: absolute;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%);
      text-align: center;
    }

    /* Style for text */
    h1 {
      font-size: 3em;
      margin-bottom: 20px;
    }

    p {
      font-size: 1.2em;
    }

    /* Skills container */
    .skills {
      display: flex;
      justify-content: center;
      margin-top: 30px;
    }

    .skills img {
      margin: 0 15px;
      width: 40px; /* Adjust size as needed */
      height: 40px;
    }

  </style>
</head>
<body>

  <div class="overlay"></div> <!-- Dark overlay to improve text visibility -->

  <div class="content">
    <h1>Welcome to My Profile</h1>
    <p>Hi, I'm Chamod 👋. Cybersecurity Enthusiast & Developer.</p>

    <!-- Warrior image -->
    <img src="https://yourimageurl.com/warrior.png" alt="Warrior" width="200px">

    <div class="skills">
      <!-- Skill icons (you can use your icons or images) -->
      <img src="https://yourimageurl.com/python-icon.png" alt="Python">
      <img src="https://yourimageurl.com/shell-icon.png" alt="Shell">
      <img src="https://yourimageurl.com/java-icon.png" alt="Java">
      <img src="https://yourimageurl.com/burp-icon.png" alt="Burp Suite">
      <img src="https://yourimageurl.com/webscan-icon.png" alt="Web Scanning">
    </div>
  </div>

</body>
</html>
