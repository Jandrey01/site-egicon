# Site da Egicon

Este é um site institucional de uma página feito com HTML, CSS e JavaScript, sem bibliotecas adicionais. Para visualizar, abra `index.html` no navegador. Os botões do WhatsApp abrem uma conversa com o número informado pelo escritório.

## Arquivos

- `index.html`: conteúdo e estrutura das seções.
- `styles.css`: cores, tipografia, layout e adaptações para telas menores.
- `script.js`: menu para celular e ano automático no rodapé.
- `vercel.json`: cabeçalhos de segurança para as respostas do site na Vercel.

## Publicação na Vercel

Se estes arquivos forem a raiz do repositório, selecione o preset **Other** e deixe o comando de build vazio: a Vercel pode servir diretamente um site feito apenas com HTML, CSS e JavaScript. Se o repositório incluir as pastas acima, configure `outputs/site-egicon` como **Root Directory**. O `vercel.json` precisa ficar na raiz selecionada.

## Personalização

As cores provisórias estão no início de `styles.css`, dentro de `:root`. A marca tipográfica “E” está no HTML e pode ser substituída pela logo quando ela estiver pronta. A seção de atuação está genérica porque a lista detalhada de serviços ainda será definida.

Antes de publicar, revise com a responsável pelo escritório os dados de contato, a lista de serviços e os textos.

## Antes de publicar como site oficial

- Confirme os dados e os contatos com a responsável pelo escritório.
- Inclua o número de registro da organização contábil no CRC-RS. O CFC orienta que a publicidade digital de organizações contábeis mostre razão social ou nome fantasia, CNPJ e esse registro.
- Combine um aviso de privacidade que explique o tratamento de dados ligado à hospedagem. O site não tem formulário, analytics ou scripts de terceiros; a Vercel informa que pode processar IP, cidade/país aproximados e dados técnicos de acesso.
- O site não usa mapa incorporado: o visitante só acessa o Google Maps ou o WhatsApp se clicar nos respectivos links.

O número de registro no CRC-RS não foi incluído porque precisa ser confirmado pelo escritório.
