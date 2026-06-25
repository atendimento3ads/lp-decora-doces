# Decora Doces — Landing Page

Landing page de conversão para a **Decora Doces** (forminhas de luxo para doces),
com identidade premium em tema escuro, tipografia serifada (Playfair Display),
hero com imagem de fundo, carrossel de produtos e CTAs para WhatsApp.

## Estrutura

```
.
├── index.html          # Landing page (HTML + CSS + JS inline)
├── assets/             # Imagens da página
│   ├── logo.png        # Logo (versão clara, p/ header escuro)
│   ├── hero-image.png  # Fundo do hero (desktop)
│   ├── hero-mobile.png # Fundo do hero (mobile)
│   └── image-01..08.png# Fotos do carrossel
└── brand/              # Materiais de origem (não usados no site)
    ├── LOGO DECORA 2026.pdf
    ├── [LP] DECORA DOCES - JUNHO 2026.docx   # copy original
    └── AD 01/02.png
```

## Como visualizar localmente

Abrir via servidor local (recomendado, para imagens e fontes carregarem):

```bash
python3 -m http.server 8000
# acesse http://localhost:8000
```

## Publicação

Hospedado via **GitHub Pages** (branch `main`, raiz do repositório).
