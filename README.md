# Gráfico 5.44 — Tolueno (TOL)

Gráfico interativo em Python + Plotly baseado no `Dd_grafico_5_44.csv`.

## Dados

- Campo das estações: `estacao`.
- Anos: 2016–2025.
- Separador de campos: `;`.
- Separador decimal: `,`.
- Valores ausentes permanecem como lacunas.

## Visual

- Eixo Y: 0–9 µg/m³.
- Intervalo: 1 µg/m³.
- Rótulos do eixo Y com vírgula decimal.
- Fundo `#DDE9F4`.
- Grade horizontal pontilhada.
- Uma série por estação.
- Marcadores circulares.
- Tooltip interativo.
- Zoom.
- HTML autocontido para GitHub Pages.

## Gerar

```bash
pip install pandas plotly
python gerar_grafico.py
```

## Publicar

```bash
git init
git add .
git commit -m "Adicionar grafico 5.44 TOL"
git branch -M main
git remote add origin https://github.com/SEU_USUARIO/SEU_REPOSITORIO.git
git push -u origin main
```

No GitHub:
**Settings → Pages → Build and deployment → Source → GitHub Actions**
