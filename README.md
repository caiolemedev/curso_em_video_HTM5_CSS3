# curso_em_video_HTM5_CSS3
 Curso de HTML5 and CSS3 do canal Curso em Video

<h1>Anotações</h1>

<h2>Módulo 1</h2>

**Capítulo 1 - Aulas 0~4**
    <p>Introdução, literatura e história da internet</p>
***
**Capítulo 2 - Aula 1 - Como a internet funciona?**
    <p>1 byte = 8 bits <br>
    Padrão de representação: UTF-8 <br>
    MB = megabyte - utilizado para armazenamento <br>
    Mb = megabit - utilizado para transmissão <br>
    modem = aparelho de modulação e demodulação <br>
    cliente - computador do usuário <br>
    servidor - base de dados onde serão buscadas as informações <br>
    DNS - Domain Name System - funciona como uma "lista telefônica" dos servidores <br>
    Sistemas de rotas - são os caminhos que os dados são transferidos entre servidor e cliente </p>
***
**Capítulo 2 - Aula 2 - O que é domínio e hospedagem?**
    <p>Novo site criado no meu PC não pode ser acessada por outra pessoa
    Para acesso a sites desenvolvidos por mim é necessário um domínio (endereço) e uma hospedagem (servidor)
    Domínio = Nome único, pago anualmente, vários TLDs
    Hospedagem = espaço de armazenamento, pago mensalmente, suporte para e-mail e linguagens
    URL - dividida em:
        subdomínio = www ou caiolemedev
        domínio = github.com (com, br, gov, au, -> final do domínio é o TLD)
        caminho = /caiolemedev </p>
***
**Capítulo 3 - Aula 1 - A diferença entre HTML, CSS e JavaScript**
    <p>HTML e CSS não são linguagens de programação
    "Eu desenvolvo em HTML e CSS" - forma correta
    HTML - hypertext markup language
        Focada em conteúdo: texto, imagem, vídeo, tabela, etc.
    CSS - cascading style sheets
        Focada no design: tamanho, posição, cores, sombras, etc.
    JS - JavaScript
        Focada nas interações: botões, validações, animações, pop-ups, etc.
    Conteúdo HTML - abertura e fechamento de tags:
        < h1> título < /h1>
        < p> parágrafo < /p>
        < img src="foto.png" alt="Exemplo de foto">
        Toda tag pode ter parâmetros e valores
    Estilo CSS - dentro de uma tag style com uso de seletores:
        h1 {
            font-family: Arial;
            font-size: 20pt;
            color: blue;
        }
        Declarações dentro do seletores com propriedade e valores
        Precisa finalizar com ";"
    Estrutura básica para o HTML
        Tipo de documento = HTML
        Língua do documento = lang (pt-br)
        Dividido em head (configurações) e body (conteúdo)
        No head:
            meta charset = UTF-8 (para usar acentuação)
            name = viewport e content = ...1.0 (utilizar toda área do navegagor e não aplicar zoom)
            title = título do site
        No body:
            colocar o conteúdo, por ex título com h1
    Como funciona no chrome: analisar a cópia gerada do HTML e CSS original e apresentar a interpretação visual </p>
***
**Capítulo 3 - Aula 2 - Front-end, Back-end e Full stack**
    <p>Site estático - mesmo site distribuído para todos os clientes
    Front-end:
        Tecnologias Client-Side (funcionam no navegador do cliente): HTML, CSS e JS
    Back-end:
        Tecnologias Server-Side (funcionam no servidor): PHP, JS (Node), C#, Phyton, Ruby e Java
    Funcionamento: cliente (produz site dinâmico) > servidor (produz "site" HTML) > banco de dados
    Full Stack = Front-end + Back-end </p>
***
**Capítulo 4 - Aula 1 - Instalando todas as ferramentas**
    <p>Programas necessários: Chrome, Visual Studio Code, Plugin para visualizar página no VS e GitHub Desktop (versionamento) </p>
***
**Capítulo 4 - Aula 2 - Seu primeiro código em HTML**
    <p>Desenvolvido ex001 - Olá, mundo! (salvo na pasta de exercícios desse repositório)</p>
***
**Capítulo 5 - Aula 1 - Parágrafos e Quebras**
    <p>Desenvolvido ex002 - Parágrados e Quebras de Linha (salvo na pasta de exercícios desse repositório)
    Obs: utilizado caracteres especiais de maior e menor por meio de código &lt; e &gt; </p>
