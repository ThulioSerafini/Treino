TREINO FIT — PWA

Esta versão foi corrigida para funcionar como um Progressive Web App (PWA), com:
- manifest.json
- service worker para funcionamento offline após a primeira abertura
- IndexedDB para guardar cargas, repetições e histórico de forma mais robusta
- botão de instalação quando o navegador disponibilizar
- cronômetro de descanso
- links de execução no YouTube
- exportação dos dados em JSON

IMPORTANTE:
Um PWA NÃO deve ser aberto como arquivo file://. Para instalar no Android, os arquivos precisam estar publicados em HTTPS (ou rodando em localhost). Depois de abrir pelo Chrome em HTTPS, use o botão "Instalar" do app ou o menu do navegador > Instalar aplicativo / Adicionar à tela inicial.

Hospedagem gratuita:
- GitHub Pages
- Cloudflare Pages
- Netlify

O ZIP está pronto para ser enviado a qualquer hospedagem estática que aceite HTML/CSS/JS.
