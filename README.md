<div align="center">

# César Aaron Herrera

**Engenharia de Software @ FIAP** · **Infraestrutura de TI @ Grupo ALUN**

São Paulo, SP

[![Email](https://img.shields.io/badge/Email-1F2328?style=flat-square&logo=gmail&logoColor=white)](mailto:cesaraaronherrera66@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-1F2328?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/cesaraaronherrera/)

</div>

---

## Sobre

Construo backend em Java e ferramental em Python. Meu interesse tem se concentrado em **dados e
modelos preditivos** — como transformar texto e sinal bruto em algo que sustente uma decisão, e
como medir se a inferência realmente generaliza em vez de decorar o conjunto de treino.

Antes da graduação, concluí o Ensino Médio com curso Técnico em Administração na Etec de Arujá, o
que me deu uma base de negócios que uso para entender o problema antes de modelar a solução.

## Stack

![Java](https://img.shields.io/badge/Java-1F2328?style=flat-square&logo=openjdk&logoColor=white)
![Spring](https://img.shields.io/badge/Spring_Boot-1F2328?style=flat-square&logo=springboot&logoColor=white)
![Python](https://img.shields.io/badge/Python-1F2328?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-1F2328?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-1F2328?style=flat-square&logo=javascript&logoColor=white)
![C++](https://img.shields.io/badge/C++-1F2328?style=flat-square&logo=cplusplus&logoColor=white)

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-1F2328?style=flat-square&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-1F2328?style=flat-square&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-1F2328?style=flat-square&logo=linux&logoColor=white)
![Git](https://img.shields.io/badge/Git-1F2328?style=flat-square&logo=git&logoColor=white)
![React](https://img.shields.io/badge/React-1F2328?style=flat-square&logo=react&logoColor=white)

## Projetos

### Oryx · Challenge FIAP 2026 — TOTVS

Plataforma de inteligência conversacional para times comerciais. Recebe transcrições de reuniões de
vendas e identifica onde a conversa travou, por quê, e o quanto se pode confiar nessa leitura.

Aplicação Spring Boot (Java 21, JPA, PostgreSQL) com uma camada de domínio de detectores para cinco
tipos de fricção — preço, prazo, autoridade de decisão, confiança no produto e concorrência.

A parte que mais me ensinou foi a medição. Construí em Python um gerador de dataset sintético com
**split léxico**: as formulações de cada fricção são partidas em um inventário visível e um oculto,
e quem escreve o detector só pode ler o visível. O recall que conta é o calculado sobre o conjunto
oculto — é a diferença entre generalizar e decorar. O gerador ainda gradua intensidade e inclui
controles negativos e trechos ambíguos como ruído.

_Repositório privado._

### [Global Solution 2026](https://github.com/CodeAaron-Dev/global-solution-2026-fund-Dynamic-programming-)

Monitoramento de riscos ambientais em Python, aplicando grafos, árvores binárias de busca e a
comparação entre uma solução por força bruta e um algoritmo guloso.

### [IoT DevBalance](https://github.com/CodeAaron-Dev/IoT-DevBalance)

Dispositivo em ESP32 (C++) que acompanha ciclos de trabalho e descanso, exibe o estado em display
OLED e publica as métricas por MQTT para um dashboard.

### [FIAP Bank — Terminal ATM](https://github.com/CodeAaron-Dev/fiap-ddd-java-checkpoint2-atm)

Simulação de caixa eletrônico em Java modelada com Domain-Driven Design, separando domínio,
aplicação, infraestrutura e apresentação em camadas.
