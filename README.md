📶 Sistema de Pagamento Wi-Fi Premium
Sistema completo para gerenciamento de pagamentos com integração WhatsApp, consulta meteorológica e upload automático de comprovantes.

🚀 Recursos Principais
Seleção de Planos: Escolha entre 3 planos com diferentes durações
Consulta de Clima em Tempo Real: Integração com API de previsão do tempo
Upload Automático de Comprovantes: Hospedagem direta em servidor público via ImgBB API
Integração Direta com WhatsApp: Geração automática de mensagem pré-formatada
Design Moderno e Responsivo: Interface com tema escuro e elementos neon
Validação Inteligente: Campos obrigatórios apenas para nome e telefone

⚡ Últimas Atualizações
Upload automático de imagens para o ImgBB
Design unificado com bordas amarelas e fundo escuro
Sistema de preview de imagens com bordas estilizadas
Campos opcionais para dados de pagamento
Mensagem automática com detalhes do plano selecionado
Melhorias na responsividade para mobile

📦 Pré-requisitos
Servidor web (local ou remoto)
Conta no ImgBB para API Key
Navegador moderno com suporte a:
JavaScript ES6+
Fetch API
FileReader API

🛠 Instalação
git clone https://github.com/seu-usuario/wifi-premium.git
cd wifi-premium
# Substitua 'SUA_CHAVE_API_AQUI' no arquivo index.html pela sua chave do ImgBB

⚙️ Configuração
Registre-se no ImgBB
Obtenha sua API Key gratuita
No arquivo index.html, linha ~160, substitua:
'https://api.imgbb.com/1/upload?key=SUA_CHAVE_API_AQUI'
Personalize os QR Codes e links de pagamento conforme necessário

💡 Como Usar
1. Seleção de Plano
- Clique em qualquer botão de plano
- QR Code e link de pagamento serão exibidos
2. Consulta Meteorológica
- Digite o nome da cidade
- Clique em "Buscar" para ver temperatura, umidade e vento
3. Envio de Comprovante
- Preencha nome e telefone (obrigatórios)
- Anexe imagem (opcional) - suporta JPG/PNG
- Clique no botão WhatsApp para envio automático
- O sistema incluirá automaticamente o link do comprovante

🛠 Stack Tecnológica
Frontend
HTML5 Semântico
CSS3 Custom Properties
JavaScript Vanilla ES6+
APIs Externas
ImgBB - Upload de imagens
wttr.in - Dados meteorológicos
WhatsApp Web - Integração de mensagens
Dependências
Font Awesome 6.4.2 (ícones)
Fetch API (comunicação HTTP)

🤝 Contribuição
Faça um Fork do projeto

Crie sua Feature Branch:
git checkout -b feature/nova-feature
Commit suas mudanças:

git commit -m 'feat: Minha nova feature'

Push para a Branch:
git push origin feature/nova-feature
Abra um Pull Request

📄 Licença
Distribuído sob licença MIT. Veja LICENSE para mais informações.

✉️ Contato
João Ricardo

Instagram: @joaoricardo.pe 
Email: ricardoromanos1489@hotmail.com

⚠️ Nota Importante: Substitua todos os placeholders (SUA_CHAVE_API_AQUI, links de pagamento, informações de contato) antes de usar em produção.
