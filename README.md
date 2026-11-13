# Longe lar onde fujo de mim

Site do romance **Longe lar onde fujo de mim**, de João Manoel Bentes.

É um site estático de um único arquivo: tudo (HTML, CSS, JavaScript e imagens) está dentro de `index.html`, sem etapa de build e sem dependências além das fontes do Google Fonts.

## Ver localmente

Abra o `index.html` no navegador. Se preferir um servidor local:

```bash
python3 -m http.server 8000
# depois acesse http://localhost:8000
```

## Publicar com GitHub Pages

1. Envie esta pasta para um repositório no GitHub.
2. No repositório, vá em **Settings → Pages**.
3. Em **Build and deployment**, escolha **Deploy from a branch**, branch `main` e pasta `/ (root)`.
4. Salve. Em alguns minutos o site fica disponível em `https://SEU-USUARIO.github.io/NOME-DO-REPOSITORIO/`.

## Capítulos na leitura gratuita

Atualmente estão no site os capítulos 1 a 9. Para adicionar o próximo, cole um bloco como o abaixo em `index.html`, logo acima do comentário `PRÓXIMOS CAPÍTULOS`:

```html
<section class="capitulo" id="capitulo-10">
  <h2>Capítulo Dez ou Título</h2>
  <p>Parágrafo.</p>
</section>
```

A aba do capítulo aparece sozinha: o que vem antes de " ou " no título vira o número da aba. Sussurros no meio do texto usam `<span class="voz">(Eu te vejo)</span>`.

## Link de compra

Quando a loja estiver no ar, preencha a constante `LINK_COMPRA` no começo do `<script>` de `index.html`. Os três botões de compra passam a funcionar.

## Direitos

© 2026 João Manoel Bentes. Todos os direitos reservados. O texto e as ilustrações do livro não podem ser reproduzidos sem autorização.
