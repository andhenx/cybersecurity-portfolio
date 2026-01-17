\# Incident Response – Unauthorized Access Simulation



\## Executive Summary

Este projeto simula a investigação e resposta a um incidente de segurança envolvendo

tentativas de acesso não autorizado a um servidor corporativo.

O objetivo é demonstrar habilidades de análise, documentação e resposta a incidentes.



\## Incident Details

\- \*\*Tipo de incidente:\*\* Unauthorized Access / Brute Force

\- \*\*Sistema afetado:\*\* Servidor Linux

\- \*\*Fonte do alerta:\*\* Logs de autenticação

\- \*\*Severidade:\*\* Média



\## Timeline

\- 10:02 – Detecção de múltiplas tentativas de login falhas

\- 10:05 – Identificação de IP suspeito

\- 10:10 – Bloqueio do IP no firewall

\- 10:15 – Análise de impacto

\- 10:25 – Incidente contido



\## Investigation

Foram analisados logs de autenticação para identificar padrões anormais de acesso,

como múltiplas falhas de login em curto período de tempo.



\## Containment and Eradication

\- Bloqueio do IP de origem

\- Revisão de credenciais

\- Reforço das políticas de autenticação



\## Lessons Learned

\- Importância do monitoramento contínuo

\- Necessidade de alertas automatizados

\- Uso de autenticação multifator



