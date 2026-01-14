# DATASET – SHORTCODES JANNAH (TIELABS)
EXPANSÃO DETALHADA – QUANDO E COMO UTILIZAR

Fonte oficial:
https://jannah.helpscoutdocs.com/article/128-shortcodes
tielabs-shortcodes
---

## 1. BOXES (`tie_box`)

### Quando utilizar (detalhado)

Utilize **Boxes** sempre que houver necessidade de **interromper o fluxo normal de leitura** para chamar a atenção do leitor para uma informação específica. Esse shortcode é indicado quando o conteúdo:

- Possui **importância contextual maior** do que o parágrafo comum
- Representa uma **nota editorial**, observação do autor ou aviso técnico
- Precisa ser interpretado como **alerta**, **erro**, **aviso**, **dica**, **download** ou **informação auxiliar**
- Deve ser visualmente separado para **reduzir risco de interpretação incorreta**
- Atua como **ancoragem cognitiva** em textos longos ou técnicos

Cenários típicos:
- Artigos técnicos com exceções, limitações ou avisos
- Reviews com ressalvas importantes
- Tutoriais com pré-requisitos ou riscos
- Conteúdo educacional que diferencia teoria de observação prática

Evite usar Boxes:
- Para conteúdo comum
- Em excesso (poluição visual)
- Para substituir headings estruturais

---

### Como utilizar (detalhado)

O shortcode deve **envolver apenas o conteúdo que realmente precisa de destaque**, mantendo o texto interno conciso e objetivo.

Boas práticas:
- Escolher o `type` coerente com a intenção semântica (warning ≠ info)
- Usar `title` apenas quando o rótulo ajuda na compreensão
- Evitar múltiplos boxes consecutivos sem texto intermediário
- Não inserir headings (`<h2>`, `<h3>`) dentro do box

O Box deve **complementar o texto**, nunca substituir a explicação principal.

---

## 2. BUTTONS (`tie_button`)

### Quando utilizar (detalhado)

Utilize **Buttons** sempre que desejar **direcionar explicitamente o usuário para uma ação**. Diferente de links comuns, o botão comunica intenção clara e prioridade.

Use Buttons quando:
- Existe uma **ação principal** no contexto do artigo
- O link representa **conversão**, **continuidade** ou **desdobramento**
- O leitor já recebeu informação suficiente para agir
- Você deseja reduzir ambiguidade sobre “o que fazer agora”

Cenários típicos:
- Download de materiais
- Acesso a páginas relacionadas
- Chamadas para cadastro, compra ou leitura complementar
- Continuação de série de artigos

Evite usar Buttons:
- Dentro de parágrafos corridos
- Para links de baixa relevância
- Em excesso na mesma página

---

### Como utilizar (detalhado)

O botão deve ser inserido **fora do parágrafo**, preferencialmente após uma conclusão parcial ou total.

Boas práticas:
- Texto do botão deve ser **verbo + ação clara**
- O destino (`url`) deve ser previsível para o usuário
- Usar `_blank` apenas quando sair do domínio faz sentido
- Ícones devem reforçar o significado, não decorar

O botão **encerra um raciocínio** e **inicia uma ação**.

---

## 3. TOOLTIP (`tie_tooltip`)

### Quando utilizar (detalhado)

Utilize **Tooltip** quando houver necessidade de **explicar um termo, sigla ou conceito** sem interromper o fluxo de leitura.

Indicado quando:
- O público pode ter **níveis variados de conhecimento**
- O conceito é importante, mas não central
- A explicação completa quebraria a fluidez do texto
- O termo é técnico, contextual ou ambíguo

Cenários típicos:
- Artigos técnicos
- Glossários inline
- Conceitos específicos de domínio
- Siglas ou jargões

Evite Tooltip:
- Em dispositivos onde hover não é essencial (conteúdo crítico)
- Para textos longos
- Para informações obrigatórias

---

### Como utilizar (detalhado)

O tooltip deve envolver **apenas a palavra ou pequena frase** que necessita explicação.

Boas práticas:
- Conteúdo do tooltip deve ser curto e direto
- Não repetir exatamente o texto visível
- Evitar tooltips encadeados
- Usar apenas quando realmente necessário

Tooltip **amplia compreensão**, não substitui explicação principal.

---

## 4. TAGS CLOUD (`tie_tags`)

### Quando utilizar (detalhado)

Use **Tags Cloud** quando o objetivo for **exploração semântica e navegação não linear**.

