# Sistema_de_Vendas

Este é um sistema criado para gestão de vendedores e suas respectivas vendas.

Usaremos python/tkinter e sqlite3 para o banco de dados

O sistema funcionará da seguinte forma:
    
    Serão cadastrados alguns vendedores atribuiremos pedidos a ele.
        Os pedidos serão constituídos das seguintes informações
            nome do cliente 
            nº do pedido (neste cado, o número sera preenchido manualmente)
            data de emissão do pedido
            valor negociado
            valor de entrada
            data da entrada
            data da entrega
            valor pago na entrega
            Valor pago toral (entrada + entrega)
            status (faturado/pendente/cancelado)
            observações (se faltou peça, prolema no pagamento)
    
    Com as informações obtidas sobre cada pedido, serão emitidos relatórios sobre cada vendedor, que
    componharam o fechamento mensal.
        Quantos pedidos emitidos dentro do mês vigente:
        Qual o total de pedidos emitido no mês vigente que foram faturados:
        Qual o total de pedidos emitidos em mêses anteriores que foram faturados;
        Qual o total de pedidos faturados (meses anteriores e atual);
        Qual o total de pedidos pendentes.
    Com essas informações será emitido o fechamento mensal relativo a cada vendedor e tambem dashboards para melhor 
    visualização de desempenho.

    ...
    
