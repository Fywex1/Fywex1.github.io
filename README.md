<!DOCTYPE html>
<html>
  <head>
    <title>About Me</title>
    <style>
      body {
        background: linear-gradient(-45deg, black, white, black, white);
        background-size: 400% 400%;
        animation: gradient 15s ease infinite;
        color: white;
        font-family: sans-serif;
        text-align: center;
      }
      
      @keyframes gradient {
        0% {
          background-position: 0% 50%;
        }
        50% {
          background-position: 100% 50%;
        }
        100% {
          background-position: 0% 50%;
        }
      }
      
      .card {
        background-color: white;
        color: black;
        border-radius: 20px;
        padding: 20px;
        width: 50%;
        margin: 0 auto;
        box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
      }
      
      .card h1 {
        font-size: 2.5em;
        margin-bottom: 0.5em;
      }
      
      .card p {
        font-size: 1.5em;
        margin-bottom: 1.5em;
      }
      
      .social {
        display: flex;
        justify-content: center;
      }
      
      .social a {
        display: block;
        text-decoration: none;
        color: black;
        background-color: white;
        margin: 10px;
        padding: 10px;
        border-radius: 50%;
        transition: all 0.2s;
      }
      
      .social a:hover {
        color: white;
        background-color: black;
        transform: scale(1.2);
      }
    </style>
  </head>
  <body>
    <div class="card">
      <h1>About Me</h1>
      <p>
        My name is [Your Name] and I'm a [Your Profession] based in [Your City]. 
        I'm passionate about [Your Interests/Hobbies] and enjoy [Your Activities]. 
        I also love connecting with new people, so feel free to reach out to me on any of my social media profiles!
      </p>
      <div class="social">
        <a href="[Link to your social media profile]"><i class="fab fa-twitter"></i></a>
        <a href="[Link to your social media profile]"><i class="fab fa-facebook-f"></i></a>
        <a href="[Link to your social media profile]"><i class="fab fa-instagram"></i></a>
        <a href="[Link to your social media profile]"><i class="fab fa-linkedin-in"></i></a>
        <a href="[Link to your social media profile]"><i class="fab fa-github"></i></a>
      </div>
    </div>
    
    <script src="https://kit.fontawesome.com/your-kit-id.js"></script>
  </body>
</html>
