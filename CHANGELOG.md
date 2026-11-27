# Histórico de alterações — Gelo Minerale Lançamentos

Cada envio do site para o GitHub ganha uma linha aqui e um comentário no commit.

## 27/11/2026

### 15:42 — Consignado volta para o botão direito na Expedição
- Botão direito (ou segurar) no nome, na Expedição: **Marcar como consignado**, **Ajustar saldo consignado** e **Tirar de consignado**.
- O formulário já mostra o saldo que está no quadro SALDOS P/ DEVOLUÇÃO da planilha e preenche os produtos quando a linha diz CUBO (MINERALE 3KG) ou ESC MIN (MINERALE 10KG).
- Linha da planilha só com o nome do cliente (ex.: MV BEBIDAS) é reaproveitada, sem criar linha repetida.
- Resumo do dia: o quadro "Estoque em haver" fica só para consulta (sem botões), com a coluna que diz se o saldo do site bate com a planilha.

### 15:35 — Adicionar cliente em haver pelo Resumo (substituído às 15:42)

### 15:02 — Cadastro de pessoas no modelo antigo
- **+ Novo** na Expedição volta a funcionar: a pessoa fica guardada no intermediário (Cloudflare) e aparece em todos os aparelhos.
- Para lançar saída/volta dela, o nome precisa estar num quadro da aba 1 da planilha do mês.

### 14:52 — Estoque em haver no Resumo do dia
- Lê o quadro SALDOS P/ DEVOLUÇÃO da aba do dia e compara com o saldo calculado pelo site.

### 14:39 — Saldo em haver preenchido na planilha
- Saída de cliente consignado tira do saldo; volta (boa ou ruim) devolve.
- O site preenche SAÍDA, ENTRADA e SALDO no quadro SALDOS P/ DEVOLUÇÃO de cada dia.
- Volta de cliente sem linha de volta (ex.: SURREAL) vai para o quadro DEVOLUÇÃO SURREAL.
- SURREAL marcado a partir de 28/11 com 4.016 (MINERALE 3KG) e 297 (MINERALE 10KG).

### 12:13 — Primeira versão do consignado
- Marcação de cliente consignado e menu do nome funcionando no modelo antigo (mover para pouco usados, desativar).

### 11:58 — Produção, Embalagens e Leituras numa aba só
- Aba Produção com três botões no topo; lembra o último usado.

### 11:49 — Resumo do dia com lançamentos dentro dos painéis
- Tocar no motorista (fechamento) ou no produto (produção) abre os lançamentos com editar e cancelar.
- Cancelar produção pelo Resumo.

### 11:36 — Login primeiro e link único
- A página abre direto no login; o login vale para a aba aberta.
- O endereço fica sempre limpo (sem ?v=...).

### 11:28 — Atualização automática
- O site confere a cada 2 minutos se saiu versão nova e recarrega quando ninguém está lançando.

### 11:08 — Pedido na Expedição
- Tipo, motorista e placa uma vez; vários produtos com **Incluir no pedido**; **Lançar pedido** grava uma linha por produto com as mesmas fotos.
