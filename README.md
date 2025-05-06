# English4You 

---

## Estrutura do Projeto
```
.
├── index.html
├── style.css
├── img/
│   └── (Imagens do projeto: logo, banner, etc.)
├── setores/
│   ├── pais-alunos.html
│   ├── apoio-pedagogico.html
│   ├── supervisao.html
│   ├── rh.html
│   ├── contato.html
│   └── projetos.html
├── README.md   
└── relatorio.md

```
---

## Decisões de Design

- **Identidade visual**: Utilização de azul escuro (#004080) para transmitir confiança e profissionalismo, com elementos em laranja (#ffa500) para destacar ações importantes.
- **Responsividade**: Layout desenvolvido com `flexbox` e `grid`, além de media queries para adaptação a telas de celular, tablet e desktop.
- **Clareza na navegação**: Menu principal visível em todas as páginas, com links claros para os setores principais da organização.
- **Componentização visual**: Uso de seções bem definidas (hero, cursos, sobre, depoimentos, rodapé) para organizar o conteúdo.

---

## Funcionalidades

- Página inicial com banner de boas-vindas (hero), apresentação dos cursos, área "Sobre" e depoimentos.
- Menu com redirecionamento funcional para cinco páginas de setores:
  - Pais e Alunos
  - Apoio Pedagógico
  - Supervisão
  - RH (RH)
  - Projetos
- Layout responsivo em todas as páginas.
- Estilização consistente com CSS externo (`style.css`).

---

## Tecnologias Utilizadas

- HTML
- CSS

---

## Como Executar Localmente

1. Baixe e extraia o arquivo.
2. Abra o `index.html` com um navegador.

---

## Atualização 1: Páginas dos Setores

Para atender aos requisitos, foram adicionadas páginas para os principais setores, todas acessíveis via menu no topo do site:

- Pais e Alunos (`pais-alunos.html`)
- Apoio Pedagógico (`apoio-pedagogico.html`)
- Supervisão (`supervisao.html`)
- RH (`rh.html`)
- Projetos (`projetos.html`)

---

### Atualização 2: Página de Contato 

Criada a página `contato.html` com um formulário acessível e responsivo para que usuários possam entrar em contato. O formulário utiliza o atributo `mailto:` para envio de mensagens via e-mail.
A página de contato pode ser acessada via links rápidos

---
