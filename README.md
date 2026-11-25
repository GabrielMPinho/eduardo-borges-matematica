# Eduardo Borges Matemática

Site do professor Eduardo Borges — aulas particulares e acompanhamento em Matemática em Belo Horizonte (Savassi) e online.

## Estrutura

```
index.html          site completo (HTML + CSS + JS, sem dependências)
assets/img/         logos e fotos (recortadas, fundo transparente)
design/             fonte do design no canvas (Main.dc.html + canvas.json)
```

## Rodar localmente

```bash
python3 -m http.server 8000
# abrir http://localhost:8000
```

## Publicar

Qualquer hospedagem estática serve (GitHub Pages, Netlify, Vercel). No GitHub Pages: Settings > Pages > Deploy from branch > `main` / root.

## Padrões do projeto

- Tipografia: Inter Tight (títulos, botões, navegação) e Inter (texto).
- Cores: preto `#110F0E`, amarelo da marca `#FBCB03`, off-white `#FDFCF9`.
- Header assume a cor da seção atual, some ao rolar para baixo e volta ao rolar para cima.
- Animações de entrada discretas, disparadas uma vez quando o bloco entra na tela (respeita `prefers-reduced-motion`).
- Formulário de contato monta a mensagem e abre o WhatsApp (31) 99892-8229.

## Pendências

- Mini-bio do Eduardo na seção "Quem é" (formação, anos de experiência, onde já lecionou).
