# Sistema de Gestão das Olimpíadas
O Sistema de Gestão das Olimpíadas (SGO) foi desenvolvido com o objetivo de auxiliar na organização e gerenciamento de eventos olímpicos, permitindo o controle das competições, inscrições de atletas, alocação de locais, registro de resultados e geração de relatórios de medalhas.

O sistema busca centralizar as principais funcionalidades necessárias para a administração de uma olimpíada, garantindo maior organização, controle das informações e redução de conflitos relacionados à programação das competições.

O projeto foi modelado utilizando diagramas UML desenvolvidos na ferramenta PlantUML, contemplando diferentes perspectivas arquiteturais e estruturais do sistema.

## Objetivos do Sistema
* Gerenciar competições olímpicas;
* Realizar inscrições de atletas;
* Controlar a alocação de locais das provas;
* Registrar resultados das competições;
* Gerar relatórios de medalhas por país;
* Organizar as informações do evento de forma centralizada.

## Regras de Negócio
### Cadastro de Competições
O sistema deve permitir o cadastro de competições contendo
* Modalidade
* Data
* Horário
* Local
* Lista de atletas inscritos

### Inscrição de Atletas
* Atletas podem participar de várias competições
* Cada atleta representa apenas um país por modalidade

### Alocação de Locais
* Um local não pode possuir duas competições simultaneamente
* O sistema deve evitar conflitos de horário

### Controle de Resultados
Após cada competição, o sistema deve registrar
* Medalhista de ouro
* Medalhista de prata
* Medalhista de bronze

### Relatórios de Medalhas
O sistema deve gerar relatórios contendo
* Quantidade de medalhas de ouro
* Quantidade de medalhas de prata
* Quantidade de medalhas de bronze
* Desempenho geral dos países

## Histórias de Usuário
### US01 - Cadastro de competição
Como administrador, quero cadastrar competições, para organizar as modalidades olímpicas.

### US02 - Inscrição de atletas
Como atleta, quero me inscrever em competições, para participar das olimpíadas.

### US03 - Alocação de locais
Como organizador, quero alocar locais para as competições, para evitar conflitos de horário.

### US04 - Registro de resultados
Como administrador, quero registrar os resultados das competições, para definir medalhistas.

### US05 - Relatório de medalhas
Como administrador, quero gerar relatórios de medalhas, para acompanhar o desempenho dos países.

## Diagramas
* [**Caso de Uso**](./Diagramas/Casos%20de%20Uso.pdf)
* [Classes](./Diagramas/Classe.pdf)
* [Pacotes](./Diagramas/Pacotes.pdf)
* [Implantação](./Diagramas/Implantacao.pdf)
* [Componentes](./Diagramas/Componentes.pdf)























