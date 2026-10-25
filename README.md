# Camaleão Sublimações — site

Site estático (HTML + CSS + imagens), pronto para o GitHub Pages. Não precisa de instalação nem de servidor.

## Estrutura

```
index.html     página do site
favicon.svg    logo (ícone da aba e do topo)
img/           16 fotos de produto (WebP)
```

## Publicar no GitHub Pages

1. Crie uma conta em github.com (pode usar camaleaosublima@gmail.com).
2. Clique em **New repository**. Nome sugerido: `camaleao-sublimacoes`. Deixe **Public**.
3. Na página do repositório: **Add file → Upload files**. Arraste `index.html`, `favicon.svg`, `README.md` e a pasta `img` inteira. Clique em **Commit changes**.
4. Vá em **Settings → Pages**. Em *Source*, escolha **Deploy from a branch**, branch **main**, pasta **/ (root)**. Salve.
5. Em 1 a 3 minutos o site fica no ar em `https://SEU-USUARIO.github.io/camaleao-sublimacoes/`.

## Ativar o WhatsApp

Abra `index.html` (no GitHub: clique no arquivo → ícone de lápis), procure por `const WHATSAPP = "";` e coloque o número com 55 + DDD, só dígitos:

```js
const WHATSAPP = "5515999999999";
```

Salve (Commit). Os botões "Encomendar" passam a abrir o WhatsApp com a mensagem pronta. Enquanto estiver vazio, eles abrem o Direct do Instagram @camaleaoariane.

## Trocar fotos

Substitua o arquivo em `img/` mantendo **o mesmo nome**. Formatos: canecas e camisetas 4:5 (vertical), oversize e mousepads 1:1 (quadrado).

## Domínio próprio (opcional)

Registre o domínio (ex.: camaleaosublimacoes.com.br no registro.br), depois em **Settings → Pages → Custom domain** informe o domínio e siga as instruções de DNS do GitHub.
