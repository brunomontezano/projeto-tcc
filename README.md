# Projeto do Trabalho de Conclusão de Psicologia - Bruno Montezano

![Screenshot2020-11-0311:24:36](https://user-images.githubusercontent.com/65104127/97996926-21575100-1dc7-11eb-929e-1dbb9b7f520b.png)

Esse repositório contém o código em LaTeX do Projeto do Trabaho de Conclusão em Psicologia do acadêmico Bruno Montezano, e ainda:

- O arquivo de bibliografia em extensão bib;
- A apresentação de slides do trabalho;
- As imagens e documentos utilizados no projeto/apresentação;
- Os arquivos de saída em pdf.

## Dúvidas

### Que "programa" você usa para escrever seu trabalho?

O que eu uso é uma linguagem de formatação/composição de documentos
chamada [LaTeX](https://www.latex-project.org) que permite a utilização
de uma sintaxe para escrever seu documento, possibilitando com que
você possa se focar mais no conteúdo do seu trabalho do que na
aparência ou formatação dele.

E para utilizar o LaTeX você pode escrever em praticamente qualquer
editor de texto. Existem alternativas online como Overleaf, etc.
Mas eu sou um amante das ferramentas offline, e acabo utilizando
o editor de texto [Vim](https://www.vim.org) para escrever meu código, e eu adoro ele!

### Mas eu consigo usar as regras da ABNT escrevendo em LaTeX?

Claro! Você pode utilizar um pacote chamado [abnTeX2](abntex.net.br)
que traz diversas facilidades para quem necessita escrever seu
trabalho acadêmico a partir de algumas das normas da ABNT.
Você pode modificar diversos dos parâmetros caso sua universidade
peça alguma norma atípica.

Mas de qualquer modo, recomendo fortemente este pacote para quem
precisa seguir as regrinhas!

### Como criar um arquivo .bib?

Você pode utilizar algum gerenciador de referências como [Zotero](https://www.zotero.org/)
(eu particularmente utilizo) ou Mendeley, e assim organizar e adicionar os
artigos e livros que você vai utilizar para sua bibliografia e então
exportar sua "biblioteca" para um arquivo BibTeX que você pode manusear
a partir da sintaxe do LaTeX posteriormente.

### Como criar as tabelas em LaTeX?

Eu gosto bastante de utilizar um site chamado Tables Generator
para gerar a base das minhas tabelas, e então ir otimizando e
modificando conforme minha necessidade a partir da sintaxe
dos pacotes utilizados.
Neste trabalho em específico, acabei utilizando longtable, tabu, etc.

Você pode acessar o site Tables Generator clicando
[aqui](https://www.tablesgenerator.com/).

Porém, conforme a prática for aumentando, menos dependente de ferramentas
que automatizam este processo serão necessárias, considerando que você vá
ganhando autonomia e melhor compreensão da sintaxe de tabelas em LaTeX.

## Ambiente de Desenvolvimento

- SO: [Arch Linux](https://www.archlinux.org/)
- Editor de texto: [Neovim](https://neovim.io/)
- Distribuição: [TeXLive](https://tug.org/texlive/)
- Script para compilação: [No meu repositório de configurações](https://github.com/brunomontezano/dotfiles/blob/master/.local/bin/compiler)

## Contato

Qualquer dúvida, entrar em contato pelo e-mail:

bruno.montezano@sou.ucpel.edu.br
