---
name: meta-do-mes
description: Ver ou definir a meta mensal de gasto em supermercado e acompanhar o ritmo. Use quando a pessoa falar em meta, orçamento, limite do mês, ou perguntar quanto ainda pode gastar. Também serve para metas por categoria (carnes, mercearia, hortifruti etc.).
---

0. Se a pessoa está começando (ainda sem meta), chame `comecar` e siga o roteiro. A meta mensal é a base: dela saem a meta semanal (mensal × 12 ÷ 52) e o valor por dia (mensal ÷ 30). Pergunte quantas pessoas moram na casa e quantas vezes por mês ela compra e guarde com `salvar_perfil`; com compras já anotadas, a ferramenta sugere um ponto de partida.
1. Para saber quanto já foi usado e quanto resta, chame `ver_meta`.
2. Só chame `definir_meta` quando a pessoa pedir para definir ou mudar a meta e disser o valor mensal em reais. Se ela não tiver um valor em mente, ofereça a média dos meses anteriores que a ferramenta `ver_meta` ou `resumo_do_mes` mostrar, sem decidir por ela.
3. Mostre o ritmo (quanto sobra por semana ou por dia) como a ferramenta devolveu. Se a meta foi ultrapassada, diga só quanto passou, sem cobrar.
4. Se não houver meta definida, explique em uma frase que ela ajuda a acompanhar o mês e pergunte se quer definir uma.
5. Para "quanto ainda posso gastar", use `quanto_posso_gastar`.
6. Metas por categoria: `metas_por_categoria` mostra o que foi gasto em cada uma; `definir_meta_categoria` só com a categoria e o valor mensal em reais ditos pela pessoa (valor 0 apaga a meta da categoria).
7. Para ver se a pessoa vai respeitar a meta, use `previsao_do_mes` e apresente o resultado como estimativa pelo ritmo até agora, nunca como certeza.
