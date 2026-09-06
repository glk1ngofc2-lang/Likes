# Free Fire API Tester

Site estático para GitHub Pages, apontando para:

`https://free-api-like-freefire-1-bzin.onrender.com`

## Publicar no GitHub Pages

1. Crie um repositório no GitHub.
2. Envie `index.html`, `style.css` e `README.md`.
3. Vá em **Settings → Pages**.
4. Em **Build and deployment**, selecione **Deploy from a branch**.
5. Escolha `main` e `/ (root)`.
6. Salve e aguarde o GitHub Pages publicar.

## Importante: CORS

Como o site roda no navegador, a API precisa permitir requisições do domínio do GitHub Pages através de CORS. Se o indicador mostrar **"API Offline ou CORS bloqueado"**, isso pode significar CORS, mesmo que a API esteja funcionando normalmente.

Nesse caso, mantenha a API/backend como está e coloque um pequeno proxy/backend no servidor da API. Não coloque tokens secretos no JavaScript do GitHub Pages.
