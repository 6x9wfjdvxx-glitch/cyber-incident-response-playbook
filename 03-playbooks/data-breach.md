# Playbook de Resposta a Incidentes de Vazamento de Dados
## Objetivo
Estabelecer procedimentos para identificação, contenção, investigação e resposta a incidentes relacionados ao vazamento de dados.

##Critérios de Acionamento
Este playbook deve ser acionado quando:

- Dados confidenciais forem expostos.
- Houver compartilhamento indevido de informações.
- Um sistema apresentar evidências de exfiltração de dados.
- For identificado acesso não autorizado a informações sensíveis.

  
## Classificação
- Baixa: Exposição limitada sem impacto relevante.
- Média: Dados internos comprometidos.
- Alta: Dados sensíveis comprometidos.
- Crítica: Dados regulados ou de clientes comprometidos.

  
## Fluxo de Resposta
- Detecção
- Triagem
- Contenção
- Investigação
- Avaliação de Impacto
- Recuperação
- Lições Aprendidas

  
## Contenção
- Revogar acessos indevidos.
- Interromper compartilhamentos públicos.
- Bloquear contas comprometidas.
- Preservar evidências.

  
## Investigação
Verificar:

- Dados afetados.
- Origem do incidente.
- Usuários impactados.
- Possível exfiltração.

  
## Avaliação de Impacto
Analisar:

- Dados pessoais envolvidos.
- Requisitos LGPD.
- Necessidade de comunicação aos envolvidos.
- Necessidade de notificação regulatória.


## Recuperação
- Corrigir vulnerabilidades.
- Restaurar controles de acesso.
- Validar ambiente.
- Intensificar monitoramento.

  
## Lições Aprendidas
Registrar:

- Causa raiz.
- Impacto observado.
- Melhorias necessárias.
- Plano de ação.

  
## Referências
- NIST SP 800-61 Rev. 3
- ISO 27035
- LGPD
