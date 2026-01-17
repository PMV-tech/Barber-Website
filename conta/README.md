login.html - Página de Login
Página de autenticação do sistema BarberFlow para acesso dos usuários.

Características Principais
Design moderno com gradiente azul escuro

Contas de teste pré-definidas para demonstração

Formulário de login com validação

Toggle de senha para visibilidade

Links úteis para cadastro e configuração

Contas de Teste Disponíveis
Tipo	E-mail	Senha	Função
👑 Administrador	admin@barberflow.com	123456	Acesso total ao sistema
✂️ Barbeiro	barbeiro@barberflow.com	123456	Gerenciar agendamentos
👤 Cliente	cliente@barberflow.com	123456	Fazer agendamentos
Funcionalidades JavaScript
togglePassword() - Alterna visibilidade da senha

fillCredentials(email, password) - Preenche automaticamente campos

Validação básica do formulário

Redirecionamento para dashboard após login

Layout
Container centralizado com sombra e bordas arredondadas

Logo BarberFlow com ícone de tesoura

Contas de teste destacadas com efeito hover

Formulário com campos obrigatórios

Opções "Lembrar-me" e "Esqueceu senha"

Links para registro, setup e página inicial

Dependências
../style.css - Estilos principais do sistema

../main.js - Scripts globais

Font Awesome 6.4.0 (CDN)

register.html - Página de Cadastro
Página de registro de novos usuários no sistema BarberFlow.

Características Principais
Formulário completo com todos os dados necessários

Validação de senha (mínimo 8 caracteres, confirmação)

Toggle de senha para ambos os campos

Termos de uso com scroll próprio

Seleção de tipo de conta (cliente ou barbeiro)

Campos do Formulário
Nome e Sobrenome - Obrigatórios

E-mail - Obrigatório, validação automática

Senha - Mínimo 8 caracteres, com confirmação

Telefone - Opcional

Tipo de Conta - Cliente ou Barbeiro

Aceitação dos Termos - Obrigatório

Validações
Senhas devem coincidir

Senha mínima de 8 caracteres

Aceitação dos termos obrigatória

Campos obrigatórios marcados com *

Funcionalidades JavaScript
togglePassword(inputId) - Alterna visibilidade por campo

Validação completa do formulário

Redirecionamento para login após cadastro

Layout
Container centralizado igual à página de login

Formulário em grid (2 colunas para nome/senha)

Área de termos com scroll e fundo diferenciado

Checkbox de aceitação dos termos

Links para login e página inicial

Observações
Barbeiros só podem ser cadastrados via seleção (não há cadastro de admin)

Em sistema real, validações seriam mais robustas no backend

Dados são apenas de demonstração (não persistem)

