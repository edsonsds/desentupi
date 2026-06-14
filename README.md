# 🌐 Desentupi Pro — Sistema de 200 Páginas

## 📦 O que vem nesse pacote

| Arquivo | O que faz |
|---|---|
| `template-bairro.html` | Página única que vira 200 páginas (lê o bairro da URL) |
| `bairros.js` | Lista dos 200 bairros |
| `admin-site.html` | Painel para editar conteúdo de todas as páginas |
| `index.html` | Redireciona para a página inicial |
| `vercel.json` | Config para URLs amigáveis no Vercel |
| `netlify.toml` | Config para URLs amigáveis no Netlify |
| `gerador-sitemap.html` | Cria o sitemap.xml para o Google |

---

## 🚀 Como hospedar (Vercel — 5 minutos)

### Passo 1 — Criar conta no Vercel
1. Acesse https://vercel.com
2. Clique em "Sign Up" → entre com sua conta do GitHub ou Google

### Passo 2 — Subir os arquivos
1. No painel do Vercel, clique em "Add New" → "Project"
2. Escolha "Upload" (em vez de importar do GitHub)
3. Arraste a pasta com todos os arquivos
4. Clique em "Deploy"

### Passo 3 — Pronto!
Em 30 segundos seu site está no ar em uma URL tipo:
- `https://desentupi-pro-abc123.vercel.app`

URLs que vão funcionar:
- `https://seusite.vercel.app/` → página principal
- `https://seusite.vercel.app/desentupidora-mooca` → página da Mooca
- `https://seusite.vercel.app/desentupidora-tatuape` → Tatuapé
- `https://seusite.vercel.app/admin` → painel admin

---

## 🎨 Como editar o conteúdo

1. Acesse `seusite.vercel.app/admin`
2. Edite:
   - **Contato:** telefone, WhatsApp, email
   - **Marca:** nome, CNPJ, anos no mercado
   - **Imagens:** URL das fotos (use imgur.com ou imgbb.com para subir as suas)
   - **Textos:** história da empresa
   - **Serviços:** 8 cards com ícones, fotos e descrições
   - **Equipamentos:** seus equipamentos
   - **Depoimentos:** clientes reais
   - **FAQ:** perguntas comuns
3. Clique em **"💾 Salvar alterações"**
4. As **200 páginas atualizam automaticamente!**

---

## 🖼️ Como trocar as fotos

As fotos atuais vêm do Unsplash (banco gratuito). Para usar fotos suas:

### Opção 1 — Imgur (mais fácil, sem cadastro)
1. Acesse https://imgur.com
2. Clique em "New post"
3. Arraste sua foto
4. Quando subir, clique com botão direito na foto → "Copiar endereço da imagem"
5. Cole essa URL no painel admin

### Opção 2 — ImgBB
1. Acesse https://imgbb.com
2. "Start uploading" → escolha a foto
3. Copie o "Direct link"
4. Cole no painel admin

### Tamanhos recomendados:
- **Hero (fundo):** 1600x900
- **Sobre nós:** 900x675
- **Serviços/Equipamentos:** 600x400

---

## 📍 Comprar domínio próprio (opcional)

Quando quiser ter `desentupipro.com.br` em vez de `seusite.vercel.app`:

1. Compre o domínio em https://registro.br (~R$ 40/ano)
2. No Vercel, clique no seu projeto → "Settings" → "Domains"
3. Adicione o domínio
4. O Vercel mostra 2 registros DNS para configurar no Registro.br
5. Em 1-24 horas, seu site responde no domínio próprio

---

## 🔍 Mandar o site para o Google indexar

Depois de no ar:

1. Acesse https://search.google.com/search-console
2. Adicione seu site
3. Acesse `gerador-sitemap.html` no seu site
4. Copie o XML gerado
5. Salve como `sitemap.xml` e suba no Vercel
6. No Search Console: "Sitemaps" → adicione `seusite.com.br/sitemap.xml`

Em alguns dias/semanas, as 200 páginas começam a aparecer no Google.

---

## 🔥 Firebase — primeiro acesso

A primeira vez que abrir o admin, ele cria o documento no Firebase automaticamente com os dados padrão. Pode levar 2-3 segundos.

Caminho no Firebase Console:
- Firestore Database → collection `siteContent` → document `main`

---

## ❓ Dúvidas comuns

**P: As 200 páginas são realmente 200 arquivos?**
R: Não. É 1 template inteligente que muda o conteúdo conforme o bairro da URL. Mais leve e fácil de manter.

**P: O Google vai entender que são páginas diferentes?**
R: Sim. Cada URL gera um título, descrição e meta tags únicos. O Google indexa como 200 páginas separadas.

**P: Posso adicionar mais bairros depois?**
R: Sim. Edite o arquivo `bairros.js` e adicione novos. Cada um vira uma página automaticamente.

**P: E se eu trocar uma foto no admin, demora pra atualizar?**
R: Atualiza instantaneamente. Quando alguém abre qualquer página, ela busca o conteúdo mais recente do Firebase.

---

## 🛡️ Segurança do painel admin

Atualmente o admin está aberto em `/admin`. Quando quiser proteger com senha, me avise — posso adicionar login com Firebase Auth.
