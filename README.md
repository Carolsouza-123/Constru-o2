# Da Sua Ex mais gostosa
<!DOCTYPE html>
<html lang="pt-br">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Uma Mensagem Para Você</title>
<style>
body {
font-family: 'Arial', sans-serif;
display: flex;
justify-content: center;
align-items: center;
height: 100vh;
background-color: #fce4ec;
margin: 0;
padding: 0;
}
.container {
text-align: center;
background: white;
padding: 20px;
border-radius: 15px;
box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
width: 90%;
max-width: 500px;
}
#message {
display: none;
margin-top: 20px;
padding: 20px;
background-color: #fff;
border-radius: 10px;
color: #d63384;
font-size: 20px;
line-height: 1.6;
opacity: 0;
transform: translateY(20px);
transition: opacity 1s ease, transform 1s ease;
}
input {
padding: 10px;
margin-top: 10px;
width: 80%;
text-align: center;
font-size: 16px;
border: 2px solid #d63384;
border-radius: 5px;
}
button {
margin-top: 10px;
padding: 10px 20px;
background: #d63384;
color: white;
border: none;
border-radius: 5px;
cursor: pointer;
font-size: 16px;
}
button:hover {
background: #b82c6d;
}
</style>
</head>
<body>
<div class="container">
<h2>Digite a senha para ver a mensagem</h2>
<input type="text" id="password" placeholder="DD/MM/AAAA">
<button onclick="checkPassword()">Entrar</button>
<div id="message">
<h3>Feliz aniversário, <span style="font-size: 24px; font-weight: bold;">[Nome]</span>!</h3>
<p>Hoje é um dia especial, e, mesmo com tudo o que aconteceu, eu queria te lembrar o quanto você significa pra mim. Que você tenha um ano cheio de alegrias, conquistas e, acima de tudo, felicidade. Eu sempre vou guardar com carinho os momentos que passamos juntos.</p>
<p style="font-style: italic;">Com todo o meu afeto e gratidão por tudo o que vivemos. ❤️</p>
</div>
</div>

<script>
function checkPassword() {
var input = document.getElementById("password").value;
if (input === "16/03/2024") {
document.getElementById("message").style.display = "block";
setTimeout(function() {
document.getElementById("message").style.opacity = "1";
document.getElementById("message").style.transform = "translateY(0)";
}, 200);
} else {
alert("Senha incorreta. Tente novamente!");
}
}
</script>
</body>
</html>
