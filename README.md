# Decora Doces — Landing Page

Landing page de conversão para a **Decora Doces** (forminhas de luxo para doces),
com identidade premium em tema escuro, tipografia serifada (Playfair Display),
hero com imagem de fundo, carrossel de produtos e CTAs para WhatsApp.

## Estrutura

```
.
├── index.html               # Landing page (HTML + CSS + JS inline)
├── assets/
│   ├── fonts/                        # Figtree e Playfair Display self-hosted (woff2, subset latin)
│   ├── logo.avif / .webp / .png      # Logo (webp/avif otimizados + png p/ favicon/apple-touch-icon)
│   ├── hero-desktop.webp             # Fundo do hero (desktop)
│   ├── hero-mobile.avif / .webp      # Imagem do hero (mobile)
│   ├── gallery-01..08.avif / .webp   # Fotos do carrossel
│   ├── escolha-modelos.avif / .webp  # Imagem da seção "Sem decidir sozinha"
│   ├── favicon.svg                   # Favicon (marca lótus)
│   └── *.png / *.jpg                 # Arquivos originais em alta resolução (não usados no site, mantidos como fonte)
└── brand/              # Materiais de origem (não usados no site)
    ├── LOGO DECORA 2026.pdf
    ├── [LP] DECORA DOCES - JUNHO 2026.docx   # copy original
    └── AD 01/02.png
```

Imagens são servidas em AVIF/WebP via `<picture>` (com fallback automático) e as fontes
são self-hosted em `assets/fonts/` — elimina as requisições externas ao Google Fonts,
reduzindo o peso total da página em favor da nota de performance no PageSpeed.

## Como visualizar localmente

Abrir via servidor local (recomendado, para imagens e fontes carregarem):

```bash
python3 -m http.server 8000
# acesse http://localhost:8000
```

## Publicação

Hospedado via **GitHub Pages** (branch `main`, raiz do repositório).
