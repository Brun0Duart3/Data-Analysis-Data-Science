# Data-Analysis-Data-Science

Portfólio de estudos em Ciência de Dados, com artigos, projetos e análises de dados públicos.

## Site

Portfólio estático em HTML, CSS e JavaScript, com três estudos completos e 30 gráficos incorporados.

- Estudo 1: Google Sheets — Aroma Café.
- Estudo 2: Power BI — Airbnb.
- Estudo 3: Excel — coortes e RFM.

## Publicar no GitHub Pages

Em Settings → Pages, escolha Deploy from a branch, branch main e pasta /(root), e salve.

Endereço após ativação: https://brun0duart3.github.io/Data-Analysis-Data-Science/

## Atualização

Os arquivos do site estão na raiz. `content.js` guarda a apresentação e os resumos; `original-content.js`, os textos e gráficos dos estudos; `assets/`, as imagens. Ao acrescentar estudos, atualize também as coleções e contagens de `app.js` e crie a página correspondente.

O suporte a outros idiomas permanece desativado (`settings.multilingual = false`).

## Executar localmente

Execute `python -m http.server 8000` na pasta e abra http://localhost:8000/.

Verificação de sintaxe: `node --check app.js`, `node --check content.js` e `node --check original-content.js`.
