<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Employee Contracts</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 20px;
    }

    form {
      max-width: 400px;
      margin: 0 auto;
    }

    label {
      display: block;
      margin-bottom: 8px;
    }

    input, select {
      width: 100%;
      padding: 8px;
      margin-bottom: 16px;
      box-sizing: border-box;
    }

    button {
      background-color: #4CAF50;
      color: white;
      padding: 10px;
      border: none;
      cursor: pointer;
    }

    button:hover {
      background-color: #45a049;
    }

    table {
      margin-top: 20px;
      border-collapse: collapse;
      width: 100%;
    }

    th, td {
      border: 1px solid #ddd;
      padding: 8px;
      text-align: left;
    }

    th {
      background-color: #f2f2f2;
    }
  </style>
</head>
<body>

  <h2>Employee Contracts</h2>

  <form id="employeeForm" method="post" action="">
    <label for="name">Name:</label>
    <input type="text" name="name" required>

    <label for="startDate">Contract Start Date:</label>
    <input type="date" name="startDate" required>

    <label for="endDate">Contract End Date:</label>
    <input type="date" name="endDate" required>

    <label for="sendTelegram">Send Telegram Message:</label>
    <input type="checkbox" name="sendTelegram">

    <button type="submit">Add Employee</button>
  </form>

  <?php
  // Handle form submission and save data to data.txt
  if ($_SERVER['REQUEST_METHOD'] === 'POST') {
    $name = $_POST['name'];
    $startDate = $_POST['startDate'];
    $endDate = $_POST['endDate'];
    $sendTelegram = isset($_POST['sendTelegram']) ? 'Yes' : 'No';

    $data = "$name,$startDate,$endDate,$sendTelegram\n";
    file_put_contents('data.txt', $data, FILE_APPEND | LOCK_EX);
  }
  ?>

  <table id="employeeTable">
    <thead>
      <tr>
        <th>Name</th>
        <th>Contract Start Date</th>
        <th>Contract End Date</th>
        <th>Send Telegram Message</th>
      </tr>
    </thead>
    <tbody>
      <?php
      // Read data from data.txt and display in the table
      $file = file('data.txt', FILE_IGNORE_NEW_LINES | FILE_SKIP_EMPTY_LINES);
      foreach ($file as $line) {
        list($name, $startDate, $endDate, $sendTelegram) = explode(',', $line);
        echo "<tr><td>$name</td><td>$startDate</td><td>$endDate</td><td>$sendTelegram</td></tr>";
      }
      ?>
    </tbody>
  </table>

</body>
</html>
