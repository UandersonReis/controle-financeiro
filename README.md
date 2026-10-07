# Meu Financeiro — Web V23

## Novidade principal
Importação de faturas por Excel (`.xlsx` / `.xls`), além de PDF e imagens.

### Itaú — fatura aberta
A V23 reconhece a planilha de fatura aberta do Itaú, identifica automaticamente:
- banco;
- situação da fatura (aberta/fechada);
- competência da fatura;
- final do cartão quando disponível;
- compras e parcelas;
- pagamentos e créditos/estornos.

Os pagamentos não são gravados como novas despesas. Em faturas abertas, os lançamentos recebem a competência da própria fatura (por exemplo, Outubro/2026), mesmo que a compra tenha ocorrido no fim de setembro.

A importação continua exibindo revisão antes de gravar e mantém a proteção contra duplicidades.

> Dados financeiros permanecem no navegador do usuário; não grave faturas ou backups no repositório GitHub.
