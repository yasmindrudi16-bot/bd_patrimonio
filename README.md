# bd_patrimonio
API de Patrimônio
Descrição
API REST para cadastrar, consultar, atualizar e excluir patrimônios, contendo informações como item, local, data, valor e número de patrimônio.

Instalação e execução
git clone <URL_DO_REPOSITORIO>
cd <NOME_DO_PROJETO>
npm install
npm start

A API será executada em http://localhost:3000.

Tecnologias
Node.js
Express.js
JavaScript
JSON
npm
Rotas
Método	Rota	Função
GET	/patrimonios	Listar patrimônios
GET	/patrimonios/:id	Buscar por ID
POST	/patrimonios	Cadastrar patrimônio
PUT	/patrimonios/:id	Atualizar patrimônio
DELETE	/patrimonios/:id	Excluir patrimônio

Exemplo de requisição
GET /patrimonios/1

Exemplo de resposta
{
  "id": "1",
  "item": "Notebook Dell",
  "local": "Laboratório 01",
  "dataRegistro": "2026-09-10",
  "valor": 3500.00,
  "patrimonio": "PAT-00125"
}
