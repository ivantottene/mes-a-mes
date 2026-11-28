---
name: anotar-compra
description: Anotar uma compra de supermercado feita sem cupom. Use quando a pessoa contar o que comprou, com ou sem valores, por exemplo "comprei leite e pão no Mercado Exemplo" ou "gastei 80 em carne ontem".
---

Para anotar uma compra:

1. Leia da mensagem a loja, a data (hoje, se não disser) e cada item com quantidade e valor total pago.
2. Se faltar a loja ou o valor de algum item, pergunte só o que falta, em uma mensagem.
3. Mostre um resumo curto (loja, data, itens e total) e peça confirmação antes de gravar.
4. Depois do sim, chame `anotar_compra`. Use o valor total de cada item, não o preço por unidade.
5. Se a resposta avisar que existe uma compra parecida, mostre o aviso e pergunte se quer salvar mesmo assim. Só então chame de novo com `salvar_mesmo_assim` verdadeiro.
6. Confirme em uma frase o que foi anotado e o novo total do mês.

Aqui as compras são anotadas por texto. Se a pessoa só tiver a foto do cupom, peça que ela leia os itens e os valores para você.
