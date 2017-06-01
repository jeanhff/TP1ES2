**DESCRIÇÃO DO SISTEMA**

Pelican é um sistema de código aberto escrito em Python, sendo um gerador de
site estático que não requer banco de dados e operações feitas (lógica) no lado
do servidor.

Com o Pelican é possível escrever seu próprio conteúdo com o seu editor de
escolha nos formatos reStructuredText ou Markdown. O Pelican possui uma
ferramenta simples chamada de CLI que (re)gera o seu site, além disso, facilita
a interação com sistemas distribuídos de controle de versão e web hooks.

 ![](https://github.com/jeanhff/TP1ES2/blob/master/images/image13.png)

Fonte:
[http://docs.getpelican.com/en/stable/report.html](http://docs.getpelican.com/en/stable/report.html)

O sistema possui uma ótima integração com o Jinja2, o que torna o processo de
criação dos temas muito mais fácil e intuitivo. É fácil de estender o Pelican,
apesar de já possuir uma série de plugins e temas para diferentes fins.

Além de ser fácil de usar, a ferramenta pelican-quickstart possui uma estrutura
de projeto bem consistente, incluindo tasks de publicação através Makefile e
Fabric. Configurando o pelicanconf.py, escolhendo o tema preferido e mais
alguns passos, o sistema já está pronto para uso.O Pelican possui uma
documentação simples, porém muito completa.

Outras features são:

- Publicar conteúdo em várias linguagens
- Atom/RSS feeds
- Destaque para sintaxe de código
- Importação do WordPress, DotClear, RSS feeds, e outros serviços
- Integração com ferramentas externas: Twitter, Google Analitics

O objetivo do Pelican é acabar com problemas como indisponibilidade do banco de
dados, websites invadidos por falha de segurança e acabar com a dificuldade de
se configurar um servidor. Além disso é facilitar a manutenção e manipulação,
pois a persistência é feita no disco do usuário, podendo manter o site
versionado no GitHub.

O Pelican é desenvolvido em Python e possui seu código fonte disponível no
GitHub em https://github.com/getpelican/pelican.

**EQUIPE DE DESENVOLVIMENTO**

Pelican é um sistema que possui, até o momento, dia 18/05, 6870 estrelas e 1382
forks. Possuindo 299 contribuidores, com 2971 commits e 44 releases.

A imagem abaixo demonstra os commits ao longo dos anos por usuário, desde
agosto de 2010 até os dias atuais, maio de 2017. Vemos os dois principais
desenvolvedores com seus respectivos commits:

-
●●Alexis Metaireau (almet), com 285 commits
 ![](https://github.com/jeanhff/TP1ES2/blob/master/images/image9.png)
-
●●Justin Mayer (justinmayer) com 196 commits
 ![](https://github.com/jeanhff/TP1ES2/blob/master/images/image7.png)

Fonte:
[https://github.com/getpelican/pelican/graphs/contributors](https://github.com/getpelican/pelican/graphs/contributors)

Pelos gráficos presentes nas imagens, percebe-se que o usuário almet estava
bastante ativo no começo do projeto, depois deixou de ser ativo, em meados de
2013. Já Justin começou a participar do projeto no ano de 2012, sendo mais
      ativo em 2013 e tendo participações ao longo dos anos.

**EVOLUÇÃO DO SISTEMA**

O projeto Pelican no GitHub foi iniciado no início de agosto de 2010, tendo seu
primeiro release no dia 19 de agosto de 2010 (versão 1.1) tendo como marco o
seu primeiro packaging. Posteriormente temos uma série de releases para
tratamento de problemas iniciais do projeto como tratamento e exibição de erros
quando ocorrem, atualização de ferramentas de setup e bumping de versões.

Vemos o início do tratamento de erros como no tema do sistema e particularidade
em parses de certos tipos de arquivo (versão 1.2.3), porém ainda sem maturidade
de registro de issues ligados aos releases. O projeto vai se desdobrando e
evoluindo resolvendo problemas pontuais como adição de logos, preocupação de
parses de metadados na tradução de conteúdo para HTML (versão 2.0).

A evolução continua com o ajuste de temas para valores default do Pelican,
melhorias nas produções de páginas, expansão do suporte para tipos de arquivo
PDF, novas atualizações do módulo de setup bem como acertos em pequenos
problemas e introdução de novas idéias ao projeto (versão 2.5.0).

Logo percebe-se uma evolução em pontos chaves do projeto de desenvolvimento de
software, como ajustes na branch principal e resolução de problemas mais
complexos como erros na instalação da aplicação no Sistema Operacional Windows
(versão 2.8.1). Com o passar do tempo, a comunidade começa a ter uma
participação mais ativa na criação de issues e também com pull requests
associados aos lançamentos de novos releases.

**ISSUES**

As issues ligadas ao projeto do Pelican no GitHub podem ser verificadas em:

[https://github.com/getpelican/pelican/issues](https://github.com/getpelican/pelican/issues)
. Tais issues movem o desenvolvimento fomentando novas funcionalidades bem como
apresentando pontos de falhas no sistema. No momento atual temos 965 issues
fechadas e um grande número de issues abertas, cerca de 84, muitas delas a
serem revisados, algumas apontando novos recursos e outras pendentes, veja a
imagem abaixo de acordo com as tags de classificação das issues:



 ![](https://github.com/jeanhff/TP1ES2/blob/master/images/image11.png)

Neste contexto apresentamos algumas milestones importantes para o projeto.
Temos até o momento, dia 18/05, 11 milestones fechadas, segue em ordem
cronológica de fechamento e algumas de suas particularidades:

- 08/2012 - release 3.0: Ajustes em erros pontuais vistos na última atualização
  documental, acertos na tipografia, ajustes na abertura da Wiki para sites
Demos. Acertos em variáveis locais, warnings na geração de feeds, testes
funcionais.
- 09/2012 - release 3.0.1: Acertos na Documentação como adição de lista de
  plugins acessíveis.
- 12/2012 - release 3.1: Ajustes na reescrita de URLs, extração de dados nos
  nomes de arquivos, adição de testes para webassets, em testes funcionais, em
páginas estáticas, adição de emoticons, em geradores de páginas PDF,
compatibilidade com o Google Analytics.
- 04/2013 - release 3.2: Ajustes no cabeçalho de temas, melhorias junto o
  jinja, acertos com arquivos do tipo Markdown, melhoria em recursos de
tradução de saída, acertos na geração de nomes de arquivos inválidos, acertos
em mensagens de aviso, remoção de plugins, atualizações na documentação e
ajustes nas dependências, ajustes no mapeamento de emails de usuários, ajustes
em tags dos artigos principais.
- 09/2013 - release 3.3: Acertos na discordâncias de arquivos Markdown,
  adaptação em URLs em ambiente de desenvolvimento, acertos na instalação do
Pytz, solução para Makefile em ambiente Windows, acertos para suportes junto a
Python 3, ajustes na geração de PDF, ajustes na importação Tumblr.
- 07/2014 - release 3.4: Ajustes no Python 3.3 junto ao Mac OS X, acertos nas
  tradução de links, renomeação de variáveis de ambiente, criação se uma seção
para implantações na documentação, melhorias na velocidade.
- 11/2014 - release 3.5: Ajustes na localização de imagens nos diretórios de
  conteúdo, ajustes em páginas e artigos excluídos para sub diretórios, acertos
nas configurações da documentação, ajustes nas tags de configuração
relacionadas a tipografia.
- 06/2015 - release 3.6: Ajustes nos campos de Metadados, ajustes no
  carregamento externo de recursos via HTTPS, ajustes na geração de links por
meio de tags.
- 08/2015 - release 3.6.2: Ajustes na instalação com Python 3 no Linux, ajustes
  na instalação do Pelican junto ao Python 3 no Windows, ajustes na instalação
com Python 3.4, ajustes em templates de paginação,
- 12/2016 - release 3.7: Ajustes na documentação, ajustes nas configurações de
  cabeçalho, ajustes na localização de inicialização do Pelican, acertos em
arquivos de configuração.
- 01/2017 - release 3.7.1: Ajustes no Quickstart local, acertos na
  especificação de codificação de arquivos de instalação.

Temos ainda uma milestone em aberto, que indica a próxima versão (3.8) do
sistema. Este possui 9 pull request já aceitos como acertos em páginas vazias,
melhorias e atualizações nas expressões regulares tratando certos warnings,
adição de ambiente de teste para Python 3.6, dentre outros, e um pull request
pendente relacionado com melhorias no gerador de arquivos estáticos, além de um
issue a resolver visto na padronização de paginação necessitando configurações
adicionais.

Desde agosto de 2010 até o momento foram feitos 2790 commits para atender
diversas necessidades do projeto, para melhor visualização veja a imagem abaixo
com o número de commits ao longo do tempo:

 ![](https://github.com/jeanhff/TP1ES2/blob/master/images/image2.png)

Fonte:
[https://github.com/getpelican/pelican](https://github.com/getpelican/pelican)

**CONTRIBUIÇÕES**

Como característica de um projeto de código aberto, o Pelican se mantém por
meio de contribuição de desenvolvedores e potenciais testers e analistas.
Mantendo esse padrão de desenvolvimento o Pelican possui uma Wiki para guiar os
contribuintes explicando como iniciar o estudo do sistema, exibindo seções de
ajuda e tutoriais de como contribuir com o projeto, no intuito de manter uma
padronização e qualidade de código. Veja em
[https://github.com/getpelican/pelican/wiki](https://github.com/getpelican/pelican/wiki)
.

**FRAMEWORKS, FERRAMENTAS E LINGUAGENS**

 ![](https://github.com/jeanhff/TP1ES2/blob/master/images/image12.png)

**Python**

Pelican é desenvolvido principalmente em python atualmente compatível com as
versões 2.7, 3.3, e 3.4 da linguagem.
Python é uma linguagem de programação moderna e elegante projetada
principalmente para ser produtiva e legível.

**CSS e HTML**

HTML é uma linguagem de marcação utilizada para construir páginas web enquanto
CSS é uma linguagem de mesmo tipo usada para estilizar estilizar estas páginas.
No código fonte do Pelican estas linguagens são encontradas principalmente em
templates e exemplos visto que o principal objetivo do programa e gerar páginas
web.

**Tox**

** **

Tox é uma ferramenta para automação de testes em python. No pelican ele é usado
para garantir que o código funcione em diferentes versões da linguagem e que
todas suas dependências são compatíveis e estão presentes, como pode ser visto
no trecho abaixo, extraído do arquivo tox.ini encontrado na raiz do Pelican.

 ![](https://github.com/jeanhff/TP1ES2/blob/master/images/image5.png)

**Bumpr**

Bumpr é uma ferramenta para auxiliar no controle de versão e liberação de novas
releases.

O Arquivo de configuração do bumpr do pelican pode ser visto na figura abaixo.

 ![](https://github.com/jeanhff/TP1ES2/blob/master/images/image3.png)

**Wheel**

Wheel é uma ferramenta para criar pacotes python, ou seja  uma estrutura lógica
que incorpora a versão específica de um projeto python incluindo seu código,
recursos e metadados.

**Flake8**

Flake8 e uma ferramenta que força os desenvolvedores a seguirem um determinado
estilo de código mantendo-o consistente em todo o projeto.

**Mock**

Mock é uma ferramenta para realizar testes de unidade em python.

**Jinja2**

Jinja é um mecanismo de template  para a linguagem de programação Python.
mecanismo de template web são usadas para a geração automática de páginas web
personalizadas. Jinja é um mecanismo de template baseado em texto e, portanto,
pode ser usada para gerar qualquer marcação, bem como código fonte.

**ARQUITETURA**

Visão simplificada das classes do Pelican.

 ![](https://github.com/jeanhff/TP1ES2/blob/master/images/image1.jpg)

Fonte:
[http://docs.getpelican.com/en/stable/report.html](http://docs.getpelican.com/en/stable/report.html)

Esta imagem é apenas uma simplificação do sistema, pois o mesmo não possui
interfaces e utiliza duck typing.



- **Writers:**  São responsáveis para escrever em arquivos, sejam eles: .html,
  RSS feeds, etc. Como são operações comumentes usadas,  os objetos são criados
uma vez e passados ao generator. Este é um dos motivos da adesão ao duck
typing, sua ampla utilização em Python, tendo classes semelhantes à arquivo.
Possui tratamento de paginação, deixando os arquivos bem organizados de acordo
com a entrada. A imagem abaixo ilustra a parte do código de paginação.

 ![](https://github.com/jeanhff/TP1ES2/blob/master/images/image6.png)

-
●● **Readers** : São utilizados para ler de vários formatos de entrada como
HTML, Markdown e reStructured text. À partir de um arquivo, o readers retornam
dados e conteúdo, sendo conteúdo em formato HTML. A sintaxe também deve ser
levada em consideração, se o arquivo seja no formato reStructured text,
Markdown ou HTML, deve-se inserir os dados com a seguinte sintaxe:
 ![](https://github.com/jeanhff/TP1ES2/blob/master/images/image8.png)
 ![](https://github.com/jeanhff/TP1ES2/blob/master/images/image10.png)
 ![](https://github.com/jeanhff/TP1ES2/blob/master/images/image4.png)
A primeira imagem refere-se a sintaxe do reStructured Text, a segunda Markdown
e a terceira HTML.
Todas as três imagens podem ser encontradas na página:
http://docs.getpelican.com/en/3.6.3/content.html
- **Generators:** Gera diferentes saídas de acordo com a configuração
  escolhida, como por exemplo gerar uma saída provida pelo reader que faz a
interpretação de um arquivo.

**REFERÊNCIAS**

- Disponível em
  [http://docs.getpelican.com/en/stable/](http://docs.getpelican.com/en/stable/).
Acesso em 08/05/17.
- GitHub, Pelican. Disponível em
  [https://github.com/getpelican/pelican/](https://github.com/getpelican/pelican/).
Acesso em 08/05/17.
- Disponível em
  [https://www.w3schools.com/html/](https://www.w3schools.com/html/). Acesso em
08/05/17.
- Diponível em [adobe.com/br/](http://www.adobe.com/br/). Acesso em 08/05/17.
- Disponível em
  [https://www.microsoft.com/pt-br/windows/](https://www.microsoft.com/pt-br/windows/).
Acesso em 08/05/17.
- Google Analytics. Disponível em
  [https://analytics.google.com/](https://analytics.google.com/). Acesso em
08/05/17.
- Wikipédia, Markdown. Disponível em
  [https://pt.wikipedia.org/wiki/Markdown](https://pt.wikipedia.org/wiki/Markdown).
Acesso em 08/05/17.
- Disponível em [http://pytz.sourceforge.net/](http://pytz.sourceforge.net/).
  Acesso em 08/05/17.
- Disponível [https://www.python.org/](https://www.python.org/). Acesso em
  08/05/17.
- Disponível em [https://www.tumblr.com/](https://www.tumblr.com/). Acesso em
  08/05/17.
- Mac OS. Disponível em
  [https://www.apple.com/macos/sierra/](https://www.apple.com/macos/sierra/).
Acesso em 08/05/17.
- Disponível em
  [https://en.wikipedia.org/wiki/HTTPS](https://en.wikipedia.org/wiki/HTTPS).
Acesso em 08/05/17.
- Disponível em [http://br-linux.org](http://br-linux.org). Acesso em 08/05/17.
