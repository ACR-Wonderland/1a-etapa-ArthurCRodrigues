## Feedback do código - ArthurCRodrigues

**Nota final: 33.67/100**

### Testes Base:
- **Pontos Positivos:**
  - A rota /sugestao está correta e responde adequadamente a requisições GET com query string.
  - A rota /api/lanches retorna um status 200 OK, um header Content-Type de application/json e uma lista de lanches com atributos corretos.

- **Pontos a Melhorar:**
  - A rota / não está retornando o status 200 OK esperado.
  - A rota / não está retornando o Content-Type correto como text/html.
  - A rota / não contém pelo menos um formulário como esperado.
  - A rota /sugestao não está exibindo o "nome" e "ingredientes" enviados no HTML.
  - A rota /contato (GET) não possui todos os campos esperados no formulário.
  - A rota /contato (POST) não está exibindo todos os dados enviados no formulário.
  
### Testes Bônus:
- **Pontos a Melhorar:**
  - Você não implementou o uso correto de PRG (Post-Redirect-Get).
  - Os rótulos dos formulários na rota raiz e na rota /contato não estão corretos.

### Testes de Penalidade:
- **Pontos a Melhorar:**
  - Evite permitir métodos como POST, PUT, DELETE, PATCH em rotas que não deveriam aceitá-los.
  - Certifique-se de que os tipos de conteúdo retornados pelas rotas estão corretos.
  - Verifique se os formulários possuem atributos de nome corretos.

No geral, você fez um bom progresso na implementação das rotas, mas ainda há alguns ajustes a serem feitos para atender a todos os requisitos dos testes. Continue praticando e melhorando suas habilidades em Express.js, você está no caminho certo! Se precisar de ajuda com alguma parte específica, fique à vontade para pedir suporte. Parabéns pelo esforço e continue progredindo! 👏🚀