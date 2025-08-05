# 🤖 AI Voice Assistant with OpenAI Realtime API

[![MIT License](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)
[![Deploy](https://img.shields.io/badge/Deploy-Live-blue)](https://openairealtime-agente-opt.netlify.app/)

Uma aplicação React que utiliza a [OpenAI Realtime API](https://platform.openai.com/docs/guides/realtime) para criar um agente de voz inteligente, capaz de analisar conteúdos de sites em tempo real, qualificar leads e conversar por áudio com o usuário. O projeto foi inspirado e adaptado do exemplo oficial da OpenAI: [openai-realtime-console](https://github.com/openai/openai-realtime-console).

---

## 🚀 Demonstração

Acesse a versão online:  
👉 [openai-voice-assistant-opt.vercel.app](https://openairealtime-agente-opt.netlify.app/)

---

## ✨ Funcionalidades

- **Scraping de Conteúdo**: Insira a URL de um site e extraia o texto principal usando a API ScrapingAnt.
- **Análise Inteligente**: O agente de voz recebe o conteúdo do site e atua como um qualificador de leads, fazendo perguntas e respondendo de forma concisa.
- **Conversação por Voz**: Comunicação em tempo real por áudio, com transcrição automática e respostas sintetizadas.
- **Visualização de Áudio**: Visualize a entrada e saída de áudio em tempo real.
- **Personalidade Customizada**: O agente é configurado para ser animado, genuíno e falar rapidamente, tornando a experiência mais natural e envolvente.
- **Gerenciamento de API Keys**: Interface para inserir e trocar as chaves das APIs utilizadas.

---

## 🛠️ Tecnologias Utilizadas

- [React](https://react.dev/)
- [TypeScript](https://www.typescriptlang.org/)
- [OpenAI Realtime API](https://platform.openai.com/docs/guides/realtime)
- [ScrapingAnt API](https://scrapingant.com/)
- [WebRTC](https://webrtc.org/) para transmissão de áudio
- [Sass](https://sass-lang.com/) para estilização
- [react-feather](https://github.com/feathericons/react-feather) para ícones

---

## 📦 Instalação Local

1. **Clone o repositório:**
   ```bash
   git clone https://github.com/Marcus-Boni/Open-AI-agente-Web-Scraping.git
   cd Open-AI-agente-Web-Scraping
   ```

2. **Configure as variáveis de ambiente:**
   - Crie um arquivo `.env` na raiz do projeto com o seguinte conteúdo:
     ```
     REACT_APP_SCRAPINGANT_API_KEY=coloque_sua_api_key_aqui
     ```
   - Obtenha sua chave em [ScrapingAnt](https://app.scrapingant.com/dashboard).

3. **Instale as dependências:**
   ```bash
   yarn
   # ou
   npm install
   ```

4. **Inicie o projeto:**
   ```bash
   yarn start
   # ou
   npm start
   ```

5. **Acesse no navegador:**  
   [http://localhost:3000](http://localhost:3000)

---

## 📝 Como Usar

1. **Insira a URL** do site que deseja analisar e clique em "Scrape".
2. **Aguarde** o processamento do conteúdo.
3. **Informe sua OpenAI API Key** quando solicitado (a chave fica salva localmente no navegador).
4. **Converse por voz** com o agente, que irá analisar o conteúdo do site e responder em áudio.
5. **Visualize** as transcrições e o áudio em tempo real.

---

## 📁 Estrutura do Projeto

```
src/
 ├── components/         # Componentes reutilizáveis
 ├── lib/                # Ferramentas de áudio (WAV)
 ├── pages/              # Páginas principais (VoiceChat, ScrapeForm)
 ├── utils/              # Funções utilitárias
 ├── App.tsx             # Componente principal
 └── ...
public/
 └── index.html
.env.example             # Exemplo de variáveis de ambiente
```

---

## 🔒 Segurança

- **Chaves de API**: A chave da OpenAI é armazenada apenas no `localStorage` do navegador e nunca enviada para terceiros.
- **Uso em Produção**: Para ambientes públicos, recomenda-se utilizar um backend relay para proteger as chaves da OpenAI.

---

## 🧑‍💻 Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou pull requests.

---

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](./LICENSE) para mais detalhes.

---

## 📚 Referências

- [OpenAI Realtime API Docs](https://platform.openai.com/docs/guides/realtime)
- [OpenAI Realtime Console (exemplo oficial)](https://github.com/openai/openai-realtime-console)
- [ScrapingAnt API Docs](https://docs.scrapingant.com/)

---

<div align="center">
  <b>Feito com 💚 por Marcus</b>
</div>

