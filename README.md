TechFlow Task Manager – Projeto de Engenharia de Software

# TechFlow Task Manager

## 📌 Descrição do Projeto
Este projeto simula o desenvolvimento de um sistema de gerenciamento de tarefas para uma startup de logística, utilizando metodologias ágeis e boas práticas de Engenharia de Software.

O sistema permite criar, visualizar, atualizar e remover tarefas, além de acompanhar o fluxo de trabalho em tempo real.

## 🎯 Objetivo
Desenvolver um sistema simples e funcional que demonstre:

Aplicação de metodologias ágeis

Uso de controle de versionamento

Automação de testes

Gestão de mudanças

Integração contínua utilizando GitHub Actions

## 🧩 Escopo Inicial
- CRUD de tarefas
- Organização do projeto com Kanban
- Testes automatizados
- Pipeline de CI

## 🔄 Metodologia Utilizada
Foi adotada a metodologia Kanban, utilizando o GitHub Projects para o controle visual das tarefas, permitindo o acompanhamento contínuo do progresso do projeto.

## 🛠️ Tecnologias Utilizadas
- `Python`

- `Flask`


- `Pytest`

- `GitHub Actions`

- ## 🔄 Mudança de Escopo

Durante o desenvolvimento do projeto, foi realizada uma mudança de escopo em relação ao planejamento inicial.

Inicialmente, o sistema previa apenas a implementação de um CRUD básico de tarefas. No entanto, ao longo do projeto, foi identificada a necessidade de aumentar a confiabilidade e a qualidade do software.

Como resultado, foi adicionada a seguinte funcionalidade ao escopo:

- Implementação de testes automatizados utilizando Pytest
- Criação de um pipeline de Integração Contínua (CI) com GitHub Actions
- Execução automática dos testes a cada push ou pull request na branch principal

Essa mudança foi registrada no quadro Kanban do GitHub Projects e implementada por meio de commits específicos, garantindo melhor qualidade, manutenção e aderência às boas práticas da Engenharia de Software.

## 🔧 Desafios e Correções Durante o Desenvolvimento

Durante a configuração do pipeline de Integração Contínua com GitHub Actions, foram identificados erros iniciais relacionados à execução dos testes automatizados.

O principal problema ocorreu devido à estrutura de diretórios do projeto, onde o módulo da aplicação não era localizado corretamente durante a execução do Pytest no ambiente de CI. Para solucionar esse problema, foi necessário ajustar a configuração do ambiente, garantindo que o caminho correto da aplicação fosse reconhecido durante a execução dos testes.

Após os ajustes no workflow, os testes passaram a ser executados corretamente, resultando em um pipeline funcional e estável.

## ▶️ Como Executar o Projeto

Certifique-se de ter o Python instalado.

No diretório raiz do projeto, execute:

pip install -r requirements.txt
python src/app.py


A aplicação estará disponível no navegador conforme indicado no terminal.

