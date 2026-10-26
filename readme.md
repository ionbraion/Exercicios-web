# Lista de Exercícios 1 — Programação para Internet I (2026-1)

**Instituição:** Instituto Federal de Santa Catarina (IFSC)  
**Professor:** Romulo Beninca (`romulo.beninca@ifsc.edu.br`)  
**Unidade Curricular:** Programação para Internet  
**Tema:** HTML sem CSS  

---

## 📁 Estrutura de Arquivos do Projeto

- `index.html`
- `historia_web.html`
- `http.html`
- `curriculo.html`
- `contato.html`

---

## 📝 Descrição das Atividades

### ☑ Atividade 1 — Portal inicial e navegação do site
* **Arquivo:** `index.html`

Crie a página inicial do seu pequeno site HTML. Ela deve conter:
1. Título da página no navegador usando `<title>`;
2. Um título principal usando `<h1>`;
3. Um texto de apresentação explicando o objetivo do site;
4. Uma explicação curta, com no máximo 5 linhas, diferenciando Internet e Web;
5. Um menu de navegação com links para todas as páginas (História da Web, HTTP, Estados, Currículo, Contato);
6. Uma lista ordenada explicando a sequência sugerida de leitura das páginas;
7. Uma lista não ordenada com os principais conteúdos estudados até agora;
8. Um comentário HTML com: nome do autor, turma e data de criação.
   > **Exemplo:** `<!-- Autor: Nome do Aluno | Turma: ADS | Data: 20/03/2026 -->`

**Tags obrigatórias:**  
`html`, `head`, `title`, `body`, `h1`, `h2`, `p`, `a`, `ul`, `ol`, `li`, `div`, `span`, `hr`

---

### ☑ Atividade 2 — História da Internet e da Web em HTML
* **Arquivo:** `historia_web.html`

Crie uma página explicando a evolução da Internet e da Web, apresentando uma linha do tempo textual contendo (no mínimo):
- Surgimento das redes de computadores, ARPANET, TCP/IP, DNS;
- Criação da World Wide Web, Tim Berners-Lee, HTML, HTTP, navegador, servidor web;
- Diferença entre Web 1.0 e aplicações Web modernas.

**Requisitos da página:**
1. Menu de navegação para voltar ao `index.html` e acessar as demais páginas;
2. Pelo menos duas imagens com `<img>` e texto alternativo adequado (`alt`);
3. Pelo menos três links externos para fontes de pesquisa;
4. Uma citação curta ou referência a Tim Berners-Lee ou ao CERN;
5. Uma lista de definição (`<dl>`, `<dt>`, `<dd>`);
6. Uma tabela com pelo menos 6 marcos históricos (Ano, Acontecimento e Importância).

**Tags obrigatórias:**  
`h1`, `h2`, `h3`, `p`, `img`, `a`, `div`, `span`, `hr`, `em`, `strong`, `mark`, `sub`, `sup`, `ul`, `ol`, `li`, `dl`, `dt`, `dd`, `table`, `caption`, `thead`, `tbody`, `tfoot`, `tr`, `th`, `td`

---

### ☑ Atividade 3 — HTTP na prática: requisição e resposta
* **Arquivo:** `http.html`

Crie uma página explicando o protocolo HTTP e sua aplicação na Web:
1. Explicação sobre o papel do HTTP na comunicação entre navegador e servidor;
2. Explicação sobre cliente, servidor, requisição e resposta;
3. Descrição dos métodos `GET` e `POST`;
4. Exemplo de uma requisição HTTP e de uma resposta HTTP;
5. Explicação de pelo menos 5 códigos de status HTTP (ex: `200`, `301`/`302`, `400`, `403`, `404`, `500`).

---

### ☑ Atividade 4 — Currículo HTML com Elementos de Estrutura e Formatação
* **Arquivo:** `curriculo.html`

**A. Informações do Currículo:**
- Nome completo e foto (`<img>`);
- Contato (e-mail e telefone com links funcionais `mailto:` e `tel:`);
- Breve descrição (`<p>`);
- Lista de habilidades técnicas (`<ul>` ou `<ol>`);
- Formação acadêmica (`<section>`, `<article>` ou `<div>`);
- Experiência profissional com descrições curtas (`<strong>`, `<em>`, `<mark>`).

**B. Grade de Horários:** Tabela com matérias, dias e horários.  
**C. Navegação Interna:** Menu com âncoras para as seções (ex: `#formacao`, `#experiencia`).  
**D. Tags obrigatórias:** `<div>`, `<span>`, `<p>`, `<b>`, `<em>`, `<strong>`, `<mark>`, `<sub>`, `<details>` e `<summary>`.  
**E. Recursos Extras:** Imagens e links externos (ex: LinkedIn).

---

### ☑ Atividade 5 — Página de Contato com Formulário
* **Arquivo:** `contato.html`

**A. Campos do Formulário (`<form>`):**
- Nome (obrigatório)
- E-mail (obrigatório, tipo `email`)
- Assunto
- Estado (`<select>` e `<option>`)
- Mensagem
- Botão de envio

**B. Requisitos Técnicos:**
- Tag `<label>` para cada campo vinculada via atributo `id` do `<input>`;
- Validação básica via HTML (`required`);
- Atributo `placeholder` nos campos;
- Mensagem de instrução no topo da página;
- Link de navegação voltando para a página de currículo.

---

### ☑ Atividade 6 — Publicação no GitHub Pages
1. Suba o repositório para o GitHub;
2. Ative o GitHub Pages nas configurações do repositório;
3. Teste o link gerado acessando a página inicial (`index.html`);
4. Poste no Moodle: Link do repositório e comentário sobre a experiência.