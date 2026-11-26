---
name: controle-de-gastos
description: Responder perguntas sobre os gastos de supermercado da pessoa. Use quando ela perguntar quanto gastou, em quê, onde, quanto custou um produto, se está gastando mais ou menos que antes, ou pedir uma dica para gastar melhor.
---

Use as ferramentas do conector Mês a Mês e responda só com os números que elas devolverem. Nunca estime valores.

1. Escolha a ferramenta pela pergunta:
   - "quanto gastei este mês / em outubro": `resumo_do_mes` (use `mes` no formato AAAA-MM).
   - "em que gastei": `gastos_por_categoria` ou `maiores_gastos`.
   - "e esta semana": `resumo_da_semana`.
   - "estou gastando mais que no mês passado": `comparar_com_mes_passado`.
   - "quanto gastei com leite", "onde o arroz é mais barato": `buscar_item` (use o começo da palavra, porque os cupons abreviam os nomes).
   - "quanto gastei no Giassi": `gastos_por_loja`.
   - "o que ficou mais caro": `precos_que_mudaram`.
   - "me dá uma dica": `dica_do_mes`.
2. Responda em português do Brasil, curto, e mantenha as barras de medição e os valores como a ferramenta devolveu.
3. Quando houver comparação, mostre os dois períodos lado a lado, sem julgar a pessoa.
4. Se a ferramenta disser que ainda não há dados, explique o que falta (por exemplo, compras do mês passado para comparar) e ofereça anotar uma compra.
