<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Timetable</title>
  <style>
    
    table {
      border-collapse: separate;
      border-spacing: 2px;
      background-color: #d0d0d0;
      border: 3px inset #888;
      padding: 3px;
      font-family: 'Times New Roman', Times, serif;
    }

    
    caption {
      font-weight: bold;
      font-size: 1.2rem;
      margin-bottom: 8px;
    }

    
    th, td {
      border: 2px outset #ffffff;
      background-color: #e8e8e8;
      padding: 6px 12px;
      text-align: center;
    }

    th {
      font-weight: bold;
    }
  </style>
</head>
<body>

  <table>
    <caption>Timetable</caption>
    <thead>
      <tr>
        <th>Day/Time</th>
        <th>9am</th>
        <th>10am</th>
        <th>11am</th>
        <th>12pm</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <th>Monday</th>
        <td colspan="2">CIS 210</td>
        <td>CIS 211</td>
        <td>CIS 212</td>
      </tr>
      <tr>
        <th>Tuesday</th>
        <td>CIS 122</td>
        <td>CIS 133</td>
        <td colspan="2">CIS 213</td>
      </tr>
    </tbody>
  </table>

</body>
</html>
