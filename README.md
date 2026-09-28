# FisioFitness — Clone Landing Page

Clone idêntico do site [https://fisiofitness.vercel.app/](https://fisiofitness.vercel.app/) mantendo 100% do layout, vídeos, imagens, animações, estilos e textos originais, com **dados de contato substituídos por dados fictícios**.

---

## 📱 Dados de Contato Fictícios Utilizados

Todos os pontos de contato da landing page (botão flutuante, header, cards de contato, rodapé, botões de planos e CTAs com mensagens personalizadas) foram atualizados para dados fictícios:

- **WhatsApp / Telefone**: `(92) 99999-9999` (link: `https://wa.me/5592999999999`)
- **Instagram**: `@fisiofitness_ficticio` (link: `https://www.instagram.com/fisiofitness_ficticio/`)

---

## 🚀 Como Executar Localmente

### Opção 1: Sem dependências (Node.js nativo)
```bash
npm start
# ou
node server.cjs
```
O servidor iniciará automaticamente em `http://localhost:3000` (ou na próxima porta livre, como `3001`) com suporte completo a streaming de vídeos e requisições HTTP Range.

---

## ☁️ Como Fazer Deploy

O projeto é 100% estático e pronto para deploy imediato:

- **Vercel**: Já configurado com [vercel.json](file:///c:/Users/paulovenoy/Documents/antigravity/silly-pasteur/vercel.json) (basta rodar `vercel` ou conectar o repositório).
- **Netlify**: Basta apontar para o diretório raiz.
- **GitHub Pages**: Habilitar a publicação da branch principal.

---

## 🛠️ Como Personalizar os Dados

Os dados centrais de contato e localização estão configurados no bundle em [assets/index-C3EjC3G_.js](file:///c:/Users/paulovenoy/Documents/antigravity/silly-pasteur/assets/index-C3EjC3G_.js) no objeto `Rf`:

```javascript
var Rf = {
  name: `FisioFitness`,
  city: `Manacapuru`,
  state: `AM`,
  tagline: `A mais completa da cidade`,
  instagram: `@fisiofitness_ficticio`,
  instagramUrl: `https://www.instagram.com/fisiofitness_ficticio/`,
  followers: 10.8,
  whatsapp: `5592999999999`,
  whatsappDisplay: `(92) 99999-9999`,
  priceFrom: 150
};
```
Ao alterar esse objeto, todos os botões de CTA, links do WhatsApp com mensagens pré-formatadas, redes sociais e cards são atualizados automaticamente em toda a aplicação.
