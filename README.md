Documentação do Componente de Rodapé (Footer)

Este documento detalha a estrutura, tecnologias e instruções de integração do componente de rodapé (footer) desenvolvido para o projeto acadêmico de HTML. O componente foi projetado com foco em responsividade, semântica e facilidade de manutenção.

Tecnologias Utilizadas

HTML5: Empregado para a marcação semântica estrutural (utilização de tags como , ,  e ).

CSS3: Utilizado para a estilização do componente. O layout foi construído utilizando o módulo Flexbox, garantindo a adaptação adequada do conteúdo em diferentes resoluções de tela.

Estrutura do Componente

O rodapé está organizado em uma estrutura de contêineres flexíveis, dividido nas seguintes seções:

Sobre o Projeto: Bloco de texto destinado a uma breve descrição do escopo do site.

Links Úteis: Menu de navegação secundária para as páginas principais.

Contato: Lista de links para e-mail corporativo/acadêmico e perfis em redes sociais.

Direitos Autorais (Copyright): Barra inferior contendo o ano de vigência e os direitos reservados da equipe.

Instruções de Integração

Para incorporar este componente ao projeto principal, siga as etapas abaixo:

Estilização (CSS):
Extraia o bloco de código contido entre as tags <style> do arquivo fornecido e insira-o no arquivo CSS principal do projeto, ou na respectiva seção de estilos do cabeçalho (<head>).

Estrutura (HTML):
Copie integralmente o elemento <footer class="site-footer"> até o seu fechamento </footer>.

Posicionamento:
Cole o código HTML extraído no final do documento principal, imediatamente antes do fechamento da tag </body>, assegurando que ele suceda o conteúdo da tag <main>.

Diretrizes de Customização

O código foi parametrizado de forma simples para facilitar alterações visuais. Para modificar o esquema de cores:

Cor de fundo principal: Altere o valor da propriedade background-color na classe .site-footer.

Cor da fonte principal: Altere o valor da propriedade color na classe .site-footer.

Cor de destaque (Hover e sublinhados): Altere a cor das propriedades nas classes .footer-section h3 (border-bottom) e .footer-section ul li a:hover (color).
