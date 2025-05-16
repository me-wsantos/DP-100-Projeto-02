## Microsoft Certification Challenge #3 DP-100
### Projeto 2: Criando um Chatbot em Conteúdo de PDFs
<br>
<hr>

# Sistema de Busca Inteligente para Revisão de Artigos Científicos

Imagine que você é um estudante de Engenharia de Software, prestes a escrever seu Trabalho de Conclusão de Curso (TCC). Para isso, você precisa revisar e correlacionar diversos artigos científicos. Entretanto, à medida que acumula mais documentos, torna-se cada vez mais difícil extrair informações relevantes e conectar ideias entre diferentes textos.

Diante desse desafio, este projeto utiliza inteligência artificial para facilitar o processo, criando um sistema de busca inteligente capaz de interpretar os PDFs, organizar informações e gerar respostas relevantes com base no conteúdo carregado.

## Objetivo

O objetivo deste projeto é permitir que você:

✅ Carregue arquivos PDF contendo informações relevantes para seu estudo ou projeto.  
✅ Implemente um sistema de busca vetorial para indexar e recuperar informações dos PDFs.  
✅ Utilize inteligência artificial para gerar respostas baseadas no conteúdo dos documentos carregados.  
✅ Desenvolva um chat interativo onde seja possível realizar perguntas e obter respostas contextuais fundamentadas nos arquivos.  

---

## Etapas do Projeto

### 1. Criação do Projeto no Azue AI Hub

A primeira etapa envolve a criação de um ambiente centralizado para o projeto. Este ambiente, muitas vezes chamado de "Workspace", serve como um hub para todos os artefatos e recursos de machine learning. Ele organiza datasets, experimentos, modelos treinados, pipelines de computação e endpoints de implantação, facilitando a colaboração e o gerenciamento do ciclo de vida do ML.

![project](https://github.com/me-wsantos/DP-100-Projeto-02/blob/main/prints/01_criar_ai_hub.png?raw=true)

---

### 2. Criação do do projeto no Azure AI Foundry

O "Foundry" é o ambiente onde os dados e os modelos serão integrados e gerenciados. Nesta etapa, você configura o espaço para armazenar os arquivos PDF e prepara o sistema para processar e indexar as informações. O Foundry também permite o rastreamento e versionamento dos dados.

![foundry](https://github.com/me-wsantos/DP-100-Projeto-02/blob/main/prints/02_criar_projeto_ai_foundry.png?raw=true)

---

### 3. Seleção de Modelos (LLM)

Nesta etapa, você seleciona um modelo de linguagem (Large Language Model - LLM) adequado para interpretar os textos dos PDFs e gerar respostas contextuais. Modelos como o GPT-4 ou similares podem ser utilizados para essa tarefa. A escolha do modelo deve considerar o desempenho e a capacidade de lidar com grandes volumes de texto.

![models](https://github.com/me-wsantos/DP-100-Projeto-02/blob/main/prints/03_select_model.png?raw=true)

---

### 4. Adicionando Arquivos

Os arquivos PDF contendo os artigos científicos são carregados no sistema. Durante o upload, os documentos são processados, e suas informações são extraídas e indexadas em um sistema de busca vetorial. Isso permite consultas rápidas e precisas.

![upload](https://github.com/me-wsantos/DP-100-Projeto-02/blob/main/prints/04_add_file.png?raw=true)

---

### 5. Consulta Chat

Por fim, o sistema oferece um chat interativo onde você pode realizar perguntas baseadas no conteúdo dos PDFs carregados. O sistema utiliza inteligência artificial para interpretar as perguntas e gerar respostas fundamentadas, facilitando a revisão e correlação de informações entre diferentes textos.

![chat](https://github.com/me-wsantos/DP-100-Projeto-02/blob/main/prints/05_consulta_playground.png?raw=true)

---

## Benefícios do Sistema

* **Produtividade Aprimorada**:  
    * Permite uma revisão mais eficiente de artigos científicos, otimizando o tempo de estudo.  
    * Facilita a conexão de ideias entre diferentes textos, ajudando na construção de argumentos sólidos para o TCC.  

* **Organização e Acessibilidade**:  
    * Centraliza os documentos em um único ambiente, com acesso rápido e organizado.  
    * Reduz a necessidade de buscas manuais demoradas, permitindo foco em atividades mais estratégicas.  

* **Respostas Contextuais**:  
    * Gera respostas relevantes e fundamentadas, auxiliando na compreensão e análise dos textos.

### :technologist: Autor
  <a href="https://github.com/me-wsantos">
   <img style="border-radius: 50%;" src="https://avatars.githubusercontent.com/u/179779189?v=4" width="100px;" alt=""/>
   <br />
   <p><b>Wellington Santos</b></sub></a> <a href="https://github.com/me-wsantos" title="GitHub"></a></p>
  
  [![Linkedin Badge](https://img.shields.io/badge/-Wellington--Santos-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/wellington-lima-dos-santos-13343143/)](https://www.linkedin.com/in/-wellington-santos/)
  [![Email Badge](https://img.shields.io/badge/-me@wellington--santos.com-c14438?style=flat-square&logo=Gmail&color=11ab3a&logoColor=white&link=mailto:me@wellington-santos.com)](mailto:me@wellington-santos.com)