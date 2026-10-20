# Playbook de Resposta a Incidentes de Ransomware
## Objetivo
Estabelecer procedimentos para identificação, contenção, erradicação e recuperação de incidentes relacionados a ransomware.

## Critérios de Acionamento
Este playbook deve ser acionado quando:

- Arquivos forem criptografados.
- Nota de resgate for encontrada.
- Alertas de ransomware forem gerados pelo EDR.
- Houver comportamento anômalo de criptografia em massa.


## Classificação
- Baixa: Um único dispositivo afetado.
- Média: Até 10 dispositivos afetados.
- Alta: Área de negócio impactada.
- Crítica: Sistemas corporativos indisponíveis.

  
## Fluxo de Resposta
- Detecção
- Triagem
- Contenção
- Investigação
- Erradicação
- Recuperação
- Lições Aprendidas

  
## Contenção
- Isolar equipamento afetado.
- Bloquear comunicação de rede.
- Revogar acessos suspeitos.
- Acionar equipe de resposta a incidentes.

  
## Investigação
Verificar:

- Vetor inicial de infecção.
- Usuários afetados.
- Sistemas comprometidos.
- Evidências de movimentação lateral.

  
## Recuperação
- Restaurar backups confiáveis.
- Validar integridade dos sistemas.
- Aplicar correções necessárias.
- Reforçar monitoramento.

  
## Lições Aprendidas
Registrar:

- Causa raiz.
- Impactos observados.
- Controles ausentes.
- Plano de melhoria.

  
## Referências
- NIST SP 800-61 Rev. 3
- ISO 27035
