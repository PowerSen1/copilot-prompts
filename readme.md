<!--START_SECTION:header-->
<div align="center">
  <p align="center">
    <img 
      alt="DIO Education" 
      src="https://raw.githubusercontent.com/digitalinnovationone/template-github-trilha/main/.github/assets/logo.webp" 
      width="100px" 
    />
    <h1>Projeto de Desafio - DIO Bootcamp: CAIXA - Inteligência Artificial na Prática</h1>
  </p>
</div>
<!--END_SECTION:header-->

<p align="center">
  <img src="https://img.shields.io/static/v1?label=DIO&message=Education&color=E94D5F&labelColor=202024" alt="DIO Project" />
  <a href="NIVEL"><img  src="https://img.shields.io/static/v1?label=Nivel&message=Basico&color=E94D5F&labelColor=202024" alt="Nivel"></a>

</p>
<!--  -->

Este repositório apresenta dois projetos desenvolvidos como parte do desafio do **Bootcamp DIO - CAIXA: Inteligência Artificial na Prática**.  
O objetivo é aplicar conceitos de **agentes inteligentes** e **IA aplicada** para orientação de carreira em tecnologia.

## 🔹 Projeto 1: Entrevistador de Carreira em Tecnologia

### Objetivo
Simular um **agente conversacional especializado** em conduzir entrevistas estruturadas para identificar o perfil profissional de pessoas interessadas em tecnologia.

### Escopo
- Condução de **7 perguntas sequenciais** para coleta de dados sobre interesses, experiência, disponibilidade e objetivos.  
- Aplicação de uma **matriz de decisão interna** para ranquear carreiras potenciais.  
- Apresentação das **3 melhores opções de carreira** com justificativas, vantagens, desafios e contexto de mercado.  
- Transferência das informações para o **Agent 2** (planejador de roadmap).

### Regras Críticas
- Perguntas feitas **uma por vez**.  
- Encerramento após 7 respostas.  
- Não gerar plano de estudos (responsabilidade do Agent 2).  
- Não citar salários.  

---

## 🔹 Projeto 2: Planejador de Roadmap de Carreira

### Objetivo
Simular um **agente planejador especializado** em criar roadmaps personalizados de carreira em tecnologia, com base nos dados fornecidos pelo Agent 1.

### Escopo
- Geração de um **plano completo de estudos** contendo:  
  - Visão do dia a dia da carreira  
  - Mapa de skills essenciais e complementares  
  - Roadmap de 90 dias adaptado à disponibilidade semanal  
  - Projeto de portfólio com entregáveis e critérios de aceitação  
  - Roteiro de entrevistas com exemplos de respostas estruturadas  
  - Trilha DIO recomendada  

### Regras de Personalização
- **Horas semanais**: ajuste do roadmap conforme disponibilidade.  
- **Experiência prévia**: adaptação do nível de profundidade (fundamentos, prática ou portfólio).  
- **Objetivo profissional**: foco em primeiro emprego, transição ou crescimento.  

---

## 🔹 Projeto 3: Entrevistador Técnico de Vagas em Tecnologia

### Objetivo
Simular um **agente entrevistador técnico especializado** em vagas de tecnologia, conduzindo entrevistas estruturadas para detalhar requisitos de uma posição.

### Escopo
- Condução de **4 perguntas sequenciais** sobre:  
  - **Título da vaga e propósito principal**  
  - **Senioridade esperada e justificativa**  
  - **Stack de tecnologias, frameworks e práticas essenciais**  
  - **Soft skills valorizadas**  
- Geração de um **resumo analítico** somente após confirmação explícita do usuário.  
- Flexibilidade para o usuário **alterar a vaga** ou **ajustar a quantidade de temas** conforme necessidade. 

### Regras Críticas
- Perguntas feitas **uma por vez**, sem exceções.  
- O resumo só é gerado após o usuário confirmar que todas as respostas foram dadas.  
- Início sempre com a mensagem:  
  *"Olá! Vou fazer perguntas sobre a vaga que você está estruturando. Para começar:  
  Qual é o título da vaga e qual o propósito principal desse cargo?"*  

---

## 🔹 Conexão com Inteligência Artificial

Estes projetos simulam a lógica de sistemas inteligentes aplicados em orientação de carreira:  
- **Agent 1 (Entrevistador):** utiliza princípios de **NLP (Processamento de Linguagem Natural)** e **sistemas especialistas** para conduzir entrevistas e recomendar carreiras.  
- **Agent 2 (Planejador):** aplica conceitos de **personalização baseada em regras e dados** para estruturar roadmaps adaptados ao perfil do usuário.  
- **Agent 3 (Entrevistador Técnico):** conduz entrevistas técnicas sobre vagas específicas, estruturando requisitos e gerando análises detalhadas.  

