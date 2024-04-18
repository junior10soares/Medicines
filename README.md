# Descrição da Pull Request

## Desafio

Olá! Nesta PR, estou enviando minha solução para o teste de desenvolvedor frontend Jr. da Dotlib. Desenvolvi uma aplicação em React para um bulário eletrônico, que permite consultar e visualizar bulas de medicamentos.

## Funcionalidades Implementadas

- Consulta por nome do medicamento ou laboratório farmacêutico.
- Listagem dos resultados da consulta.
- Ordenação pela data de publicação do medicamento.
- Paginação de 10 em 10 itens por página.

## API Utilizada
- `/data`: retorna todos os items paginados de 10 em 10.
- `/data/:id`: retorna um medicamento consultado pelo id.
- `/data?_page=:number`: retorna os items paginados.

## Dicionário de Dados

Forneço abaixo um resumo dos campos utilizados na aplicação:
- `id`: identificador do medicamento.
- `name`: nome do medicamento.
- `published_at`: data de publicação.
- `company`: nome do laboratório.
- `documents.id`: identificador da bula profissional ou paciente.
- `documents.expedient`: registro da bula em orgãos responsáveis.
- `documents.type`: tipo da bula (PROFESSIONAL ou PATIENT).
- `documents.url`: URL da bula.
- `active_principles.id`: identificador do princípio ativo encontrado no medicamento.
- `active_principles.name`: nome do princípio ativo encontrado no medicamento.

## O que foi analisado

Ao desenvolver esta solução, levei em consideração os critérios de avaliação listados abaixo:
- Tempo de entrega do teste.
- Organização e legibilidade do código.
- Padronização de commits.
- Separação de componentes.
- Sugestões de novas funcionalidades, como download do PDF da bula.

## Versão web
![Captura de tela de 2024-04-18 00-39-47](https://github.com/Dotlib-BR/teste-desenvolvedor-frontend/assets/113471068/9444c765-ede3-41f5-a25f-d9e27cb806ef)

## Versão mobile
![Captura de tela de 2024-04-18 00-40-22](https://github.com/Dotlib-BR/teste-desenvolvedor-frontend/assets/113471068/52141909-66ee-4533-a66f-4268f4260032)

## Deploy
O site do teste está acessível para qualquer pessoa [aqui](https://medicines.vercel.app/).

Aguardo feedbacks e estou à disposição para quaisquer esclarecimentos adicionais.

Atenciosamente,
Edson Martins Soares Junior