Indicado quando:
- O site possui volume consistente de conteúdo
- As tags são bem mantidas e significativas
- O leitor pode querer explorar assuntos relacionados
- O contexto é de descoberta, não de instrução sequencial

Cenários típicos:
- Rodapé de posts
- Páginas institucionais
- Arquivos e hubs de conteúdo

Evite Tags Cloud:
- Em artigos muito curtos
- Quando as tags são mal definidas
- Em contextos altamente lineares (tutoriais passo a passo)

---

### Como utilizar (detalhado)

O shortcode deve ser inserido em **áreas de navegação**, não no meio do texto.

Boas práticas:
- Limitar quantidade (`count`)
- Usar tags semanticamente consistentes
- Evitar duplicar função de categorias

---

## 5. HIGHLIGHT TEXT (`tie_highlight`)

### Quando utilizar (detalhado)

Utilize **Highlight Text** para **enfatizar conceitos-chave dentro de um parágrafo**, sem quebrar o fluxo textual.

Indicado quando:
- Uma palavra ou expressão é central para compreensão
- Deseja reforçar conceitos educacionais
- Precisa guiar a leitura em textos densos

Evite Highlight:
- Em excesso no mesmo parágrafo
- Para frases longas
- Para chamar atenção sem propósito semântico

---

### Como utilizar (detalhado)

Envolver **apenas o trecho essencial**, mantendo naturalidade.

Boas práticas:
- Usar com moderação
- Preferir contraste suave
- Não substituir headings ou boxes

---

## 6. DIVIDER LINE (`tie_divider`)

### Quando utilizar (detalhado)

Utilize **Divider Line** para **separar seções conceituais**, não apenas blocos visuais.

Indicado quando:
- Há mudança clara de assunto
- O artigo é longo
- Deseja melhorar escaneabilidade

Evite Divider:
- Entre parágrafos relacionados
- Em textos curtos
- Como substituto de headings

---

### Como utilizar (detalhado)

Inserir isoladamente entre seções.

Boas práticas:
- Margens coerentes com o layout
- Estilo consistente ao longo do artigo

---

## 7. LISTS (`tie_list`)

### Quando utilizar (detalhado)

Use **Lists** quando o conteúdo:
- Pode ser consumido de forma escaneável
- Representa itens, passos, características ou critérios
- Beneficia-se de visualização estruturada

Cenários típicos:
- Requisitos
- Checklists
- Benefícios
- Comparações

Evite listas:
- Para conteúdo narrativo
- Quando a ordem não é clara

---

### Como utilizar (detalhado)

Envolver listas HTML (`<ul>`, `<ol>`) dentro do shortcode.

Boas práticas:
- Itens curtos e paralelos
- Ícones coerentes com o significado
- Evitar listas excessivamente longas

---

## 8. COLUMNS (`tie_columns`, `tie_column`)

### Quando utilizar (detalhado)

Utilize **Columns** quando houver **comparação direta** ou necessidade de **disposição lado a lado**.

Indicado quando:
- Comparar conceitos
- Mostrar prós e contras
- Organizar conteúdo visualmente

Evite colunas:
- Em textos densos
- Para conteúdo linear
- Em excesso em mobile

---

### Como utilizar (detalhado)

Usar `tie_columns` como container e `tie_column` para cada bloco.

Boas práticas:
- Conteúdo equilibrado entre colunas
- Evitar colunas muito longas
- Garantir legibilidade em telas pequenas

---

## 9. QUOTE (`tie_quote`)

### Quando utilizar (detalhado)

Utilize **Quote** para destacar **citações externas ou frases de impacto**.

Indicado quando:
- Citar autores
- Reforçar autoridade
- Destacar ideias-chave

Evite quote:
- Para texto próprio sem intenção de citação
- Para parágrafos longos

---

### Como utilizar (detalhado)

Envolver apenas o texto citado.

Boas práticas:
- Informar autor quando possível
- Usar estilo coerente com o tom do artigo

---

## 10. CONTENT INDEX (`tie_content_index`)

### Quando utilizar (detalhado)

Utilize **Content Index** em **artigos longos e estruturados**, com múltiplos headings.

Indicado quando:
- O artigo possui mais de 3–4 seções
- O leitor pode querer navegar rapidamente
- SEO e UX são prioridades

Evite Content Index:
- Em artigos curtos
- Sem hierarquia clara de headings

---

### Como utilizar (detalhado)

Inserir no ponto onde o índice deve aparecer, geralmente após a introdução.

Boas práticas:
- Garantir headings bem estruturados
- Não repetir manualmente o índice

---