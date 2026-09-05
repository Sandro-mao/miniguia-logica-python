# 🐍 Miniguia de Estudos: Lógica de Programação com Python

> **Desafio de Projeto:** Formação DIO (Digital Innovation One)  
> **Ferramenta de IA Utilizada:** Google NotebookLM  
> **Tema:** Lógica de Programação Fundamental com Linguagem Python

---

## 🎯 1. Contexto e Objetivos

* **Tema Escolhido:** Lógica de Programação com Python.
* **Objetivo de Estudo:** Compreender e dominar a lógica de programação de forma universal (estruturas sequenciais, condicionais, repetições e funções), utilizando a linguagem Python como ferramenta prática para construir uma base sólida de raciocínio lógico aplicável no desenvolvimento de software.

---

## 📚 2. Curadoria de Fontes

Para alimentar o caderno temático no **NotebookLM**, utilizei fontes multimídia abertas de alta qualidade (vídeos e documento técnico):

### 🎥 Vídeos e Aulas (YouTube)
* [Vídeo 1 - Fundamentos e Algoritmos](https://www.youtube.com/watch?v=mstMhMT_UeA)
* [Vídeo 2 - Curso Prático de Python](https://www.youtube.com/watch?v=0aUscttQc-4)
* [Vídeo 3 - Imersão em Lógica de Programação](https://www.youtube.com/watch?v=epf-WQdVis0)

### 📄 Documentos e PDFs
* [PDF - Introdução à Programação (Banco Central do Brasil)](https://www.bcb.gov.br/content/estabilidadefinanceira/geotec-documentos/introducao-programacao-aula-01.pdf)

---

## 🧪 3. Engenharia de Prompts e "Cicatrizes" (Troubleshooting)

Nesta etapa, documentei as interações com o NotebookLM para extrair o melhor conhecimento dos materiais carregados:

### 🔹 Pergunta Estratégica: Os Maiores Desafios do Iniciante
* **Prompt Inicial (Tentativa 1):**  
  > *"Com base em todos os vídeos e PDFs que te enviei, qual é o principal desafio para quem tá começando a estudar lógica de programação com Python?"*
* **Ajuste de Prompt (Tentativa 2 - Refinada):**  
  > *"Com base nos materiais que enviei, liste os 3 maiores desafios de um iniciante em Lógica com Python (ex: indentação, transpor o raciocínio humano para código, entender estruturas de repetição) e apresente uma dica prática dos próprios materiais para superar cada um."*
* **Resposta Obtida da IA (Síntese Consolidada):**
  1. **O impulso de codar antes de planejar:** O erro de tentar digitar códigos imediatamente sem entender o problema. *Dica:* Aplicar o Método dos 5Qs e imaginar como resolver o problema manualmente passo a passo antes de abrir o editor.
  2. **Confundir palavras reservadas (Keywords) com variáveis:** Dificuldade em distinguir o que é sintaxe fixa do Python (ex: `for`, `in`, `print`) das escolhas livres do programador. *Dica:* Testar substituir mentalmente as variáveis por palavras aleatórias ou usar editores com realce de sintaxe (*syntax highlighting*).
  3. **Erros de Identação (`IndentationError`):** Confusão com espaços em branco e blocos de código. *Dica:* Configurar o editor para usar espaços de forma padronizada e usar comandos de debug para rastrear o fluxo.

---

## 📖 4. Miniguia de Estudo (Entrega Final)

### 📌 4.1. Resumo Estruturado do Assunto

* **Algoritmo e Planejamento:** Antes de escrever qualquer linha de código, o programador deve estruturar os passos lógicos (entradas, processamento e saídas). O código é apenas a tradução dessa lógica para uma linguagem que a máquina entende.
* **Variáveis e Tipos de Dados:** Espaços na memória para guardar informações. Em Python, lidamos com números inteiros (`int`), decimais (`float`), textos (`str`) e valores lógicos (`bool`).
* **Tomada de Decisão (Condicionais):** Estruturas como `if`, `elif` e `else` que permitem ao programa ramificar caminhos com base em condições verdadeiras ou falsas.
* **Laços de Repetição (`for` e `while`):** Mecanismos para automatizar tarefas repetitivas, seja por uma quantidade fixa de vezes ou enquanto uma condição específica for verdadeira.

---

### 🧠 4.2. Glossário de Conceitos Aprendidos

* **Algoritmo:** Sequência finita, lógica e ordenada de instruções para solucionar um problema.
* **Indentação:** Recuo no início da linha de código. No Python, ela é obrigatória e define quais instruções pertencem a um mesmo bloco (como dentro de um `if` ou `for`).
* **Palavra Reservada (Keyword):** Termos que possuem significado especial para a linguagem Python (ex: `def`, `return`, `if`) e não podem ser usados como nomes de variáveis.
* **Variável:** Um "rótulo" ou espaço de armazenamento na memória que guarda um valor mutável durante a execução do programa.

---

### 🛠️ 4.3. Prompts Reutilizáveis para Revisões Futuras

Conjunto de prompts que podem ser aplicados no NotebookLM em futuras sessões de revisão:

1. **Gerador de Exercícios Práticos:**
   > *"Com base nas fontes, crie 3 desafios práticos de lógica em Python focados em [INSERIR TÓPICO]. Dê apenas os enunciados e aguarde minha resposta para corrigir."*
2. **Explicador de Erros de Sintaxe:**
   > *"Analise o código abaixo, identifique onde está o erro conceitual ou de indentação e explique de forma simples como corrigir: [INSERIR CÓDIGO]"*
3. **Simulador de Quiz de Fixação:**
   > *"Elabore um quiz rápido com 4 perguntas de múltipla escolha sobre estruturas condicionais e de repetição em Python, com o gabarito explicado no final."*
