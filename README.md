# Ruz Records — Site Oficial

> *for artists, for the future.*

Site oficial da **Ruz Records**, gravadora independente de Phonk e Brazilian Phonk fundada em novembro de 2025 por **Raul (Ruz)**.

---

## 📁 Estrutura do Projeto

```
ruz-records.html    → arquivo único do site (HTML + CSS + JS inline)
README.md           → este arquivo
favicon.ico         → (a adicionar) ícone do site
favicon-32x32.png   → (a adicionar)
favicon-16x16.png   → (a adicionar)
apple-touch-icon.png → (a adicionar)
og-image.jpg        → (a adicionar) imagem para redes sociais (1200×630px)
```

---

## 🚀 Como usar

O site é um **arquivo HTML único** — sem dependências externas além das Google Fonts.

### Abrir localmente
Basta abrir o `ruz-records.html` em qualquer navegador moderno.

### Publicar
Faça upload do `ruz-records.html` para qualquer serviço de hospedagem:

| Serviço | Plano | Observação |
|---|---|---|
| [Vercel](https://vercel.com) | Gratuito | Recomendado |
| [Netlify](https://netlify.com) | Gratuito | Drag & drop do arquivo |
| [GitHub Pages](https://pages.github.com) | Gratuito | Renomear para `index.html` |
| Hospedagem tradicional (cPanel) | Pago | Upload via FTP |

---

## ⚙️ Configurações a personalizar

### 1. Domínio
Substituir `https://ruzrecords.com` nas meta tags pelo domínio real:
```html
<meta property="og:url" content="https://SEU-DOMINIO.com"/>
<link rel="canonical" href="https://SEU-DOMINIO.com"/>
```

### 2. Imagem Open Graph
Criar uma imagem `og-image.jpg` (1200×630px) com a identidade da gravadora e referenciar:
```html
<meta property="og:image" content="https://SEU-DOMINIO.com/og-image.jpg"/>
```
Essa imagem aparece ao compartilhar o link no WhatsApp, Instagram, Discord, etc.

### 3. Favicon
Gerar os arquivos de favicon em [favicon.io](https://favicon.io) usando a logo da Ruz Records e colocar na pasta raiz.

### 4. Playlist do Spotify
A playlist oficial já está integrada:
```
https://open.spotify.com/playlist/0WIxKjXOVe6eR6yunMyfM3
```
Para trocar, substituir o ID em dois lugares no HTML:
- Iframe embed na seção Playlist
- Link "Abrir Playlist Oficial no Spotify" na barra inferior

### 5. Links das músicas no Spotify
Cada card de música tem um `href="#"` — substituir pelo link real da faixa no Spotify:
```html
<a href="https://open.spotify.com/track/ID_DA_FAIXA" ...>
```

### 6. Fotos dos artistas e capas das músicas
Os círculos cinzas (`.art-photo`) e os quadrados das músicas (`.trk-cover`) são placeholders.
Para adicionar imagens reais, incluir dentro de cada elemento:
```html
<div class="art-photo" style="background-image:url('foto-artista.jpg');background-size:cover;"></div>
```

---

## 🎨 Identidade Visual

| Elemento | Valor |
|---|---|
| Fundo | `#000000` (preto absoluto) |
| Texto principal | `#FFFFFF` |
| Prata/metallic | `#C8C8C8` |
| Platinum | `#00E5CC` (ciano) |
| Gold | `#FFD700` (dourado) |
| Silver | `#C8D8E8` (prata azulada) |
| Bronze | `#CD8B4A` |
| Hitmaker / Viral | `#FF3000` (laranja-vermelho) |
| Spotify | `#1DB954` (verde) |
| PhonkList nav | `#E03030` (vermelho) |

### Fontes (Google Fonts)
- **Bebas Neue** — títulos display grandes
- **Syne** — headings, labels, UI
- **DM Sans** — corpo de texto

---

## 📱 Responsividade

| Breakpoint | Layout |
|---|---|
| > 900px | Desktop completo |
| ≤ 900px | Colunas colapsam para 1 |
| ≤ 768px | Mobile: nav oculta, grids 2 colunas |
| ≤ 480px | Mobile pequeno: grids 1 coluna |

---

## 🏷️ Rankings de Artistas

| Tier | Cor | Critério |
|---|---|---|
| Platinum | `#00E5CC` | Artista de maior destaque |
| Gold | `#FFD700` | Alto volume de lançamentos |
| Silver | `#C8D8E8` | 5+ lançamentos |
| Bronze | `#CD8B4A` | Até 4 lançamentos |
| 💿 Bronze Disco | Bronze animado | 1M+ streams no selo |
| ⚡ Hitmaker | `#FF3000` | 1+ faixa viral no selo |

---

## 👥 Equipe

| Nome | Cargo | Artista |
|---|---|---|
| Raul | Founder / A&R | Ruz |
| Gabriel | Head Ops | DJ BLK |

---

## 📊 Status atual (Mai/2025)

- **5M+** streams totais
- **40+** artistas registrados
- **10+** países representados
- **Nº1** gravadora em ascensão no nicho de Phonk no Brasil
- **7 meses** de existência

---

## 🔧 Stack técnica

- **HTML5** semântico (`<main>`, `<section>`, `<article>`, `<nav>`, `<footer>`)
- **CSS3** puro — sem frameworks (Grid, Flexbox, Custom Properties, Animations)
- **JavaScript** vanilla — sem bibliotecas
- **Google Fonts** — única dependência externa
- **Spotify Embed** — playlist integrada

---

*© 2025 Ruz Records. All rights reserved.*
