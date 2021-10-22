<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<title>Formulario</title>
</head>
<body>
	<form method="POST" action="http://formadorestic.com/alumnosdaw/procesaformulario.php">
		<label for="name">Nombre:</label>
			<input type="text" name="nombre" id="name" placeholder="Introduzca nombre" required><br><br>
		<label for="correo">Correo email:</label>
			<input type="email" name="email" id="correo"><br><br>
		<label for="años">Edad:</label>
			<input type="number" name="edad"><br><br>
		<label for="mayor"></label>
			<input type="radio" name="mayormenor" id="mayor" value="Mayor">Mayor<br><br>
		<label for="menor"></label>
			<input type="radio" name="mayormenor" id="menor" value="Menor">Menor <br><br>
			<input type="submit" value="Enviar">
	</form>
</body>
</html>
