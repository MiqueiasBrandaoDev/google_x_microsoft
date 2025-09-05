# PLANO DE MIGRAÇÃO - Microsoft 365 para Google Workspace

## CONTEXTO
- **Domínio atual:** camozziconsultoria.com.br
- **Novo domínio:** cedblindagemdigital.com.br
- **Objetivo:** Migração completa do Microsoft 365 para Google Workspace

---

## ETAPAS DA MIGRAÇÃO

### FASE 1: PREPARAÇÃO E FERRAMENTAS

#### 1. Contratar/avaliar ferramentas necessárias para migração
- Ferramentas de backup (Teams, SharePoint, Exchange)
- Ferramentas de migração de dados
- Softwares auxiliares para conversão de arquivos

#### 2. Fazer backup completo do Teams (conversas e arquivos)
- Exportar todas as conversas dos canais
- Backup de arquivos compartilhados no Teams
- **Importante:** Conversas do Teams ficarão apenas no backup (não serão migradas)

#### 3. Fazer backup completo dos emails (Outlook/Exchange)
- Exportar todas as caixas de correio
- Incluir pastas, regras e configurações
- Backup de calendários e contatos

#### 4. Fazer backup completo do SharePoint (documentos e estrutura)
- Backup de todos os sites e bibliotecas
- Preservar estrutura de permissões
- Documentar organização atual

---

### FASE 2: CONTRATAÇÃO E CONFIGURAÇÃO GOOGLE

#### 5. Contratar plano Google Workspace adequado
- Avaliar quantidade de usuários
- Escolher plano com storage suficiente
- Considerar funcionalidades necessárias

#### 6. Configurar domínio cedblindagemdigital.com.br no Google Workspace
- Verificação de domínio
- Configuração DNS
- Ativação dos serviços

---

### FASE 3: ESTRUTURAÇÃO NO GOOGLE

#### 7. Recriar estrutura organizacional no Google Drive (equivalente ao SharePoint)
- Reproduzir organização de pastas
- Configurar unidades compartilhadas
- Estabelecer hierarquia de permissões

#### 8. Migrar emails do Microsoft 365 para Gmail
- Usar ferramenta de migração do Google
- Preservar histórico e organização
- Migrar contatos e calendários

#### 9. Migrar arquivos do SharePoint para Google Drive
- Transferir documentos mantendo estrutura
- Verificar tipos de arquivo suportados
- Ajustar permissões no novo ambiente

---

### FASE 4: CONFIGURAÇÃO COMPLETA

#### 10. Configurar todas as ferramentas Google (Calendar, Meet, etc.)
- Google Calendar (substituir Outlook Calendar)
- Google Meet (substituir Teams para reuniões)
- Google Chat (comunicação interna)
- Outras ferramentas necessárias

#### 11. Configurar políticas de segurança no Google Workspace
- Políticas de senha
- Autenticação de dois fatores
- Controles de compartilhamento
- Backup automático

---

### FASE 5: MIGRAÇÃO DE USUÁRIOS

#### 12. Migrar usuários e configurar permissões
- Criar contas de usuário
- Configurar grupos e permissões
- Treinar equipe nas novas ferramentas

#### 13. Período de testes paralelos antes da migração final
- Testar funcionalidades críticas
- Validar acessos e permissões
- Período de adaptação da equipe

---

### FASE 6: FINALIZAÇÃO

#### 14. Configurar servidor de email ponte (camozziconsultoria.com.br)
- Contratar catch-all na Hostinger
- Configurar redirecionamentos automáticos
- Manter domínio antigo como ponte de emails

#### 15. Testes finais e validação da migração
- Verificar funcionamento completo
- Validar todos os dados migrados
- Confirmar que todos os usuários estão operacionais

---

## OBSERVAÇÕES IMPORTANTES

- **Conversas do Teams:** Apenas backup, não serão migradas
- **Emails:** Migração completa com histórico
- **SharePoint:** Estrutura será recriada no Google Drive
- **Domínio antigo:** Permanecerá como ponte para emails
- **Treinamento:** Necessário para adaptação às ferramentas Google

---

## CRONOGRAMA ESTIMADO
- **Fases 1-2:** 1-2 semanas
- **Fases 3-4:** 2-3 semanas  
- **Fases 5-6:** 1-2 semanas
- **Total:** 4-7 semanas (dependendo da complexidade dos dados)