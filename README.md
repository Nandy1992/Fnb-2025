# Fnb-2025
<!DOCTYPE html>
<html lang="en">
<head>
<title>Page Title</title>
<meta charset="UTF-8">

<style>
@font-face { 
  font-family: "Merriweather Sans";
  src: url('MerriweatherSans-Medium.ttf') format('truetype');
}

body {
  background: #FFFFFF;
  margin-bottom: 200px;
}

@keyframes BackgroundGradient {
  0%{background-position:0% 50%;}
  50%{background-position: 100% 50% }
  100%{background-position: 0% 50%}

}

.VCE{
  color: #f2f2f2;
  background: linear-gradient(45deg, #FCE38A, #f5ad4d, #fd81b5, #f74689, #ad5af3, #8a13ef );
  background-size: 450% 100%;
  animation: BackgroundGradient 30s ease infinite;  
  padding: 20px;
  margin: 30px;
  border-radius: 0.5rem;
}

.VCE_Title{
  font-family: "Merriweather Sans", sans-serif;
  font-weight: 400;
  font-size: 30px;
  margin-bottom: 0;
}

.JTime{
  font-family: "Merriweather Sans", sans-serif;
  font-size: 20px;
}

button {
  font-family: "Merriweather Sans", sans-serif;
  font-size: 16px;
  padding: 15px 22px;
  border:3px #f2f2f2 solid;
  border-radius:20px;
  word-break: break-word;
  white-space: normal;  
}

</style>
</head>
<body>
<div class="container">
<div class="VCE">
<h2 class="VCE_Title">Visual Code Editor for HTML, CSS and JavaScript</h2>
<hr style="  border: 3px solid #f2f2f2;">
<p class="JTime">Whatever code you write above, Live Preview will be visible here</p>
<br>
<button type="button" onclick="document.getElementById('Example').innerHTML = Date()">a Javascript Date and Time</button>
<p class="JTime" id="Example"></p>
<p class="JTime">Hit the "Clear" button and start typing Code.</p>
</div>
</body>
</html>
