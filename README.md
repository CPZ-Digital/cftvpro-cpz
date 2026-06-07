# Orçamento CPZ / B&A Vision

Gerador de propostas comerciais para instalações de câmeras de segurança.  
App web single-file — roda direto no navegador, sem servidor, sem instalação.

---

## Funcionalidades

- **Dois modos de marca** — CPZ Digital (azul) e B&A Vision (verde), alternados pelo app
- **Catálogo de produtos e infraestrutura** carregado via Google Sheets (CSV)
- **Cálculo automático** com multiplicadores por tipo de projeto e nível de dificuldade
- **Formas de pagamento** — À Vista (50/50 ou Nx Pix), Boleto (+5%), Cartão (+10%)
- **Viabilidade financeira** — desabilita automaticamente opções onde o caixa fica negativo
- **Geração de PDF** — proposta profissional com logo, tabelas, parcelas e assinatura
- **Exportação Excel (.xlsx)** — duas abas:
  - *Orçamento*: dados do cliente, equipamentos, infraestrutura e resumo
  - *Financeiro*: todas as 16 combinações de pagamento pré-calculadas com caixa acumulado
- **Compartilhamento WhatsApp** — Web Share API no mobile, link wa.me no desktop
- **Persistência local** — estado salvo no navegador (localStorage), restaurado ao reabrir

---

## Arquivos

| Arquivo | Descrição |
|---|---|
| `index.html` | App completo (CSS + HTML + JS, single-file) |
| `template-pdf.html` | Template da proposta PDF com placeholders `{{key}}` |
| `cpz-assinatura.png` | Logo CPZ Digital |
| `ba-vision-assinatura.png` | Logo B&A Vision |

---

## Como usar

1. Faça o download ou clone o repositório
2. Abra `index.html` no navegador
3. Selecione o tipo de projeto e adicione os equipamentos
4. Configure a forma de pagamento
5. Exporte como PDF ou planilha Excel

> Não requer servidor, backend ou instalação de dependências.  
> Todas as bibliotecas são carregadas via CDN.

---

## Tecnologias

- [html2pdf.js](https://github.com/eKoopmans/html2pdf.js) — geração de PDF no browser
- [ExcelJS](https://github.com/exceljs/exceljs) — geração de planilhas .xlsx estilizadas
- Google Sheets (publicado como CSV) — catálogo de produtos

---

## Licença

Uso interno — CPZ Digital / B&A Vision.
