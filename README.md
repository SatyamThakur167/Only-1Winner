# Only-1Winner

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Only 1Winner Tournament</title>
  <style>
    body {
      margin: 0;
      font-family: "Poppins", sans-serif;
      background: #0a0a0a;
      color: #fff;
      text-align: center;
    }
    header {
      background: linear-gradient(90deg, #000, #1a1a1a);
      padding: 25px 10px;
      border-bottom: 2px solid #ffcc00;
      box-shadow: 0 0 20px #ffcc00;
    }
    h1 {
      color: #ffcc00;
      text-shadow: 0 0 15px #ffcc00;
      font-size: 2.2em;
      margin: 0;
    }
    h2 {
      color: #ffcc00;
    }
    .tagline {
      font-size: 1.1em;
      color: #ccc;
    }
    .tournament-section {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      margin: 30px 0;
      gap: 20px;
    }
    .card {
      background: #1c1c1c;
      border: 1px solid #ffcc00;
      border-radius: 12px;
      width: 280px;
      padding: 20px;
      box-shadow: 0 0 15px #ffcc00;
      transition: transform 0.3s;
    }
    .card:hover {
      transform: scale(1.05);
      box-shadow: 0 0 25px #ffcc00;
    }
    .card h3 {
      color: #ffcc00;
      margin-bottom: 10px;
    }
    .btn {
      background: #ffcc00;
      color: #000;
      border: none;
      padding: 10px 20px;
      border-radius: 8px;
      font-weight: bold;
      cursor: pointer;
      transition: 0.3s;
    }
    .btn:hover {
      background: #fff200;
      transform: scale(1.05);
    }
    form {
      background: #1a1a1a;
      width: 90%;
      max-width: 400px;
      margin: 40px auto;
      padding: 25px;
      border-radius: 15px;
      border: 1px solid #ffcc00;
      box-shadow: 0 0 15px #ffcc00;
    }
    input, button {
      width: 90%;
      padding: 10px;
      margin: 10px 0;
      border-radius: 8px;
      border: none;
      font-size: 1em;
    }
    button[type="submit"] {
      background: #ffcc00;
      color: #000;
      font-weight: bold;
      cursor: pointer;
    }
    button[type="submit"]:hover {
      background: #fff200;
    }
    .payment {
      margin: 40px 0;
    }
    .upi {
      font-size: 1.2em;
      color: #ffcc00;
      font-weight: bold;
    }
    img.qr {
      width: 220px;
      margin-top: 15px;
      border-radius: 10px;
      box-shadow: 0 0 20px #ffcc00;
    }
    footer {
      background: #111;
      padding: 15px;
      color: #999;
      font-size: 0.9em;
      border-top: 1px solid #222;
    }
    a {
      color: #ffcc00;
      text-decoration: none;
    }
  </style>
</head>
<body>
  <header>
    <h1>Only 1Winner</h1>
    <p class="tagline">One Team Winner 🏆</p>
  </header>

  <section>
    <h2>Weekly Tournaments</h2>
    <div class="tournament-section">
      <div class="card">
        <h3>Week 1 Tournament</h3>
        <p>Entry Fee: ₹20</p>
        <p>Winner: ₹900 | Runner-up: ₹200</p>
        <button class="btn" onclick="document.getElementById('register').scrollIntoView({behavior:'smooth'})">Register Now</button>
      </div>

      <div class="card">
        <h3>Week 2 Tournament</h3>
        <p>Entry Fee: ₹20</p>
        <p>Winner: ₹900 | Runner-up: ₹200</p>
        <button class="btn" onclick="document.getElementById('register').scrollIntoView({behavior:'smooth'})">Register Now</button>
      </div>

      <div class="card">
        <h3>Week 3 Tournament</h3>
        <p>Entry Fee: ₹20</p>
        <p>Winner: ₹900 | Runner-up: ₹200</p>
        <button class="btn" onclick="document.getElementById('register').scrollIntoView({behavior:'smooth'})">Register Now</button>
      </div>
    </div>
  </section>

  <section id="register">
    <h2>📝 Registration Form</h2>
    <form action="https://formsubmit.co/ss0061808@gmail.com" method="POST">
      <input type="text" name="Player Name" placeholder="Enter your name" required>
      <input type="text" name="Game ID" placeholder="Enter your Game ID" required>
      <input type="text" name="Phone Number" placeholder="Enter your phone number" required>
      <button type="submit">Submit Registration</button>
    </form>
  </section>

  <section class="payment">
    <h2>💵 Pay Entry Fee</h2>
    <p>Send ₹20 using the UPI ID below or scan the QR code 👇</p>
    <p class="upi">ss0061808@okaxis</p>
    <img src="qr.png" alt="UPI QR Code" class="qr">
    <p>After payment, submit your registration form.</p>
  </section>

  <footer>
    <p>Contact: <a href="mailto:ss0061808@gmail.com">ss0061808@gmail.com</a></p>
    <p>© 2025 Only 1Winner | All Rights Reserved</p>
  </footer>
</body>
</html>
