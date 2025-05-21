<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>Smart Railway Station - IoT Project</title>
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <link href="https://fonts.googleapis.com/css2?family=Segoe+UI&display=swap" rel="stylesheet" />
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css" />
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background: linear-gradient(to right, #f4f7f9, #e0ecf1);
      color: #333;
    }

    header {
      background: linear-gradient(to right, #2c3e50, #4ca1af);
      color: white;
      padding: 40px 20px;
      text-align: center;
      position: relative;
      overflow: hidden;
    }

    header h1 {
      margin: 0;
      font-size: 36px;
      animation: fadeInDown 1s ease forwards;
    }

    header p {
      font-size: 18px;
      margin-top: 10px;
      animation: fadeInUp 1.5s ease forwards;
    }

    nav {
      background: #2c3e50;
      padding: 10px;
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      animation: fadeIn 2s ease forwards;
    }

    nav a {
      color: white;
      text-decoration: none;
      margin: 10px 15px;
      font-weight: bold;
      transition: color 0.3s ease;
    }

    nav a:hover {
      color: #f1c40f;
    }

    .container {
      max-width: 1000px;
      margin: 30px auto;
      padding: 20px;
      animation: fadeIn 2.5s ease forwards;
    }

    .summary {
      padding: 20px;
      background: #ffffff;
      border-left: 6px solid #3498db;
      border-radius: 10px;
      margin-bottom: 30px;
      box-shadow: 0 3px 8px rgba(0, 0, 0, 0.08);
      display: flex;
      align-items: center;
      gap: 20px;
    }

    .summary h2 {
      margin-top: 0;
      color: #2c3e50;
      flex: 1;
    }

    .summary .icon {
      font-size: 80px;
      color: #3498db;
      flex-shrink: 0;
      animation: bounce 2s infinite;
    }

    .card {
      background: white;
      border-radius: 12px;
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
      margin-bottom: 20px;
      overflow: hidden;
      transition: transform 0.3s ease;
      animation: fadeInUp 1.2s ease forwards;
    }

    .card:hover {
      transform: translateY(-5px);
      box-shadow: 0 8px 20px rgba(0, 0, 0, 0.15);
    }

    .card h2 {
      margin: 0;
      padding: 18px 20px;
      background: linear-gradient(to right, #3498db, #2980b9);
      color: white;
      font-size: 20px;
      display: flex;
      align-items: center;
      gap: 10px;
    }

    .card h2 .icon {
      font-size: 24px;
    }

    .card-content {
      padding: 20px;
      background: #f9f9f9;
      line-height: 1.6;
      font-size: 16px;
    }

    ul {
      padding-left: 20px;
    }

    .team {
      margin-top: 40px;
      text-align: center;
      animation: fadeIn 3s ease forwards;
    }

    .team h3 {
      margin-bottom: 10px;
      color: #2c3e50;
    }

    .team p {
      margin: 5px 0;
      font-weight: 600;
      font-size: 18px;
    }

    footer {
      background: #2c3e50;
      color: white;
      text-align: center;
      padding: 20px;
      margin-top: 50px;
      font-size: 14px;
    }

    footer a {
      color: #f1c40f;
      text-decoration: none;
    }

    button {
      display: block;
      margin: 40px auto 10px;
      padding: 12px 28px;
      font-size: 16px;
      background-color: #3498db;
      color: white;
      border: none;
      border-radius: 8px;
      cursor: pointer;
      transition: background-color 0.3s ease;
      animation: fadeIn 3.5s ease forwards;
    }

    button:hover {
      background-color: #2980b9;
    }

    /* Animations */
    @keyframes fadeIn {
      from {
        opacity: 0;
      }
      to {
        opacity: 1;
      }
    }

    @keyframes fadeInUp {
      from {
        opacity: 0;
        transform: translateY(30px);
      }
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }

    @keyframes fadeInDown {
      from {
        opacity: 0;
        transform: translateY(-30px);
      }
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }

    @keyframes bounce {
      0%, 100% {
        transform: translateY(0);
      }
      50% {
        transform: translateY(-10px);
      }
    }
  </style>
</head>
<body>

<header>
  <h1>Smart Railway Station with IoT</h1>
  <p>Modernizing Travel with Smart Tech</p>
</header>

<nav>
  <a href="#overview">Overview</a>
  <a href="#tracking">Train Tracking</a>
  <a href="#waiting">Waiting Rooms</a>
  <a href="#surveillance">Surveillance</a>
  <a href="#app">Mobile App</a>
  <a href="#waste">Waste Management</a>
  <a href="#features">Extra Features</a>
  <a href="#team">Team</a>
</nav>

<div class="container">

  <div id="overview" class="summary">
    <i class="fas fa-network-wired icon"></i>
    <div>
      <h2>Project Overview</h2>
      <p>This project aims to enhance the Indian railway experience using IoT technologies. It improves real-time information, safety, cleanliness, and passenger convenience at stations.</p>
    </div>
  </div>

  <div id="tracking" class="card">
    <h2><i class="fas fa-train icon"></i> 1. Real-Time Train Tracking</h2>
    <div class="card-content">
      <p>Uses GPS sensors to track train positions and update digital displays and mobile apps instantly.</p>
    </div>
  </div>

  <div id="waiting" class="card">
    <h2><i class="fas fa-chair icon"></i> 2. Smart Waiting Rooms</h2>
    <div class="card-content">
      <p>Sensors adjust lights and fans based on occupancy. Live data helps passengers find less crowded areas.</p>
    </div>
  </div>

  <div id="surveillance" class="card">
    <h2><i class="fas fa-video icon"></i> 3. AI-based Surveillance</h2>
    <div class="card-content">
      <p>AI-powered CCTV monitors for theft, crowd surges, or unattended items and alerts authorities in real-time.</p>
    </div>
  </div>

  <div id="app" class="card">
    <h2><i class="fas fa-mobile-alt icon"></i> 4. Mobile App Integration</h2>
    <div class="card-content">
      <p>The app displays live train status, delay alerts, and platform navigation features.</p>
    </div>
  </div>

  <div id="waste" class="card">
    <h2><i class="fas fa-trash-alt icon"></i> 5. Smart Waste Management</h2>
    <div class="card-content">
      <p>Smart bins detect garbage levels and notify cleaning crews before overflow occurs.</p>
    </div>
  </div>

  <div id="features" class="card">
    <h2><i class="fas fa-plus-circle icon"></i> 6. Additional Smart Features</h2>
    <div class="card-content">
      <ul>
        <li>Free WiFi hotspots at all major junctions.</li>
        <li>Charging stations for phones and laptops.</li>
        <li>Emergency alert buttons for women’s safety.</li>
        <li>Voice announcements synced with display boards.</li>
        <li>Touchless ticket scanners.</li>
      </ul>
    </div>
  </div>

  <div id="team" class="team">
    <h3>Team Members</h3>
    <p><strong>Karthikeyan</strong></p>
    <p><strong>Sham Ganesh</strong></p>
  </div>

  <button onclick="alert('Thank you for viewing our Smart Station Project!')">End Presentation</button>

</div>

<footer>
  <p>Connect with us: <a href="mailto:smartstation@project.com">smartstation@project.com</a></p>
  <p>&copy; 2025 Smart Railway Station Project</p>
</footer>

</body>
</html>
