# 📚 Minha Estante de Leituras — PWA

Registre seus livros lidos por mês com capa, datas de início/fim, páginas e gênero.

---

## ▶️ Opção 1 — Usar localmente (sem internet)

1. Baixe todos os arquivos desta pasta para uma pasta no seu computador/celular
2. Abra o arquivo `estante-leituras.html` no Chrome ou Edge
3. O banner **"Instalar"** aparecerá automaticamente → clique para adicionar à tela inicial como app

> ⚠️ O upload de imagem funciona apenas fora do preview do Claude (aberto direto no navegador).

---

## 🌐 Opção 3 — Publicar no GitHub Pages (acesso de qualquer lugar)

### Passo a passo:

**1. Crie uma conta no GitHub**
→ https://github.com/signup (gratuito)

**2. Crie um repositório novo**
- Clique em **"New repository"**
- Nome: `minha-estante` (ou qualquer nome)
- Marque **"Public"**
- Clique **"Create repository"**

**3. Suba os arquivos**
- Clique em **"uploading an existing file"**
- Arraste TODOS estes arquivos de uma vez:
  - `estante-leituras.html`
  - `manifest.json`
  - `sw.js`
  - `icon-192.png`
  - `icon-512.png`
- Clique **"Commit changes"**

**4. Ative o GitHub Pages**
- Vá em **Settings** (aba do repositório)
- Menu lateral → **Pages**
- Em "Branch", selecione **main** e pasta **/ (root)**
- Clique **Save**

**5. Acesse seu app**
Após ~2 minutos, seu app estará em:
```
https://SEU_USUARIO.github.io/minha-estante/estante-leituras.html
```

**6. Instalar no celular**
- Abra a URL no Chrome do Android
- O banner de instalação aparece automaticamente
- Ou toque nos **3 pontinhos → "Adicionar à tela inicial"**

---

## 📱 Funciona offline?
Sim! Após a primeira visita, o Service Worker (`sw.js`) guarda o app em cache.
Você pode usar sem internet — mas as fontes do Google podem não carregar offline.

## 💾 Os dados são salvos?
Os livros ficam no `localStorage` do navegador — sobrevivem ao fechar o app.
Cada dispositivo tem seu próprio armazenamento (não sincroniza entre celular e PC).

