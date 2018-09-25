# Machine_Learning_Classificacao
Classificação 

Para este projeto, exploraremos os dados disponíveis publicamente em LendingClub.com. O Lending Club conecta pessoas que precisam de dinheiro (mutuários) às pessoas que têm dinheiro (investidores). Um investidor, deseja investir apenas em pessoas que tenham um perfil de alta probabilidade para pagar de volta. Vamos tentar criar um modelo que ajude a prever isso.

Usaremos dados de empréstimos de 2007-2010 e tentaremos classificar e prever se o devedor pagou ou não o empréstimo na íntegra.

Aqui está o que as colunas representam:

credit.policy: 1 se o cliente atender aos critérios de subscrição de crédito de LendingClub.com e 0 caso contrário.
propósito: A motivação para o empréstimo (recebe os valores "credit_card", "debt_consolidation", "educational", "major_purchase", "small_business" e "all_other").
int.rate: A taxa de juros do empréstimo, como proporção (uma taxa de 11% seria armazenada como 0,11). Os mutuários julgados pela LendingClub.com como sendo mais arriscados recebem taxas de juros mais altas.
parcela: as parcelas mensais devidas pelo mutuário, se o empréstimo for financiado.
log.annual.inc: O logaritmo natural da renda anual autorreferida do mutuário.
dti: O rácio dívida / rendimento do mutuário (montante da dívida dividido pelo rendimento anual).
fico: A pontuação de crédito do mutuário.
days.with.cr.line: O número de dias que o mutuário teve uma linha de crédito.
revol.bal: o saldo rotativo do mutuário (quantia não paga no final do ciclo de faturamento do cartão de crédito).
revol.util: A taxa de utilização da linha de crédito do tomador (o valor da linha de crédito utilizada em relação ao crédito total disponível).
inq.last.6mths: O número de pedidos do mutuário aos credores nos últimos 6 meses.
delinq.2yrs: O número de vezes que o mutuário tinha 30 ou mais dias de atraso em um pagamento nos últimos 2 anos.
pub.rec: O número de registros públicos depreciativos do mutuário (pedidos de falência, penhoras fiscais ou julgamentos).
