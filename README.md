# Puff Produtos — site

Página única (HTML + CSS + um pouco de JavaScript), sem dependências. Abre rápido no telemóvel.

## O que tem
- Pedido em 3 toques (produto → quantidade → nome e zona) que abre o WhatsApp com a mensagem pronta.
- Origem (120 m), qualidade, "para a tua rotina", enchimento no Rocha Pinto, produtos, lojas, perguntas frequentes.
- Barra fixa no telemóvel com "Ligar" e "Fazer pedido".

## Onde mudar
- **Número do WhatsApp:** em `index.html`, procurar `var WA = "244959103750"`.
- **Telefone visível:** procurar `959 103 750` e `tel:+244959103750`.
- **Lojas e links do mapa:** secção `<!-- Lojas -->`.
- **Perguntas:** secção `<!-- Perguntas -->`.
- **Imagens:** pasta `imagens/` (WebP otimizado).

## Publicar na Vercel
Add New → Project → importar `puffprodutos` → Framework Preset **Other** → Deploy.
