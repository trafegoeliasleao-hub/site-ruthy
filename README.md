# Site Ruthy Peixoto — Cílios & Sobrancelhas

Landing page única para Ruthy Peixoto, designer de cílios e sobrancelhas.

## 📁 Estrutura

```
site-ruthy/
├── index.html
└── imagens/
    ├── 1.jpeg   → Brasileiro
    ├── 2.jpeg   → Henna
    ├── 3.jpeg   → Efeito Fox
    ├── 4.jpeg   → Americano
    ├── 5.jpeg   → Design de Sobrancelha
    ├── 6.jpeg   → Egípcio
    ├── 7.jpeg   → Fio a Fio
    └── 8.jpeg   → Hero + Sobre (Ruthy no estúdio EYSH)
```

## 🚀 Deploy no Cloudflare Pages

1. Coloque as 8 imagens dentro da pasta `imagens/`
2. Vá em https://dash.cloudflare.com → Workers & Pages → Create → Pages → Upload assets
3. Arraste a pasta **inteira** `site-ruthy/` (com `index.html` + `imagens/`)
4. Project name: `ruthy-peixoto` (ou o que preferir) → Deploy

Pronto, o site vai estar em `https://ruthy-peixoto.pages.dev`.

## 🔧 Customizações fáceis

- **Trocar WhatsApp:** procurar `5593992086804` no HTML e substituir.
- **Trocar Instagram:** procurar `ruthypeixotoblog` e substituir.
- **Trocar imagem de um serviço:** ou renomear o arquivo na pasta `imagens/` ou alterar o `src="imagens/X.jpeg"` no card correspondente.
- **Trocar preço/descrição:** editar direto no HTML, cada serviço é um bloco `<article class="service-card">`.

## 🎨 Identidade

- Fontes: Italiana (display) + Cormorant Garamond (corpo)
- Paleta: off-white `#FAF8F4`, preto `#0E0E0E`, dourado `#C9A84C`
- Sem dependências externas além do Google Fonts
