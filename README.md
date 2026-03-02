# osbaldoalcarazAssignment5.github.io
<!DOCTYPE html>
<html>
	<head>
		<title>Fancify Shamcify</title>

		<!-- link to your script file here -->
		<script src="fancifymytext.js"></script>
		
	</head>

	<body>
		<h1>Fancify my Text</h1>
		

		<!-- Your UI controls go here -->
		 <Text> 
			<label for="textBox" style="font-size:30px;">Text </label> 
			<textarea rows = "4" cols="30" type="Text" id="textBox" name = "textBox"> </textarea> <br>

			<label for="fancyBox" style="font-size:30px;">Fancify </label> 
			<p id="textID"></p>
			<button onclick="BiggerButton()">Bigger</button> <br>
			<input type="radio" onchange="FancyText()" id="textBox" name="textFont" value="FF">
			<label for="html">FancyShmancy</label><br>
			<input type="radio" onchange="NormalText()" id="textBox" name="textFont" value="BB">
			<label for="css">BoringBetty</label><br>

			<label for="fancyBox" style="font-size:30px;">Moo </label> <br>
			<button onclick="MooButton()">Moo</button> <br>
			<Text>
		
	</body>
</html>