***
**Capítulo 5 - Aula 2 - Símbolos e Emoji no seu tite**
    <p>Editado ex002 - Adicionando símbolos especiais e emojis através de códigos (atualização salva na pasta de exercícios desse repositório)
    Obs: para adicionar emojis corretamente colocar &#x antes de depois o código hexadecimal da emojipedia (após o U+)
    Exemplo: &#x1F919; </p>
***
**Capítulo 6 - Aula 1 - Você tem direito de usar qualquer imagem no seu site?**
    <p>Procurar imagem no Google > ferramentas > Direitos de uso<br>
    Ou acessar Unsplash, Pexels e outros bancos de imagem gratuitos</p>
***
**Capitulo 6 - Aula 2 - Quais são os formatos para imagens na Web?**
    <p>Formatos: JPEG (mais compacto) ou PNG (permite transparência).</p>
***

**Capítulo 6 - Aula 3 - O tamanho das imagens importa para um site?**
    <p>Tomar cuidado com tamanho da imagem para o site não ficar pesado demais. Gimp para ajustar e redimensionar. Grande = 1500, Média = 600, lateral = 400, rodapé = 200.</p>
***

**Capítulo 6 - Aula 4 - A tag img em HTML5**
    <p>Construindo ex003 com imagens na mesma pasta, em subpastas e via URL externa (salvo na pasta de exercícios desse repositório)</p>
***

**Capítulo 6 - Aula 5 - Como mudar o favicon de um site**
    <p>Formato .ico, acessar favicon.io para converter ou criar um favicon. Para adicionar, no campo head digitar link, escolher a opção favicon e selecionar o arquivo desejado. Criado ex004 com o favicon (salvo na pasta de exercícios desse repositório).</p>
***

**Capítulo 7 - Aula 1 - Hierarquia de Títulos**
    <p>Os titulos são marcado pela tag h de 1 à 6 respeitando a hierarquia conforme um índice de livro. </p>
***

**Capítulo 8 - Aula 1 - Semântica no HTML5**
    <p>Semântica => significado é mais importante que a forma. Tomar cuidado com tags que não são mais utilizadas como bgcolor, u, font no HTML. As tags de forma foram migradas para as folhas de estilo em CSS. Verificar tags obsoletas no site w3.org</p>
***

**Capítulo 8 - Aula 2 - Negrito e Itálico**
    <p>Diferença de tags semânticas e não semânticas (de forma). Tags de forma serão usadas no CSS no HTML devemos usar semânticas, como stong e em no exercício 008.</p>
***

**Capítulo 8 - Aula 3 - Formatações adicionais em HTML**
    <p>Demonstrado outras tags para texto marcado, excluído, inserido, sobrescrito e subscrito adicionadas ao exercício 008.</p>
***

**Capítulo 8 - Aula 4 - Citações e Códigos**
    <p>Praticando mais tags HTML como código-fonte, pré-formatação, abreviações e citações no exercício 009.</p>
***

**Capítulo 9 - Aula 1 - Listas OL e UL**
    <p>Criação de listas ordenadas e não odenadas. Tags type para modificar o indexador da lista. Na lista ordenda para começar de outro número se usa a tag start.</p>
***

**Capítulo 9 - Aula 2 - Listas mistas e de definição**
    <p>Criação de listas mistas dentro das listas principais, ajustada formatação interna. Lista de definições para criação de dicionários.</p>
***

**Capítulo 10 - Aula 1 - Links e Âncoras em HTML5**
    <p>Cada link possui uma âncora. Primeiro buscador do google é o google e o segundo é o youtube (também é do google). SEO - search engine optimization - otimização do site para ser encontrado pelo google. Para abrir em uma nova aba colocar target = _blank e rel = external. Para links patrocinados ou outras fontes, é possível usar a tag rel = nofollow</p>
***

**Capítulo 10 - Aula 2 - Links internos**
    <p>Para fazer um link interno você pode ter outras páginas dentro da original. Não precisa da url inteira mas para navegar nas pastas usar ./ para subir o nível, ../ sobe dois níveis. Para usar as tags inserir target = _self e rel = next ou prev, facilita a procura pelos mecanismos de busca.</p>
***
**Capítulo 10 - Aula 3 - Links para Downloads**
    <p>Incluir o link do arquivo na tag href e inserir as tags download = nome do arquivo e type conforme lista da iana media types.</p>
***

**Capítulo 11 - Aula 1 - Imagens Dinâmicas**
    <p>Criação de 3 imagens de tamanhos diferentes no GIMP para 3 tipos de dispositivos diferentes: celular, tablet e computador.</p>
***

