# Trabalho Prático — DS122 (2026/2)

Repositório-base do Sistema Web de Catálogo de Produtos, trabalho prático individual de Desenvolvimento de Aplicações Web 1 (DS122), 2026/2.

## Resumo
As entregas desse trabalho são feitas no GitLab e serão atualizadas conforme o andamento da disciplina.

## Diário de bordo

### Descrição do sistema

*(o que a aplicação faz e como está organizada em arquivos e pastas)*
<br>
A aplicação consiste em um site para um brechó. O site terá a área pública (acesso dos usuários) que são: Cátalogo, busca e contato, e a área administrativa (acesso dos donos do negócio).
<br> 
As páginas (catalogo, contato, index e sobre) estão na pasta pages, a folha de estilos está na pasta css e as imagens utilizadas estão na pasta public.

### Entrega 1 — Front-end estático
1. Página Inicial
No cabeçalho utilizei nav e ul para os links. Na seção destaque, no html foi utilizado img e figure e no css Grid para os cards estáticos.
2. Catálogo
A maior dificuldade dessa seção foi fazer com que após 1050px ficassem apenas 4 colunas, por questões estéticas. Descobri que não poderia usar o mesmo CSS que utilizei no container de produtos da página inicial, que era a grade que se adaptava sem media query, então fiz por media query mesmo.

### Entrega 2 — Interatividade com JavaScript

*(o que foi implementado, dificuldades encontradas e como foram resolvidas)*

### Entrega 3 — Back-end com PHP + MySQL

*(o que foi implementado, dificuldades encontradas e como foram resolvidas)*
