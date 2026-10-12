# SIGHT

Site institucional estático em português brasileiro. O arquivo de entrada é `index.html`. Não há dependências, JavaScript, formulário, servidor de aplicação ou etapa de compilação.

## Publicação

No GitHub Pages, publique a raiz do repositório com `index.html`, `css/` e `assets/`. Todos os caminhos são relativos e funcionam também em repositórios de projeto.

Para revisar localmente, abra `index.html` no navegador ou inicie um servidor estático nesta pasta.

## Identidade visual

O cabeçalho e o rodapé usam diretamente `assets/logo.JPG`, com enquadramento via CSS para retirar as margens. O arquivo original permanece intacto. Pequenas variações do fundo do JPG são suavizadas nas bordas do enquadramento.

O favicon é um recorte quadrado do símbolo original, reduzido para 64 × 64 pixels.

Todas as cores da interface estão em `:root`, no início de `css/style.css`. O fundo predominante do JPG é #1A2835. O destaque #F3AF8A foi amostrado da forma interna em pêssego. Os gradientes e as variações de compressão do logo original são preservados; não são cores adicionais da interface.

## Contato

O endereço `rafael@sight.solar` tem um link `mailto:` que abre o aplicativo de e-mail do visitante.

## Área para vídeo

O elemento `#hero-video-slot` reserva a área de fundo do destaque inicial. Ao inserir um vídeo, preserve a legibilidade do texto e a ilustração alternativa. Use arquivos locais otimizados, sem áudio, com controle acessível para pausar. Respeite a preferência de movimento reduzido e evite carregar vídeo nessa situação. Mantenha a página abaixo de 5 MB e cada arquivo abaixo de 25 MB.

## Revisão

As capturas e o relatório atualizados ficam na pasta `review/`. Não são carregados pelo site e não precisam ser publicados.
