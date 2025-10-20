# garpeld3.github.io
layout: page
title: "PAGE-TITLE"
permalink: /URL-PATH
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Student Registration Form</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Comic Sans MS', cursive;
      background: linear-gradient(to bottom right, #ffb6c1, #ffe6cc);
      height: 100vh;
      overflow-x: hidden;
    }

    .navbar {
      position: fixed;
      top: 0;
      width: 100%;
      background-color: #a63f78;
      padding: 15px 30px;
      color: white;
      display: flex;
      justify-content: space-between;
      align-items: center;
      z-index: 1000;
      box-shadow: 0 2px 8px rgba(0, 0, 0, 0.2);
    }

    .navbar .logo {
      font-size: 20px;
      font-weight: bold;
    }

    .navbar ul {
      list-style: none;
      display: flex;
      gap: 20px;
    }

    .navbar ul li a {
      color: white;
      text-decoration: none;
      font-weight: 500;
      transition: color 0.3s;
    }

    .navbar ul li a:hover {
      color: #ffd700;
    }

    .main {
      display: flex;
      justify-content: space-between;
      align-items: stretch;
      margin-top: 70px;
      height: calc(100vh - 70px);
    }
    .container {
      flex: 1;
      background: #f4f4f4;
      padding: 40px;
      border-top-right-radius: 20px;
      border-bottom-right-radius: 20px;
      box-shadow: 3px 0 10px rgba(0, 0, 0, 0.1);
      max-width: 500px;
    }

    h2 {
      text-align: center;
      color: #333;
      margin-bottom: 25px;
    }

    label {
      display: block;
      margin-top: 15px;
      margin-bottom: 5px;
      font-weight: bold;
    }

    input[type="text"],
    input[type="email"],
    select,
    textarea {
      width: 100%;
      padding: 10px;
      border: 1px solid #bbb;
      border-radius: 5px;
    }

    .gender-options {
      display: flex;
      gap: 10px;
      margin-top: 5px;
    }

    button {
      margin-top: 20px;
      width: 100%;
      padding: 10px;
      background-color: #4285f4;
      color: white;
      border: none;
      border-radius: 5px;
      font-size: 16px;
      cursor: pointer;
      transition: background 0.3s;
    }

    button:hover {
      background-color: #357ae8;
    }

    .right-side {
      flex: 1;
      background: linear-gradient(to bottom right, #fddde6, #ffcad4);
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      text-align: center;
      padding: 40px;
      color: #4a235a;
    }

    .right-side h1 {
      font-size: 32px;
      margin-bottom: 15px;
    }

    .right-side p {
      font-size: 18px;
      max-width: 400px;
      line-height: 1.5;
    }

    .quote {
      margin-top: 25px;
      font-style: italic;
      font-size: 16px;
      color: #5e3370;
    }

    @media (max-width: 800px) {
      .main {
        flex-direction: column;
      }

      .container, .right-side {
        border-radius: 0;
        max-width: 100%;
      }

      .right-side {
        padding: 20px;
      }
    }
  </style>
</head>
<body>

  <nav class="navbar">
    <div class="logo">Student Registration</div>
    <ul>
      <li><a href="#">Home</a></li>
      <li><a href="#">Register</a></li>
      <li><a href="#">Courses</a></li>
      <li><a href="#">Contact</a></li>
    </ul>
  </nav>

  <div class="main">
    <div class="container">
      <h2>Student Registration</h2>
      <form action="#" method="post">
        <label for="fullName">Full Name</label>
        <input type="text" id="fullName" name="fullName" required>

        <label for="email">Email</label>
        <input type="email" id="email" name="email" required>

        <label for="phone">Phone Number</label>
        <input type="text" id="phone" name="phone" required>

        <label>Gender</label>
        <div class="gender-options">
          <label><input type="radio" name="gender" value="Male"> Male</label>
          <label><input type="radio" name="gender" value="Female"> Female</label>
        </div>

        <label for="course">Course</label>
        <select id="course" name="course" required>
          <option value="">Select</option>
          <option value="BSc">BIT CompTech</option>
          <option value="BA">BIT Electronics</option>
          <option value="BCom">HTM</option>
          <option value="BTech">HM</option>
          <option value="MBA">EDUCATION MATH</option>
          <option value="MBA">EDUCATION Science and Arts</option>
          <option value="MBA">EDUCATION English</option>
          <option value="MBA">EDUCATION Filipino</option>
        </select>

        <label for="address">Address</label>
        <textarea id="address" name="address" rows="3" required></textarea>

        <button type="submit">Register</button>
      </form>
    </div>

    <div class="right-side">
      <h1>Welcome Future Scholars!</h1>
      <p>Join our community of passionate learners and take the first step toward your dreams. Fill out the form and start your academic journey with us today.</p>
      <div class="quote">“Education is the passport to the future, for tomorrow belongs to those who prepare for it today.”</div>
    </div>
  </div>

</body>
</html>
<!--Kyle Jaek M. Cahayagan-->
<!--BIT 1B-->
