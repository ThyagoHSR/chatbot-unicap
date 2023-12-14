
Documentação do Projeto Chatbot Unicap
1. Introdução
Bem-vindo à documentação do projeto Chatbot Unicap! Este documento fornece informações essenciais para entender, configurar e implantar o chatbot desenvolvido para a Faculdade Unicap. Este projeto é parte integrante do Trabalho de Conclusão de Curso (TCC) e utiliza a plataforma Typebot para implementação.

2. Estrutura do Projeto
O projeto consiste em uma página HTML que incorpora o chatbot fornecido pela plataforma Typebot. Aqui está uma visão geral dos principais arquivos e pastas:

index.html: Arquivo principal da aplicação que contém a estrutura HTML e integração com o Typebot.
style.css: Arquivo de estilo que define a aparência da página.
manifest.json: Arquivo de manifesto para configurar as propriedades da Progressive Web App (PWA).
pwabuilder-sw.js: Arquivo JavaScript que registra o service worker para oferecer uma experiência PWA.
assets/: Pasta que armazena imagens e ícones utilizados na aplicação.
3. Configuração
Antes de implantar o chatbot, é necessário fazer algumas configurações:

3.1. Typebot
Obtenha as credenciais do Typebot para o seu projeto.
No arquivo index.html, substitua chatbot-unicap-pscf88a pelo identificador do seu projeto Typebot.
Personalize as configurações do Typebot conforme necessário, como a mensagem de pré-visualização e temas, no bloco de script Typebot.initBubble.
3.2. Imagens e Ícones
Certifique-se de substituir as imagens e ícones na pasta assets/ pelos relacionados à Faculdade Unicap.

4. Implantação
Para implantar o projeto, siga estas etapas:

Carregue todos os arquivos para um servidor web ou use uma plataforma de hospedagem, como Vercel, Netlify ou GitHub Pages.
Certifique-se de que o arquivo pwabuilder-sw.js esteja no mesmo diretório que index.html.
Acesse a página implantada para visualizar o chatbot em ação.
5. Funcionalidades
O chatbot foi projetado para fornecer informações relevantes sobre a Faculdade Unicap. Os usuários podem iniciar uma conversa e obter respostas automáticas.

6. Considerações Finais
Este projeto é uma contribuição valiosa para o TCC, demonstrando a implementação prática de um chatbot para facilitar a interação e fornecer informações aos usuários da Faculdade Unicap.
