# 💻 Laboratório 04 – Exercício 04

Este repositório contém os arquivos e configurações do exercício 01 do Laboratório 04 da Web Academy. O objetivo é aprender a configurar e utilizar **GitHub Actions** para automatizar tarefas em projetos de desenvolvimento.

## 📌 Objetivos do exercício

Consolidar o uso de pipelines através da configuração de pipelines que utilizam condicionais e deploy em infra-estrutura em nuvem!

## 🛠️ Estrutura do projeto
.github/ └── workflows/ └── wa-google-cloudrun-docker.yml

## Pré-Requisitos:
- Ter uma conta no GitHub
- Máquina com Linux / Windows instalado e Git já configurado com a conta do GitHub
- Ter uma conta no Docker Hub
- Arquivos disponíveis no Colabweb para o Laboratório (caso necessário)

## 🚀 Como funciona o workflow:

O arquivo `wa-google-cloudrun-docker.yml` define um fluxo de trabalho que é executado automaticamente quando há um `push` ou `pull request` no branch `main`. Ele pode incluir etapas como:

- Instalar dependências
- Rodar testes
- Gerar builds

## 📂 Como usar

1. Clone o repositório:
   ```bash
   git clone https://github.com/Danielevs/WACAD015-Fundamentos-de-Integra-o-Cont-nua-e-Deploy---Lab04

2. Faça alterações e envie para o GitHub

git add .

git commit -m "Atualiza workflow"

git push

