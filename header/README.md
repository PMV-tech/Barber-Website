header.html - Cabeçalho do Sistema
Arquivo HTML que define a estrutura básica do cabeçalho para todas as páginas do sistema BarberFlow.

🎯 Propósito
Prover uma base consistente para todas as páginas do sistema, incluindo configurações essenciais, estilos globais e recursos compartilhados.

🔧 Elementos Principais
1. Metatags Essenciais
charset="UTF-8" - Suporte a caracteres especiais

viewport - Responsividade para dispositivos móveis

Título dinâmico (preenchido por cada página)

2. Folhas de Estilo
../style.css - Estilos principais do sistema

Font Awesome 6.4.0 (CDN) - Ícones para toda a interface

Estilos inline específicos para otimização

3. Variáveis CSS Personalizadas
css
:root {
    --primary-color: #1a1a2e;    /* Azul escuro */
    --secondary-color: #16213e;  /* Azul mais escuro */
    --accent-color: #4cc9f0;     /* Azul claro/accent */
}
4. Animações CSS
fadeIn - Fade in para elementos

slideDown - Deslizar para baixo

Classes utilitárias: .fade-in, .slide-down

5. Customização da Scrollbar
Largura: 8px

Track: Cinza claro

Thumb: Azul claro (accent-color)

Hover: Azul mais escuro

Bordas arredondadas

🎨 Sistema de Cores
Nome	Código	Uso
Primary	#1a1a2e	Fundos principais, títulos
Secondary	#16213e	Gradientes, elementos secundários
Accent	#4cc9f0	Botões, links, destaques
⚡ Otimizações de Performance
Font Awesome via CDN - Cache global, carregamento rápido

CSS inline essencial - Reduz requests HTTP

Variáveis CSS - Manutenção facilitada

Scrollbar customizada - Experiência consistente

🔄 Como Usar
Incluir em todas as páginas:

html
<!DOCTYPE html>
<html lang="pt-br">
<!-- header.html começa aqui -->
<!-- Conteúdo específico da página -->
<!-- footer.html termina aqui -->
</html>
Utilizar classes utilitárias:

html
<div class="fade-in slide-down">Conteúdo animado</div>
Usar variáveis CSS:

css
.element {
    color: var(--accent-color);
    background: var(--primary-color);
}
📱 Responsividade
Viewport otimizado para dispositivos móveis

Unidades relativas (rem/em)

Breakpoints definidos no style.css principal

🛡️ Considerações Técnicas
Compatibilidade: HTML5 válido, suporte a navegadores modernos

Performance: CSS inline mínimo para renderização rápida

Manutenção: Variáveis centralizadas para fácil alteração

Acessibilidade: Estrutura semântica básica

🔗 Dependências Externas
Font Awesome: Ícones da interface (v6.4.0)

../style.css: Estilos principais do sistema

Observação: Este arquivo deve ser combinado com footer.html para formar uma página HTML completa.

