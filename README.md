# Desafio - Vaga - Pessoa desenvolvedora back-end PHP - Laravel
Olá, bem-vindo ao desafio para a vaga Pessoa Desenvolvedora back-end PHP!
Mais importante do que dizer quem somos, é dizer no que acreditamos. A OM30 é uma empresa que acredita na inovação como a melhor forma de trazer qualidade de vida às pessoas.
Pensando nisso, nosso teste para essa oportunidade, elaboramos um pequeno projeto desafio para conhecermos um pouco de sua experiência ;)

## Objetivo
Desenvolver um cadastro de pacientes, do qual possamos testar toda sua capacidade de criação de arquitetura, qualidade do código, validações e usabilidade.

## Diferenciais técnicos para a vaga:
- Experiência em desenvolvimento integrações entre sistemas;
- Conhecimento na realização de testes automatizados;
- Conhecimento em desenvolvimento de API's RESTful;
- Conhecinhemto em Vue.js

## Requisitos

### Sua aplicação deve:
- [ ] Obrigatoriamente para o desenvolvimento do back-end utilizar o framework Laravel.
- [ ] Desenvolver uma listagem de pacientes com busca, do qual deve-se permitir a adição, edição, visualização e exclusão de cada um dos pacientes.
- [ ] Cada paciente deve ter um endereço cadastrado em uma tabela à parte.
- [ ] Utilizar para banco de dados PostgreSQL e Redis (Cache e Queue).
- [ ] Utilizar migration, factory, faker e seeder.
- [ ] Cadastro de novos pacientes, contendo os campos, respectivas validações:
    - [ ] Foto do Paciente;
    - [ ] Nome Completo do Paciente*;
    - [ ] Nome Completo da Mãe*;
    - [ ] Data de Nascimento*;
    - [ ] CPF* (com validação);
    - [ ] CNS*(cartão nacional de saúde, com validação);
    - [ ] Endereço completo, (CEP, Endereço, Número, Complemento, Bairro, Cidade e Estado)*;
- [ ] Criar um endpoint para consulta de CEP que implemente a API do ViaCEP e faça cache (Redis) dos dados para futuras consultas.
- [ ] Criar um endpoint que faça importação de dados (pacientes) via arquivo .csv e seja processada em queue.
- [ ] Utilizar docker e docker-compose para execução do projeto (queremos avaliar seu conhecimento, seja criativo e não use o Laravel Sail).

## Material de apoio:
- Endereço: Utilizar a API do ViaCEP - https://viacep.com.br/;
- Algoritmo para validação do CNS (https://integracao.esusab.ufsc.br/ledi/documentacao/regras/algoritmo_CNS.html);

## Diferenciais:
- Utilizar algum padrão para commits;
- Possuir cobertura de testes unitários de 80% do código (PHP Unit);
- Integrar a aplicação ao Laravel Horizon para o monitoramento das queues;
- Utilizar o supervisord para o gerenciamento dos serviços necessários para o desenvolvimento e a execução do projeto;
- Utilizar elasticsearch para busca otimizada de pacientes;
- Paginar a listagem de pacientes;

## O que avaliamos?
- Lógica;
- Qualidade do código;
- Criatividade;
- Estrutura no github;

Fique a vontade para incluir algum diferencial em seu desafio!

## Entrega
- A entrega deve ser em 2 dias feita em um repositório público no GitHub, que deve conter:
- O código do projeto versionado no github em repositório público.
- O projeto deve ser entregue de forma "containerizada", com banco de dados (postgres, redis, e php), lembrando das configurações necessárias para execução dos testes.
- O projeto deve ter em sua pasta root, uma collection do insomnia nomeada (endpoints.json) contendo endpoints necessários para os testes e a avaliação do desafio.
- O projeto deve ter em sua pasta root, um arquivo nomeado import.csv
contento o template necessário para a importação.
- Um arquivo README que descreva o que foi feito e as etapas para rodar o
projeto, executar os testes e gerar o code coverage.
- Enviar o link do repositório para o meu e-mai ou whatsapp.
Importante: Não se preocupe se não conseguir entregar todos os requisitos: dê o seu melhor! 💪

Boa sorte ! =)

<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

<p align="center">
<a href="https://github.com/laravel/framework/actions"><img src="https://github.com/laravel/framework/workflows/tests/badge.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

## About Laravel

Laravel is a web application framework with expressive, elegant syntax. We believe development must be an enjoyable and creative experience to be truly fulfilling. Laravel takes the pain out of development by easing common tasks used in many web projects, such as:

- [Simple, fast routing engine](https://laravel.com/docs/routing).
- [Powerful dependency injection container](https://laravel.com/docs/container).
- Multiple back-ends for [session](https://laravel.com/docs/session) and [cache](https://laravel.com/docs/cache) storage.
- Expressive, intuitive [database ORM](https://laravel.com/docs/eloquent).
- Database agnostic [schema migrations](https://laravel.com/docs/migrations).
- [Robust background job processing](https://laravel.com/docs/queues).
- [Real-time event broadcasting](https://laravel.com/docs/broadcasting).

Laravel is accessible, powerful, and provides tools required for large, robust applications.