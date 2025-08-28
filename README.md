
# Guia de Fornecedores de Materiais Cerâmicos

Arquivos:
- `index_fornecedores.html` — interface do site
- `fornecedores.json` — dados dos fornecedores (edite este arquivo para atualizar a lista)

## Como publicar no GitHub Pages

1. Crie um repositório (ex.: `fornecedores`).
2. Envie os dois arquivos para a raiz do repositório.
3. Ative o GitHub Pages em **Settings → Pages** e selecione a branch `main` (pasta `/root`).
4. Acesse: `https://SEU_USUARIO.github.io/fornecedores/index_fornecedores.html`.

### Comandos (linha de comando)
```bash
git init
git branch -M main
git remote add origin https://github.com/SEU_USUARIO/fornecedores.git
git add index_fornecedores.html fornecedores.json
git commit -m "Publica guia de fornecedores"
git push -u origin main
```
