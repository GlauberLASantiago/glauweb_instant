# GlauWeb Instant

Ferramenta web simples para transformar rapidamente código HTML em um arquivo `.html` pronto para download. Basta colar o código gerado por uma IA ou outro sistema e salvar automaticamente o arquivo no computador.

## Visão geral

O **GlauWeb Instant** foi criado para facilitar o fluxo de trabalho de quem gera páginas HTML rapidamente (especialmente com IA). Em vez de criar arquivos manualmente, o usuário apenas cola o código HTML na interface e o sistema gera automaticamente um arquivo `.html` para download.

A aplicação funciona totalmente no navegador, sem necessidade de servidor ou instalação.

## Funcionalidades

- Interface simples e minimalista
- Campo para colar código HTML
- Contador automático de caracteres
- Geração automática de arquivo `.html`
- Download direto no navegador
- Nome do arquivo gerado automaticamente a partir de:
  - `<title>` da página
  - ou `<h1>` caso não exista título
- Sanitização automática do nome do arquivo
- Totalmente executado no **lado do cliente (client-side)**

## Tecnologias utilizadas

- HTML5
- CSS3
- JavaScript puro (Vanilla JS)

## Como funciona

1. O usuário cola o código HTML no campo de texto.
2. O sistema verifica se existe conteúdo.
3. O script tenta extrair um nome de arquivo a partir de:
   - `<title>` da página
   - ou `<h1>`
4. O conteúdo é convertido em um **Blob HTML**.
5. Um link de download é gerado automaticamente.
6. O arquivo é baixado como `.html`.

Todo o processo ocorre **localmente no navegador**, sem enviar dados para servidores.

## Estrutura do projeto

O projeto é composto por um único arquivo:

- `index.html` — contém interface, estilos e lógica JavaScript

## Como usar

1. Baixe ou clone o repositório:

```
git clone <URL_DO_REPOSITORIO>
```

2. Abra o arquivo `index.html` no navegador.

3. Cole o código HTML no campo de texto.

4. Clique em **SALVAR COMO .HTML**.

5. O arquivo será gerado automaticamente e baixado.

## Casos de uso

Esta ferramenta pode ser útil para:

- gerar rapidamente páginas HTML criadas por IA
- converter snippets em arquivos HTML
- salvar páginas protótipo
- testes rápidos de interfaces
- ensino de HTML em ambientes educacionais

## Possíveis melhorias

- pré-visualização da página antes de baixar
- modo escuro
- arrastar e soltar código
- compactação automática do HTML
- exportação para `.zip`
- suporte a múltiplos arquivos

## Público-alvo

- professores
- estudantes
- desenvolvedores iniciantes
- usuários de ferramentas de IA que geram HTML

## Créditos

Desenvolvido por **Prof. Glauber Santiago — UFSCar**.

## Licença

Este projeto pode ser distribuído sob a licença de sua escolha (por exemplo, MIT).
