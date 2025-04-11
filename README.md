# cibersecurity-desafio-ransomware

## Entendendo um Ransomware na Prática com Python

# Etapas de criação do Ransomware
## Totalmente confeccionado através do terminal do Kali Linux.
- Antes de tudo, criei uma pasta "projeto-ransomware" e, dentro dela, criei os arquivos "encrypter.py", "decrypter.py" e "teste.txt. Assim definindo o diretório que tanto o encriptador quanto o descriptador iriam funcionar, ambos sobre o arquivo "teste.txt";
- Após a criação dos arquivos, confeccionei o código do encriptador, utilizando da biblioteca "pyaes" para me auxiliar no processo de encriptação do arquivo. Esse código abre e lê o arquivo "teste.txt", remove o arquivo, cria uma chave de criptografia (que deve conter 16 caracteres para se enquadrar nos padrôes devidos), criptografa o arquivo e o salva no diretório.
- Logo em seguida elaborei o código do arquivo do descriptador, também me utilizando da biblioteca pyaes para reunir as informações já declaradas no arquivo de encriptação e, através dessa biblioteca, descriptografar o arquivo e fornecer as informações contidas antes nele.   ;
- Por fim, antes de executar os arquivos, defini um texto teste dentro do arquivo "teste.txt": "Arquivo completamente descriptografado". Assim, posso testar se o arquivo realmente retorna as informações presentes nele antes da execução do ransomware;

## O projeto foi um sucesso, todos os arquivos funcionaram perfeitamente e o arquivo não só foi criptografado e decriptografado, mas também retornou a mesma frase teste presente antes do ransomware.

## Todos os códigos e arquivos estão presentes no repositório.
