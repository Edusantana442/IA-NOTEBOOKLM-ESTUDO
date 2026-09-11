# Caderno Tematico no NotebookLM: Clean Code (Codigo Limpo)

> **Desafio de Projeto DIO:** Aprendizagem Ativa com Inteligencia Artificial  
> **Repositorio:** `IA-NOTEBOOKLM-ESTUDO`  
> **Autor(a):** [Eduardo Santana Almeida]  
> **Link para o Caderno no NotebookLM:** [Acesse meu Caderno Tematico](https://notebook.google.com/notebook/85ff4f1b-e4a9-4528-959e-90f8b65848ab)

---

## Contexto e Objetivos

### Contexto
Escrever codigos que o computador compreenda é simples, mas o desafio da engenharia de software é digitar um codigo legivel e facil de ser gerido por diversas pessoas. Neste projeto, utilizei o **NotebookLM** para criar um miniguia pratico focado em **Clean Code**.

### Objetivos
1. **Repertório de Fontes:** Selecionar conteúdos essenciais sobre Clean code para ter um repertório confiável sobre o tema.
3. **Miniguia de Estudos:** Consolidar os conceitos aprendidos em uma documentacao reutilizavel para consultas diarias.

---

## Curadoria de Fontes

Para alimentar a base do NotebookLM, foram utilizadas as seguintes fontes:

1. **[Artigo/Guia sobre Clean Code e Principios de Software](https://www.alura.com.br › Artigos › Back-end)**
2. **[Guia de Estilos de Codigo e Boas Praticas](https://www.devmedia.com.br › Artigos › Java)**
3. **[Documentacao sobre Principios SOLID e Refatoracao](https://www.dio.me › articles › clean-code-a-filosofia-da-...)**
4. **submissao-597-arquivo-2581 (1).pdf**

---
## Engenharia de Prompts e "Cicatrizes"

1. Com base nas fontes fornecidas, quais são as regras fundamentais do clean code:
 De forma geral, um **código limpo** (Clean Code) é caracterizado como um código **legível, testável e fácil de ser mantido**[1][2]. Para atingir esse nível de qualidade, as fontes destacam um conjunto de regras e boas práticas fundamentais:

### 1\. Boas Práticas de Escrita e Formação de Código

* **Definição de nomes significativos:** Escolher nomes precisos, diretos e concisos para variáveis, funções, parâmetros, classes e métodos[3][4]. O nome deve representar claramente o significado e a real intenção sem conflitos de linguagem, não havendo necessidade de temer nomes grandes[3][4].
* **Funções simples e curtas:** Assim como os métodos, as funções devem ser curtas, simples e altamente objetivas[5][6]. Cada função deve cumprir um papel único, ou seja, **fazer apenas uma única coisa**[5][6].
* **Uso consciente de comentários:** Devem ser tratados como "um mal necessário" e evitados ao máximo[4]. Antes de escrever um comentário, o ideal é tentar melhorar o próprio código[4]. Opte por comentar apenas trechos realmente complexos que exijam explicações adicionais, pois comentários mal administrados poluem o visual e podem ficar desatualizados com o tempo[4][7]. Para está resposta ele usou as fontes da Alura e da dio.

2. cite as três principais:
De forma bem resumida, as **três características fundamentais** que definem um código limpo segundo as fontes são[1]:

1. **Legível**: O código deve ser fácil de entender e apresentar um fluxo de leitura contínuo[2][3]. Como os desenvolvedores passam muito mais tempo lendo código do que escrevendo, uma boa legibilidade reduz drasticamente o esforço e o cansaço mental[2][4].
2. **Testável**: O código precisa ser estruturado de modo que permita a execução de testes automatizados[4][5]. Ter uma boa cobertura de testes traz segurança para realizar alterações e garante que os cenários previstos continuem funcionando como o esperado[4][6].
3. **Fácil de ser mantido (Manutenível)**: O sistema deve permitir modificações e evoluções de forma simples e segura, seja para adicionar novas funcionalidades ou para refatorar a estrutura sem quebrar outras partes do software[4][7]. Para está resposta ele utilizou a fonte da Alura.

3. monte um curto planejamento por ordem de prioridade para eu deixar um codigo em clean code de no maxico 5 linhas:
* **Garantir testes automatizados:** Crie testes de unidade para alterar a estrutura com segurança sem quebrar o sistema[1].
* **Definir nomes significativos:** Ajuste variáveis, funções e classes com nomes precisos e diretos que revelem sua intenção[4][5].
* **Eliminar duplicações e simplificar:** Extraia métodos e classes para dividir funções extensas e remover código repetido[6].
* **Ajustar formatação e remover poluição:** Organize a indentação visual e elimine comentários desnecessários ou desatualizados[5].
* **Refatorar e aplicar a Regra do Escoteiro:** Melhore a estrutura continuamente, deixando o código sempre mais limpo a cada alteração[10][11]. Pra está resposta ele utilizou a fonte da Dio e o pdf.

Fiz as perguntas e percebi que elas estavam ficando grandes demais, então na última pergunta limitei a resposta para 5 linhas, o bot entendeu erroneamente que eram em 5 tópicos que mesmo com o erro de inter pretação da parte dele encurtou bastante a resposta que foi gratificante.

---

## Miniguia de Estudo (Entrega Final)

### 1. Resumos Estruturados

Em resumo o Clean Code é uma filosofia de desenvolvimento focada em criar softwares legíveis, testáveis e de fácil manutenção, reduzindo custos e tempo de desenvolvimento. Sua escrita baseia-se na escolha de nomes significativos e precisos, na criação de funções curtas com papel único e na eliminação de duplicações. Essa prática adota a Regra do Escoteiro para manter a limpeza contínua e a refatoração constante sem alterar o comportamento externo observável do sistema. A confiabilidade do código é garantida por meio de testes automatizados e metodologias como o TDD, tornando o software seguro contra falhas. Por fim, sua arquitetura apoia-se nos princípios SOLID para evitar a rigidez e a fragilidade, mantendo o sistema coeso, flexível e desacoplado.
---

### 2. Glossario de Conceitos

* **Clean Code:** Técnica de desenvolvimento focada em tornar a escrita e a leitura intuitivas, garantindo um código fácil de manter e reduzindo custos com erros.
* **Nomes Significativos:** Escolha de nomes concisos, precisos e diretos para variáveis, funções e classes que revelem sua real intenção sem ambiguidades.
* **Funções Simples:** Métodos curtos, objetivos e focados, projetados para ter um papel único e realizar apenas uma coisa no sistema.
* **Regra do Escoteiro:** Princípio que orienta o desenvolvedor a deixar o código mais limpo do que estava antes de realizar qualquer alteração].
* **Refatoração:** Alteração na estrutura interna do código para torná-lo mais simples e legível sem modificar seu comportamento externo observável.
* **TDD:** Desenvolvimento guiado por testes estruturado no ciclo contínuo *Red* (criar teste que falha), *Green* (código mínimo) e *Refactor* (limpeza).
* **SOLID:** Conjunto de cinco princípios da Programação Orientada a Objetos que mantêm a arquitetura do software desacoplada, coesa e flexível.
* **SRP (Responsabilidade Única):** Princípio do SOLID que exige que uma classe possua apenas uma função ou conceito a gerenciar no sistema.
* **Extrair Método (** **Extract Method** **):** Técnica de refatoração para eliminar duplicações, unificando blocos repetidos em métodos com nomes explicativos.
* **Extrair Classe (** **Extract Class** **):** Divisão de classes sobrecarregadas com múltiplas responsabilidades em novas classes organizadas e coesas.

---

### 3. Prompts Reutilizaveis

Use estes comandos no NotebookLM para revisoes futuras:
1. quero que vc faça um resumo estruturado do que é clean code em 5linhas e sem ter topicos
2. Com base nas fontes fornecidas, quais são as regras fundamentais do clean code
3. O que são Code Smells segundo as fontes? Liste 3 exemplos práticos e suas soluções.
