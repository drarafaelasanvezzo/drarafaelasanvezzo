# Pacote FINAL — caminho RELATIVO da imagem

## O que fazer
1) No GitHub, apague tudo que não for **index.html**, **perfil.jpg**, **README.md**.
2) Envie estes 3 arquivos na **raiz** do repositório.
3) Na Vercel, em Settings → Build & Output Settings:
   - Framework Preset: Other
   - Build Command: (vazio)
   - Install Command: (vazio)
   - Output Directory: (vazio)
4) Em Deployments, faça **Redeploy** e marque **Clear build cache**.
5) Teste: abra a URL do site e confira se a foto aparece.

## Observações importantes
- O `index.html` usa **caminho RELATIVO**: `perfil.jpg`
  → O arquivo **perfil.jpg** deve estar na MESMA pasta do `index.html`.
- Verifique no GitHub se o nome é exatamente **perfil.jpg** (sem .JPG, sem espaço, sem .jpeg).
- Em Windows, desative “Ocultar extensões dos tipos de arquivo conhecidos” para não virar `perfil.jpg.jpg`.
