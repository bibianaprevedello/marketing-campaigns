# Marketing Campaigns
Este projeto se trata de uma análise de campanhas de marketing de uma empresa que vende acessórios para veículos.

![](pexels-cottonbro-4488642.jpg)

## 1. Problema

A empresa de data science foi contratada para desenvolver um algoritmo que maximize as campanhas de CRM de uma empresa que vende acessórios para veículos. Com base no histórico de compras, **foram desenvolvidas campanhas específicas para atingir um grupo restrito de clientes e garantir o máximo de adesão possível**. Para tanto, clientes foram clusterizados em três níveis:

- Família: classe de veículo (Carro, Moto, Caminhão ou Off-Road)
- Grupo: conjunto de produtos por interesse. Por exemplo, acessórios para lataria e adesivação (“lataria_adesivacao”) inclui cera, adesivos para veiculos, produtos anti-riscos, etc.
- Subgrupo: subdivisão por categorias de produtos. Por exemplo: produtos premium, básico, high-end

Como forma de garantir que as campanhas tiveram um impacto positivo no hábito de consumo dos clientes, uma parte dos clientes de cada campanha foi alocado em **grupos de controle, qu não recebeu as campanhas da ação de CRM**.

## 2. Objetivo

O objetivo deste projeto é apresentar os resultados ao cliente em dashboard, levando em consideração so KPIs selecionados para mostrar os resultados de CRM, de que forma isolar o efeito das campanhas nos resultados auferidos pelos KPIs e se o investimento realizado (em descontos) retornou ao cliente.

## 3. Descrição da Tabela

- 'anomes' - Ano e mês do disparo da campanha (campanhas pode ter sido disparadas em mais de um mês)
- 'codcamp' - Código da campanha
- 'codcliente' - Identificador do cliente
- 'familia' - vide info acima
- 'grupo' - vide info acima,
- 'subgrupo' - vide acima,
- 'gt' - True (pertencente ao grupo que recebe campanha), False (pertencente ao grupo que não recebe campanha - Grupo de Controle)
- 'validade_de' - data de início da campanha,
- 'validade_ate' - data de fim da campanha
- 'fat' - faturamento gerado pelo cliente no período da campanha
- 'fat_bl' - faturamento gerado pelo cliente no mês anterior a campanha (baseline)
- 'lucro' - lucro gerado pelo cliente no período da campanha
- 'lucro_bl' - lucro gerado pelo cliente no mês anterior a campanha (baseline)
- 'custo' - Desconto concedido sobre os produtos promocionados

**Dica:** Caso o cliente com classe gt = “True” não tenha custo, isto significa que o cliente foi a loja porém não usou os descontos recebidos pela campanha.

[LinkedIn](https://www.linkedin.com/in/bibiana-prevedello/)