**Capítulo 11 - Aula 2 - Imagens que se adaptam sozinhas**
    <p>Usando a tag source dentro da tag picture é possível carregar imagens diferentes usando max ou min width em px. A imagem base fica na tag img e será carregada como padrão caso tenha espaço, normalmente usamos a maior. Precisa ser feita na ordem do menos para o maior.</p>
***

**Capítulo 11 - Aula 3 - Colocando audios no seu site**
    <p>Carregando audios no site via tag audio, parâmetros como autoplay (não funcionou), controls e loop são possíveis. É recomendado colocar em mp3 ou ogg, e pode-se tentar carregar de diferentes formas para evitar problemas.</p>
***
**Capítulo 11 - Aula 4 - Formatos de vídeo**
    <p>Baixar videos para livre uso no pexels e converter utilizando o handbreak. Preparar videos e formatos para o site, mais utilizado é o mp4</p>
***

**Capítulo 11 - Aula 5 - Vídeos em hospedagem própria**
    <p>Adicionando videos usando a tag video, similar com imagens. Buscar diferentes tipos para compatibilidade com vários navegadores. Usar tag controls para reprodução e poster para capa do vídeo. Sempre adicionar parágrafo alternativo para navegadores sem suporte.</p>
***

**Capítulo 11 - Aula 6 - Incorporação de vídeos de fontes externas**
    <p>No youtube, usar o botão compartilhar e selecionar incorporar, ajustar os parâmetros e inserir no seu site, tags anteriores não são necessárias.</p>
***

**Capítulo 12 - Aula 1 - Estilos CSS inline**
    <p>Usar a tag style em cada parâmetro para editar o estilo (propriedades CSS) de cada item do site. Essa técnica polui o HTML.</p>
***

**Capítulo 12 - Aula 2 - Estilos CSS internos**
    <p>Criação de estilos internos. Melhor que o anterior pois edita por tags, portanto simplifica. Mas existem desvantagens como ser específico para uma única página e ser muito grande para ficar no mesmo arquivo que o conteúdo.</p>
***

**Capítulo 12 - Aula 3 - Estilos CSS externos**
    <p>Criar um arquivo externo CSS com o estilo das páginas e referenciar via links em todas. As alterações na página de estilo serão aplicadas a todas. É possível adicionar mais de uma folha de estilo no mesmo arquivo html por meio de links, eles serão somados. Podemos utilizar os 3 métodos de estilo mas eles respeitarão a hierarquia inline > interno > externo.</p>
***

<h2>Módulo 2</h2>

**Capítulo 13 - Aula 01 - Psicologia das Cores com CSS3**
    <p>Cada cor exerce um impacto diferente nas pessoas e influenciam a decisão de consumo das pessoas. Exemplo: facebook, twitter, linkedin, intel, etc.. todas azuis. Texto branco com letras pretas causa cansaço para sites com muito textos.</p>
***

**Capitulo 13 - Aula 02 - Representando cores com CSS3**
    <p>Podemos inserir cor de várias formas: por nome, por código hexadecimal (6 dígitos, sendo 2 representando vermelho, 2 de verde e 2 de azul), RGB (red, green and blue) e HSL (hue, saturation and luminosity).</p>
***

**Capítulo 13 - Aula 03 - Harmonia de cores**
    <p>Circulo cromático combina simetria com as cores. Cores Primárias, Secundárias e Terciárias (cor primária-cor secundária, parecido com tons pastéis). Divisão por "temperatura". Partir a escolha pela cor principal que passará o sentimento geral, de 3 a 5 cores (+ preto e branco), verificar cor primária da logo. Cores complementares (contraste, lado oposto), cores análogas (com ou sem complementar), cores analogas relacionadas (duas cores analogas e pula uma), cores intercaladas (escolhe uma e pula outra, mas é mais "dura"), cores triádicas, monocromia (1 cor alterando saturação e luminosidade) </p>
***

**Capítulo 13 - Aula 04 - Paleta de cores**
    <p>Criar uma paleta de cores usando Adobe Color. Como extrai tema e degrade de uma imagem para criar paleta. Usando o paletton para gerar um exemplo de site.</p>
***

**Capítulo 13 - Aula 05 - Como capturar cores da tela?**
    <p>Para capturar cores dos sites é só instalar a extensão colorzilla. Colocar o mouse em cima da cor e clicar para copiar o código hexadecimal.</p>
***

**Capítulo 13 - Aula 06 - Como criar degradê com CSS?**
    <p>Usar comando backgournd.image com a função interna linear-gradient indicando direção (to top, right, etc ou 45deg), primeira cor, segunda cor, terceira cor, etc. Para configurações globais das CSS usar o seletor *{}. Não usar muitas cores e exagerar no gradiente. Cores usadas: rgb(139, 214, 219),rgb(31, 178, 189).</p>
