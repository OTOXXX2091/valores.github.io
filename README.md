<!DOCTYPE html> 
<html lang="en"> 

<head> 
	<meta charset="UTF-8" /> 
	<meta name="viewport"
		content="width=device-width, 
				initial-scale=1.0" /> 
	<link rel="stylesheet"
		href="style.css" /> 
	<title>Valores</title> 
</head> 

<body> 
	<div class="containerNew"> 
		<header> 
			

			<div class="timer"> 
				<p> 
					: 
					<span id="timer"> 
						0 
					</span> 
				</p> 
			</div> 
		</header> 

		<main class="quiz"> 
			<div id="quiz-start"> 
				<div class="landing"
					id="start-screen"> 
					<h1 id="top"> 
						Valores de la empresa
					</h1> 
					
					<p> 
						En el siguiente quiz 
						encontraremos preguntas
						sobre los valores de la empresa  
					</p> 
					<button id="start"> 
						Empezar 
					</button> 
				</div> 
			</div> 

			<div class="hide" id="questions"> 
				<h2 id="question-words"></h2> 
				<div class="options" id="options"> 
				</div> 
			</div> 

			<div class="hide" id="quiz-end"> 
				<h2>Finalizado</h2> 
				<p>Tu puntuacion Final es: 
					<span id="score-final"> 
					</span> 
				</p> 
				<p> 
					Ingrese su Nombre: 
					<input type="text"
						id="name"
						max="3" /> 
					<button id="submit-score"> 
						Subir 
					</button> 
				</p> 
			</div> 

			<div id="feedback"
				class="feedback hide"> 
			</div> 
		</main> 
	</div> 
	<script src="script.js"></script> 
</body> 

</html>

