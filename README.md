# Trabalho Prático — DS122 (2026/2)

Repositório-base do Sistema Web de Catálogo de Produtos, trabalho prático individual de Desenvolvimento de Aplicações Web 1 (DS122), 2026/2.

## Como usar este repositório

Faça o **fork** deste repositório para o seu grupo do GitLab e desenvolva nele as três entregas. É um único fork para o semestre inteiro: não crie um fork novo a cada entrega, o histórico de commits deste mesmo repositório é o que sustenta o diário de bordo.

O procedimento de fork e configuração do grupo é o mesmo usado nas tarefas da disciplina, descrito em [Instruções para submissão de tarefas](https://tads-ufpr-alexkutzke.github.io/ds122-alexkutzke/instrucoes_submissao_tarefas_e_trabalhos.html).

O enunciado completo — requisitos de cada entrega, prazos e critérios de avaliação — está na [Especificação do trabalho prático](https://tads-ufpr-alexkutzke.github.io/ds122-alexkutzke/especificacao_trabalho_02_26.html).

## Diário de bordo


- Repositório GitLab com ao menos 3 commits com mensagens descritivas.
- Registro no README.md do que foi feito em cada etapa e das dificuldades encontradas.

### Descrição do sistema

*(o que a aplicação faz e como está organizada em arquivos e pastas)*
A aplicação consiste em um site para um brechó. O site terá a área pública (acesso dos usuários) que são: Cátalogo, busca e contato, e a área administrativa (acesso dos donos do negócio).

### Entrega 1 — Front-end estático
1. Página Inicial
No cabeçalho utilizei <nav> e <ul> para os links. Na seção destaque, no html foi utilizado img e figure e Grid no css para os cards estáticos.
2. Catálogo
A maior dificuldade dessa seção foi fazer com que após 1050px ficassem apenas 4 colunas, por questões estéticas. Descobri que não poderia usar o mesmo CSS que utilizei no container de produtos da página inicial, que era a grade que se adaptava sem media query, então fiz por media query mesmo.
*(o que foi implementado, dificuldades encontradas e como foram resolvidas)*

### Entrega 2 — Interatividade com JavaScript

*(o que foi implementado, dificuldades encontradas e como foram resolvidas)*

### Entrega 3 — Back-end com PHP + MySQL

*(o que foi implementado, dificuldades encontradas e como foram resolvidas)*
