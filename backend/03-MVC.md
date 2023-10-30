# MVC

## O que é❓
MVC é o acrônimo de `M`odel-`V`iew-`C`ontroller que é um padrão de projeto / padrão de arquitetura, que usamos de base para criar nossas aplicações.

## Como funciona❓
Nesse padrão de arquitetura dividimos nosso código de acordo em 3 parte com suas funcionalidades:
- Models: os códigos de models são códigos que tem relação com o banco de dados, ou seja caso você queira fazer alguma operação (SELECT, INSERT, DELETE e etc) tera que faze-la em uma model;
- Views: os códigos de view são códigos relacionados com vizulização, ou seja são códigos que geram telas (no caso da web);
- Controllers: os códigos de controller são os códigos relacionados com a lógica/regra de negocio do projeto, ou seja nele você irá criar a lógica do sistema e chamar os códigos view e model caso seja necessário;

![image](https://github.com/RenanKawamoto/ConceitosImportantes/assets/71828598/8088d531-2058-4d72-84dd-77b470946a16)

## Curiosidades:
- Existem casos que a `regra de negocio` do sistema fica nas `Models`, uma vez que nela que realmente irá ocorrer processos do CRUD e o controller se torna somente um administrados das models;
- Em casos que trabalhamos com modelo backend e frontend com apis, podemos fazer uma associação dizendo que o `Backend irá ficar com MC (Models e Controllers) e o Frontend irá ficar com o V (views)`;
