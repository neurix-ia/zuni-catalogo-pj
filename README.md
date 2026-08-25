# Zuni Atacado — catálogo digital PJ

Catálogo digital enviado pelo agente Zuni no meio da conversa do WhatsApp, pra clientes PJ (restaurante, hotel/pousada, salão de eventos) navegarem modelos, cores e diferenciais sem sair do fluxo do chat.

## Estrutura

- `index.html` — página completa, autocontida (imagens embutidas como data URI, sem dependência externa além do Google Fonts).
- `assets/` — fotos de origem usadas na página (comprimidas para web).

## Como funciona

A página não tem CTA de "falar no WhatsApp" — ela assume que a pessoa já está numa conversa com o agente e só saiu pra ver o catálogo. Ao clicar num modelo e/ou numa cor, aparece uma barra fixa embaixo com um botão "Copiar pra colar no chat", que gera um texto tipo:

> Oi! Já escolhi aqui no catálogo: modelo Retangular Externo, cor Vinho. Pode me ajudar a fechar o pedido?

A pessoa cola isso de volta na conversa do WhatsApp e o agente/vendedora segue o atendimento a partir dali.

## GitHub Pages

Se habilitado, a página fica acessível em `https://neurix-ia.github.io/zuni-catalogo-pj/`.

## Fonte dos assets

Material fornecido pela Zuni Couros (fotos e vídeos reais dos produtos). Vídeos não foram incluídos nesta versão — arquivo fica pesado demais pra abrir de forma confiável em celular (limite de memória do navegador mobile pra vídeo embutido). Enviados separadamente.
