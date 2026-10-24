# Dashboard de Vendas Porsche

Dashboard interativa em um único arquivo HTML, criada a partir de uma planilha com 100 vendas da Porsche. Não precisa de instalação nem de servidor: basta abrir `porsche-dashboard.html` no navegador.

## Perguntas de negócio respondidas

1. **Quais famílias de modelo sustentam a receita?** Receita, número de vendas e ticket médio por família (911, Taycan, Cayenne, Panamera, Macan, 718).
2. **Como o cliente paga?** Receita por método de pagamento.
3. **Onde se concentra a receita?** Os maiores estados por receita.

## Recursos

- Indicadores de topo: vendas, receita, ticket médio e taxa de entrega
- Filtros por família, ano-modelo, pagamento, status, estado e cidade
- Clique nas barras dos gráficos para filtrar
- Tabela ordenável com as vendas do recorte
- Tema claro e escuro

## Tratamento dos dados

- Valores em dólares (US$).
- O filtro de ano usa o **ano-modelo** do carro, porque 24 das 100 datas de venda estão marcadas como `INVALID`.
- Os 40 modelos foram agrupados em 6 famílias.
- Os 10 status de entrega foram reduzidos a 4: Entregue, A caminho, Pendente e Cancelada.
- A receita inclui as vendas canceladas, a menos que o filtro de status as exclua.
- Nomes de clientes e vendedores não foram incluídos no arquivo.

## Tecnologias

HTML, CSS e JavaScript puros, sem bibliotecas. Fontes: Barlow Semi Condensed e Inter (Google Fonts).
Elaborado por: Mauro Luis
