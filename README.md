# Mês a Mês

Controle o gasto de supermercado semana a semana e mês a mês, e entenda o que você compra por categoria, conversando com o Claude. Você anota as compras e pergunta quanto gastou, em quê e onde ficou mais barato.

## Como conectar

1. Abra https://mes-que-vem-api.tottene.workers.dev/conectar, aceite a política de privacidade e crie sua conta. Não pedimos nome, e-mail nem telefone.
2. Guarde o link pessoal que aparece, uma única vez.
3. No Claude, abra Personalizar (Customize) > Conectores > Adicionar conector personalizado, cole o link e escolha autenticação "Sem login".

## Como usar

Peça em português, por exemplo: "anote uma compra no Giassi: leite 5,50 e pão 8", "quanto gastei este mês?", "onde o arroz ficou mais barato?" ou "o que ficou mais caro?". As skills ensinam o Claude a escolher a ferramenta certa, a confirmar os itens antes de anotar uma compra e a mostrar os números como o conector devolve.

## Ferramentas do conector

Resumo do mês e da semana, gastos por categoria, loja e item (com preço por loja), comparação com o mês passado, preços que mudaram, dica do mês, últimas compras, ver e definir meta, exportar dados e anotar compra.

## Dados

O plugin envia ao servidor do Mês que Vem (mes-que-vem-api.tottene.workers.dev) apenas o que a ferramenta precisa, como o mês consultado, o nome de um produto ou os itens de uma compra que você pediu para anotar. Ele só lê e grava dados da sua própria conta. Para trocar a chave ou apagar a conta e todos os dados, use https://mes-que-vem-api.tottene.workers.dev/minha-conta. Política de privacidade: https://mes-que-vem-api.tottene.workers.dev/privacidade. Documentação: https://mes-que-vem-api.tottene.workers.dev/docs.
