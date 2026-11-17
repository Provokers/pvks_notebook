# Treinamento interno Provokers

Notebook do Copilot e Bíblia de Design PVKS.

O conteúdo do `index.html` está criptografado (AES-256-GCM, chave derivada por PBKDF2 com 600.000 iterações). A senha não fica gravada em nenhum arquivo.

## Antes de subir

Coloque o arquivo `AlloVariable.woff2` dentro da pasta `fonts/`. Veja `fonts/LEIA-ME.txt`.

## Publicar no GitHub Pages

1. Crie um repositório novo no GitHub.
2. Envie para a raiz do repositório: `index.html`, `.nojekyll`, `robots.txt`, `README.md` e a pasta `fonts/`.
3. Em Settings > Pages, escolha Deploy from a branch, branch `main`, pasta `/ (root)`, e salve.
4. Em alguns minutos o site fica em `https://SEU-USUARIO.github.io/NOME-DO-REPO/`.

## Atualizar

Para trocar o conteúdo ou a senha, gere um novo `index.html` e substitua o arquivo no repositório.
