# Simulador Eternure

Simulador de custo e precificação para a Eternure (personalização e brindes).

Calcula, em tempo real, custo total, imposto de compra, margem de lucro, preço
de venda e imposto de venda a partir dos mesmos dados e fórmulas da planilha
original da empresa, e permite exportar o resumo para PDF e Excel.

## Uso

Abra `index.html` diretamente no navegador (não requer build nem servidor).

## Estrutura

- `index.html` — página principal do simulador
- `css/styles.css` — estilos
- `js/app.js` — lógica de cálculo e exportação (PDF/Excel)
- `js/vendor/` — jsPDF (vendorizado) e logo em base64
- `assets/logo.svg` — logo da Eternure
