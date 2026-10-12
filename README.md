# 📚 HQ → EPUB para Kindle

Conversor que roda 100% no navegador (celular ou PC). Nenhum arquivo sai do seu aparelho.

- **Entrada:** CBZ, CBR (ZIP ou RAR), PDF e MOBI/AZW3 de HQ (páginas em imagem, sem DRM)
- **Saída:** EPUB de layout fixo, comprimido para caber no limite (padrão 48 MB)
- **Compressão:** redimensiona para a tela do Kindle, converte para tons de cinza e reduz a qualidade JPEG aos poucos até caber

## Como publicar (GitHub Pages)

1. Crie um repositório e envie `index.html` e `README.md`
2. **Settings → Pages → Branch: `main` / root → Save**
3. Abra `https://SEU-USUARIO.github.io/NOME-DO-REPO/` no celular

## Roadmap

- [x] CBR com RAR real (WASM)
- [x] MOBI de HQ → EPUB
- [ ] MOBI de texto → EPUB (reflow)
- [ ] PWA instalável (manifest + service worker)
- [ ] Modo mangá (direita → esquerda)
