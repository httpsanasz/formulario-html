# formulario-html
primeiro formulario html

<html>

<head>

    <meta charset="UTF-8">
    
</head>

<body>
	<!--Entrada de dados com formulário-->
  
  <form action = "cadastro.php" method = "POST">	
  
	<fieldset>
  
		<legend>Cadastro do Aluno</legend>
    
		<label><b>Nome:</b></label>
    
		</br><input type="text" name="nome">
    
		</br><label><b>Cidade:</b></label>
    
		</br><input type="text" name="cidade">
    
		</br><label><b>Idade:</b></label>
    
		</br><input type="text" name="idade">
    
		</br></br>
    
		<input type="submit" name="btn_enviar" value="Enviar">
    
		<input type="reset" name="btn_enviar" value="Limpar">
    
	</fieldset>
  
	</form>
  
</body>

</html>
