<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Tiriveedhi Sai Venkatesh - Portfolio</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
    }
    .container {
      display: flex;
      height: 100vh;
    }
    .left-section {
      width: 50%;
      background-color: #f4f4f4;
      padding: 60px;
      display: flex;
      flex-direction: column;
      justify-content: center;
    }
    .left-section h1 {
      font-size: 40px;
      margin-bottom: 10px;
    }
    .left-section h2 {
      font-size: 24px;
      margin-bottom: 20px;
      color: #555;
    }
    .left-section p {
      font-size: 16px;
      line-height: 1.6;
      margin-bottom: 10px;
    }
    .left-section a {
      color: #0077cc;
      text-decoration: none;
      display: block;
      margin-top: 10px;
    }
    .right-section {
      width: 50%;
      background: url('background.jpg') no-repeat center center/cover;
      display: flex;
      align-items: center;
      justify-content: center;
    }
    .profile-photo {
      width: 250px;
      height: 250px;
      border-radius: 50%;
      border: 5px solid #fff;
      object-fit: cover;
    }
  </style>
</head>
<body>

<div class="container">
  <div class="left-section">
    <h1>Tiriveedhi Sai Venkatesh</h1>
    <h2>Boomi Integration Developer</h2>
    <p><strong>Email:</strong> venkatesh@gmaul.com</p>
    <p><strong>Phone:</strong> 123456322434</p>
    <a href="#">LinkedIn: linkedin.com/in/venkatesh</a>
    <a href="#">GitHub: github.com/venkatesh</a>
  </div>
  <div class="right-section">
    <img src="profile_photo.jpg" alt="Profile Photo" class="profile-photo" />
  </div>
</div>

</body>
</html>
