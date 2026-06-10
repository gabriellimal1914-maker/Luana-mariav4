# Luana Maria — Método Repair Brows

Site premium para Luana Maria, especialista em reconstrução de sobrancelhas e criadora do **Método Repair Brows**.

---

## 📁 Estrutura do Projeto

```
repairbrows/
├── index.html          ← Página principal
├── style.css           ← Estilos (Mobile First)
├── script.js           ← Interações e integrações
├── assets/
│   └── luana-maria.png ← Foto profissional de Luana
└── README.md           ← Este arquivo
```

---

## 🖼️ Como Adicionar Fotos de Antes & Depois

1. Coloque suas imagens dentro da pasta `assets/`
2. Abra `index.html` no editor de texto
3. Localize os blocos `<div class="ad-placeholder ad-before">` e `<div class="ad-placeholder ad-after">`
4. Substitua o conteúdo por uma tag `<img>`:
   ```html
   <img src="assets/nome-da-foto.jpg" alt="Antes" style="width:100%;height:100%;object-fit:cover;" />
   ```

Faça o mesmo para as seções `resultados-grid` substituindo os `resultado-placeholder`.

---

## 🚀 Publicar no GitHub Pages

1. Crie um repositório no GitHub (ex: `repairbrows-site`)
2. Faça upload de todos os arquivos para a branch `main`
3. Vá em **Settings → Pages**
4. Em "Source", selecione `Deploy from a branch → main → / (root)`
5. Aguarde 1–2 minutos
6. Acesse o link gerado (ex: `https://seuusuario.github.io/repairbrows-site/`)

---

## 🌐 Publicar na Vercel

### Opção A — Via Interface Web (Recomendado)
1. Acesse [vercel.com](https://vercel.com) e crie uma conta
2. Clique em **"New Project"**
3. Importe do GitHub ou faça upload da pasta
4. Não é necessária nenhuma configuração adicional
5. Clique em **Deploy**

### Opção B — Via Vercel CLI
```bash
npm i -g vercel
cd repairbrows
vercel
```

---

## ✏️ Personalização Rápida

| O que alterar | Onde encontrar |
|---|---|
| Número do WhatsApp | Buscar `5511991675603` em `index.html` e `script.js` |
| Endereço da clínica | Seção `<footer>` em `index.html` |
| Link do Instagram | Buscar `mariasobrancelhas_` em `index.html` |
| Link do Ebook | Buscar `pay.kiwify.com.br` em `index.html` |
| Depoimentos reais | Seção `depoimentos` em `index.html` |
| Horário de atendimento | Seção footer em `index.html` |
| Cores do site | Variáveis `:root` no início de `style.css` |

---

## 📱 Testando no Celular (Local)

Para visualizar no celular sem publicar, você pode:
1. Abrir o `index.html` direto no navegador do celular (via cabo USB ou transferência de arquivos)
2. Ou usar uma extensão como **Live Server** no VS Code e acessar pelo IP local da sua rede Wi-Fi

---

## 📞 Contatos Configurados

- **WhatsApp:** +55 11 99167-5603
- **Instagram:** @mariasobrancelhas_
- **Ebook:** https://pay.kiwify.com.br/Dlbnrcc
- **Endereço:** Av. Fiorelli Peccicacco, 1035 — Perus, São Paulo SP

---

## 🛠️ Tecnologias Utilizadas

- HTML5 semântico
- CSS3 (Custom Properties, Grid, Flexbox, Media Queries)
- JavaScript Vanilla (ES6+)
- Google Fonts: Cormorant Garamond + Jost
- Zero dependências externas — funciona apenas abrindo o `index.html`

---

*Site desenvolvido com foco em Mobile First e alto desempenho.*
