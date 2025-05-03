<html lang="en">
<head>
<meta charset="UTF-8">
<title>CSS3 Imagery Assignment</title>
<style>
body {
font-family: Arial, sans-serif;
background: #f2f2f2;
padding: 20px;
text-align: center;
}

.container {
display: flex;
flex-wrap: wrap;
justify-content: center;
gap: 20px;
}

.image-box {
width: 200px;
height: 200px;
overflow: hidden;
border: 2px solid #ccc;
border-radius: 10px;
box-shadow: 5px 5px 15px rgba(0,0,0,0.2);
transition: transform 0.3s;
}

.image-box:hover {
transform: scale(1.05);
}

.image-box img {
width: 100%;
height: 100%;
object-fit: cover;
}

h1 {
margin-bottom: 40px;
}
</style>
</head>
<body>

<h1>CSS3 Imagery Assignment</h1>

<div class="container">
<div class="image-box">
<img src="penguins.png" alt="Penguins">
</div>
<div class="image-box">
<img src="tic-tac-toe.png" alt="Tic Tac Toe">
</div>
<div class="image-box">
<img src="dinosaur.png" alt="Dinosaur">
</div>
<div class="image-box">
<img src="seagull.png" alt="Seagull">
</div>
<div class="image-box">
<img src="https://github.com/user-attachments/assets/378a15aa-f458-4d26-b663-07bf2a96da54" alt="Butterfly">
</div>
<div class="image-box">
<img src="presenting.png" alt="Presenting">
</div>
</div>

</body>
</html>
