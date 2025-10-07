# 💱 Conversor de Moedas

Uma aplicação web simples que permite converter valores entre diferentes moedas, utilizando dados de uma API de câmbio em tempo real. Criado com foco em praticar habilidades em JavaScript, consumo de API e desenvolvimento de interface web moderna.

---

## 📌 Índice

- [Visão Geral](#visão-geral)
- [Funcionalidades](#funcionalidades)
- [Tecnologias Utilizadas](#tecnologias-utilizadas)
- [Instalação e Execução Local](#instalação-e-execução-local)
- [Como Usar](#como-usar)
- [Variáveis de Ambiente](#variáveis-de-ambiente)
- [Melhorias Futuras](#melhorias-futuras)
- [Contribuindo](#contribuindo)
- [Licença](#licença)
- [Contato](#contato)

---

## 👀 Visão Geral

O **Conversor de Moedas** é uma aplicação que permite a conversão de valores entre moedas como Real (BRL), Dólar (USD), Euro (EUR), entre outras. A aplicação faz uso de uma API externa para buscar as taxas de câmbio em tempo real.

Você pode acessar a aplicação diretamente aqui: [🔗 Link para o projeto online (se aplicável)](https://seu-link.vercel.app)

![preview](./assets/preview.png) <!-- Substitua pelo caminho correto da imagem de preview -->

---

## ✅ Funcionalidades

- ✅ Conversão entre múltiplas moedas
- ✅ Interface amigável e responsiva
- ✅ Validação de valores inseridos
- ✅ Exibição da taxa de câmbio utilizada
- ✅ Atualização automática da cotação ao mudar as moedas

---

## 🛠 Tecnologias Utilizadas

- HTML5
- CSS3
- JavaScript (ES6+)
- API de Câmbio (ex: [exchangerate-api.com](https://www.exchangerate-api.com/) ou similar)
- (Se aplicável) Vite ou Webpack
- (Se aplicável) Deploy via Vercel ou Netlify

---

## 🧪 Instalação e Execução Local

Clone o projeto e execute localmente:

```bash
# Clone este repositório
git clone https://github.com/Kamilly02/conversor-de-moedas.git

# Acesse o diretório do projeto
cd conversor-de-moedas

# Instale as dependências (se houver)
npm install

# Inicie o servidor de desenvolvimento
npm run dev

# Ou abra o arquivo index.html diretamente em seu navegador

## 💡 Como Usar

1. Abra o navegador e acesse: `http://localhost:5173` (ou o endereço indicado pelo Vite).
2. Insira o valor que deseja converter.
3. Selecione a moeda de origem e a moeda de destino.
4. Clique em **Converter** e veja o resultado.

---

## 🔐 Variáveis de Ambiente

Se estiver usando uma API que requer autenticação, crie um arquivo `.env` na raiz do projeto com:

```env
VITE_API_KEY=sua_chave_da_api  
VITE_API_URL=https://api.exemplo.com

## 🚧 Melhorias Futuras

- [ ] Adicionar gráfico histórico de câmbio  
- [ ] Implementar tema escuro  
- [ ] Tradução da interface (i18n)  
- [ ] Armazenamento em cache para reduzir chamadas à API  
- [ ] Transformar em PWA (Progressive Web App)

---

## 🤝 Contribuindo

Contribuições são sempre bem-vindas!

### Para contribuir:

1. Faça um fork do repositório  
2. Crie uma branch para sua feature:

```bash
git checkout -b feature/nova-funcionalidade
