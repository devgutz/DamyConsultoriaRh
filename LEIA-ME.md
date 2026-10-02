# Damy Consultoria de RH

Site estático com a identidade creme, verde sálvia e terracota da versão anterior, adaptado para consultoria em recursos humanos. O símbolo enviado pela cliente está em `damy-rh-symbol.png` e é usado no cabeçalho, no rodapé, na seção de contato e no favicon. Os demais elementos gráficos são criados em CSS.

## Publicação

Publique **index.html**, **termos-de-uso.html**, **styles.css**, **home.css**, **termos.css**, **favicon.svg**, **damy-rh-symbol.png** e **robots.txt** no diretório público do site, preservando os nomes dos arquivos. `styles.css` contém a identidade visual e os elementos compartilhados; `home.css` estiliza a página inicial; `termos.css` estiliza os Termos de Uso. Cada HTML carrega a base compartilhada antes de sua folha específica. Confira se o servidor entrega o arquivo em `https://SEU-DOMINIO/robots.txt`: regras de um `robots.txt` dentro de uma subpasta não se aplicam ao domínio inteiro. Em GitHub Pages de projeto com endereço `usuario.github.io/repositorio/`, o arquivo precisará ser configurado na raiz de `usuario.github.io` para ter efeito nesse host.

Depois de definir a URL pública definitiva, inclua no `<head>` do HTML `link rel="canonical"` e `meta property="og:url"` com essa URL absoluta. Se desejar publicar um sitemap XML, use a mesma URL pública absoluta para a página e para a diretiva `Sitemap:` no `robots.txt`. Não foram inseridos URLs fictícios para evitar apontar os mecanismos de busca para um endereço antigo ou incorreto.

Confirme com a cliente o número de WhatsApp `(11) 96745-0869`, herdado do arquivo recebido, e o escopo exato dos serviços antes da publicação. Se a página antiga mudar de endereço, configure um redirecionamento permanente para a nova URL no serviço de hospedagem.

## Revisão dos Termos antes da publicação

Os Termos descrevem o site estático atual, sem cadastro, pagamentos nem contratação automática. Confirme o nome ou razão social e CNPJ/CPF do responsável pela operação, o canal de contato, o escopo real dos serviços e a identificação que deve constar na página. Publique uma Política de Privacidade específica, coerente com hospedagem, eventuais ferramentas de análise, WhatsApp, retenção e fornecedores efetivamente usados. Se o site ganhar formulários, contas, pagamentos ou processos seletivos, atualize os Termos antes de ativar essas funções. Recomenda-se revisão jurídica da versão final.

As palavras-chave relevantes aparecem de forma natural no título, na descrição, no título principal e nas seções de serviços. A metatag `keywords` contém apenas sete termos coerentes com o conteúdo; o Google não usa essa metatag como sinal de classificação.
