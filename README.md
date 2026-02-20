Atualização 01 — 19/02/2026

Dando continuidade no projeto.

Decidi transformar este projeto em uma experiência mais completa. A ideia inicial era somente testar as funcionalidades de cada código, sem ter um objetivo concreto, o que me fez pesquisar um modelo para articular esses testes em um projeto verdadeiro. Entre todas as ideias que tive a curto prazo para dar início aos estudos mais aprofundados, a que melhor me situei foi fazer um portfólio pessoal.

Apesar de a ideia ser bem complexa ao meu ver inicial, decidi continuar o projeto aos poucos, pois considero que, daqui para frente, mesmo que eu não o conclua de cara, já terei uma base sólida de conhecimentos e experiências adquiridas em HTML5. Além disso, terei a base de um projeto útil que utilizarei para possíveis vagas de emprego e exposição de novos repositórios em um futuro próximo.

Detalhando o commit

Irei explicar um pouco de como funciona a arquitetura e as tecnologias deste commit. O HTML5 é uma linguagem de estruturação, o que significa que é ele que faz todo o esqueleto de um site; sem ele, não seria possível inserir as formatações básicas estruturais. Pense em um arquivo .doc que está totalmente vago: sem texto, sem título, até mesmo sem nome. O primeiro passo que você faz, além de criar um arquivo novo, é definir as instâncias cruciais do que deseja que ele tenha, certo? No HTML é a mesma coisa, só que em forma de código.

Para começar a desenvolver, é necessário ter um editor de código. No meu caso, estou utilizando o VS Code, mas é claro que existem vários outros como WebStorm, Adobe Dreamweaver, Vim e Nano. Alguns deles são específicos para trabalhar em outros sistemas operacionais. Após a configuração do editor, o usuário poderá adicionar extensões de trabalho. No meu caso, estou utilizando somente a extensão Live Server, que serve para pré-visualizar a estruturação do site em uma aba da web em LocalHost.

A partir de então, está tudo pronto para começar a codar. Na aba de explorador (Explorer), você já poderá criar um novo arquivo .html. O usuário pode inserir o nome que desejar, mas o ideal é estabelecer um padrão fixo para facilitar o acesso às informações. No meu caso, inseri o nome de index.html. Index significa índice na tradução literal, mas nesse ramo podemos dizer que é o "Ponto de Partida" do HTML; por isso é ideal estabelecer padrões como este em novos projetos. Com isso, abrirá a página onde o usuário poderá escrever as linhas de código.

Separando o código do commit em partes

Recapitulando a ideia do arquivo .doc, podemos perceber que já temos duas coisas prontas:

- Editor de código configurado.
- Arquivo inicial criado.

O próximo passo é começar a escrever o código. Para isso, temos os primeiros comandos básicos que são: <!DOCTYPE html> e <html lang="pt-br">.

O comando <!DOCTYPE html> é o primeiro passo que devemos fazer, pois é ele que informa aos navegadores, independentemente de qual seja, que os dados contidos naquele arquivo foram escritos na versão mais recente do HTML. Já o comando <html lang="pt-br"> informa duas coisas: a tag <html> define a "raiz do código" (todo o conteúdo ficará dentro dela até o seu fechamento em </html>). Por outro lado, o atributo lang="pt-br" informa ao navegador que todo o conteúdo será em uma linguagem específica, no meu caso, o Português do Brasil.

A próxima etapa já entra no que podemos chamar de parte real do projeto, onde começaremos a configurar a estrutura. Geralmente, a primeira coisa que se faz ao escrever um documento novo é definir as configurações e o título, depois a introdução e, por último, o rodapé. Aqui é a mesma coisa.

O comando:

<head>
    <meta charset="UTF-8"> 
    <title> Lucas | Portfólio </title>
</head>

Se estrutura da seguinte maneira: <head></head> refere-se à "cabeça" do código, onde as informações de configuração e metadados são inseridas. O comando <meta charset="UTF-8"> informa ao navegador que o padrão de formatação de caracteres (acentos como ~, ´, , etc.) é específico para aquela linguagem. Isso é necessário porque o padrão inicial do HTML é baseado no inglês (que quase não possui acentos); para evitar erros em diferentes idiomas, determinamos esse padrão no início. Avançando, temos o <title></title>`, que define o título que aparece na aba do navegador.

Logo após, vem o comando <body></body>. Ele informa tudo o que o programador quer que seja efetivamente exibido no site. Dentro dele, inserimos:

<header></header>: Define o cabeçalho visual do site, onde geralmente fica o menu ou o topo.

<nav></nav>: Indica a área de navegação onde ficam os links principais.

<ul></ul>: Cria uma lista não ordenada para organizar os itens.

<li></li>: Define cada item individual dentro dessa lista.

<main></main>: Indica o conteúdo principal e central da página.

<section></section>: Separa o conteúdo em diferentes seções ou temas.

<hr>: Insere uma linha horizontal para dividir visualmente os conteúdos.

<h1> até <h6>: Determinam a hierarquia e a importância dos títulos.

<p></p>: Utilizado para criar parágrafos de texto.

<strong></strong>: Serve para destacar palavras, deixando-as em negrito.

<br>: Realiza uma quebra de linha simples no texto.

<footer></footer>: Define o rodapé, a parte final da página.

<a></a>: Cria links para outras páginas ou para âncoras na mesma página.

<small></small>: Usado para textos menores, como avisos de direitos autorais.

Esta primeira versão ainda não está finalizada.
Meus próximos objetivos são:

- Melhorar a exibição de dados de contato.
- Adicionar imagens e mídias personalizadas.
- Iniciar a estilização do portfólio com CSS.
- Inserir novos conteúdos conforme o aprendizado avança.