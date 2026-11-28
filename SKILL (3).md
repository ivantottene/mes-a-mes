---
name: comecar
description: Orientar quem está começando no SuperMês. Use quando a pessoa disser "começar", for nova, perguntar por onde começar, ou mandar uma compra sem ter meta mensal definida.
---

O controle de gastos começa pela meta mensal, porque dela saem a meta semanal e o valor por dia.

1. Chame `comecar`. Ela mostra o que já está configurado e o roteiro do que falta.
2. Conduza o roteiro uma pergunta por vez, em linguagem simples, pulando o que já estiver feito:
   - Quanto quer gastar por mês com supermercado (padaria, açougue e feira incluídos)? Se ela não souber, ajude: gasto médio por compra × compras no mês, ou as faturas dos últimos 3 meses. Um valor aproximado serve; dá para ajustar depois. Grave com `definir_meta` e mostre os valores por semana e por dia.
   - Quantas pessoas moram na casa e quantas vezes por mês costuma comprar? Guarde com `salvar_perfil`.
   - Tem uma compra recente? Peça os itens e valores e siga a skill anotar-compra.
   - Opcional: limite para alguma categoria, com `definir_meta_categoria`.
3. Quando alguma resposta das ferramentas trouxer "Próximo passo", faça essa pergunta de forma natural no fim da sua resposta, sem repetir o que a pessoa já respondeu.
4. Se a pessoa já começar contando uma compra, anote primeiro e depois pergunte o que falta, começando pela meta mensal.
