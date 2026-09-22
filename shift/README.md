# REDLINE - Landing Page

Trabalho prático de Landing Page para Eventos (disciplina de HTML/CSS - TADS, 2º semestre).

Escolhi um evento fictício de cultura automotiva chamado **REDLINE**, um encontro de carros que acontece em Cascavel, no Paraná. A ideia foi fugir um pouco do tema "festa/festival" e criar algo com uma pegada mais urbana.

## Como abrir

É só baixar/clonar o repositório e abrir o arquivo `index.html` no navegador. Não precisa instalar nada, é só HTML e CSS puro (sem framework, sem JS).

## Estrutura de pastas

```
redline/
├── index.html
├── css/
│   └── style.css
├── images/
│   ├── favicon.svg
│   ├── logo.svg
│   ├── categoria-jdm.svg
│   ├── categoria-muscle.svg
│   ├── categoria-classicos.svg
│   ├── categoria-offroad.svg
│   ├── categoria-stance.svg
│   ├── categoria-motos.svg
│   └── mapa.svg
└── README.md
```

## O que usei

- Tags semânticas do HTML5 (`header`, `nav`, `main`, `section`, `article`, `footer`, `address`, `details/summary`, `form`)
- Flexbox pra organizar o header, os botões, o formulário e o rodapé
- CSS Grid pras seções de categorias, programação, ingressos, local e formulário
- Variáveis CSS (`:root`) só pra cores, pra não ficar repetindo hexadecimal em tudo quanto é lugar
- Fonte "Oswald" do Google Fonts pros títulos, e fonte padrão do sistema (Arial) pro resto do texto
- Media query em 768px e 1024px pra ficar responsivo (mobile primeiro, depois vai abrindo os grids)

## Seções da página

1. Cabeçalho com menu
2. Banner principal (nome do evento, data e local)
3. Sobre o evento + números
4. Categorias que participam do julgamento
5. Programação do dia (manhã, tarde, noite)
6. Ingressos (visitante, expositor, pista/paddock)
7. Como chegar
8. Perguntas frequentes
9. Formulário de inscrição
10. Rodapé

## Observação

O formulário não manda pra lugar nenhum de verdade (não tem back-end), é só a parte visual mesmo, já que o foco do trabalho é HTML e CSS.
