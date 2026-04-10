index.html
<!DOCTYPE html>
<html>
<body style="text-align:center; margin-top:100px;">

<button onclick="abrirSobre()" style="padding:20px; font-size:20px;">
📩 Abrir sobre
</button>

<h1 id="resultado"></h1>

<script>
function abrirSobre() {
  let opciones = ["💀 Eliminado", "✅ Vivo"];
  let random = Math.floor(Math.random() * opciones.length);
  document.getElementById("resultado").innerText = opciones[random];
}
</script>

</body>
</html>
