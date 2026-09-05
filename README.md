# daylon-site

Site estático simples para deploy no Cloudflare Pages.

Como publicar no Cloudflare Pages
1. Acesse https://dash.cloudflare.com/ e abra a seção Pages.
2. Crie um novo projeto e conecte o repositório GitHub `daylonnoleto/daylon-site`.
3. Configure:
   - Branch: `main`
   - Framework preset: None (ou Static)
   - Build command: deixe vazio
   - Build output directory: `/` (ou deixe em branco, dependendo da UI)
4. Crie o projeto — o Cloudflare Pages fará deploy automático nas alterações no branch configurado.

Conteúdo do repositório
- `index.html` — página principal (já adicionada).
- `style.css` — estilos (já adicionada).
- `README.md` — este arquivo com instruções.
