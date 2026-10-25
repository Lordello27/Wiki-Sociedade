# Wiki de lore

## Publicar no GitHub Pages
1. Crie um repositório e envie todos estes arquivos para a branch `main`.
2. Em `index.html`, preencha `CONFIG.repo` com `"seu-usuario/seu-repo"` e mude o `title`.
3. No GitHub: **Settings → Pages → Source: GitHub Actions**.
4. A cada commit, o site é republicado e o índice de páginas é gerado automaticamente.

## Como escrever
- Cada página é um arquivo `.md` dentro de `content/` (pastas livres).
- Cabeçalho opcional no topo: `titulo`, `categoria`, `imagem` e `infobox` (a caixa lateral).
- `[[Nome da Página]]` ou `[[Nome|texto]]` cria links; se a página não existe, o link fica vermelho e leva à criação.
- Imagens: coloque em `images/` e use `![descrição](images/arquivo.png)`.
- Botão **Editar** no site: edita com pré-visualização; para publicar, use "Abrir no GitHub" e faça o commit.

## Testar no computador
Abra um terminal na pasta e rode `python3 -m http.server`, depois acesse http://localhost:8000
(abrir o `index.html` direto do arquivo não funciona).
