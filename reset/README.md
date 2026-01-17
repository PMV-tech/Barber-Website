reset_sistema.html - Página de Reset do Sistema
Página administrativa para reinicialização completa do sistema BarberFlow com dados de exemplo.

⚠️ AVISO CRÍTICO
Operação destrutiva - Apaga todos os dados existentes e recria o sistema do zero.

🎯 Funcionalidade
Reinicializa o banco de dados com:

Remoção total dos dados atuais

Recriação da estrutura do banco

População com dados de exemplo para testes

🔒 Múltiplas Camadas de Confirmação
1. Campo de Confirmação Textual
Digitar "RESETAR" (maiúsculas)

Validação em tempo real

Feedback visual (vermelho/verde)

2. Checkboxes de Confirmação
✅ Fiz backup dos dados importantes

✅ Entendo que não pode ser desfeito

3. Modal de Confirmação Final
Última chance antes da execução

Mensagem de alerta dramática

Requer clique manual de confirmação

📋 Etapas do Processo de Reset
🔴 1. Apagar Dados Atuais
Remoção de todos os registros

Agendamentos, clientes, usuários

Limpeza completa do banco

🟡 2. Reinicializar Banco
Recriação das tabelas

Estrutura limpa e otimizada

Configurações padrão aplicadas

🟢 3. Criar Dados de Exemplo
Usuários: Admin, Barbeiro, Cliente

Clientes fictícios

Agendamentos de demonstração

Serviços variados

⚡ Funcionalidades de Segurança
checkConfirmation() - Validação em tempo real

performReset() - Processo controlado com delays

Estado do botão dinâmico (habilitado/desabilitado)

Simulação de loading durante execução

Redirecionamento para login após conclusão

🎨 Design e UX
Ícone de alerta grande (64px)

Cores de alerta: Amarelo (#ffc107) e Vermelho (#dc3545)

Seções destacadas com bordas coloridas

Passos visuais com ícones específicos

Campo de confirmação com estilo dramático

🔄 Alternativas Sugeridas
🔧 Reconfigurar - Setup personalizado

🗄️ Ver Banco - Inspeção da estrutura

👤 Meu Perfil - Gerenciamento individual

⚡ Fluxo do Usuário
Leitura dos avisos e consequências

Digitação de "RESETAR" no campo

Marcação das checkboxes de confirmação

Habilitação do botão de reset

Confirmação final via modal

Processamento com feedback visual

Redirecionamento automático

📱 Responsividade
Layout centralizado em todas as telas

Elementos empilhados em mobile

Tamanhos de fonte adequados

Espaçamentos otimizados

🛡️ Considerações de Segurança
Apenas demonstração: Em produção, adicionar autenticação

Proteção adicional: Verificar tipo de usuário (apenas admin)

Logging: Registrar ações de reset

IP restriction: Limitar acesso por IP em produção

💡 Cenários de Uso
Desenvolvimento: Reset rápido para testes

Demonstração: Clientes/Stakeholders

Treinamento: Novos administradores

Debugging: Solução de problemas críticos

Nota Crítica: Esta página NÃO deve ser acessível em ambiente de produção sem autenticação forte e logs de auditoria. Em produção, considere métodos alternativos como migrações de banco de dados.

