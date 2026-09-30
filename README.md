# biranet

Página de pré-lançamento de [bira.net](https://bira.net), com identidade visual em homenagem a Biramar.

## Conteúdo

- `index.html`: página responsiva, estilos e comportamento.
- `assets/biranet.webp`: marca aprovada, em formato sem perda de pixels.
- `assets/inter-regular.woff` e `assets/inter-bold.woff`: fontes locais.
- `FONT-LICENSE.txt`: licença SIL Open Font License das fontes Inter.
- `CNAME`: domínio personalizado existente (`bira.net`).

A página não depende de banco de dados, compilação ou serviços externos. O botão “Por trás do nome” abre a história da marca. A animação respeita a preferência por reduzir movimentos.

## Manutenção

Mantenha o arquivo `index.html` e a pasta `assets` juntos na raiz publicada. Para servir localmente, execute `python3 -m http.server 8080` nesta pasta e abra `http://localhost:8080`.

A versão visual foi aprovada pelo responsável. A imagem foi reencodificada sem perda, com igualdade dos pixels verificada, e as fontes foram convertidas para WOFF. O código JavaScript e as referências de arquivos foram verificados. A conferência visual automatizada não estava disponível no ambiente de criação.
