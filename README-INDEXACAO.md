# Pacote de Indexação (Google)
Arquivos incluídos:
- robots.txt
- sitemap.xml
- google1234567890abcdef.html  (ARQUIVO DE EXEMPLO — troque pelo arquivo EXATO que o Search Console fornecer)

## Como usar
1) **Envie `robots.txt` e `sitemap.xml` para a RAIZ do seu site** (mesma pasta do index.html).
2) **No Google Search Console**:
   - Adicione a propriedade de domínio: drarafaelasanvezzo.com.br
   - Método recomendado: **TXT no Registro.br** (DNS) — mais estável.
   - Alternativa: **Arquivo HTML**. Se escolher este método, o Google vai dar um nome de arquivo (ex.: `googleXXXXXXXXXXXX.html`) e um conteúdo. **Baixe o arquivo do Google e envie para a raiz do site.** O arquivo `google1234567890abcdef.html` aqui é apenas um **exemplo** para você ver como fica.
3) Em **Sitemaps**, envie: `sitemap.xml`
4) Em **Inspeção de URL**, cole suas páginas principais e clique **Solicitar indexação**.

## Dicas
- Após publicar, teste no navegador:
  - https://drarafaelasanvezzo.com.br/robots.txt
  - https://drarafaelasanvezzo.com.br/sitemap.xml
  - https://drarafaelasanvezzo.com.br/google1234567890abcdef.html  (se usar verificação por arquivo HTML)
- Se o Search Console disser que a URL não está disponível (404), é porque o arquivo **não está no deploy**. Refaça o deploy com **Clear build cache** na Vercel.
