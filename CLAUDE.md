# CLAUDE.md — cato-demos

Repositório com as demos e modelos de site da Cato Mídias. A raiz `index.html` é a **página vitrine** que lista tudo.

## Regra principal: manter a vitrine atualizada

Toda vez que uma demo ou modelo for **criado, atualizado, renomeado ou removido** neste repositório, atualize o `index.html` da raiz **na mesma tarefa**, sem precisar pedir:

- Cada pasta `demo-*/` e `modelo-*/` que tenha `index.html` precisa ter um card na vitrine.
- O link do card aponta para a pasta com barra no final (ex.: `href="demo-oriri/"`).
- Use o padrão de card que já existe:
  ```html
  <li><a class="card" href="demo-nome/"><em>Demo</em><strong>Nome do Cliente</strong><small>O que faz · Cidade</small></a></li>
  ```
  - `<em>`: `Demo` para pastas `demo-*`, `Modelo` para pastas `modelo-*`.
  - `<strong>`: nome do negócio (tire do `<title>` da demo).
  - `<small>`: descrição curta do serviço + cidade.
- Ordem: demos primeiro (mais recentes no topo), depois os modelos.
- Se uma pasta for removida, remova o card. Antes de finalizar, confira que todo `href` da vitrine corresponde a uma pasta existente.

## Não mexer no conteúdo das demos sem pedido

Quando a tarefa for só atualizar a vitrine, não altere nada dentro das pastas `demo-*/` e `modelo-*/`.

## Identidade da vitrine

A vitrine é material da Cato: cores âmbar `#FCA001`, vermelho `#B70223`, preto e off-white; fontes Lot (títulos) e Montserrat (texto); tom próximo e direto ("a gente", "nós").
