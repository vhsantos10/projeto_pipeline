# Projeto Jenkins Pipeline Simples

Este é um projeto simples para demonstrar a criação de um pipeline básico no Jenkins. O pipeline é configurado para realizar três etapas: Build, Test e Deploy.

## 📁 Estrutura do Projeto

projeto_pipeline/
├── index.html
└── Jenkinsfile
- **index.html**: A página HTML que será publicada no servidor durante a etapa de deploy.
- **Jenkinsfile**: Define o pipeline do Jenkins, com as etapas de Build, Test e Deploy.

## 🚀 Pipeline Jenkins

O `Jenkinsfile` contém três etapas principais:

1. **Build**: Simula o processo de build (atualmente apenas um `echo` indicando que o repositório será clonado).
2. **Teste**: Simula a execução de testes (também com um `echo` para indicar a ação).
3. **Deploy**: Simula o deploy do arquivo `index.html` para o servidor.

## ✅ Pré-requisitos

- Jenkins instalado
- Repositório Git configurado no Jenkins

## 📝 Como usar

1. Clone o repositório ou faça um fork.
2. Crie um job no Jenkins e aponte para o repositório.
3. Execute o pipeline para ver as mensagens de cada etapa.

## 🧪 O que o pipeline faz

### 1. **Build**

A etapa de build simula o processo de construção do seu projeto. Atualmente, esta etapa apenas exibe uma mensagem de `echo` informando que o repositório foi clonado.

### 2. **Teste**

A etapa de teste simula a execução de testes em seu código. Aqui, também, temos uma mensagem de `echo` indicando o processo de clonagem de repositório. No futuro, você pode adicionar comandos reais de execução de testes.

### 3. **Deploy**

Na etapa de **Deploy**, o pipeline simula a publicação do arquivo `index.html` no servidor. Em um pipeline real, esta etapa seria responsável por fazer o upload ou disponibilizar a aplicação em um servidor de produção.

Atualmente, o comando de deploy no seu pipeline é um simples `echo`:

