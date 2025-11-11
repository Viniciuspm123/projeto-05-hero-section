🚀 Projeto 05: A Seção "Hero" de Landing Page (Call-to-Action)
Este projeto demonstra a criação de uma seção "Hero" (topo de página) completa, responsiva e focada em um forte Call-to-Action (CTA), utilizando HTML semântico e CSS moderno.

O objetivo principal desta seção é capturar a atenção do usuário e direcioná-lo para a próxima etapa (clicar no botão "Saiba Mais").

✨ Visão Geral
A seção "Hero" é o primeiro elemento que o usuário vê ao acessar a página.

Título de Impacto: "A Tecnologia que Transforma o Futuro"

Subtítulo de Suporte: Explica a proposta de valor.

Botão CTA: "Saiba Mais" – o foco da ação.

🛠️ Tecnologias Utilizadas
HTML5: Estrutura semântica e metadados otimizados para SEO.

CSS3: Estilização moderna, com uso de Flexbox para centralização e design responsivo (com min-height: 100vh).

📁 Estrutura do Projeto
Para que o projeto funcione corretamente, a estrutura de pastas deve ser a seguinte:

/Projeto-05-Hero-Section/
├── index.html
├── README.md (Este arquivo)
├── css/
│   └── style.css
└── assets/
    ├── logo.png             (Favicon)
    └── gradiente-colors.jpg (Imagem de fundo)
⚙️ Como Configurar e Visualizar
Siga estes passos simples para rodar o projeto localmente:

Clone ou Baixe: Baixe o conteúdo deste repositório (ou crie os arquivos conforme o código fornecido) em uma pasta local.

Organize os Assets: Certifique-se de que o arquivo de imagem de fundo (gradiente-colors.jpg) e o favicon (logo.png) estão dentro da pasta assets/.

Abra o HTML: Abra o arquivo index.html diretamente no seu navegador.

Live Server (Recomendado): Se você estiver usando o VS Code, utilize a extensão "Live Server" para visualizar as alterações em tempo real.

🔑 Destaques do CSS
O arquivo style.css utiliza as seguintes técnicas avançadas para a criação da seção Hero:

Centralização Perfeita:

CSS

.hero-section {
    display: flex;
    align-items: center; /* Centraliza verticalmente */
    justify-content: center; /* Centraliza horizontalmente */
    min-height: 100vh; /* Ocupa 100% da altura da tela */
}
Contraste e Legibilidade: Utiliza texto branco (#ffffff) sobre um fundo escuro (#000000 / imagem de fundo), e limita a largura do conteúdo (max-width: 700px) para melhorar a leitura em telas grandes.

Efeito CTA (Call-to-Action): O botão (.hero-button) utiliza transições (transition: 0.3s) e o efeito transform: translateY(-2px) no hover para criar um feedback visual suave e incentivar o clique.

Criado por Vinicius Marques.
