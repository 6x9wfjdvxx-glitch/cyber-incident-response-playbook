# Playbook de Resposta a Comprometimento de Conta Privilegiada
## Objetivo
Estabelecer procedimentos para identificar, conter, investigar e recuperar incidentes relacionados ao comprometimento de contas privilegiadas.

## Critérios de Acionamento
Este playbook deve ser acionado quando:

- Uma conta administrativa apresentar comportamento suspeito.
- Houver login privilegiado não autorizado.
- Forem detectadas alterações críticas não autorizadas.
- For identificado uso indevido de privilégios administrativos.


## Classificação
- Baixa: Tentativa de acesso sem sucesso.
- Média: Acesso privilegiado restrito a um sistema.
- Alta: Múltiplos sistemas afetados.
- Crítica: Comprometimento de administradores corporativos.


## Fluxo de Resposta
- Detecção
- Triagem
- Contenção
- Investigação
- Erradicação
- Recuperação
- Lições Aprendidas


## Contenção
- Bloquear a conta comprometida.
- Revogar sessões ativas.
- Redefinir credenciais.
- Revisar permissões atribuídas.
- Acionar equipe de segurança.

  
## Investigação
Verificar:

- Origem do acesso.
- Data e hora da atividade.
- Sistemas acessados.
- Alterações realizadas.
- Possível movimentação lateral.


## Recuperação
- Restaurar permissões corretas.
- Validar integridade dos sistemas.
- Reforçar MFA.
- Atualizar controles de monitoramento.


## Lições Aprendidas
Registrar:

- Causa raiz.
- Controles falhos.
- Impacto do incidente.
- Plano de remediação.


## Referências
- NIST SP 800-61 Rev. 3
- ISO 27035
- Microsoft Entra ID Security Best Practices
