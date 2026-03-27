# qa-sistema-agendamento.5NB
Projeto de Quality Assurance – Sistema de Agendamento. Protótipo em Python e testes manuais/automatizados.

Sistema de Agendamento – Projeto de Quality Assurance
Integrantes do Grupo

Arthur Salgado
Hakeem Oloye
Gustavo Vitória
Hernan Muniz

Tema Escolhido

O tema escolhido para o projeto é “Sistema de Agendamento”. A proposta consiste em desenvolver um sistema simples que permita aos usuários criar, visualizar e remover compromissos. O sistema será inicialmente implementado em Python e servirá como base para a aplicação de práticas de Quality Assurance, incluindo testes manuais, testes automatizados e testes de API.

Descrição do Sistema

O sistema tem como objetivo gerenciar compromissos de forma simples e organizada. Ele permitirá o cadastro de usuários, a criação de agendamentos, a verificação de possíveis conflitos de horário, a consulta de compromissos cadastrados e o cancelamento de registros.

O público-alvo do sistema é composto por pessoas que precisam organizar compromissos pessoais ou profissionais, como estudantes, trabalhadores e demais usuários em geral.

O problema que o sistema se propõe a resolver é a falta de organização e os conflitos de horário, oferecendo uma solução simples para registrar compromissos e manter controle sobre atividades agendadas.

Funcionalidades Principais

Entre as funcionalidades previstas para o desenvolvimento do sistema estão:

Cadastro de usuário.
Login.
Criação de agendamentos contendo data, horário e descrição.
Listagem de todos os agendamentos do usuário.
Cancelamento de agendamentos existentes.
Definição Inicial de Testes

Para esta etapa inicial foram definidos cinco cenários de teste principais, conforme orientado:

Testar login com senha incorreta, cujo resultado esperado é a exibição de uma mensagem indicando que a senha está errada.
Testar a criação de um agendamento em um horário já ocupado. O sistema deve identificar o conflito e impedir a criação.
Testar o cadastro de um agendamento com uma data inválida, como “40/12/2025”. O sistema deve rejeitar a entrada e solicitar uma correção.
Testar o cancelamento de um agendamento inexistente. O comportamento esperado é a apresentação de uma mensagem informando que o registro não foi encontrado.
Testar a consulta de agendamentos quando nenhum compromisso foi criado. O sistema deve indicar que não há agendamentos cadastrados.
Tecnologias e Ferramentas

O protótipo será desenvolvido em Python 3.x utilizando entrada e saída via terminal, por meio das funções input() e print(). Para auxiliar no funcionamento, serão utilizadas bibliotecas como datetime para validação de datas e json para armazenamento simples das informações.

Em etapas futuras, o sistema poderá evoluir para uma API utilizando Flask ou FastAPI, possibilitando testes adicionais com ferramentas como Postman.

Para a realização dos testes, serão utilizadas ferramentas como pytest para testes automatizados, unittest como alternativa para testes internos, requests para validação de API e eventualmente Selenium se houver necessidade de testes de interface gráfica.

Organização do Grupo

Cada integrante do grupo desempenhará um papel inicial no projeto. Arthur Salgado será responsável pelo desenvolvimento do protótipo. Hakeem Oloye ficará encarregado da documentação e criação dos cenários de teste. Gustavo Vitória será responsável pelos testes manuais e automatizados. Hernan Muniz atuará na organização do repositório e no controle de versões. Apesar da divisão de tarefas, todos os membros participarão das demais etapas do projeto.
