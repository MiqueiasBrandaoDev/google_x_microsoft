# PLANO DE MIGRAÇÃO - Microsoft 365 para Google Workspace

## CONTEXTO
- **Domínio atual:** camozziconsultoria.com.br
- **Novo domínio:** cedblindagemdigital.com.br
- **Objetivo:** Migração completa do Microsoft 365 para Google Workspace

---

## ETAPAS DA MIGRAÇÃO

### FASE 1: CONTRATAÇÕES NECESSÁRIAS

#### 1. Contratar todas as ferramentas necessárias
**Hostinger - Business Starter Email:**
- Plano: Business Starter
- 6 usuários: R$ 3,49 cada = R$ 20,94/mês (promocional 12 meses)
- Renovação: R$ 7,99 cada = R$ 47,94/mês a cada 4 anos
- Funcionalidade: Catch-all para camozziconsultoria.com.br

**Google Workspace Business Standard:**
- 6 usuários: R$ 81,80 cada = R$ 490,80/mês
- 2TB de armazenamento por usuário
- IA Gemini avançada incluída
- Meet com gravação, assinatura eletrônica

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

### FASE 2: CONFIGURAÇÃO GOOGLE WORKSPACE

#### 5. Configurar domínio cedblindagemdigital.com.br no Google Workspace
- Verificação de domínio
- Configuração DNS
- Ativação dos serviços

---

### FASE 3: ESTRUTURAÇÃO NO GOOGLE

#### 6. Recriar estrutura organizacional no Google Drive (equivalente ao SharePoint)
- Reproduzir organização de pastas
- Configurar unidades compartilhadas
- Estabelecer hierarquia de permissões

#### 7. Migrar emails do Microsoft 365 para Gmail
- Usar ferramenta de migração do Google
- Preservar histórico e organização
- Migrar contatos e calendários

#### 8. Migrar arquivos do SharePoint para Google Drive
- Transferir documentos mantendo estrutura
- Verificar tipos de arquivo suportados
- Ajustar permissões no novo ambiente

---

### FASE 4: CONFIGURAÇÃO COMPLETA

#### 9. Configurar todas as ferramentas Google (Calendar, Meet, etc.)
- Google Calendar (substituir Outlook Calendar)
- Google Meet (substituir Teams para reuniões)
- Google Chat (comunicação interna)
- Outras ferramentas necessárias

#### 10. Configurar políticas de segurança no Google Workspace
- Políticas de senha
- Autenticação de dois fatores
- Controles de compartilhamento
- Backup automático

---

### FASE 5: MIGRAÇÃO DE USUÁRIOS

#### 11. Migrar usuários e configurar permissões
- Criar contas de usuário
- Configurar grupos e permissões
- Treinar equipe nas novas ferramentas

#### 12. Período de testes paralelos antes da migração final
- Testar funcionalidades críticas
- Validar acessos e permissões
- Período de adaptação da equipe

---

### FASE 6: FINALIZAÇÃO

#### 13. Configurar servidor de email ponte (camozziconsultoria.com.br) na Hostinger
- Ativar catch-all na Hostinger (já contratado na etapa 1)
- Configurar redirecionamentos automáticos
- Manter domínio antigo como ponte de emails

#### 14. Testes finais e validação da migração
- Verificar funcionamento completo
- Validar todos os dados migrados
- Confirmar que todos os usuários estão operacionais

#### 15. Cancelar ferramentas antigas
- Cancelar licenças Microsoft 365 (12 usuários + Ana Luiza)
- Cancelar assinatura ChatGPT
- **Economia total**: R$ 595,68/mês → R$ 511,74/mês = **R$ 83,94/mês**

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