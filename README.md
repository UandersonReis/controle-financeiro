# Meu Financeiro — Web V19

Correção estrutural do importador:
- sem seleção manual de banco/mês/ano;
- identifica banco e finais de cartão no documento;
- lê PDF textual e usa OCR em imagem/PDF digitalizado;
- separa compra, pagamento, saldo anterior e estorno/crédito;
- reconhece parcelamentos;
- revisão obrigatória antes de importar;
- pagamentos e saldo anterior não entram como despesas.

A aplicação continua usando armazenamento local até a etapa de login/nuvem.
