# Relatório - Os Meus Livros

## 1. Objetivo

O objetivo deste exercício consistiu em desenvolver uma aplicação móvel com recurso à framework Ionic, subordinada ao tema **Os Meus Livros**. A app procura apresentar uma pequena biblioteca pessoal, com foco em livros marcantes, opiniões individuais, organização por categorias e acompanhamento do estado de leitura.

## 2. Descrição Sumária da App

A aplicação foi desenhada para contexto mobile e inclui:

- ecrã inicial com visão global da coleção;
- ecrã de apresentação do autor da app;
- ecrã de listagem de livros com pesquisa;
- ecrã de organização por categorias literárias;
- ecrã de progresso de leitura;
- ecrã de detalhe individual de cada livro.

## 3. Funcionalidades Implementadas

### Requisitos mínimos assegurados

- Protótipo funcional com navegação por `sidemenu`;
- Utilização de texto e imagem;
- Mais de 4 ecrãs distintos;
- Cor global personalizada (`biblioteca`);
- Estrutura modular por páginas;
- Apresentação visual cuidada e focada em usabilidade.

### Funcionalidades adicionais

- pesquisa por título, autor e género;
- agrupamento dos livros por categoria;
- detalhe individual por livro;
- indicação de livros lidos e por ler;
- avaliação pessoal e citação marcante em cada livro;
- indicadores rápidos no ecrã inicial.

## 4. Aspetos Relevantes da Implementação

Os dados dos livros foram centralizados num ficheiro próprio, permitindo separar conteúdo e interface. Esta abordagem facilita manutenção, reutilização e eventual expansão da coleção.

O sistema de navegação foi construído com `ion-menu` e rotas lazy-loaded, garantindo uma experiência simples e coerente entre páginas.

A identidade visual foi reforçada com uma cor principal própria, diferente das cores de origem do Ionic, e com capas em formato SVG para assegurar consistência visual e leveza no carregamento.

## 5. Aspetos a Melhorar

- permitir edição dinâmica do estado de leitura;
- guardar dados em armazenamento local;
- adicionar filtros avançados por classificação e género;
- substituir os dados de autor pelos dados pessoais definitivos;
- produzir os PBF finais para anexar ao relatório.

## 6. Observações Finais

A aplicação cumpre os requisitos mínimos do enunciado e acrescenta algumas funcionalidades de organização e exploração de conteúdo. O projeto foi pensado para ser simples de demonstrar, mas suficientemente completo para evidenciar competências de estruturação, navegação e design em Ionic.
