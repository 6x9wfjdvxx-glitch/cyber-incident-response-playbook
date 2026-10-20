# Playbook de Resposta a Incidentes de Phishing
## Objetivo
Estabelecer procedimentos padronizados para identificar, conter, erradicar e recuperar incidentes relacionados a phishing.

## Critérios de Acionamento
Este playbook deve ser acionado quando:

- Um usuário reportar e-mail suspeito.
- Houver alerta do Microsoft Defender.
- Credenciais forem inseridas em página maliciosa.
- Malware for distribuído por e-mail.
  
 
## Classificação
Severidade	Critério 

Baixa	      | E-mail recebido sem interação 

Média	      | Clique em link malicioso 

Alta        | Credenciais comprometidas

Crítica     | Múltiplas contas afetadas

## Fluxo de Resposta
Detecção
↓
Triagem
↓
Contenção
↓
Investigação
↓
Erradicação
↓
Recuperação
↓
## Lições Aprendidas
Contenção
Bloquear remetente
Remover e-mails da organização
Revogar sessões ativas
Redefinir senha do usuário afetado
Validar MFA
Investigação
Verificar:

## Usuários afetados
Evidências de acesso indevido
Download de arquivos maliciosos
Movimentação lateral
Recuperação
Restaurar acesso do usuário
Validar integridade do ambiente
Reforçar monitoramento
## Lições Aprendidas
Registrar:

Causa raiz
Controles ausentes
Melhorias necessárias
Plano de ação
Referências
NIST SP 800-61 Rev. 3
NIST Cybersecurity Framework 2.0
ISO 27035
