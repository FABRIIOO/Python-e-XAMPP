# Python-e-XAMPP
Como rodar o python no xampp

******** Rodar o Python no XAMPP ***********

  1° passo instalar o XAMPP em C:/
  
  2° Isntalar o python ou no htdocs, para buscar o python no arquivo .py insere #!/python27/python
   OU  
     Instalar o python no C:/ para buscar o python instalado insira em seu arquivo #!C:/Python27/python lembre-se CUIDADO 
     com o nome das pastas em maiúsculas ou minusculas isso faz diferença.
 
  3° insira em seu arquivo C:\xampp\apache\conf\httpd.conf insira em AddType application/x-gzip .gz .tgz essa extensão .py fica assim AddType application/x-gzip .gz .tgz .py 
     LEMBRE-SE assim que você inserir isso no httpd.conf reinicia o xampp.
  4° insira em seu arquivo .py o seguinte 
      - Se o python estiver instalado no C:/ insira esse código no arquivo python #!C:/Python27/python		

	#!C:/Python27/python
	print ("Content-type: text/html\n\n")
	print ("Ola mundo lindo com python")
	
	OU
      - Se o python estiver instaldo no htdocs insira isse codigo no arquivo python #!/python27/python
	
	#!/python27/python
	print ("Content-type: text/html\n\n")
	print ("Ola mundo lindo com python")
		
  5° Agora acesse o localhost/SeuArquivoPython e pronto. 
 [[[[[[[[[[[[[[[[[[[[[ SE DER ERRO 500 PODE SER PORQUE O SEU ARQUIVO .PY NÃO ENCONTROU O PYTHON NO SERVIDOR ]]]]]]]]]]]]]]]]]]]]]]] 
