# Caderno Tematico no NotebookLM: Clean Code (Codigo Limpo)

> **Desafio de Projeto DIO:** Aprendizagem Ativa com Inteligencia Artificial  
> **Repositorio:** `IA-NOTEBOOKLM-ESTUDO`  
> **Autor(a):** [Eduardo Santana Almeida]  
> **Link para o Caderno no NotebookLM:** [Acesse meu Caderno Tematico](https://notebook.google.com/notebook/85ff4f1b-e4a9-4528-959e-90f8b65848ab)

---

## Contexto e Objetivos

### Contexto
Escrever codigo que o computador entenda e simples; o verdadeiro desafio da engenharia de software e escrever codigo legivel e facil de manter por pessoas. Neste projeto, utilizei a plataforma **NotebookLM** para aplicar grounding (ancoragem de respostas em fontes confiaveis) e criar um miniguia pratico focado nas boas praticas de **Clean Code**.

### Objetivos
1. **Curadoria de Fontes:** Selecionar materiais essenciais sobre legibilidade, refatoracao e padroes de projeto.
2. **Engenharia de Prompt:** Testar e refinar comandos na IA para extrair explicacoes, tabelas e exemplos praticos sem alucinacoes.
3. **Miniguia de Estudos:** Consolidar os conceitos aprendidos em uma documentacao reutilizavel para consultas diarias.

---

## Curadoria de Fontes

Para alimentar a base do NotebookLM, foram utilizadas as seguintes fontes:

1. **Artigo/Guia sobre Clean Code e Principios de Software**
2. **Guia de Estilos de Codigo e Boas Praticas**
3. **Documentacao sobre Principios SOLID e Refatoracao**

---

## Engenharia de Prompts e Troubleshooting

Abaixo estao os testes de prompts realizados no NotebookLM para extrair as melhores respostas:

| Intencao | Prompt Inicial | Resultado / Dificuldade | Prompt Refinado (Solucao) |
| :--- | :--- | :--- | :--- |
| **Boas Praticas de Funcoes** | "Como criar funcoes limpas?" | Trouxe respostas genericas sobre programacao. | "Com base nas fontes fornecidas, quais sao os 3 criterios principais para criar funcoes limpas (ex: tamanho, responsabilidade unica, argumentos)?" |
| **Exemplos Praticos** | "O que e um code smell?" | Explicacao teorica sem aplicacao tecnica. | "Liste 3 exemplos praticos de Code Smells presentes no texto e mostre a solucao recomendada para cada um." |
| **Simulado de Estudo** | "Me faca perguntas sobre o tema" | Perguntou coisas muito fora do escopo. | "Com base exclusivamente no material fornecido, crie um quiz de 3 perguntas sobre nomes significativos com gabarito ao final." |

---

## Miniguia de Estudo (Entrega Final)

### 1. Resumos Estruturados

#### Nomes Significativos
* **Revelem a intencao:** Variaveis e funcoes devem dizer claramente por que existem e o que fazem (ex: use `diasDesdeAUltimaModificacao` ao inves de `d`).
* **Evite desinformacao:** Nao use siglas obscuras ou nomes parecidos para coisas totalmente diferentes.

#### Funcoes Limpas
* **Facam apenas uma coisa:** Uma funcao deve ter apenas uma responsabilidade (Single Responsibility Principle).
* **Poucos argumentos:** O ideal e que uma funcao receba 0 ou no maximo 2 argumentos. Mais do que isso dificulta o teste e a leitura.

---

### 2. Glossario de Conceitos

* **Code Smell (Cheiro de Codigo):** Qualquer sintoma no codigo que indica um problema estrutural ou de legibilidade mais profundo.
* **Refatoracao:** O processo de reestruturar o codigo existente para melhorar sua clareza sem alterar o comportamento externo da aplicacao.
* **Boy Scout Rule (Regra do Escoteiro):** "Deixe o codigo mais limpo do que quando voce o encontrou."

---

### 3. Prompts Reutilizaveis

Use estes comandos no NotebookLM para revisoes futuras:
1. *"Analise este trecho de codigo sob as regras de Clean Code e sugira melhorias: [cole o codigo]"*
2. *"Explique o conceito de DRY (Don't Repeat Yourself) com um exemplo pratico em linguagem simples."*

---

## Como Visualizar este Projeto

Voce pode acessar o repositorio diretamente aqui pelo GitHub ou interagir com o caderno atraves do link do [NotebookLM](https://notebook.google.com/notebook/85ff4f1b-e4a9-4528-959e-90f8b65848ab).
