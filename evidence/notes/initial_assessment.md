# NIGHTJAR — Avaliação Técnica Inicial

## Resumo executivo
O cenário simulado descreve a abertura de um arquivo compactado, seguida pelo início de um processo, eventos de acesso a arquivos e uma conexão de saída. A sequência merece investigação, mas os registros foram criados para fins educacionais e não representam um incidente real.

## Avaliação técnica
A proximidade temporal entre a abertura do anexo e o início de InvoiceViewer.exe sugere uma possível relação entre os eventos. O acesso a configurações de aplicativos e a conexão de saída também mereceriam validação em uma investigação real.

## Nível de confiança
Baixo para qualquer conclusão sobre comportamento malicioso, pois a análise utiliza exclusivamente dados simulados e uma amostra de texto inofensiva.

## O que falta investigar em um caso real
- Identificar o caminho, a origem e a assinatura digital do executável.
- Correlacionar o processo com os eventos de rede.
- Examinar registros de DNS, conexões e processos relacionados.
- Verificar se houve acesso efetivo a credenciais ou transferência de dados sensíveis.
- Preservar as evidências originais e registrar a cadeia de custódia.

## Conclusão
O cenário apresenta uma sequência de eventos potencialmente suspeita, mas não comprova infecção, roubo de credenciais ou exfiltração. A conclusão deve permanecer inconclusiva até que existam evidências adicionais e verificáveis.

## Escopo e ressalva
NIGHTJAR é um exercício fictício de análise de logs e documentação técnica. Nenhum malware real foi utilizado ou executado.
