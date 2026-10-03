# Damy Consultoria de RH — pacote de publicação

Site estático em português para `https://devgutz.github.io/DamyConsultoriaRh/`. Mantém a identidade em creme, verde sálvia e terracota, com o símbolo enviado pela cliente em `damy-rh-symbol.png`. Os elementos gráficos das páginas são feitos em CSS.

## Arquivos

| Arquivo | Uso |
| --- | --- |
| `index.html` | Página inicial e acesso aos quatro serviços. |
| `estruturacao-de-rh.html`, `recrutamento-e-selecao.html`, `treinamento-e-desenvolvimento.html`, `desenvolvimento-de-liderancas.html` | Páginas próprias de cada serviço. |
| `termos-de-uso.html`, `politica-de-privacidade.html` | Documentos do site. |
| `styles.css`, `home.css`, `servico.css`, `termos.css` | Base comum e estilos das páginas inicial, de serviços e legais. |
| `damy-rh-symbol.png`, `favicon.svg` | Símbolo e ícone. |
| `sitemap.xml`, `robots.txt` | Arquivos técnicos. |
| `robots-raiz-github-pages.txt` | Modelo para a raiz de `devgutz.github.io`; **não** publicá-lo com esse nome como arquivo ativo. |

## Publicação no GitHub Pages

Publique os arquivos do site na raiz do repositório que alimenta `/DamyConsultoriaRh/`, mantendo nomes e links relativos. Não publique `index(1).html`: essa cópia de trabalho não faz parte do pacote e criaria outra URL para a página inicial. Abra a página inicial, cada serviço, os Termos, a Política de Privacidade e `sitemap.xml` depois da atualização para conferir o resultado ao vivo.

O GitHub Pages deste projeto usa o host `devgutz.github.io`. O arquivo `robots.txt` dentro de `/DamyConsultoriaRh/` **não controla o rastreamento desse host**. Para tornar ativa a diretiva `Sitemap`, coloque o conteúdo de `robots-raiz-github-pages.txt` como `robots.txt` na raiz do site `https://devgutz.github.io/` (normalmente no repositório de usuário `devgutz.github.io`, se existir). Se outros projetos compartilham o host, preserve as regras e sitemaps que já estiverem nesse arquivo e acrescente a linha deste projeto. A ausência de um `robots.txt` na raiz não bloqueia o rastreamento por padrão.

As URLs canônicas, `og:url`, dados estruturados e sitemap foram definidos para o endereço público acima. Se o domínio mudar, atualize todos antes da publicação. Depois, configure o redirecionamento do endereço antigo quando possível.

## Google Search Console

Verifique a propriedade correspondente a `https://devgutz.github.io/DamyConsultoriaRh/` ou uma propriedade de domínio que a inclua. Envie `https://devgutz.github.io/DamyConsultoriaRh/sitemap.xml` em **Sitemaps**. Use **Inspeção de URL** para verificar a página inicial e as páginas de serviços; envie a solicitação de indexação se necessário. O sitemap e as metatags são sinais, não garantias de indexação ou posição.

## Revisão com a cliente antes de considerar a entrega final

Confirme o número `(11) 96745-0869`, o nome empresarial ou identificação pública adequada da responsável, o escopo real dos quatro serviços e o canal para pedidos de privacidade. Os textos legais descrevem esta versão estática, sem formulário, analytics, pagamentos ou recebimento de currículos no site. Confira a operação real de WhatsApp, a conservação das conversas, fornecedores e bases legais com a cliente e, quando necessário, com orientação jurídica. Se forem adicionados formulários, cookies, analytics ou fluxos de seleção de candidatos, revise a Política de Privacidade e os Termos antes de ativá-los.
