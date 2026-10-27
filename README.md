# Lava Car Kuster

Site de pedidos do Lava Car Kuster. O cliente vê os serviços com descrição e preço, escolhe o que quer, preenche os dados e envia tudo pelo WhatsApp com a mensagem já montada.

WhatsApp: (28) 99921-4001

## Como funciona

É um único arquivo, o `index.html`, sem servidor e sem banco de dados. O botão do WhatsApp é um link `https://wa.me/NUMERO?text=MENSAGEM`, montado em JavaScript com os serviços escolhidos.

## Como editar

Tudo fica no topo do `<script>` em `index.html`:

- `WHATSAPP`: número com 55 + DDD, só dígitos.
- `SERVICOS`: categoria, nome, preço, descrição e foto de cada serviço. `apartir: true` mostra "a partir de" no preço. Para usar uma foto, coloque a imagem numa pasta `fotos/` e preencha `foto: "fotos/nome.jpg"`.

## Demonstração

`demo.mp4` mostra um pedido do começo ao fim (gravado com os preços de exemplo da primeira versão).
