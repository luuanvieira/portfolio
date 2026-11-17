# Portfólio: Luan Vieira

Site pessoal feito à mão em HTML e CSS, sem framework. Mostra a trajetória e os projetos
(Painel da Agência, Cifrei, Um Pé Sneaker Store e Passione Tattoo Studio).

## Estrutura

```
index.html    conteúdo da página
style.css     estilos (tema "painel industrial")
favicon.svg
img/          prints dos projetos (1280 px, WebP)
```

## Colocar os links dos projetos

Em `index.html`, cada projeto tem dois botões:

```html
<a class="botao" href="" ...>Ver online</a>
<a class="botao botao--contorno" href="" ...>Código</a>
```

Coloque o endereço no `href`. Enquanto estiver vazio, o botão fica escondido.

## Publicar na Vercel (grátis)

1. Suba esta pasta para um repositório no GitHub (ex.: `portfolio`).
2. Entre em vercel.com com a conta do GitHub e clique em **Add New → Project**.
3. Escolha o repositório e clique em **Deploy**. Não precisa configurar nada: é um site estático.
4. Cada `git push` atualiza o site sozinho.

Alternativa: GitHub Pages (Settings → Pages → Deploy from branch → `main`).

## Ver no computador

Abra o `index.html` no navegador, ou rode `npx serve .` na pasta.
