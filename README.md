# AR Kids — site

Site estático (HTML + imagens) da AR Kids, loja de moda infantil em Boa Vista - RR.
Não tem build: a Vercel só publica os arquivos.

## Estrutura (tudo na raiz do repositório)

```
index.html
vercel.json
README.md
img/
  logo-redonda.png, favicon.png, apple-touch-icon.png
  loja-*.jpg, look-*.jpg, sacola.jpg
```

## Publicar na Vercel

1. No GitHub, crie um repositório (ex.: `ar-kids`) e envie **o conteúdo** desta pasta, não o .zip e não uma pasta dentro de outra. O `index.html` precisa aparecer na primeira tela do repositório.
2. Na Vercel: **Add New → Project → Import** o repositório.
3. Configuração:
   - Framework Preset: **Other**
   - Root Directory: **./** (deixe como está)
   - Build Command: deixe **vazio**
   - Output Directory: deixe **vazio**
   - Install Command: deixe **vazio**
4. Clique em **Deploy**.

Criado por Vendora Labs — instagram.com/vendora_labs
