# Treinamento interno Provokers

Notebook do Copilot e Bíblia de Design.

O conteúdo do `index.html` está criptografado (AES-256-GCM, chave derivada da senha por PBKDF2 com 600.000 iterações). A senha não fica gravada em nenhum arquivo do repositório.

## Publicar no GitHub Pages

1. Crie um repositório novo no GitHub.
2. Envie os arquivos desta pasta para a raiz do repositório: `index.html`, `.nojekyll`, `robots.txt` e este `README.md`.
3. Em Settings > Pages, escolha Deploy from a branch, branch `main`, pasta `/ (root)` e salve.
4. Em alguns minutos o site fica disponível em `https://SEU-USUARIO.github.io/NOME-DO-REPO/`.

## Atualizar o conteúdo

Gere um novo `index.html` criptografado a partir da versão nova da apresentação e substitua o arquivo no repositório.
