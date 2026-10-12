# YugenYumi Client — Site Premium com Capturas Reais

Esta versão atualiza o site anterior **sem reconstruí-lo**, usando as **21 capturas reais** enviadas do Launcher YugenYumi **9.0.0-dev**. O rótulo do projeto apresentado no site continua **9.1.0-dev**. As imagens são históricas e estão identificadas corretamente no próprio site.

## Publicar no GitHub Pages

1. Extraia o ZIP recebido.
2. Envie **os arquivos que estão dentro de `yugenyumi-site-main/`** para a **raiz** do repositório GitHub Pages, substituindo `index.html`, `styles.css`, `script.js`, `site-config.js` e a pasta `assets/`.
3. Se o GitHub Pages ainda não estiver ativo: Settings > Pages > Deploy from a branch > branch `main` > `/(root)`.
4. Aguarde a atualização. Para descartar cache visual antigo do navegador, use Ctrl+F5.

**Não publique o ZIP inteiro como arquivo dentro do repositório esperando que o Pages o abra automaticamente**. O Pages precisa ler o `index.html` na pasta configurada.

## Conteúdo novo

- Hero com **captura real** do Launcher; alternância entre Início, Módulos e Configurações Gerais.
- 21 capturas reais, com thumbnails de carregamento progressivo, preservando proporções e sem cortes.
- Filtros: Interface, Recursos, Personalização e Sistema.
- Visor em destaque (lightbox) com botões anterior/próximo, Escape, setas do teclado e gesto de deslizar no celular.
- Visual dark glass e tons violeta/ciano combinando com o Launcher, em desktop e celular.
- Site estático em HTML/CSS/JavaScript, sem build, sem Node e sem cookies/serviços de terceiros obrigatórios para o funcionamento. Fontes externas são opcionais e possuem fallback.

## Versões e links

Edite o arquivo `site-config.js` para trocar:

- `version`: versão do client anunciada no site (hoje: `9.1.0-dev`);
- `screenshotVersion`: versão de onde vieram as capturas (hoje: `9.0.0-dev`);
- `releaseUrl`: endereço verdadeiro das Releases para downloads oficiais;
- `repositoryUrl`: endereço verdadeiro do projeto no GitHub.

**Atenção:** os links de repositório/Releases foram preservados da versão anterior e apontam para `carlosvcl/yugenyumi-site`; verifique se é o repositório correto antes de compartilhar o site para downloads. O site não incorpora executáveis `.exe` e não promete que já exista Release pública.

## Capturas

Arquivos em `assets/screenshots/`:

- Cada tela possui uma versão `.webp` de alta definição (1919 pixels de largura) e outra `-thumb.webp` reduzida para carregar a galeria rapidamente.
- Os arquivos originais PNG enviados continuam sendo os originais desta conversa; o site usa WebP otimizado apenas para diminuir o tamanho de carregamento.
- As telas documentam elementos visuais, não garantem que cada recurso exibido esteja finalizado ou testado no jogo.

Para substituir capturas futuras, atualize os arquivos/imagens e as entradas de `screenshots` no `site-config.js` e os cards correspondentes do `index.html`.

## Testes locais

Revisados em Chromium nas larguras 320, 360, 390, 430, 560, 600, 768, 820, 1024, 1280, 1440 e 1920 px, incluindo filtros, lightbox, setas de navegação, hero interativo e menu mobile.

O YugenYumi é um projeto independente e não é afiliado à Mojang Studios ou Microsoft.
