# Banco Brasil Quiz & Simulados — Landing Page

Landing page do aplicativo **Banco Brasil: Quiz & Simulados** para concurso de Agente Comercial do Banco do Brasil (nível médio).

## Seções

- **Hero** — Apresentação do app com links para a Google Play e planos
- **Módulos** — Como o app pode acelerar a aprovação
- **Disciplinas** — As 26 disciplinas do edital (130 módulos, 1.300 questões), no formato da tela Conteúdo do app
- **Dinâmica** — Metodologia de estudo ativo com questões comentadas
- **Offline** — Banco de dados SQLite integrado, funciona sem internet
- **Planos** — Mensal (R$ 14,90), Anual (R$ 29,90) e Vitalício (R$ 49,90)
- **Carrossel** — Galeria de telas do aplicativo (placeholder até os prints oficiais)
- **FAQ** — Perguntas frequentes sobre justificativas, atualizações, modo offline, simulados e planos

## App

- Pacote: `br.com.sdiascode.bancobrasil`
- Site: https://bb.sdiascode.com.br/
- Legal: https://legal-bb.sdiascode.com.br/
- Grade de disciplinas (fonte da verdade): `app_banco_brasil/my_app_banco_brasil/lib/core/conteudo_app.dart`

## Pendências

- Confirmar preços dos planos na Play Console antes do release

## Imagens

- `img/banner.jpg` (1024×500, desktop) e `img/banner-tablet.jpg` (1024×500) — versões do banner
  `detalhes_app/landingpage/img/banner_1024x500.jpeg`; `img/banner-mobile.jpg` (768×375) reduzida
  para smartphones. O CSS limita o banner a 900px de largura.
- `img/img01.jpg` a `img/img08.jpg` (682×1440) — prints de
  `detalhes_app/tela_app_bb_phone/Screenshot_*.png` convertidos PNG → JPEG.

## Tecnologias

- HTML5 semântico
- CSS3 (variáveis, flexbox, grid, gradientes)
- JavaScript vanilla (carrossel com autoplay)

## Como usar

Abra o `index.html` no navegador ou sirva com um servidor local:

```bash
npx serve .
```
