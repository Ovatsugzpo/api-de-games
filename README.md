# API DE GAMES
Esta api serve pra listar/editar/deltar jogos
## EndPoints
### GET /games
Esse endpoint é responsavel por retornar a listagem de todos os games cadastrados no banco de dados
#### Parametros
Nenhum
#### Respostas
##### OK! 200
Caso essa resposta aconteça vc vai receber a listagem de games
##### Falha na autenticação! 401
Caso receba essa resposta, é pq aconteceu uma falha durante o processo de autenticação. Motivos: token invalido/expirado
