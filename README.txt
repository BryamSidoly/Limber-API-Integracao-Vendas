Limber Cross API - Swagger UI (gerado)
=====================================

Como usar:
1. Extraia este .zip em uma pasta.
2. Abra o arquivo index.html em um navegador (requer acesso à internet para carregar Swagger UI via CDN).
3. A Swagger UI apontará para o arquivo openapi.yaml local e permitirá testar as rotas contra o servidor de testes.

URL base usada no spec: https://testescard.limbersoftware.com.br

Observações importantes (fornecidas):
- Para evitar erros: envie os campos no formato number ou string. Caso o campo não for preenchido envie null.
- Rate limit: até 3 requisições por segundo.
- Token válido por até 7 dias. Token tipo bearer.

Erros padronizados:
- 401: expired token -> Renovar o token
- 401: invalid token -> Ambiente errado. Troque card por testescard ou vice-versa
- 400: Campo faltando, com formato ou tipo errado.
- 500: Erro de interpretação do servidor. Entre em contato com a equipe de suporte ou Implantação

Gerado a partir do arquivo Postman: API Cross Limber Software v2.postman_collection.json
