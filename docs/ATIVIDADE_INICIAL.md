ATIVIDADE INICIAL DO PROJETO – DEFINIÇÃO E PLANEJAMENTO

1. Objetivo da Atividade
Nesta primeira etapa, o grupo deverá iniciar o projeto de Quality Assurance organizando as ideias, definindo o sistema e estruturando o planejamento inicial.
O foco não é programar neste momento, e sim organizar o trabalho de forma clara para facilitar as próximas etapas.
Pensem nesta fase como a base do projeto. Quanto mais bem feita, mais fácil será o restante.
2. Formação dos Grupos
Formar grupos de até 5 integrantes
Confirmar todos os membros antes de iniciar
Garantir que todos participem
Orientação: evitem deixar tudo com apenas um integrante. Dividir responsabilidades desde o início ajuda muito.
3. Escolha do Tema
Escolham um dos temas propostos:
Sistema de Gestão Financeira 
E-commerce (Loja Virtual)
Plataforma de Cursos Online
Sistema de Agendamento
API de Usuários
Orientação: escolham um tema que o grupo entenda bem. Isso facilita na hora de pensar nos testes.
4. Atividades a serem realizadas
O grupo deverá elaborar um documento contendo os itens abaixo.
4.1 Identificação do Grupo
Arthur Salgado
Hakeem Oloye
Gustavo Vitória
Hernan Muniz 

Orientação: já definam um padrão de organização. Isso ajuda na apresentação final.

4.2 Tema Escolhido
Sistema de Agendamento
Proposta:
 Desenvolver um sistema simples de agendamentos, permitindo que usuários criem, visualizem e removam compromissos. O sistema será desenvolvido inicialmente em Python e possibilitará a aplicação das práticas de Quality Assurance, incluindo testes manuais, automatizados e testes de API
4.3 Descrição do Sistema
Descrever de forma objetiva:
O que o sistema faz:
 Permite cadastro de usuários, criação de compromissos, verificação de conflitos de horário, consulta de agendamentos e cancelamento.
Quem utilizará o sistema:
 Pessoas que precisam organizar compromissos de forma simples, como estudantes, profissionais e usuários em geral.
Qual problema ele resolve:
 Evita conflitos de agenda e falta de organização, oferecendo uma ferramenta simples para registrar horários e controlar compromissos.

Orientação: evitem textos longos. Se não conseguem explicar em poucas linhas, o sistema ainda não está claro.
4.4 Funcionalidades Principais
Listar pelo menos 5 funcionalidades.
Exemplos:
Cadastro de Usuário
Login
Criar Agendamento (data, horário e descrição)
Listar Agendamentos do Usuário
Cancelar Agendamento Existente

Orientação: pensem em funcionalidades simples, mas que possam ser testadas.
4.5 Definição Inicial de Testes
Criar pelo menos 5 cenários de teste.
Cada cenário deve indicar:
O que será testado
O comportamento esperado
Cenários escolhidos:
Login com senha incorreta
 Resultado esperado: Mensagem “Senha incorreta” deve ser exibida.
Criar agendamento em horário já ocupado
 Resultado esperado: Sistema deve bloquear o registro e informar conflito.
Criar agendamento com data inválida (ex.: 40/12/2025)
 Resultado esperado: Sistema deve rejeitar a data e solicitar correção.
Cancelar agendamento inexistente
 Resultado esperado: Deve informar que o agendamento não foi encontrado.
Consultar lista de agendamentos vazia
 Resultado esperado: Sistema deve mostrar “Nenhum agendamento encontrado”.

Orientação: um bom teste tenta encontrar erro, não apenas confirmar que funciona.
4.6 Tecnologias e Ferramentas
Informar:
Como pretendem desenvolver o protótipo em Python
Python 3.x
Entrada e saída via input() e print() (terminal)
Uso de bibliotecas:
datetime → validação de datas
json → armazenamento simples
Possível versão evoluída para API (fase avançada do projeto):
Flask ou FastAPI
Testes via Postman
Quais ferramentas pretendem utiliza:
pytest → testes automatizados
unittest → alternativa interna do Python
requests → testes de API
Postman → testes de endpoints (se API for criada)
Selenium (opcional, caso se crie interface)

Orientação: não precisa escolher tudo agora, mas tenham uma direção.
4.7 Organização do Grupo
Definir quem ficará responsável por:
Arthur Salgado: Desenvolvimento do protótipo
Hakeem Oloye: Documentação, preparação dos cenários de teste
Gustavo Vitória: Testes iniciais (manuais e automatizados)
Hernan Muniz: Organização do repositório e controle de versões
Orientação: todos devem participar. Mesmo com divisão, ninguém deve ficar sem função.
5. Criação do Repositório no GitHub
Cada grupo deverá:
Criar um repositório no GitHub
Definir um nome para o projeto
Adicionar todos os integrantes como colaboradores
Criar um arquivo README.md contendo:
Nome do projeto
Integrantes
Tema escolhido
Descrição inicial
Orientação: não deixem para depois. O repositório será usado durante todo o projeto.
6. Entrega da Atividade
O grupo deverá entregar:
Documento em PDF ou Word
Link do repositório no GitHub
7. Prazo
Entrega até hoje às 22h turmas da noite e 10 horas, turmas da manhã, apenas um componente envia para rodrigo.moreira@pro.fecaf.com.br 
8. Observações Importantes
Não é necessário desenvolver código nesta etapa
O foco é planejamento e organização
A criação do repositório é obrigatória
Esta etapa impacta diretamente o andamento do projeto
Orientação Final
Tratem este projeto como uma experiência real. Organização, clareza e divisão de tarefas fazem diferença. Grupos que se organizam bem no início tendem a ter melhores resultados nas próximas etapas.
