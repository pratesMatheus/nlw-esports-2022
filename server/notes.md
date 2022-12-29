Em ambiente de desenvolvimento nossa aplicação usa o localhost

 * Vamor criar a primeira rota da nossa aplicação, com método get():
 * - primeiro parâmetro é o endereço da aplicação
 * - o segundo parãmetro é uma função (NOTA: essa função recebe dois parâmetros: requisição e resposta)

### HTTP methods / API RESTful: 
 * GET - operação de leitura;
 * POST - quando for criar algo no back-end
 * PUT - editar uma entidade no back-end
 * PATCH - editar um info específica em uma entidade
 * DELETE - remover uma entidade do back-end
 * 
 * HTTP Codes:
 * 201 - algo foi criado! //created
 * 
 * Métodos HTTP são bem mais uma convenção, mas também são a melhor forma de criar uma API RESTful

### Tipos de parâmetros:
 * Query: vem através do ponto de interrogação. Query params são usados para persistir estado e possuem uma nomeação. São parâmetros da URL e jamais devem ser usados com uso de informações pessoais
 *  ex.:  localhost:3333/ads?page=2
 * 
 * Route: Também são parâmetros da URL, mas não possuem nomeação. São intrissicamente reconhecíveis pelas pessoas na URL;
 * Body: Usado quando enviamos uma ou várias informações em uma única requisição, por exemplo, formulário. É o mais recomendado para informações mais sensíveis;
 