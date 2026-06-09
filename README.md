# CFTVPro — Manual de Uso

App web para gerar propostas comerciais de instalação de câmeras de segurança.  
Funciona no celular e no computador, pode ser instalado como app e funciona offline.

> **Link de acesso:** consulte o Adriano.

---

## Instalação no celular (recomendado)

**Android (Chrome):**
1. Abra o link acima no Chrome
2. Toque no menu ⋮ → **"Adicionar à tela inicial"**
3. O app aparece como ícone na tela inicial

**iPhone (Safari):**
1. Abra o link acima no Safari
2. Toque no botão compartilhar (quadrado com seta)
3. Toque em **"Adicionar à Tela de Início"**

---

## Modos de operação

O app funciona em dois modos — um para cada empresa.

| | CPZ Digital | B&A Vision |
|---|---|---|
| **Cor** | Azul | Verde |
| **Logo no PDF** | CPZ Digital | B&A Vision |
| **CNPJ** | 58.589.970/0001-54 | 62.456.202/0001-08 |
| **Responsável** | Adriano | Bruno & Adriano |

**Como alternar:** toque **3 vezes rápidas** no título "Orçamento" no topo do app.  
O app abre em **B&A Vision por padrão**.

---

## Passo a passo — Gerar um orçamento

### 1. Tipo de projeto
Selecione o tipo de instalação:
- **Analógica** — câmeras HDCVI/AHD tradicionais
- **IP** — câmeras em rede
- **Wi-Fi** — câmeras sem fio
- **Automação** — sistemas de automação
- **Sensores** — alarmes e sensores

### 2. Adicionar equipamentos
- Toque em **+ Produto** para adicionar câmeras, DVRs, NVRs, etc.
- Digite o nome ou código no campo de busca e selecione o item
- Ajuste a quantidade
- O preço é preenchido automaticamente pelo catálogo
- Para alterar o preço manualmente: toque no valor e edite

### 3. Adicionar infraestrutura
- Toque em **+ Infraestrutura** para adicionar cabos, conectores, eletrocalhas, etc.
- Mesmo processo dos equipamentos

### 4. Dias de trabalho
- **Dias de trabalho** — quantos dias você vai na obra
- **Dias de diarista** — quantos dias o diarista vai junto (R$ 120/dia)

### 5. Dificuldade
Selecione o nível de dificuldade da instalação:
- **Fácil** — acesso simples, pouco cabeamento
- **Médio** — situação padrão
- **Difícil** — altura, laje, muito cabeamento ou acesso ruim

### 6. Desconto
Campo "Desconto %" no card de resultado. O valor original fica riscado e aparece a economia gerada.

---

## Formas de pagamento

Toque em **💳 Pagamento** na barra inferior.

| Forma | Acréscimo |
|---|---|
| À vista (Pix) | Sem acréscimo |
| Boleto | +5% |
| Cartão | +10% |

**À vista** tem duas opções:
- **50% + 50%** — metade na assinatura, metade na entrega
- **Nx Pix** — parcelado em Pix (2 a 6 vezes)

O app verifica automaticamente se o caixa aguenta cada opção de parcelamento e **desabilita as inviáveis** (quando o projeto fica no negativo antes de receber).

---

## Exportar proposta

Toque em **Exportar** (no botão de Pagamento) ou no ícone de download.

Preencha os dados do cliente:
- **Nome** e **Telefone** são obrigatórios
- **E-mail**, **Data**, **Validade**, **Prazo de execução** e **Garantia** são opcionais
- **Observações** — campo livre para anotações que aparecem no PDF

Depois escolha:

### PDF
Gera a proposta completa com logo, dados do cliente, equipamentos, parcelas e assinaturas.  
Após salvar, aparece o botão **WhatsApp** para enviar direto ao cliente.

### Excel (.xlsx)
Gera planilha com duas abas:
- **Orçamento** — todos os dados da proposta
- **Financeiro** — todas as 16 combinações de pagamento calculadas, com caixa acumulado por parcela (verde = positivo, vermelho = negativo)

---

## Histórico de propostas

Toque no **ícone de relógio** na barra inferior.

Cada proposta salva mostra:
- **Marca** (B&A Vision ou CPZ)
- **Status** — Aguardando / Aprovada / Recusada
- **Alerta de vencimento** — aparece quando falta 3 dias ou menos para expirar

**Ações disponíveis:**
- **Reabrir** — carrega a proposta no app (pede confirmação se houver orçamento em aberto)
- **Duplicar** — cria uma cópia para usar como base em um job parecido
- **✓ Aprovada / ✗ Recusada** — marca o status (clique novamente para desfazer)
- **Excluir** — remove do histórico

**Salvar manualmente:** digite um nome no campo e toque em "Salvar".  
**Auto-save:** toda vez que você exporta PDF ou XLS, a proposta é salva automaticamente.

### Backup
- **Exportar backup** — baixa um arquivo `.json` com todo o histórico
- **Importar backup** — restaura propostas de um backup (não duplica as que já existem)

### Estatísticas
O topo do histórico mostra: total de propostas, taxa de aprovação e quantidade aprovada.

---

## Indicador de margem (uso interno)

Toque em **"Ver detalhes"** no card de resultado.

Campo **Custo estimado %** — informe qual percentual do total vai para custos (padrão: 60%).  
O app calcula automaticamente:
- **Lucro bruto** = total − custo estimado
- **Margem** = lucro ÷ total

Esses dados **não aparecem no PDF** — são só para controle interno.

---

## Novo orçamento

Toque no **ícone de reset** (setas circulares) na barra inferior.  
Pede confirmação antes de apagar tudo. O app volta ao estado inicial com B&A Vision ativo.

---

## Catálogo de produtos

Os preços e produtos são carregados automaticamente do Google Sheets toda vez que o app abre.  
Para atualizar preços ou adicionar produtos: edite a planilha no Google Sheets — na próxima abertura do app os dados já estarão atualizados.

---

## Dúvidas ou problemas

Falar com **Adriano** — responsável pelo app.
