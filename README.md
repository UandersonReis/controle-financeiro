# Meu Financeiro — Web V26

Correção do importador para o PDF real do Bradesco.

- identifica Bradesco pelo layout mesmo quando o nome do banco não aparece no texto do PDF;
- entende a sequência DIA → LANÇAMENTO/VALOR → MÊS usada na fatura;
- mantém lançamentos subsequentes na mesma data;
- identifica cartões finais e parcelas;
- pagamentos e saldo anterior não entram como despesas.
