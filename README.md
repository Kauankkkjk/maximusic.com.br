# Site Max Music (demonstração)

Loja virtual da Max Music (instrumentos musicais, Belém/PA) em um único arquivo: `index.html`.
Não precisa de instalação nem de build. Fontes, imagens e scripts já estão dentro do arquivo.

## Publicar no GitHub

1. No GitHub, clique em **New repository** e crie um repositório novo (sugestão: `max-music-site`).
2. Em **Add file > Upload files**, envie `index.html` e `README.md`.
3. Clique em **Commit changes**.

## Publicar na Vercel

1. Em vercel.com, entre com sua conta do GitHub e clique em **Add New > Project**.
2. Escolha o repositório `max-music-site` e clique em **Import**.
3. Em **Framework Preset**, deixe **Other**. Não precisa de comando de build.
4. Clique em **Deploy**. Em cerca de um minuto sai o link `.vercel.app`.
5. Para usar um domínio próprio: **Settings > Domains** no projeto da Vercel.

Cada novo commit no GitHub publica a atualização automaticamente.

Atenção: o plano gratuito (Hobby) da Vercel é voltado a uso pessoal e não comercial. Confira os termos atuais antes de publicar o site de uma loja. Alternativas que também servem sites estáticos: Cloudflare Pages, Netlify e GitHub Pages.

## Como editar

Abra `index.html` e procure:

- `const PRODUTOS` — lista de produtos (nome, marca, categoria, resumo, ficha técnica).
  Para mostrar preço, adicione `preco: 999.90` ao produto. Para promoção, adicione também `antigo: 1199.90`.
  Sem `preco`, o site mostra "Consulte o valor" e o pedido vai pelo WhatsApp.
- `const EMPRESA` — razão social, CNPJ e e-mail usados nas políticas de privacidade e cookies.
- `const HERO` — banners do topo (um por marca).

## Observações

- As políticas de privacidade e de cookies são um modelo. Peça a um profissional para revisar antes do uso real.
- O fechamento do pedido é pelo WhatsApp. Não há pagamento online nem controle de estoque.
- Fontes embutidas: TeX Gyre Heros Cn (GUST Font License) e Poppins (SIL Open Font License).
