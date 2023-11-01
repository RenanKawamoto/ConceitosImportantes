# API

## O que é API❓
API, que significa Application Programming Interface (Interface de Programação de Aplicação), pode parecer um termo técnico complexo, mas vou explicar de uma forma mais simples:

Uma API é como um conjunto de regras que permite que diferentes sistemas e serviços se comuniquem. Imagine que seja uma ponte entre diferentes partes de um software. A principal ideia por trás disso é tornar mais fácil usar as funcionalidades de um sistema sem precisar entender como esse sistema é construído por dentro.

Embora essa definição ajude a entender o conceito básico, a verdade é que APIs realmente começam a fazer sentido quando você começa a usá-las na prática. No final deste texto, vou fornecer um link para uma API que você pode experimentar para ter uma ideia mais concreta.

## Como funciona uma API web❓
Uma API web funciona com um conjunto de "Rotas" (essas são basicamente URLs) que, quando acessadas com os "métodos" corretos, retornam informações úteis. Essas rotas recebem "Requisições" de outros sistemas e retornam "Respostas" que podem ser usadas da maneira desejada.

- O que são Requisições:
  - Requisições são como "pedidos" enviados para um sistema. Geralmente, utilizamos as "Requisições HTTP" porque são comuns e utilizam o protocolo HTTP, que é amplamente utilizado na web.
  - A estrutura de uma requisição HTTP inclui:
    - Método HTTP: Isso define a ação a ser realizada na API, como GET para obter dados, POST para criar dados, PUT para atualizar dados e DELETE para excluir dados.
    - Rota: A URL que identifica o recurso da API que você deseja acessar.
    - Cabeçalhos (Headers): Informações adicionais enviadas com a requisição, como autenticação, tipo de conteúdo, entre outras.
    - Corpo (Body): Os dados que você deseja enviar com a requisição, geralmente usado em solicitações POST e PUT.

- O que são Respostas:
  - As respostas são retornadas pela API após o processamento da requisição. Elas incluem:
    - Código de Status HTTP: Um código numérico que indica se a requisição foi bem-sucedida (por exemplo, 200 para OK) ou se houve um erro (por exemplo, 404 para Not Found).
    - Cabeçalhos (Headers): Informações adicionais fornecidas pela API, como detalhes sobre a resposta e informações de autenticação.
    - Corpo (Body): Os dados retornados pela API, geralmente em um formato como JSON, XML, HTML ou outro formato compatível.

No contexto de uma API web, a comunicação ocorre por meio dessas requisições e respostas, permitindo que sistemas se interconectem e compartilhem dados e funcionalidades de maneira padronizada.

Para experimentar uma API na prática, você pode visitar: https://pokeapi.co/
