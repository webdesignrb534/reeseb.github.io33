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
<img src="https://github.com/user-attachments/assets/6c13faff-9b57-493d-8c48-84c5c6c1ff51" alt="Penguins">
</div>
<div class="image-box">
<img src="https://github.com/user-attachments/assets/881d276c-e19e-4b43-9d47-21b1cd04b939" alt="Football Field">
</div> 
border: 27px solid #000;
border-image: url(https://github.com/user-attachments/assets/c12b94df-d6c1-4e02-9d44-cb23f37b79db) 27 round;
<div class="image-box">
<img src="https://github.com/user-attachments/assets/1c2e8b9b-0e58-43f6-befb-e3feeda330a8" alt="Dinosaur">
</div>
<div class="image-box">
<img src="https://github.com/user-attachments/assets/d4b80427-29a8-444b-9c5e-443ed24ef788" alt="Seagull">
</div>
<div class="image-box">
<img src="https://github.com/user-attachments/assets/378a15aa-f458-4d26-b663-07bf2a96da54" alt="Butterfly">
</div>
<div class="image-box">
<img src="" alt="Presenting">
</div>
</div>

</body>
</html>