---

## 🔹 Exemplo Prático de Execução

### 🧑‍💻 Simulação com Agent 1 (Entrevistador)

**Pergunta 1:** O que mais te atrai em tecnologia - resolver problemas, criar produtos ou entender sistemas?  
**Resposta:** Resolver problemas.  

**Pergunta 2:** Você já tem experiência na área de tecnologia ou está começando do zero?  
**Resposta:** Estou começando do zero.  

**Pergunta 3:** Quantas horas por semana você consegue dedicar aos estudos?  
**Resposta:** 8 horas por semana.  

**Pergunta 4:** No seu dia a dia, você prefere lidar mais com pessoas, dados ou código?  
**Resposta:** Dados.  

**Pergunta 5:** Qual é seu objetivo principal: conseguir o primeiro emprego, fazer transição de carreira ou crescer na função atual?  
**Resposta:** Conseguir o primeiro emprego.  

**Pergunta 6:** Quais assuntos ou tecnologias mais despertam seu interesse?  
**Resposta:** Inteligência Artificial e Ciência de Dados.  

**Pergunta 7:** Você tem alguma experiência prévia (mesmo que não seja em tech) que gostaria de aproveitar nessa nova jornada?  
**Resposta:** Sim, experiência em estatística aplicada.  

---

### 📊 Análise do Agent 1

🥇 **1º Lugar: Cientista de Dados - 18/20**  
💡 Afinidade com dados e interesse em IA.  
⚖️ Vantagens: alta demanda, aplicação prática de estatística.  
⚖️ Desafios: curva de aprendizado em programação e machine learning.  
📈 Mercado: em crescimento, variando por região e experiência.  

🥈 **2º Lugar: Analista de Dados - 16/20**  
💡 Boa porta de entrada para iniciantes.  
⚖️ Vantagens: menor curva de aprendizado, foco em ferramentas de análise.  
⚖️ Desafios: transição futura para papéis mais técnicos.  
📈 Mercado: consolidado em diversos setores.  

🥉 **3º Lugar: Engenheiro de Machine Learning - 14/20**  
💡 Alinhado ao interesse em IA, mas exige maior maturidade técnica.  
⚖️ Vantagens: inovação e projetos avançados.  
⚖️ Desafios: necessidade de experiência sólida em programação.  
📈 Mercado: competitivo e em expansão.  

---

### 📥 Transferência para Agent 2

Informações enviadas:  
- Carreira escolhida: Cientista de Dados  
- Horas semanais: 8h  
- Experiência: zero  
- Objetivo: primeiro emprego  
- Preferência: dados  
- Interesses: IA, Ciência de Dados, estatística aplicada  

---

### 📦 Plano Gerado pelo Agent 2

🧩 **Visão do Dia a Dia**  
- Coleta e limpeza de dados  
- Construção de modelos estatísticos  
- Aplicação de algoritmos de machine learning  
- Comunicação de insights para áreas de negócio  
- Documentação e versionamento de projetos  

🧠 **Mapa de Skills**  
- Core: Python, Estatística, SQL  
- Nice-to-have: Power BI, Tableau  
- Tecnologias: Pandas, Scikit-learn, TensorFlow  

📅 **Roadmap de 90 dias (8h/semana)**  
- Mês 1: Fundamentos de Python e Estatística  
- Mês 2: Prática com análise de dados e machine learning básico  
- Mês 3: Projeto de portfólio e preparação para entrevistas  

🚀 **Projeto de Portfólio**  
- Projeto: Predição de churn de clientes  
- Entregáveis: dataset tratado, modelo treinado, relatório de insights  
- Critérios: acurácia mínima, documentação clara, apresentação visual  

💬 **Roteiro de Entrevistas**  
- Pergunta: "Explique um projeto de dados que você realizou."  
- Resposta: Estruturar explicação em problema, solução, resultado e impacto.  

🎓 **Trilha DIO Recomendada**  
- Trilha: *Formação Cientista de Dados*  
- Conexão: cobre fundamentos, prática e projetos aplicados.  

---

## 🔹 Conclusão

O repositório demonstra a aplicação prática de **Inteligência Artificial em agentes conversacionais e sistemas de recomendação**, integrando entrevistas estruturadas e planos de estudo personalizados.  
Essa abordagem reforça
