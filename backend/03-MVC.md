# MVC (Model-View-Controller)

## O que é❓
MVC é a abreviação de Model-View-Controller, que é um padrão de projeto ou arquitetura usado como base para o desenvolvimento de aplicações.

## Como funciona❓
Neste padrão de arquitetura, dividimos o código em três partes com funções distintas:
- *Models:* Os códigos do modelo lidam com o banco de dados. Eles são responsáveis por realizar operações como SELECT, INSERT, DELETE e assim por diante.
- *Views:* Os códigos da visualização estão relacionados à interface do usuário. Eles geram a aparência das telas, especialmente em aplicações web.
- *Controllers:* Os códigos do controlador tratam da lógica e das regras de negócio do projeto. Aqui, você cria a lógica do sistema e pode chamar códigos das visualizações e modelos conforme necessário.

![image](https://github.com/RenanKawamoto/ConceitosImportantes/assets/71828598/8088d531-2058-4d72-84dd-77b470946a16)

## Curiosidades:
- Em alguns casos, a "regra de negócio" do sistema pode estar nas "Models", principalmente quando as operações de CRUD são executadas nesse componente. Nesse cenário, o "Controller" atua mais como um administrador das "Models".
- Em situações em que há uma separação entre o backend e o frontend com APIs, é comum dizer que o "Backend" fica com as "MC" (Models e Controllers), enquanto o "Frontend" fica com a "V" (Views).

A arquitetura MVC ajuda a organizar o código e separar as responsabilidades, tornando o desenvolvimento de aplicativos mais eficiente e fácil de manter.
