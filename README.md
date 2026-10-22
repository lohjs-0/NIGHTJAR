# NIGHTJAR
### Case File 001 — The Stolen Session

> Projeto educacional de investigação digital e Threat Intelligence.
> Todos os eventos e indicadores do cenário são fictícios.

## Overview

NIGHTJAR simula uma investigação de segurança iniciada após a abertura de um anexo suspeito. O exercício explora análise de logs, identificação de indicadores, hashing de evidências e documentação técnica.

## Scenario

Uma organização fictícia, Aster Tecnologia, registra uma sequência de eventos envolvendo um arquivo compactado, a execução de InvoiceViewer.exe, acessos a arquivos e uma conexão de saída.

O objetivo é organizar os eventos, formular hipóteses e documentar os limites das conclusões.

## Evidence

| ID | Artefato | Análise |
|---|---|---|
| E-01 | endpoint_events.log | Filtragem e correlação temporal de eventos simulados |
| E-02 | sample_note.txt | Identificação de tipo, extração de strings e SHA-256 |
| — | ioc_matrix.md | Classificação de indicadores, fatos e hipóteses |
| — | initial_assessment.md | Avaliação técnica preliminar |

## Tools and Techniques

- Kali Linux
- Bash
- grep — filtragem de logs
- awk — extração de campos
- sha256sum — cálculo de hash SHA-256
- file — identificação do tipo de arquivo
- strings — extração de texto legível
- Markdown — documentação técnica

## Key Findings

- A sequência temporal foi extraída e organizada.
- O hash do log foi recalculado e permaneceu idêntico nas verificações realizadas.
- A amostra de treinamento foi identificada como texto ASCII.
- Os indicadores foram classificados com ressalvas e limitações explícitas.

## Limitations

Este projeto utiliza eventos simulados e uma amostra de texto inofensiva. Não foi utilizado nem executado malware real.

O endereço 203.0.113.42 pertence a uma faixa reservada para documentação. Os dados não representam indicadores reais de comprometimento.

Nenhuma conclusão de infecção, roubo de credenciais ou exfiltração real pode ser extraída deste exercício.

## Learning Objectives

- Praticar análise básica de logs em Linux.
- Compreender o uso de hashes para verificar integridade.
- Distinguir fatos observados de hipóteses investigativas.
- Documentar evidências e limitações de forma reproduzível.

## Disclaimer

NIGHTJAR is a fictional educational case study created for defensive cybersecurity learning. It does not describe a confirmed real-world incident.
