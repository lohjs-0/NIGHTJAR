# NIGHTJAR — Matriz de Indicadores

Todos os eventos abaixo são fictícios e fazem parte de um exercício educacional.

| Indicador | Tipo | Origem | Avaliação |
|---|---|---|---|
| InvoiceViewer.exe | Nome de processo | Log simulado E-01 | Suspeito no contexto; não confirmado como malware |
| Documento_Fiscal_1022.zip | Nome de arquivo | Log simulado E-01 | Anexo associado à sequência investigada |
| 203.0.113.42 | Endereço IPv4 | Log simulado E-01 | Faixa reservada para documentação; não é um IOC público real deste caso |
| 203.0.113.42:443 | Destino de rede | Log simulado E-01 | Conexão de saída simulada; o uso de HTTPS não foi confirmado |
| 184 KB | Volume de saída | Log simulado E-01 | Volume registrado no cenário; conteúdo transmitido desconhecido |

## Fatos registrados no cenário
- O anexo foi aberto às 09:21:03.
- O processo InvoiceViewer.exe foi iniciado às 09:22:17.
- O log registra acessos a arquivos e uma conexão de saída.
- O volume de saída registrado foi de 184 KB.

## Hipóteses a investigar
- O processo pode ter sido iniciado em consequência da abertura do anexo.
- A conexão pode estar relacionada ao processo.
- O volume de saída pode representar uma transferência de dados.

## Limitações
Os eventos são simulados. Não existe amostra maliciosa real associada ao exercício.
Não há evidência suficiente para afirmar roubo de credenciais ou exfiltração.
O endereço 203.0.113.42 pertence a uma faixa reservada para documentação.