***

**Capítulo 13 - Aula 07 - Criando um exemplo real**
    <p>Construindo um exemplo de site com diferentes configurações para body, main, h1, h2 e p. Cada cor foi retirada da paleta do adobe colors e as configurações básicas usadas para ajustar o estilo em arquivo separado.</p>
***

**Capítulo 14 - Aula 01 - Primeiros passos em Tipografia**
    <p>Na idade média os livros eram copiados a mão. Gutenberg investou a prensa mecânica de tipos móveis. Tipografia surgiu para criar estulos de letras mais adequadas para leitura. Letras também transmitem sentimentos.</p>
***

**Capítulo 14 - Aula 02 - Anatomia do tipo**
    <p>Análise da fonte Times new roman que é a fonte padrão das maiorias dos navegadores. A fonte é baseada pela letra x minúscula. A altura do corpo (total) é o que é configurado na CSS.</p>
***

**Capítulo 14 - Aula 03 - Famílias de fonte em CSS**
    <p>Usar font-family com mais de 1 parâmetro para não ter problemas com o tipo de dispositivo. Terminar a declaração sempre com uma fonte genérica. É possível coloar o mesmo estilo pra mais de uma tag, basta seprar por vírgula, ex: h1, h2 {}.</p>
***

**Capítulo 14 - Aula 04 - Tamanho de fonte e suas medidas**
    <p>Medidas absolutas: cm, mm, in, px, pt, pc. Medidas relativas: em (relativo a altura m), ex (relativo a altura x), rem (relativo ao root, fonte do body), vw (relativo a largura da tela), vh (relativo a altura da tela) e % (porcentagem). Utilizar a referência em! 16px é o tamanho normal, que é igual a 1 em.</p>
***

**Capítulo 14 - Aula 05 - Peso, estilo e shorthand font**
    <p>Para escolher o peso da fonte usar: font-weight. Parâmetros: literais (normal, bold, etc.) ou numéricos (de 100 até 900). Nem todas as fontes tem todas as opções. Font-style para colocar itálico e text-decoration para sublinhar.  Short hand: font: style weight size family (deve respeitar a sequência).</p>
***

**Capítulo 14 - Aula 06 - Usando Google Fonts**
    <p> Acessar Google Fonts e selecionar a fonte e estilos da fonte que deseja utilizar. Colocar dentro da tag style ou no arquivo CSS a função import (não necessário baixar).</p>
***

**Capítulo 14 - Aula 07 - Usando fontes externas**
    <p>Acessar dafont para baixar as fotnes e colocar na pasta do projeto. Criar a fonte com a regra font-face (tomar cuidado com o modo de configurar). Para inserir colocar o format () como opentype (otf), truetype(ttf), embedded-opentype, truetype-aat (Apple Advanced Typography), svg.</p>
***

**Capítulo 14 - Aula 08 - Capturando fontes de um site**
    <p>Instalar extensão Fonts Ninja no chrome para "ler" uma fonte de um site. Clicar no ninja, não precisa assinar o serviço e o app vai mostrar todas as fontes usadas. Ao passar o mouse por cima e mostra todas as características da letra. É possível testar a fonte numa janela pop-up e copiar o código da fonte.</p>
***

**Capítulo 14 - Aula 09 - Capturando fontes de imagens**
    <p>Usar sites como: whatfontis, carregar imagem e seguir os passos do site para tentar identificar a fonte. Não é muito preciso e pode não funcionar.</p>
***

**Capítulo 14 - Aula 10 - Alinhamento de texto com CSS**
    <p>Alinhamento de texto com a propriedade text-align. Deve ser feito somente via CSS dentro da tag style ou na folha de estilo. Para dar o espaçamento de início de parágrafo utilizar text-indent e a medida.</p>
***

**Capitulo 15 - Aula 01 - Usando o id com CSS**
    <p>Usar seletores personalizados quando existem 2 elementos da mesma classe mas requerem configurações diferentes. A # no CSS identifica id do HTML e . no CSS identifica class do HTML. Usar: h1#principal ou só #principal.</p>
***

**Capítulo 15 - Aula 02 - As diferenças entre id e class**
    <p>A regra do W3C é utilizar somente 1 id espcifico por elemento por página HTML. Utilizar class para classificar os elementos similares e utilizar a mesma configuração. É possível ter um elemento com id e class, mas o id se sobrepõe ao class. Configurações genéricas e depois específicas.</p>
