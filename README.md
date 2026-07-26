# railway-reservation
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Railway Reservation System</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background-color: #f5f9ff;
      color: #333;
    }
    header {
      background-color: #004080;
      color: white;
      padding: 15px;
      text-align: center;
    }
    nav {
      display: flex;
      justify-content: center;
      background-color: #0066cc;
    }
    nav a {
      color: white;
      padding: 14px 20px;
      text-decoration: none;
    }
    nav a:hover {
      background-color: #004080;
    }
    .search-form {
      max-width: 600px;
      margin: 30px auto;
      padding: 20px;
      background: white;
      border-radius: 8px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
    }
    .search-form input, .search-form select, .search-form button {
      width: 100%;
      padding: 10px;
      margin: 8px 0;
    }
    footer {
      background-color: #004080;
      color: white;
      text-align: center;
      padding: 10px;
      position: fixed;
      bottom: 0;
      width: 100%;
    }
  </style>
</head>
<body>
  <header>
    <h1>Railway Reservation System</h1>
  </header>
  <nav>
    <a href="#">Home</a>
    <a href="#">Book Tickets</a>
    <a href="#">Train Schedule</a>
    <a href="#">PNR Status</a>
    <a href="#">Contact Us</a>
  </nav>

  <section class="search-form">
    <h2>Book Your Ticket</h2>
    <form>
      <input type="text" placeholder="Departure Station" required>
      <input type="text" placeholder="Destination Station" required>
      <input type="date" required>
      <select required>
        <option value="">Select Class</option>
        <option>First Class</option> 
