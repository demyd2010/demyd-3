<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Restaurant Menu</title>
  <style>
    body {
      font-family: Calibri, sans-serif;
      margin: 50;
      color: white }
    .menu {
      width: 400px;
      height: 550px;
      padding: 20px;
      margin: 20px;
      border: 2px solid #ccc;
      background-size: cover;
      background-position: center; }
    .breakfast {
      background-image: url('breakfast 2.jpg'); }
    .lunch {
      background-image: url('lunch 2.jpg');
    }
    .dinner {
      background-image: url('dinner 3.jpg'); }
	h2 {
      	font-size: 32px;
      	font-weight: bold;
      	margin-bottom: 15px;
        margin-top: 5px;}
    ul {
      list-style-type: none;
      padding: 0;
    }
    li {
      margin-bottom: 5px;
      font-size: 24px; 
    }
    ul {
      list-style-type: none;
      padding: 0;
    }
    li {
      margin-bottom: 5px;
    }
  </style>
</head>
<body>
  <div class="menu breakfast">
    <h2>Breakfast Menu</h2>
    <ul>
      <li>Pancakes</li>
      <li>Omelette</li>
      <li>Fruit Salad</li>
    </ul>
  </div>
  <div class="menu lunch">
    <h2>Lunch Menu</h2>
    <ul>
      <li>Chicken Caesar Salad</li>
      <li>Pasta Carbonara</li>
      <li>Grilled Vegetables</li> 
    </ul>
  </div>
  <div class="menu dinner">
    <h2>Dinner Menu</h2>
    <ul>
      <li>Steak with Garlic Butter</li>
      <li>Salmon with Lemon Dill Sauce</li>
      <li>Mushroom Risotto</li>
    </ul>
  </div>
</body>
</html>