***

**Capítulo 15 - Aula 03 - Pseudo-classes em CSS**
    <p>Pseudo-classes são para configurações de estado, colocar id ou class : pseudo-classe. Aplicação de estado para mostrar menus de dropdown quando colocar o mouse em cima usando tag display.</p>
***

**Capítulo 15 - Aula 04 - Pseudo-elementos em CSS**
    <p>Usando pseudo-classes para configurar os links de acordo com uma ação. É possível criar pseudo-elementos usando :: após a classe ou id. Para usar um children precisamos colocar > após o id ou class. Cada uma é utilizada em um tipo de situação diferente dentro de um seletor personalizado.</p>
***

**Capítulo 16 - Aula 01 - Modelo de Caixas: primeiro passos**
    <p>Características: height, width, border, padding (espaço entre conteúdo e borda), margin (espaço entre borda e outro elemento) e ouline (fora da borda). Tipos de caixa: box-level (sempre ocupa a largura total da tela e pula uma linha para inserir outra box) e inline-level (não pula linha e não quebra linha para inserir uma nova caixa). Box-level: div, h1, p, main, header, nav, article, aside, footer, form e video. Inline-level: span, a, code, small, strong, em, sup, sub, label, button, input e select.</p>
***

**Capítulo 16 - Aula 02 - Modelo de Caixas na prática pt1**
    <p>Analisando com chrome: user agent stylesheet são as configurações padrões do navegador. Usar o devtools para verificar as alterações e alterar momentaneamente a página.</p>
***

**Capítulo 16 - Aula 03 - Modelo de Caixas na prática pt2**
    <p>Margem com configuração auto centraliza a caixa. Simplificando os comandos usando shorthand. border: width style color; padding: top right bottom left; ou padding 10px; ou padding 10px 20px; (1o valor é top e bot é 10px e o right e left é 20px). Margin segue padding e outline segue border. Display altera o modo como é apresentado a caixa, inline-block mostra o elemento na linha mas com características de bloco.</p>
***

**Capítulo 16 - Aula 04 - Grouping Tags em HTML5**
    <p>Criado ex box02 para demonstrar a utilização das tags e configurações principais. Não existe uma hierarquia padrão para as tags, somente para facilitar as buscas separar o body por header, main e footer.</p>
***

**Capitulo 16 - Aula 05 - Sombra nas Caixas**
    <p>Usar shorhand do box-shadow: right bottom spread black. Usar sempre preto e colocar transparência um pouco abaixo de 50%. Usar antes dos deslocamentos inset para borda interna do elemento.</p>
***

**Capítulo 16 - Aula 06 - Caixas com vértices arredondados**
    <p>Usar shorthand do comando border-radius: top-left top-right bottom-right bottom-left. Pode ser usada como percentual e se o elemento for quadradado, usar 50% transforma num circulo.</p>
***

**Capítulo 16 - Aula 07 - Bordas decoradas**
    <p>Criar arquivo para a borda e inserir como border-image-source. Não recomendo!!</p>
***

**Capítulo 16 - Aula 08 - Desafio!**
    <p>Desafio é o capítulo 17 inteiro!</p>
***

**Capítulo 17 - Aula 01 - Criando um mini projeto**
    <p>Preparando o ambiente com as informações e arquivos necessários.</p>
***

**Capítulo 17 - Aula 02 - Navegando pelo projeto pronto**
    <p>Análise do projeto pronto com as funções e responsividades.</p>
***

**Capítulo 17 - Aula 03 - Planejando a estrutura do site**
    <p>Preparando a estrutura do site usando mockflow e achando as fontes adequadas.</p>
***

**Capítulo 17 - Aula 04 - Layout -> Código**
    <p>Esboço do conteúdo no site e criação do arquivo CSS.</p>
***

**Capítulo 17 - Aula 05 - Organizando o conteúdo**
    <p>Organização do conteúdo, colocar links, imagens e videos e criando a lista do site.</p>
***

**Capítulo 17 - Aula 06 - Variáveis em CSS**
    <p>Configurando as cores e fontes usando variáveis no CSS. Usar seletor root e declarar variável com 2 traços antes ( --cor0). Para configurações globais usar seletor *, ex: colocar todas as margens e paddings para zero.</p>
***

**Capítulo 17 - Aula 07 - Responsividade na prática**
    <p>Responsividade com tamanho mínimo e máximo para ser utilizado em diferentes dispositivos. Tamanhos máximos e mínimos para a main do site, img com 100% de largura e substituída por outra quando reduzir muito (usando picture).</p>
***

