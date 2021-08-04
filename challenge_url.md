# Teste Backend

A intenção do desafio é avaliar sua capacidade de aprendizado.
Não tem problema caso não consiga terminar algo e tenha receio de enviar sem alguma funcionalidade porém sempre
estamos aqui para tirar dúvidas.

O desafio consiste de criar uma aplicação backend para encurtar URL's (como serviços tipo goo.gl, tinyurl fazem).

Por exemplo, utilizando a aplicação eu deveria ser capaz de chamar uma rota de:

POST localhost:4000/short_url

```json
{
  "url": "http://www.google.com.br"
}
```

E receber algum tipo de resposta com uma URL encurtada, como por exemplo:

```json
{
  "short_url": "localhost:4000/ABC"
}
```

Que seja capaz de me redirecionar para a url original `http://google.com.br`.

## Informações Gerais

A funcionalidade principal da aplicação já foi descrita acima, outras funcionalidades desejadas são:

- A criação de usuários no sistema deve ser aberta, um usuário consiste de:
  - Email;
  - Senha.
- Um usuário deve ser capaz de "logar" no sistema, recebendo algum tipo de dado identificador (token, id ou semelhante)
- A criação de URL's encurtadas deve ser feita somente por usuários cadastrados, que consiste de:
  - URL original;
  - URL encurtada;
  - Usuário que criou ela;
  - Quando foi criada.
- A visualização das URLs que "meu" usuário criou.
- Não deve permitir que usuários vejam as URLs encurtadas de outros usuários.
- Todos devem ser sempre capaz de acessar as URLs encurtadas geradas.

## Dicas

- Você pode nos contatar sempre que tiver qualquer tipo de dúvida.
- O que foi descrito neste documento são as funcionalidades básicas do projeto, não se atenha à "possivies estruturas"
  documentadas aqui.
- As rotas de criação de usuário podem ser abertas para qualquer um utilizar, as outras rotas devem ser privadas,
  isso pode ser feito com um Token de autorização utilizando alguma biblioteca disponível.

## Requerimentos

- O desafio pode ser realizado em qualquer linguagem utilizando qualquer framework de preferência.
- Deve ser utilizado algum tipo de Banco de Dados para salvar as URL's encurtadas.

## Extras

- Testes são bem vindos! :)
- README detalhado de como rodar/testar a aplicação também!
- Não salvar a senha do usuário em texto puro ganha pontos extras.
