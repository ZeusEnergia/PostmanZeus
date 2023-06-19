# PostmanZeus
Biblioteca do Postman com exemplos de como acessar dados do sistema Zeus via API 

# Utilização:

 1. O primeiro passo de utilização é a atualização das variáveis de ambiente dentro do Postman. Caso ainda não tenha os dados de login e senha para utilização da API em seu ambiente, entre em contato com a equipe de suporte. O idMigracao é obtido pela API com a chamada "Listar migrações". o idUnidade é obtido pela API com a chamada "Partes cadastradas no ambiente";
 
![Variaveis do postman para atualizar.](https://miracleworks.co/images/github/gitDoc1.png)

 2. Faça o login na plataforma, através da chamada "Authenticate". Não é necessária nenhuma modificação na chamada, basta executar que as variáveis de ambiente previamente definidas serão utilizadas e o retorno será um TOKENID para identificação nas demais chamadas. Este token tem duração de 30 minutos.
 
![Tela do postman com o "Authenticate" preenchido](https://miracleworks.co/images/github/gitDoc2.png)

 3. Em posse deste Id já é possível fazer as outras chamadas da API. Dentro do Postman o id já será utilizado automaticamente.

# Dados extras:
Dentro da documentação preparamos diversos exemplos, descrições e comentários com intuito de facilitar a experiencia de quem irá consumir a API do Zeus:

![Exmplos de documentação dentro do postman](https://miracleworks.co/images/github/gitDoc3.png)
