## Desafio

Agora, para testar seus conhecimentos em lógica computacional utilizando conceitos de entradas e saídas, atribuição de variáveis e concatenação de Strings, vamos desenvolver uma solução algorítmica que simule o comportamento de um agendamento de pagamento. Buscando auxiliar os clientes de um sistema bancário a agendar seus pagamentos recorrentes, o programa deverá solicitar ao usuário informações sobre a conta a ser paga, como o nome do beneficiário, o valor da conta a ser paga e a data de vencimento. Em seguida, o programa fornecerá uma mensagem de confirmação do agendamento com as informações fornecidas.

## Entrada

O programa deve solicitar as seguintes informações:

    1.Nome do beneficiário.

    2.Valor a ser pago (em reais, sem casas decimais).

    3.Data de vencimento no formato "DD/MM/AAAA" (Dia, Mês e Ano separados por barras).

## Saída

"Pagamento Agendado! Valor: R$ [Valor da Conta], vencimento [Data de Vencimento]."

| Entrada | Saída|
| ---|--- |
| Sabrina 5000 04/12/2023 | Pagamento Agendado! Valor: R$ 5000, vencimento 04/12/2023. |
| Fabio 300 14/01/2023 | Pagamento Agendado! Valor: R$ 300, vencimento 14/01/2023. |
| Marcelo 1000 31/12/2023 | Pagamento Agendado! Valor: R$ 1000, vencimento 31/12/2023. |

```
let nomeBeneficiario;
let valorConta;
let dataVencimento;

// Neste bloco, temos as funções gets para ler os valores de entrada:
nomeBeneficiario = gets();
valorConta = parseFloat(gets());
dataVencimento = gets();

// TODO: Imprima a saída adequada utilizando o conceito de template strings:
```