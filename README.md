# Projeto_Segmentacao_Clientes


# Segmentação de Clientes - Departamento de Marketing

###Entendimento do Negócio


.

Desenvolveremos a segmentação de clientes de um banco, em pelo menos 4 grupos, para definir melhores estratégias de marketing de acordo com cada perfil. Utilizaremos nesse projeto a técnica de agrupamento (clustering) com o algoritmo K-Means, para agrupar esses clientes de acordo com características parecidas.

.

O conjunto de dados de amostra resume o comportamento de uso de cerca de 9.000 titulares de cartão de crédito ativos durante os últimos 6 meses. O arquivo está no nível do cliente com 18 variáveis ​​comportamentais.

- Dados: https://www.kaggle.com/arjunbhasin2013/ccdata

.

A seguir está o dicionário de dados para o conjunto de dados do cartão de crédito:

.

**CUST_ID:** Identificação do cliente

**BALANCE:** Saldo para fazer compras

**BALANCE_FREQUENCY:** Com que frequência o Saldo é atualizado, pontuação entre 0 e 1 (1 = atualizado com frequência, 0 = não atualizado com frequência)

**PURCHASES:** Quantidade de compras realizadas

**ONEOFF_PURCHASES:** Quantidade de compras feitas à vista

**INSTALLMENTS_PURCHASES:** Quantidade de compras parceladas

**CASH_ADVANCE:** Dinheiro adiantado

**PURCHASES_FREQUENCY:** Frequência das compras, entre 0 e 1 (1 = comprado com frequência, 0 = não comprado com frequência)

**ONEOFF_PURCHASES_FREQUENCY:** Frequência de compras à vista (1 = comprado com frequência, 0 = não comprado com frequência)

**PURCHASES_INSTALLMENTS_FREQUENCY:** Frequência de compras parceladas (1 = frequentemente feito, 0 = não feito com frequência)

**CASH_ADVANCE_FREQUENCY:** Frequência de saques de dinheiro adiantado

**CASH_ADVANCE_TRX:** Número de transações feitas com "Cash in Advanced"

**PURCHASES_TRX:** Número de compras

**CREDIT_LIMIT:** Limite do cartão de crédito

**PAYMENTS:** Valor pago

**MINIMUM_PAYMENTS:** valor mínimo pago

**PRC_FULL_PAYMENT:** Percentual de pagamentos da fatura "completa"

**TENURE:** Posse do titular do cartão
