# Pacote de correção — imagem garantida

## Estrutura no GitHub (raiz)
- index.html  → usa '/perfil.jpg?v=1' com quedas para 'perfil.jpg', '/perfil.jpeg', 'perfil.jpeg'
- perfil.jpg  → SUBSTITUA por sua foto real (mantenha exatamente este nome)
- README.md

## Passos
1) Apague do repositório tudo que não for **index.html**, **perfil.jpg**, **README.md**.
2) Envie estes 3 arquivos na **raiz** do repositório.
3) Vercel → Deployments → **Redeploy** → marque **Clear build cache**.
4) Teste direto: `https://SEU-DOMINIO/perfil.jpg?v=1`

Se essa URL abrir a foto, ela aparece no site.
