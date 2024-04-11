# Mapeamento do Potencial de Movimentação de Cargas no Aeroporto de SJK

Projeto API - 1° Semestre - Logística 2024, baseado na metodologia ágil SCRUM, procurando desenvolver a Proatividade, Autonomia, Colaboração e Entrega de Resultados dos estudantes envolvidos.

# Índice

* [Projeto](#projeto-template)
* [Equipe](#equipe)
* [Objetivo do Projeto](#objetivo-do-projeto)
* [Sprints](#Sprints)
* [Burndown](#Burndown)
* [Backlog do produto](#Backlog-do-produto)
* [Funcionalidades e registros (vídeos e apresnetações) das sprints](#uncionalidades-e-registros-(vídeos-e-apresnetações)-das-sprints)
* [Competências desenvolvidas](#competências-desenvolvidas)


# Projeto 
* **Introdução** 

Nosso projeto de logística visa mapear potenciais cargas para movimentação
no Aeroporto de São José dos Campos (SJK), com base em dados de
importações e exportações dos municípios da Região Metropolitana do Vale do
Paraíba (RMVALE) e do Litoral Norte.

* **Objetivo**

Desenvolvimento de uma interface gráfica que ofereça ao cliente uma análise visual, interativa e eficiente do fluxo de importação e exportação associado ao aeroporto de São José dos Campos (SJK). Utilizando os dados extraídos do ComexStat, uma base de dados governamental, esta interface visa facilitar e aprimorar a análise de potenciais novos investimentos, direcionando-os para o aeroporto SJK.

* **Projeto (API)**

Desenvolvimento de um projeto pedagógico baseado na Metodologia API, visando o ensino-aprendizado centrado no desenvolvimento de competências. Este projeto é fundamentado nos pilares do aprendizado com problemas reais (RPBL), validação externa e mentalidade ágil. Utilizando estratégias para compreender o problema, conceber uma solução viável, desenvolver e implementar o MVP (Minimum Viable Product), seguido pela sua operação (CDIO).


# Equipe
|    Função     | Nome                                  |                                                                                                                                                      LinkedIn & GitHub                                                                                                                                                      |
| :-----------: | :------------------------------------ | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
| Product Owner |   Yasmin Aureliano         |     [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/joaomarcosoliveiraa) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/JoaoM-py)              |
| Scrum Master  | Ana Caroline |      [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/mariagabrielareis/) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/MariaGabrielaReis)     |
| Team Member   | Fernando Ribeiro              |         [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/antonio-nepomuceno-04943720a/) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/Nepoun)        |
|  Team Member  | Rafaela Jonas                 |         [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/caio-vitor-c1/) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/CaioVitorDias1)        |
|  Team Member  | Nicolas Freitas                 |   [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/gabriel-camargo-915452196/) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/GabrielCamargoL)   |
|  Team Member  | Mariana Dominiciano       |           [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/gioliveirass) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/gioliveirass)          |


## Tecnologias Utilizadas

 ### Tecnologias Específicas/Apoio
![Excel](data:image/png;base64,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)
> Excel
> Jira Software
> Power BI
> Teams

  
 ### Tecnologias da Informação
 > Liste aqui todas as tecnologias utilizadas para concluir a entrega

# Sprints

Sprint | Previsão | Status| Histórico|
|------|--------|------|--------|
|Kick Off | 11/03/2024 | concluido| [Ver Relatório](https://fatecsjc-prd.azurewebsites.net/downloads/estagio/modelo_relatorio_estagio_gpi.docx) | 
|1 | 15/04/2024 | em progresso | [Ver Relatório](https://fatecsjc-prd.azurewebsites.net/downloads/estagio/modelo_relatorio_estagio_gpi.docx) | 
|2|  06/05/2024| em progresso |[Ver Relatório](https://fatecsjc-prd.azurewebsites.net/downloads/estagio/modelo_relatorio_estagio_gpi.docx) | 
|3| 27/05/2024 | a fazer|[Ver Relatório](https://fatecsjc-prd.azurewebsites.net/downloads/estagio/modelo_relatorio_estagio_gpi.docx) | 
|4| 17/06/2024 |a fazer |[Ver Relatório](https://fatecsjc-prd.azurewebsites.net/downloads/estagio/modelo_relatorio_estagio_gpi.docx)  | 
|Feira de Soluções|27/06/2024 |a fazer |[Ver Relatório](https://fatecsjc-prd.azurewebsites.net/downloads/estagio/modelo_relatorio_estagio_gpi.docx) | 

## Cronograma
Ao clicar você será redirecionado ao cronograma detalhado desse projeto, lá é possivel encontar as datas das atividades, o responsável por cada atividade, o estágio em que cada atividade se encontra e a qual sprint cada atividade pertence.

#### Cronograma das Sprints[(clique aqui)](https://github.com/users/AndreLuizRibeiro/projects/4)

# Requisitos

Requisitos funcionais 
- Conteúdo da apresentação   
- Relatórios 
- Experiência do usuário ao oferecer algo mais (UX)

  
Requisitos não funcionais
- Usar tecnologias especifícas/apoio/tecnológicas
- Metodologias ágil
- Power BI / Jira / Canvas
  
# Backlog do produto
  
<div align="center">
    
![product backlog](https://user-images.githubusercontent.com/69374340/172057734-320d9e43-19e9-409a-8f2d-7d159a1aaa9a.png)
![sprint backlog](https://user-images.githubusercontent.com/69374340/172057787-dcc1ecce-1b08-464b-850e-7019dc050056.png)
</div>


# Burndown
![sprint backlog](https://github.com/RoqueMoura/Template/blob/main/.img/Burndown.PNG)


## Sprint 1. Concepção
- [x] Defina o propósito do template;
- [x] Identifique os elementos principais;
- [x] Esboce o layout;
- [x] Escolha cores e fontes;
- [x] Desenvolva o design;
- [ ] Teste e revise;
- [ ] Documente instruções de uso;
- [ ] Criação do vídeo;
- [ ] Finalize e aprovação.

## Sprint 2. Desenvolvimento do Projeto
- [ ] Documento passo a passo;
- [ ] Vídeo passo a passo;
- [ ] Treinamento com os professores;
- [ ] Treinamento com os alunos;
- [ ] Monitoramento e ajustes.
      
## Sprint 3 . Implementação
- [x] Defina o propósito do template;
- [x] Identifique os elementos principais;
- [x] Esboce o layout;
- [x] Escolha cores e fontes;
- [x] Desenvolva o design;
- [ ] Teste e revise;
- [ ] Documente instruções de uso;
- [ ] Criação do vídeo;
- [ ] Finalize e aprovação.
      
## Sprint 4. Operacionalização
- [x] Defina o propósito do template;
- [x] Identifique os elementos principais;
- [x] Esboce o layout;
- [x] Escolha cores e fontes;
- [x] Desenvolva o design;
- [ ] Teste e revise;
- [ ] Documente instruções de uso;
- [ ] Criação do vídeo;
- [ ] Finalize e aprovação.

# Funcionalidades e registros (vídeos e apresentações) das sprints

Apresentação das funcionalidades
Confira a seguir uma demonstraão das funcionalidades para cada tipo de usuário do sistema:

Adicionar video e documentos nessa seção

[![Nome do Vídeo](https://img.youtube.com/vi/pBy1zgt0XPc/0.jpg)](https://www.youtube.com/embed/pBy1zgt0XPc)

# Competências desenvolvidas

## Hard Skill (saber tecnológico)
<details>
<summary>Hard Skills desenvolvidas</summary>
  
| Tecnologia/Metodologia | Classificação |
| ---------------------- | ------------- |
| GitHub | ★ ★ ★ ★ ★ ★ ★ ☆ ☆ ☆ |
| Gestão de Projetos | ★ ★ ★ ★ ★ ★ ☆ ☆ ☆ ☆ |
| Scrum Master | ★ ★ ★ ★ ★ ★ ★ ☆ ☆ ☆ |
| Prodct Owner | ★ ★ ★ ★ ★ ★ ★ ☆ ☆ ☆ |
| Markdown | ★ ★ ★ ★ ★ ★ ★ ☆ ☆ ☆ |
| Git Projects | ★ ★ ★ ★ ★ ★ ★ ☆ ☆ ☆ |
 
</details>

## Soft Skill (saber comportamental)
<details>
<summary>Soft Skills desenvolvidas</summary>

| Habilidades | Classificação |
| ---------------------- | ------------- |
| Colaboração | ★ ★ ★ ★ ★ ☆ ☆ ☆ ☆ ☆ |
| Proatividade| ★ ★ ★ ★ ★ ★ ☆ ☆ ☆ ☆ |
| Pensamento Crítico | ★ ★ ★ ★ ★ ★ ★ ☆ ☆ ☆ |
| Gerenciamento de Tempo | ★ ★ ★ ★ ★ ★ ★ ☆ ☆ ☆ |
| Adaptabilidade | ★ ★ ★ ★ ★ ★ ★ ☆ ☆ ☆ |
| Resiliência | ★ ★ ★ ★ ★ ★ ★ ☆ ☆ ☆ |

</details>



