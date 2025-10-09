<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Simple Navbar</title>
  <style>
    
    .navbar {
      display: flex;
      background-color: #9e3434;
      padding: 10px;
      text-align: right;
    }

    .navbar a {
      color: white;
      text-decoration: none;
      padding: 10px 15px;
      text-align: center;
    }

    
    .navbar a:hover {
      background-color: #f03939;
      border-radius: 10px;
    }
    section {
       padding-bottom: 80px;

    }
    #home {
        padding-bottom: 1000px;
        background-color: aqua;
    }#about {
        padding-bottom: 1000px;
        background-color: rebeccapurple;
    }#services {
        padding-bottom: 1000px;
        background-color: red;
    }#contact {
        padding-bottom: 1000px;
        background-color: green;
    }

   
    @media (max-width: 600px) {
      .navbar {
        flex-direction: column;
      }
    }
  </style>
</head>
<body>
  <div class="navbar">
    <a href="#home">Home</a>
    <a href="#about">Abouts</a>
    <a href="#services">Services</a>
    <a href="#contact">Contacts</a>
  </div>
      <section id="home">
        <h2>Hello Guys!</h2>
        <h3> Welcome to <b><i>Tasnim's Page</i></b> </h3>
        <img src="https://th.bing.com/th/id/OIP.Ede9_F5yPMT7NV2jmmjMSQHaE8?w=224&h=180&c=7&r=0&o=7&cb=12&pid=1.7&rm=3" alt="Image">
        </section>
        <section id="about">
        <h2>I am in TyBscIT </h2>
        My hobbies are  Sports,Coding.
        </section>
        <section id="services">
           <h2>Login Form</h2>
    <form action="/submit" method="post">
        <!-- Input for Name -->
        <label for="name">Name:</label>
        <input type="text" id="name" name="name" placeholder="Enter your name" required>
        <br><br>
        
        <!-- Input for Password -->
        <label for="password">Password:</label>
        <input type="password" id="password" name="password" placeholder="Enter your password" required>
        <br><br>
        
        <!-- Submit Button -->
        <button type="submit">Submit</button>

        </section>
        <section id="contact">
        <h2>9978667540</h2>
        <gmailID:->tasnimmulani@gmail.com</gmailID:->
        </section>
