# A Lógica da Justiça Matemática

Site do trabalho da **Equipe Beremiz Samir** para a Mostra de Lógica para Computadores 2026/2 (ESAMC Uberlândia, Sistemas de Informação).

O site explica o **Problema dos 8 Pães**, do Capítulo III de *O Homem que Calculava* (Malba Tahan), e a solução em VisuAlg:

- vídeo explicativo da equipe, com capítulos por integrante;
- o dilema das 8 moedas (5 e 3 contra 7 e 1);
- a lógica dos terços (1 pão = 3 pedaços);
- simulador para testar outros números;
- código VisuAlg executado passo a passo, com memória e console;
- fluxograma, teste de mesa, conclusões e referências.

Todo o site é um único arquivo: `index.html`. Não precisa de instalação nem de build.

## Colocar o vídeo do YouTube

Abra o `index.html`, procure por `LINK DO VÍDEO NO YOUTUBE` e cole o link entre as aspas:

```js
const VIDEO_URL = "https://youtu.be/XXXXXXXXXXX";
```

O vídeo passa a tocar dentro do site e os capítulos abrem no minuto de cada integrante.

## Publicar com GitHub Pages

1. No repositório, abra **Settings → Pages**.
2. Em **Source**, escolha **Deploy from a branch**.
3. Selecione a branch `main` e a pasta `/ (root)` e clique em **Save**.
4. Em cerca de 1 minuto o site fica disponível em `https://<seu-usuario>.github.io/<nome-do-repositorio>/`.

Depois de publicar, gere o QR Code da folha A4 com esse endereço.

## Equipe

Mateus Rausch Voz de Alcântara, Ítalo Távio de Oliveira, Davi Alves Lima, Lucas Gabriel Faria, Cauã Araújo e David Israel.

Orientação: Prof.ª Daniela Carvalho Monteiro Ferreira. Disciplina: Lógica para Computadores (2026/2).
