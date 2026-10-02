# Atualização visual — Flip Design & Soluções 3D

## Referência aplicada

O `index.html` e a paleta foram alinhados aos arquivos de referência enviados (`pasted_content_2.txt` e `pasted_content.txt`). A versão final usa o layout da calculadora Flip, fundo preto quente, superfícies marrom-escuras, textos creme e verde-limão da marca.

## Alterações realizadas

- Substituído o `index.html` pelo HTML completo da referência, incluindo o título “Calculadora — Flip”, a marca curta “Flip” e o popup do Financeiro Flip.
- Substituído o `style.css` pelo CSS completo da referência verde-limão.
- Atualizadas as cores de tema do `index.html` e do `manifest.json` para `#120E09`.
- Restaurado `assets/logo.png` com o símbolo oficial verde da Flip.
- Restaurado `assets/favicon.png` com o favicon oficial verde da Flip.
- Recriados `assets/icon-192.png` e `assets/icon-512.png` a partir do favicon oficial.
- Conferidas as referências do HTML: favicon em `assets/favicon.png`, logo em `assets/logo.png`, Apple Touch Icon e PWA em `assets/icon-192.png`.
- Atualizado o cache do service worker para `flip-calc-v6-reference`, evitando que a versão dourada anterior permaneça instalada.
- Mantidos os links do site e catálogo da Flip.
- Adicionado o Instagram com a estrutura compatível com o JavaScript (`footerSocialLink`/`footerSocialHandle`), usando `@flip_design_solucoes3d` como padrão.
- Rodapé atualizado com direitos autorais da Flip e ano automático usando `new Date().getFullYear()`.
- Ajustado o cabeçalho para separar visualmente “Flip Design & Soluções 3D” de “Calculadora”, com espaçamento e regras responsivas para evitar sobreposição em celulares.
- Mantida a lógica da calculadora e as chaves internas do `localStorage`, preservando históricos e configurações existentes.

## Paleta principal

- Fundo: `#120E09`
- Fundo secundário: `#16110B`
- Superfície: `#17130D`
- Campos: `#1C170F`
- Texto principal: `#F4EFE3`
- Texto comum: `#C9C1B0`
- Verde principal: `#7DC917`
- Verde claro: `#B5E96E`
- Verde escuro: `#55940E`
- WhatsApp: `#25D366`

## Validação

- JavaScript validado com `node --check`.
- Manifesto validado como JSON.
- Arquivos de logo, favicon e ícones verificados como PNG.
- Referências de assets conferidas no HTML e no manifesto.
- Pacote ZIP testado com `unzip -t`.

## Modelo de orçamento profissional

- Adicionado o botão **Orçamento** ao painel de resultado, habilitado após um cálculo válido.
- Criado um modelo comercial premium com fundo off-white, tipografia limpa, detalhes em verde-limão e estrutura completa: identificação, dados do cliente, itens, subtotal, frete, total, pagamento, prazo, observações e rodapé institucional.
- O modal permite editar número, data, cliente, contato, dois itens, frete e prazo.
- Incluídas as ações **Imprimir / PDF**, **Copiar orçamento** e **Enviar pelo WhatsApp**.
- A impressão usa uma folha A4 limpa, ocultando os controles e mantendo apenas o documento comercial.
- Cache PWA atualizado para `flip-calc-v7-professional-quote`.

## Identidade do orçamento e WhatsApp

- O cabeçalho do orçamento agora usa o logo original da Flip (`assets/logo.png`) junto do nome **Flip Design & Soluções 3D**.
- A linha de atividades foi atualizada para: Impressão 3D • Modelagem 3D • Prototipagem • Personalização • Peças Sob Medida • Miniaturas • Brindes Personalizados • Projetos 3D.
- O texto enviado pelo WhatsApp passou a usar a mesma marca e a mesma lista de atividades.
