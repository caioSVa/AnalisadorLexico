# AnalisadorLexico
Anlisador Léxico simples feito em python.
Reconhece tokens como palavras-chave, operadores, delimitadores, identificadores, números, strings, literais de caractere e 
tembém lida com comentários e quebras de linha.
Não identifica alguns operadores como: &&, ||, +=, -=.
O código que deve ser analisado to tipo .p deve ser colocado no arquivo main.py, e para executar o código com Makefile é necessário executar "make run" no terminal, caso o código seja válido os tokens serão salvos em um arquivo de texto "tokens.txt", mas caso ocorra algum erro léxico, o erro será registrado em "erros.txt". E para excluir os arquivos gerados, caso queira, basta executar no terminal o comando "make clean".
A saída no arquivo de texto seguirá o formato de: o tipo de Token, o lexema lido e em qual linha do código ele está. 
Os erros identificados são: Números mal formatados, literal de caractere inválido, string sem aspas de fechamento e caracteres não registrados.
