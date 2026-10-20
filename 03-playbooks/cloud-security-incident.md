# Playbook de Resposta a Incidentes em Ambiente Cloud
## Objetivo
Estabelecer procedimentos para identificação, contenção, investigação e recuperação de incidentes de segurança em ambientes cloud.

# Critérios de Acionamento
Este playbook deve ser acionado quando:

- Houver acesso não autorizado a recursos cloud.
- Credenciais forem comprometidas.
- Recursos forem expostos publicamente indevidamente.
- Houver suspeita de exfiltração de dados em ambiente cloud.


## Classificação
- Baixa: Exposição sem impacto operacional.
- Média: Recurso isolado comprometido.
- Alta: Múltiplos recursos comprometidos.
- Crítica: Dados sensíveis ou serviços críticos afetados.


## Fluxo de Resposta
- Detecção
- Triagem
- Contenção
- Investigação
- Erradicação
- Recuperação
- Lições Aprendidas


## Contenção
- Revogar credenciais comprometidas.
- Restringir acessos suspeitos.
- Isolar recursos afetados.
- Revisar permissões e papéis.


## Investigação
Verificar:

- Logs de acesso.
- Recursos impactados.
- Origem da atividade suspeita.
- Possível exfiltração de dados.
- Alterações realizadas no ambiente.


## Recuperação
- Restaurar configurações seguras.
- Corrigir vulnerabilidades identificadas.
- Validar controles de segurança.
- Reforçar monitoramento contínuo.


## Lições Aprendidas
Registrar:

- Causa raiz.
- Impacto observado.
- Controles ausentes.
- Melhorias recomendadas.


## Referências
- NIST SP 800-61 Rev. 3
- ISO 27035
- Microsoft Defender for Cloud
- Microsoft Sentinel
