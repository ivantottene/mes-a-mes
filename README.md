# Mês a Mês

Controle o gasto de supermercado semana a semana e mês a mês, e entenda o que você compra por categoria, conversando com o Claude. Você anota as compras e pergunta quanto gastou, em quê e onde ficou mais barato.

## Como conectar

Quer ver antes com dados de mentira? Abra https://mes-que-vem-api.tottene.workers.dev/demo: a conta de demonstração já vem com dois meses de compras fictícias e se apaga sozinha em 3 dias.

**Com login (recomendado).** No Claude, abra Personalizar (Customize) > Conectores > Adicionar conector personalizado e cole só o endereço `https://mes-que-vem-api.tottene.workers.dev/mcp`. O Claude abre uma página do Mês a Mês: crie sua conta anônima (não pedimos nome, e-mail nem telefone) e guarde o código de recuperação, que aparece uma única vez, em um gerenciador de senhas. Se já tem conta, entre com o código de recuperação ou com o link pessoal. Depois você volta ao Claude já conectado. Ao instalar este plugin, o endereço já vem configurado.

**Com link pessoal (alternativa).**

1. Abra https://mes-que-vem-api.tottene.workers.dev/conectar, aceite a política de privacidade e crie sua conta.
2. Guarde o link pessoal e o código de recuperação que aparecem, uma única vez, em um gerenciador de senhas.
3. No Claude, abra Personalizar (Customize) > Conectores > Adicionar conector personalizado, cole o link e escolha autenticação "Sem login".

## Como usar

Peça em português, por exemplo: "quais mercados estão mais baratos?", "anote leite e ovos na lista de compras", "o que está acabando?", "defina uma meta de R$ 400 para carnes", "como vou fechar o mês?", "anote uma compra no Giassi: leite 5,50 e pão 8", "quanto gastei este mês?", "onde o arroz ficou mais barato?" ou "o que ficou mais caro?". As 4 skills (controle de gastos, anotar compra, meta do mês e lista de compras) ensinam o Claude a escolher a ferramenta certa, a confirmar os itens antes de anotar uma compra e a mostrar os números como o conector devolve.

## Ferramentas do conector (25)

- **Consultas:** resumo do mês e da semana, gastos por categoria, loja e item (com preço por loja), comparação com o mês passado, preços que mudaram, dica do mês, últimas compras, maiores gastos.
- **Análises:** comparar mercados (o nome da loja é unificado, então "giassi" e "GIASSI LTDA" são o mesmo mercado), itens mais comprados, ticket médio e frequência, quanto ainda posso gastar.
- **Planejamento:** lista de compras com custo estimado pelos últimos preços pagos (ver, adicionar, tirar) e "o que está acabando", pelo ritmo de compra de cada item.
- **Metas:** meta mensal, metas por categoria e previsão de como o mês vai fechar.
- **Dados:** anotar compra e exportar dados.

As ferramentas que gravam dados (anotar compra, definir metas, adicionar e tirar da lista) pedem sua permissão a cada uso.

## Dados

O plugin envia ao servidor do Mês que Vem (mes-que-vem-api.tottene.workers.dev) apenas o que a ferramenta precisa, como o mês consultado, o nome de um produto ou os itens de uma compra que você pediu para anotar. Ele só lê e grava dados da sua própria conta. Se perder o link, o código de recuperação gera um link novo sem perder as compras (seção "Perdi o link" da página Minha conta). Para trocar a chave ou apagar a conta e todos os dados, use https://mes-que-vem-api.tottene.workers.dev/minha-conta. Política de privacidade: https://mes-que-vem-api.tottene.workers.dev/privacidade. Documentação: https://mes-que-vem-api.tottene.workers.dev/docs.
