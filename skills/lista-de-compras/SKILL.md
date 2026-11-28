---
name: lista-de-compras
description: Montar e consultar a lista de compras da pessoa, com custo estimado pelos preços que ela já pagou, e dizer o que provavelmente está acabando. Use quando ela falar em lista, o que falta comprar, o que acabou ou o que precisa repor.
---

Use só as ferramentas do conector SuperMês e mostre os valores como elas devolverem. Nunca invente preços.

1. "Anote leite e ovos na lista", "acabou o café": chame `adicionar_na_lista` com os nomes simples, um por produto.
2. "Como está minha lista", "quanto vai custar": chame `ver_lista_de_compras`. O custo é uma estimativa com uma unidade de cada item, pelo último preço pago; diga isso se a pessoa estranhar o valor.
3. "Tira o leite da lista" ou "tira o item 2": chame `tirar_da_lista` com o nome ou o número. Só limpe a lista toda (valor "tudo") se a pessoa pedir.
4. "O que está acabando", "o que preciso repor": chame `o_que_esta_acabando`. É uma previsão pelo ritmo de compras, não um estoque real; as ofertas de colocar na lista dependem da pessoa aceitar.
5. Itens sem histórico de preço ficam de fora da estimativa; a ferramenta avisa quantos.
