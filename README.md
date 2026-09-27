# Trabalho Final - Front-End I

Site pessoal em página única, desenvolvido como Trabalho Final da disciplina
de Front-End I. O projeto evoluiu a partir de uma atividade prática anterior
(HTML5 e CSS3 básicos) até uma estrutura completa, semântica e responsiva,
apresentando o autor, as tecnologias estudadas e a jornada de aprendizado
ao longo do curso.

## Tecnologias

- HTML5
- CSS3

Não são utilizados frameworks, bibliotecas ou JavaScript.

## Estrutura

```
trabalho-final-front-end-1/
├── index.html      # página principal (apresentação, sobre, habilidades, tabela, artigo e aside)
├── contato.html     # página de contato
├── style.css        # folha de estilos externa
└── imagens/
    ├── codigo-html-css.svg      # ilustração usada na seção "Sobre"
    └── jornada-aprendizado.svg  # ilustração usada no artigo
```

## Requisitos implementados

- HTML semântico: `header`, `nav`, `main`, quatro `section`, `article`, `aside` e `footer`.
- Título principal, subtítulos, parágrafos, texto em destaque e uso pontual de `<br>` em conteúdo de contato.
- Duas imagens locais (SVG) com `alt` descritivo, incluindo uma em `figure`/`figcaption`.
- Links externo (MDN, GitHub), interno (`contato.html`), âncoras (`#inicio`, `#sobre`, etc.) e menu de navegação.
- Lista não ordenada e lista ordenada com conteúdo relacionado ao tema.
- Tabela com `thead`/`tbody`, cabeçalho, 3+ colunas e 4 linhas de dados.
- CSS externo com seletor universal, de elemento, de classe, de ID e agrupado, além de `width`, `height`, `margin`, `padding`, `background-color`, `color` e alinhamento.
- Responsividade com media query para telas menores, imagens flexíveis e tabela com rolagem horizontal em telas pequenas.
- Boas práticas de acessibilidade: `lang="pt-BR"`, `alt` em imagens, hierarquia de headings e sem texto essencial embutido em imagem.

## Execução

Basta abrir o arquivo `index.html` diretamente em qualquer navegador
(não é necessário servidor ou instalação de dependências).
