# 🎯 Pacote SEO Completo — Desentupi Pro

## 📦 O que vem nesse pacote

| Arquivo | O que faz |
|---|---|
| `template-bairro.html` | Template das 200 páginas (atualizado com Schema.org + Open Graph + meta tags) |
| `sobre.html` | Página "Sobre a empresa" com história, valores e estatísticas |
| `politica-privacidade.html` | Página LGPD (já existente) |
| `sitemap.xml` | Mapa do site para o Google (203 URLs) |
| `robots.txt` | Diz ao Google quais páginas indexar |

---

## 🚀 Como subir tudo

### Passo 1 — Substituir/Subir os 5 arquivos no GitHub

Acesse: https://github.com/edsonsds/desentupi

**Arquivos para SUBSTITUIR (já existem):**
- `template-bairro.html` → cola o novo conteúdo

**Arquivos NOVOS (subir):**
- `sobre.html`
- `politica-privacidade.html` (se ainda não subiu)
- `sitemap.xml`
- `robots.txt`

### Passo 2 — Aguardar Vercel republicar (30-60 segundos)

### Passo 3 — Verificar

```
https://desentupi.vercel.app/sobre.html
https://desentupi.vercel.app/politica-privacidade.html
https://desentupi.vercel.app/sitemap.xml
https://desentupi.vercel.app/robots.txt
```

---

## 🔍 O que melhorou tecnicamente

### ✅ Schema.org (LocalBusiness)
Código JSON-LD invisível que diz ao Google:
- Você é uma empresa local de desentupimento
- Em São Paulo
- Aberto 24h, todos os dias
- Atende a Grande SP, ABC, etc.
- Tem 4.9 estrelas
- Oferece os serviços (vaso, pia, hidrojateamento...)

**Resultado:** Google entende melhor e pode mostrar **rich snippets** (estrelas, horário, telefone) direto nos resultados.

### ✅ Open Graph (preview no WhatsApp)
Quando alguém compartilhar o link no WhatsApp, vai aparecer:
- Imagem grande
- Título "Desentupidora 24h em [Bairro] | Desentupi Pro"
- Descrição apelativa

### ✅ Meta tags otimizadas
- `geo.region`, `geo.position` → diz ao Google que você é de São Paulo
- `canonical` → evita conteúdo duplicado
- `robots` → permite indexação completa
- Cada página de bairro tem **título único, descrição única, keywords únicas**

### ✅ Sitemap.xml
Lista organizada de **todas as 203 páginas** (200 bairros + sobre + política + home) com prioridades. O Google indexa mais rápido.

### ✅ robots.txt
- Permite indexação geral
- Bloqueia o admin e testador (não devem aparecer no Google)
- Aponta para o sitemap

### ✅ Página Sobre
- Conta a história da empresa
- Mostra valores (agilidade, transparência, etc.)
- Estatísticas em destaque
- Schema.org de AboutPage
- Link no rodapé de todas as páginas

---

## 📈 Próximos passos para aparecer no Google

### 1️⃣ Google Search Console (essencial)
1. Acesse https://search.google.com/search-console
2. Adicione propriedade: `https://desentupi.vercel.app`
3. Verifique a propriedade (eles te dão um arquivo HTML para subir)
4. Vá em **Sitemaps** → adicione `sitemap.xml`
5. Aguarde — em 1-7 dias o Google começa a indexar as 200 páginas

### 2️⃣ Google Meu Negócio (MUITO importante)
1. Acesse https://business.google.com
2. Crie perfil
3. Endereço de São Paulo (pode ser comercial)
4. Categoria: "Empresa de desentupimento"
5. Foto, horário 24h, telefone, site
6. **Foque em conseguir avaliações 5 estrelas** — esse é o fator #1 para aparecer

### 3️⃣ Criar imagem de preview para WhatsApp
O Open Graph aponta para `https://desentupi.vercel.app/og-preview.jpg` mas o arquivo ainda não existe.

**Crie uma imagem 1200x630px com:**
- Logo da Desentupi Pro
- "Desentupidora 24h"
- "Atendimento em toda Grande SP"
- Foto profissional de fundo

Suba como `og-preview.jpg` no repositório do GitHub.

### 4️⃣ Comprar domínio próprio
Quando puder, compre `desentupipro.com.br` no registro.br (~R$ 40/ano):
- Vai aparecer melhor no Google que `.vercel.app`
- Passa profissionalismo
- Configure no Vercel em Settings → Domains

---

## 🧪 Como verificar se ficou tudo certo

### Schema.org
1. Abra: https://search.google.com/test/rich-results
2. Cole uma URL sua, ex: `https://desentupi.vercel.app/desentupidora-mooca.html`
3. Tem que dar **válido** e mostrar o LocalBusiness

### Open Graph
1. Abra: https://www.opengraph.xyz/
2. Cole sua URL
3. Vai mostrar como vai aparecer no WhatsApp

### Mobile-friendly
1. Abra: https://search.google.com/test/mobile-friendly
2. Cole sua URL
3. Tem que dar **mobile-friendly** ✅

### Velocidade
1. Abra: https://pagespeed.web.dev
2. Cole sua URL
3. Procure ter nota acima de 90 (em mobile e desktop)

---

## 📊 Resultado esperado

**Após 7-30 dias:**
- Google indexa as 200 páginas
- Aparece em buscas longas tipo "desentupidora 24h Mooca"

**Após 60-90 dias (com Meu Negócio + avaliações):**
- Aparece em buscas locais "desentupidora perto de mim"
- Estrelas aparecem no resultado da busca
- Primeiros chamados orgânicos chegam

**Após 6 meses:**
- Primeira página do Google para várias buscas
- Volume orgânico consistente

---

## 🆘 Suporte

Algum problema? Me chama e te ajudo com:
- Configuração do Search Console
- Criação da imagem og-preview.jpg
- Análise de erros de indexação
- Conversão do domínio próprio
