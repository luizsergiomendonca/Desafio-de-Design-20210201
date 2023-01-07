# Design Challenge 20210201

## Introduction

This is a challenge to test your knowledge of Design and Prototyping;

In this challenge, there are several ways to develop and obtain the proposed results. The objective is to evaluate its form of structuring and autonomy in decisions to build something scalable.

### First things first
 
- Prepare the project to be available on Github, copying the contents of this repository to yours (or use the project's fork and point to Github). Confirm that the project's visibility is public (don't forget to put the reference to this challenge in the readme);
- The project must use the specific Language in its Job Posting (if applying). For example: Python, R, Scala and others;
- Consider as deadline 5 days from the start of the challenge. If you have been invited to take the test and it is not possible to complete within this period, please notify the person who invited you to receive instructions on what to do.
- Document the entire research process for the development of the activity (README.md in your repository); the results of these tasks are just as important as your thought process and decisions as you complete them, so try to document and present your hypotheses and decisions as much as possible.

## Challenge / Case

The company Trevo Digital works with several customers globally in more than 15 countries, one of the main characteristics of the company is the strong positioning in the digital sector with a team focused on generating quality leads.
Therefore, all projects must be very well structured with SEO, fluidity and reuse in mind (components reused in several projects).
Its goal is to create a project that gives attention to the requirements mentioned above.

## Resources

1. Use some online collaboration design tool. Ex: Figma

## Step by step

In this challenge, we worked on the elaboration of an initial structure of the Design System and the development the mobile and web prototypes of the screens of the Dashboard project of a new Trevo Digital Client.

Before starting work, the requirements and analysis team developed the initial WireFrame for the desktop version of the project:

![Dashboard](/assets/Dashboard.png)

To work on the prototype, we must follow the color palette that the client sent:

![Colors](/assets/colors.png)

### Design System

The Design System for the project will be an initial draft with:

- Font Types
- Colors
- Components


### Desktop Version

To develop Desktop screens, we must review whether the UI and UX are appropriate/consistent/satisfying before working on the prototype. With your knowledge, review the proposal and apply the necessary corrections that you consider necessary to improve the usability of the project.

### Mobile Version

No Wireframe proposal was developed for the mobile version, so we should elaborate it following the structure of the desktop version, but applying the necessary adjustments for the new version.


### Extras

- **Differential 1** Create a tablet proposal
- **Differential 2** Use fluid components on Figma or Adobe XD
- **Differential 3** Prototyping a new screen that contains a table with users list and dynamic filters (Search, Order by, etc..) 


## Repository Readme

- Must contain the title of the project
- A description of a sentence
- General instructions and final project files
- Captures of the final result of the Project
- Link to access the project if an Online system has been used.
- Don't forget [.gitignore](https://www.toptal.com/developers/gitignore)

## Last Step

Warn about the finalization and send for correction at: [https://coodesh.com/review-challenge](https://coodesh.com/review-challenge)
After this stage, the presentation / correction of the project will be scheduled.

## Instructions for Presentation:

1. It will be necessary to share the screen during the video call;
2. Leave all solution projects previously open on your computer before starting the call;
3. Leave the environments configured and ready to run;
4. Prepare yourself because you will be asked about each step and decision of the Challenge;
5. Prepare a list of questions, doubts, suggestions for improvements and feedbacks (if you have one).

## Support
Use [our community](https://coodesh.com/developers#community) to ask questions about the process or send an email to contato@coodesh.com.

# Desenvolvimento da solução

## O processo 

1. Inventário
2. Descoberta
3. Handoff

![Processo](/assets/Processo.png)

## Inventário

Nessa etapa investigamos e analisamos todos os insumos fornecidos. Aqui é onde se realiza um benchmark interno para entender como tal componente se comporta, qual sua característica, para quais cenários é utilizado.

Em um artboard organizamos todas as informações recebidadas.

![Empresa](/assets/Informa%C3%A7%C3%B5es%20da%20empresa.png)

![Projeto](/assets/Informa%C3%A7%C3%B5es%20do%20projeto.png)

![Requisitos](/assets/Requisitos%20para%20o%20design%20system.png)

![Desktop](/assets/Vers%C3%A3o%20Desktop.png)

![Mobile](/assets/Vers%C3%A3o%20Mobile.png)

![Tablet](/assets/Vers%C3%A3o%20Tablet.png)


Após essa análise verificaremos os insumos recebidos.

### Análise do Wireframe

Aqui identificamos todos os componentes e verificamos se há consistência e equilíbrio na diagramação dos elementos dentro do template.

![Identificando](/assets/Identificando%20os%20componentes.png)


## Grid

Agora reorganizamos os elementos respeitando um grid de 12 colunas para desktop e 4 colunas para mobile. Foi utilizado o padrão bootstrap respeitando a proporção de 8px. 



### Grid para desktop

![Grid](/assets/grid.png)

### Grid para mobile

![WireframeMobile](/assets/mockup-mobile.png)


## Descoberta

Nesta fase e a investigação não é mais interna mas sim externa, analisamos os principais design systems do mercado (como Carbon, Material Design, Ant Design) para entender como o componente estudado é apresentado por cada um deles.

Após fazer todas essas comparações e análise, começamos a entender quais são as boas práticas oficiais recomendadas, os estados possíveis do componente e como responder aquelas perguntas que surgiram na etapa do inventário.


## Cores

Para a composição das cores foi levado em consideração as cores da identidade visual da empresa. Para a composição das telas será utilizado o padrão 60 / 30 / 10.

![Cores](/assets/Cor3.png)

## Tipografia

A família tipográfica que será utilizada neste design system será a Nunito Sans.

![Tipografia](/assets/Tipografia.png)


