# Explorando IA Generativa em um Pipeline de ETL com Python

Este repositório foi dividido em duas etapas. A primeira etapa se refere ao projeto [Santander Dev Week](https://github.com/LuuhMitre/pipeline_ETL_explorando_IA_generativa/tree/24c0b6bd6de54bafb25ce370f34316e7661fcd84/santander_dev_week), desenvolvido durante o acompanhamento às aulas do professor [Venilton FalvoJr](https://github.com/falvojr). 

A segunda etapa se refere ao desafio de projeto solicitado no final do módulo **Explorando IA Generativa em um Pipeline de ETL com Python**. 

O projeto [Pedidos](https://github.com/LuuhMitre/pipeline_ETL_explorando_IA_generativa/tree/24c0b6bd6de54bafb25ce370f34316e7661fcd84/desafio_de_projeto) está subdivido nas etapas:

- **EXTRACT**: Nesta etapa foram extraídos os dados do arquivo [pedidos.csv](https://github.com/LuuhMitre/pipeline_ETL_explorando_IA_generativa/blob/24c0b6bd6de54bafb25ce370f34316e7661fcd84/desafio_de_projeto/pedidos.csv), obtendo as colunas:
    - idOrder
    - costumerName
    - orderStatus
    - deliveryTime
    - statusMessage

- **TRANSFORM**: Nesta etapa é gerado uma *Mensagem de Status*, onde é informado a etapa em que o pedido se encontra e o prazo estimado de entrega.

- **LOAD**: Nesta etapa a coluna *statusMessage* é atualizada com a *Mensagem de Status* gerada na etapa **TRANSFORM**
