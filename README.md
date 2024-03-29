# curso_em_video_HTM5_CSS3

Curso de HTML5 and CSS3 do canal Curso em Video

<h1>Anotações</h1>

<h2>Módulo 1</h2>

**Capítulo 1 - Aulas 0~4**

<p>Introdução, literatura e história da internet</p>

---

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

---

**Capítulo 2 - Aula 2 - O que é domínio e hospedagem?**

<p>Novo site criado no meu PC não pode ser acessada por outra pessoa
Para acesso a sites desenvolvidos por mim é necessário um domínio (endereço) e uma hospedagem (servidor)
Domínio = Nome único, pago anualmente, vários TLDs
Hospedagem = espaço de armazenamento, pago mensalmente, suporte para e-mail e linguagens
URL - dividida em:
subdomínio = www ou caiolemedev
domínio = github.com (com, br, gov, au, -> final do domínio é o TLD)
caminho = /caiolemedev </p>

---

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

---

**Capítulo 3 - Aula 2 - Front-end, Back-end e Full stack**

<p>Site estático - mesmo site distribuído para todos os clientes
Front-end:
Tecnologias Client-Side (funcionam no navegador do cliente): HTML, CSS e JS
Back-end:
Tecnologias Server-Side (funcionam no servidor): PHP, JS (Node), C#, Phyton, Ruby e Java
Funcionamento: cliente (produz site dinâmico) > servidor (produz "site" HTML) > banco de dados
Full Stack = Front-end + Back-end </p>

---

**Capítulo 4 - Aula 1 - Instalando todas as ferramentas**

<p>Programas necessários: Chrome, Visual Studio Code, Plugin para visualizar página no VS e GitHub Desktop (versionamento) </p>

---

**Capítulo 4 - Aula 2 - Seu primeiro código em HTML**

<p>Desenvolvido ex001 - Olá, mundo! (salvo na pasta de exercícios desse repositório)</p>

---

**Capítulo 5 - Aula 1 - Parágrafos e Quebras**

<p>Desenvolvido ex002 - Parágrados e Quebras de Linha (salvo na pasta de exercícios desse repositório)
Obs: utilizado caracteres especiais de maior e menor por meio de código &lt; e &gt; </p>

---

**Capítulo 5 - Aula 2 - Símbolos e Emoji no seu tite**

<p>Editado ex002 - Adicionando símbolos especiais e emojis através de códigos (atualização salva na pasta de exercícios desse repositório)
Obs: para adicionar emojis corretamente colocar &#x antes de depois o código hexadecimal da emojipedia (após o U+)
Exemplo: &#x1F919; </p>

---

**Capítulo 6 - Aula 1 - Você tem direito de usar qualquer imagem no seu site?**

<p>Procurar imagem no Google > ferramentas > Direitos de uso<br>
Ou acessar Unsplash, Pexels e outros bancos de imagem gratuitos</p>

---

**Capitulo 6 - Aula 2 - Quais são os formatos para imagens na Web?**

<p>Formatos: JPEG (mais compacto) ou PNG (permite transparência).</p>

---

**Capítulo 6 - Aula 3 - O tamanho das imagens importa para um site?**

<p>Tomar cuidado com tamanho da imagem para o site não ficar pesado demais. Gimp para ajustar e redimensionar. Grande = 1500, Média = 600, lateral = 400, rodapé = 200.</p>

---

**Capítulo 6 - Aula 4 - A tag img em HTML5**

<p>Construindo ex003 com imagens na mesma pasta, em subpastas e via URL externa (salvo na pasta de exercícios desse repositório)</p>

---

**Capítulo 6 - Aula 5 - Como mudar o favicon de um site**

<p>Formato .ico, acessar favicon.io para converter ou criar um favicon. Para adicionar, no campo head digitar link, escolher a opção favicon e selecionar o arquivo desejado. Criado ex004 com o favicon (salvo na pasta de exercícios desse repositório).</p>

---

**Capítulo 7 - Aula 1 - Hierarquia de Títulos**

<p>Os titulos são marcado pela tag h de 1 à 6 respeitando a hierarquia conforme um índice de livro. </p>

---

**Capítulo 8 - Aula 1 - Semântica no HTML5**

<p>Semântica => significado é mais importante que a forma. Tomar cuidado com tags que não são mais utilizadas como bgcolor, u, font no HTML. As tags de forma foram migradas para as folhas de estilo em CSS. Verificar tags obsoletas no site w3.org</p>

---

**Capítulo 8 - Aula 2 - Negrito e Itálico**

<p>Diferença de tags semânticas e não semânticas (de forma). Tags de forma serão usadas no CSS no HTML devemos usar semânticas, como stong e em no exercício 008.</p>

---

**Capítulo 8 - Aula 3 - Formatações adicionais em HTML**

<p>Demonstrado outras tags para texto marcado, excluído, inserido, sobrescrito e subscrito adicionadas ao exercício 008.</p>

---

**Capítulo 8 - Aula 4 - Citações e Códigos**

<p>Praticando mais tags HTML como código-fonte, pré-formatação, abreviações e citações no exercício 009.</p>

---

**Capítulo 9 - Aula 1 - Listas OL e UL**

<p>Criação de listas ordenadas e não odenadas. Tags type para modificar o indexador da lista. Na lista ordenda para começar de outro número se usa a tag start.</p>

---

**Capítulo 9 - Aula 2 - Listas mistas e de definição**

<p>Criação de listas mistas dentro das listas principais, ajustada formatação interna. Lista de definições para criação de dicionários.</p>

---

**Capítulo 10 - Aula 1 - Links e Âncoras em HTML5**

<p>Cada link possui uma âncora. Primeiro buscador do google é o google e o segundo é o youtube (também é do google). SEO - search engine optimization - otimização do site para ser encontrado pelo google. Para abrir em uma nova aba colocar target = \_blank e rel = external. Para links patrocinados ou outras fontes, é possível usar a tag rel = nofollow</p>

---

**Capítulo 10 - Aula 2 - Links internos**

<p>Para fazer um link interno você pode ter outras páginas dentro da original. Não precisa da url inteira mas para navegar nas pastas usar ./ para subir o nível, ../ sobe dois níveis. Para usar as tags inserir target = \_self e rel = next ou prev, facilita a procura pelos mecanismos de busca.</p>

---

**Capítulo 10 - Aula 3 - Links para Downloads**

<p>Incluir o link do arquivo na tag href e inserir as tags download = nome do arquivo e type conforme lista da iana media types.</p>

---

**Capítulo 11 - Aula 1 - Imagens Dinâmicas**

<p>Criação de 3 imagens de tamanhos diferentes no GIMP para 3 tipos de dispositivos diferentes: celular, tablet e computador.</p>

---

**Capítulo 11 - Aula 2 - Imagens que se adaptam sozinhas**

<p>Usando a tag source dentro da tag picture é possível carregar imagens diferentes usando max ou min width em px. A imagem base fica na tag img e será carregada como padrão caso tenha espaço, normalmente usamos a maior. Precisa ser feita na ordem do menos para o maior.</p>

---

**Capítulo 11 - Aula 3 - Colocando audios no seu site**

<p>Carregando audios no site via tag audio, parâmetros como autoplay (não funcionou), controls e loop são possíveis. É recomendado colocar em mp3 ou ogg, e pode-se tentar carregar de diferentes formas para evitar problemas.</p>

---

**Capítulo 11 - Aula 4 - Formatos de vídeo**

<p>Baixar videos para livre uso no pexels e converter utilizando o handbreak. Preparar videos e formatos para o site, mais utilizado é o mp4</p>

---

**Capítulo 11 - Aula 5 - Vídeos em hospedagem própria**

<p>Adicionando videos usando a tag video, similar com imagens. Buscar diferentes tipos para compatibilidade com vários navegadores. Usar tag controls para reprodução e poster para capa do vídeo. Sempre adicionar parágrafo alternativo para navegadores sem suporte.</p>

---

**Capítulo 11 - Aula 6 - Incorporação de vídeos de fontes externas**

<p>No youtube, usar o botão compartilhar e selecionar incorporar, ajustar os parâmetros e inserir no seu site, tags anteriores não são necessárias.</p>

---

**Capítulo 12 - Aula 1 - Estilos CSS inline**

<p>Usar a tag style em cada parâmetro para editar o estilo (propriedades CSS) de cada item do site. Essa técnica polui o HTML.</p>

---

**Capítulo 12 - Aula 2 - Estilos CSS internos**

<p>Criação de estilos internos. Melhor que o anterior pois edita por tags, portanto simplifica. Mas existem desvantagens como ser específico para uma única página e ser muito grande para ficar no mesmo arquivo que o conteúdo.</p>

---

**Capítulo 12 - Aula 3 - Estilos CSS externos**

<p>Criar um arquivo externo CSS com o estilo das páginas e referenciar via links em todas. As alterações na página de estilo serão aplicadas a todas. É possível adicionar mais de uma folha de estilo no mesmo arquivo html por meio de links, eles serão somados. Podemos utilizar os 3 métodos de estilo mas eles respeitarão a hierarquia inline > interno > externo.</p>

---

<h2>Módulo 2</h2>

**Capítulo 13 - Aula 01 - Psicologia das Cores com CSS3**

<p>Cada cor exerce um impacto diferente nas pessoas e influenciam a decisão de consumo das pessoas. Exemplo: facebook, twitter, linkedin, intel, etc.. todas azuis. Texto branco com letras pretas causa cansaço para sites com muito textos.</p>

---

**Capitulo 13 - Aula 02 - Representando cores com CSS3**

<p>Podemos inserir cor de várias formas: por nome, por código hexadecimal (6 dígitos, sendo 2 representando vermelho, 2 de verde e 2 de azul), RGB (red, green and blue) e HSL (hue, saturation and luminosity).</p>

---

**Capítulo 13 - Aula 03 - Harmonia de cores**

<p>Circulo cromático combina simetria com as cores. Cores Primárias, Secundárias e Terciárias (cor primária-cor secundária, parecido com tons pastéis). Divisão por "temperatura". Partir a escolha pela cor principal que passará o sentimento geral, de 3 a 5 cores (+ preto e branco), verificar cor primária da logo. Cores complementares (contraste, lado oposto), cores análogas (com ou sem complementar), cores analogas relacionadas (duas cores analogas e pula uma), cores intercaladas (escolhe uma e pula outra, mas é mais "dura"), cores triádicas, monocromia (1 cor alterando saturação e luminosidade) </p>

---

**Capítulo 13 - Aula 04 - Paleta de cores**

<p>Criar uma paleta de cores usando Adobe Color. Como extrai tema e degrade de uma imagem para criar paleta. Usando o paletton para gerar um exemplo de site.</p>

---

**Capítulo 13 - Aula 05 - Como capturar cores da tela?**

<p>Para capturar cores dos sites é só instalar a extensão colorzilla. Colocar o mouse em cima da cor e clicar para copiar o código hexadecimal.</p>

---

**Capítulo 13 - Aula 06 - Como criar degradê com CSS?**

<p>Usar comando backgournd.image com a função interna linear-gradient indicando direção (to top, right, etc ou 45deg), primeira cor, segunda cor, terceira cor, etc. Para configurações globais das CSS usar o seletor \*{}. Não usar muitas cores e exagerar no gradiente. Cores usadas: rgb(139, 214, 219),rgb(31, 178, 189).</p>

---

**Capítulo 13 - Aula 07 - Criando um exemplo real**

<p>Construindo um exemplo de site com diferentes configurações para body, main, h1, h2 e p. Cada cor foi retirada da paleta do adobe colors e as configurações básicas usadas para ajustar o estilo em arquivo separado.</p>

---

**Capítulo 14 - Aula 01 - Primeiros passos em Tipografia**

<p>Na idade média os livros eram copiados a mão. Gutenberg investou a prensa mecânica de tipos móveis. Tipografia surgiu para criar estulos de letras mais adequadas para leitura. Letras também transmitem sentimentos.</p>

---

**Capítulo 14 - Aula 02 - Anatomia do tipo**

<p>Análise da fonte Times new roman que é a fonte padrão das maiorias dos navegadores. A fonte é baseada pela letra x minúscula. A altura do corpo (total) é o que é configurado na CSS.</p>

---

**Capítulo 14 - Aula 03 - Famílias de fonte em CSS**

<p>Usar font-family com mais de 1 parâmetro para não ter problemas com o tipo de dispositivo. Terminar a declaração sempre com uma fonte genérica. É possível coloar o mesmo estilo pra mais de uma tag, basta seprar por vírgula, ex: h1, h2 {}.</p>

---

**Capítulo 14 - Aula 04 - Tamanho de fonte e suas medidas**

<p>Medidas absolutas: cm, mm, in, px, pt, pc. Medidas relativas: em (relativo a altura m), ex (relativo a altura x), rem (relativo ao root, fonte do body), vw (relativo a largura da tela), vh (relativo a altura da tela) e % (porcentagem). Utilizar a referência em! 16px é o tamanho normal, que é igual a 1 em.</p>

---

**Capítulo 14 - Aula 05 - Peso, estilo e shorthand font**

<p>Para escolher o peso da fonte usar: font-weight. Parâmetros: literais (normal, bold, etc.) ou numéricos (de 100 até 900). Nem todas as fontes tem todas as opções. Font-style para colocar itálico e text-decoration para sublinhar. Short hand: font: style weight size family (deve respeitar a sequência).</p>

---

**Capítulo 14 - Aula 06 - Usando Google Fonts**

<p> Acessar Google Fonts e selecionar a fonte e estilos da fonte que deseja utilizar. Colocar dentro da tag style ou no arquivo CSS a função import (não necessário baixar).</p>

---

**Capítulo 14 - Aula 07 - Usando fontes externas**

<p>Acessar dafont para baixar as fotnes e colocar na pasta do projeto. Criar a fonte com a regra font-face (tomar cuidado com o modo de configurar). Para inserir colocar o format () como opentype (otf), truetype(ttf), embedded-opentype, truetype-aat (Apple Advanced Typography), svg.</p>

---

**Capítulo 14 - Aula 08 - Capturando fontes de um site**

<p>Instalar extensão Fonts Ninja no chrome para "ler" uma fonte de um site. Clicar no ninja, não precisa assinar o serviço e o app vai mostrar todas as fontes usadas. Ao passar o mouse por cima e mostra todas as características da letra. É possível testar a fonte numa janela pop-up e copiar o código da fonte.</p>

---

**Capítulo 14 - Aula 09 - Capturando fontes de imagens**

<p>Usar sites como: whatfontis, carregar imagem e seguir os passos do site para tentar identificar a fonte. Não é muito preciso e pode não funcionar.</p>

---

**Capítulo 14 - Aula 10 - Alinhamento de texto com CSS**

<p>Alinhamento de texto com a propriedade text-align. Deve ser feito somente via CSS dentro da tag style ou na folha de estilo. Para dar o espaçamento de início de parágrafo utilizar text-indent e a medida.</p>

---

**Capitulo 15 - Aula 01 - Usando o id com CSS**

<p>Usar seletores personalizados quando existem 2 elementos da mesma classe mas requerem configurações diferentes. A # no CSS identifica id do HTML e . no CSS identifica class do HTML. Usar: h1#principal ou só #principal.</p>

---

**Capítulo 15 - Aula 02 - As diferenças entre id e class**

<p>A regra do W3C é utilizar somente 1 id espcifico por elemento por página HTML. Utilizar class para classificar os elementos similares e utilizar a mesma configuração. É possível ter um elemento com id e class, mas o id se sobrepõe ao class. Configurações genéricas e depois específicas.</p>

---

**Capítulo 15 - Aula 03 - Pseudo-classes em CSS**

<p>Pseudo-classes são para configurações de estado, colocar id ou class : pseudo-classe. Aplicação de estado para mostrar menus de dropdown quando colocar o mouse em cima usando tag display.</p>

---

**Capítulo 15 - Aula 04 - Pseudo-elementos em CSS**

<p>Usando pseudo-classes para configurar os links de acordo com uma ação. É possível criar pseudo-elementos usando :: após a classe ou id. Para usar um children precisamos colocar > após o id ou class. Cada uma é utilizada em um tipo de situação diferente dentro de um seletor personalizado.</p>

---

**Capítulo 16 - Aula 01 - Modelo de Caixas: primeiro passos**

<p>Características: height, width, border, padding (espaço entre conteúdo e borda), margin (espaço entre borda e outro elemento) e ouline (fora da borda). Tipos de caixa: box-level (sempre ocupa a largura total da tela e pula uma linha para inserir outra box) e inline-level (não pula linha e não quebra linha para inserir uma nova caixa). Box-level: div, h1, p, main, header, nav, article, aside, footer, form e video. Inline-level: span, a, code, small, strong, em, sup, sub, label, button, input e select.</p>

---

**Capítulo 16 - Aula 02 - Modelo de Caixas na prática pt1**

<p>Analisando com chrome: user agent stylesheet são as configurações padrões do navegador. Usar o devtools para verificar as alterações e alterar momentaneamente a página.</p>

---

**Capítulo 16 - Aula 03 - Modelo de Caixas na prática pt2**

<p>Margem com configuração auto centraliza a caixa. Simplificando os comandos usando shorthand. border: width style color; padding: top right bottom left; ou padding 10px; ou padding 10px 20px; (1o valor é top e bot é 10px e o right e left é 20px). Margin segue padding e outline segue border. Display altera o modo como é apresentado a caixa, inline-block mostra o elemento na linha mas com características de bloco.</p>

---

**Capítulo 16 - Aula 04 - Grouping Tags em HTML5**

<p>Criado ex box02 para demonstrar a utilização das tags e configurações principais. Não existe uma hierarquia padrão para as tags, somente para facilitar as buscas separar o body por header, main e footer.</p>

---

**Capitulo 16 - Aula 05 - Sombra nas Caixas**

<p>Usar shorhand do box-shadow: right bottom spread black. Usar sempre preto e colocar transparência um pouco abaixo de 50%. Usar antes dos deslocamentos inset para borda interna do elemento.</p>

---

**Capítulo 16 - Aula 06 - Caixas com vértices arredondados**

<p>Usar shorthand do comando border-radius: top-left top-right bottom-right bottom-left. Pode ser usada como percentual e se o elemento for quadradado, usar 50% transforma num circulo.</p>

---

**Capítulo 16 - Aula 07 - Bordas decoradas**

<p>Criar arquivo para a borda e inserir como border-image-source. Não recomendo!!</p>

---

**Capítulo 16 - Aula 08 - Desafio!**

<p>Desafio é o capítulo 17 inteiro!</p>

---

**Capítulo 17 - Aula 01 - Criando um mini projeto**

<p>Preparando o ambiente com as informações e arquivos necessários.</p>

---

**Capítulo 17 - Aula 02 - Navegando pelo projeto pronto**

<p>Análise do projeto pronto com as funções e responsividades.</p>

---

**Capítulo 17 - Aula 03 - Planejando a estrutura do site**

<p>Preparando a estrutura do site usando mockflow e achando as fontes adequadas.</p>

---

**Capítulo 17 - Aula 04 - Layout -> Código**

<p>Esboço do conteúdo no site e criação do arquivo CSS.</p>

---

**Capítulo 17 - Aula 05 - Organizando o conteúdo**

<p>Organização do conteúdo, colocar links, imagens e videos e criando a lista do site.</p>

---

**Capítulo 17 - Aula 06 - Variáveis em CSS**

<p>Configurando as cores e fontes usando variáveis no CSS. Usar seletor root e declarar variável com 2 traços antes ( --cor0). Para configurações globais usar seletor \*, ex: colocar todas as margens e paddings para zero.</p>

---

**Capítulo 17 - Aula 07 - Responsividade na prática**

<p>Responsividade com tamanho mínimo e máximo para ser utilizado em diferentes dispositivos. Tamanhos máximos e mínimos para a main do site, img com 100% de largura e substituída por outra quando reduzir muito (usando picture).</p>

---

**Capítulo 17 - Aula 08 - Responsividade na prática**

<p>Aplicando os conceitos anteriores no nosso site.</p>

---

**Capítulo 17 - Aula 09 - Configurando o header e menu**

<p>Adicionando configurações do header e menu. Para o menu, utilizando o pseudo-elemento hover para alterar o tipo do texto e cor quando passar o mouse em cima. Utilizado também no menu o transition-duration para configurar o tempo que levará para alterar a configuração quando o mouse passar por cima.</p>

---

**Capítulo 17 - Aula 10 - Melhorando o formato do conteúdo**

<p>Ajustando parágrafos, h2, links e destaques. Usando gradiente no h2 até o transparente.</p>

---

**Capítulo 17 - Aula 11 - Rodapé, conteúdo periférico e links**

<p>Configurando footer, aside e links. Na lista, usar 2 colunas por conta de telas pequenas. Usando margem negativa para vazar do elemento. Usado emojipedia para configurar o marcador da lista.</p>

---

**Capítulo 17 - Aula 12 - Vídeo responsivo**

<p>Feito algumas configurações pontuais para dispositivos com telas muito pequenas. Video responsivo, utilizado uma div envelopando o vídeo e inserido o conceito de posição absoluta e relativa para que ele se torne responsivo. Os percentuais devem ser ajustados para cada vídeo.</p>

---

<h2>Módulo 3</h2>

**Capítulo 18 - Aula 01 - O que é Git e GitHub?**

<p>Explicação sobre repositório local e remoto e versionamento de código. Push - atualização do repositório remoto (GitHub).</p>

---

**Capítulo 18 - Aula 02 - Instalando Git e GitHub no PC**

<p>Processo de instalação do Git e GitHub Desktop para facilitar o gerenciamento dos arquivos.</p>

---

**Capítulo 18 - Aula 03 - Criando conta no GitHub**

<p>Processo de criação da conta do GitHub e atualização do perfil.</p>

---

**Capítulo 18 - Aula 04 - Primeiro repositório Git e GitHub**

<p>Transferindo todos os exercícios do curso para o repositório local e remoto como backup.</p>

---

**Capítulo 18 - Aula 05 - Gerenciando Respositórios no GitHub**

<p>Como criar um repositório vazio, excluir e modificar responsitórios.</p>

---

**Capítulo 18 - Aula 06 - Hospedando site gratuitamente com GitHub Pages**

<p>Como usar o GitHub pages num repositório para abrir os arquivos internos, o readme é aberto como página principal e pode conter links para os exercícios internos. Criar um novo repositório para o projeto Android, colar os arquivos do projeto na pasta, nomear a página principal de index.html, ir nas opções do GitHub, não escolher tema e selecionar master branch (projetos únicos) e gerar url. Gerar um QR code no site QR code generator para o site. GitHub pages só é compatível com HTML, CSS e JS na página, não é compatível com outras linguagens e banco de dados.</p>

---

**Capítulo 18 - Aula 07 - Manutenção em sites hospedados no GitHub Pages**

<p>Trocando o margin por padding no subtítulo do site. Alterado primeiro no computador, comitado para a branch master, push para o repositório remoto.</p>

---

**Capítulo 18 - Aula 08 - Recursos Sociais do GitHub**

<p>É possível seguir pessoas, repositórios, projetos, etc. Como usar os recursos sociais do GitHub.</p>

---

**Capítulo 18 - Aula 09 - Clonando um repositório**

<p>Usando o GitHub para clonar um repositório, é só logar no seu perfil e clicar em fazer download ou clonar com GitHub Desktop (esteja logado) e pronto.</p>

---

**Capítulo 18 - Aula 10 - GitHub em vários PCs**

<p>Instalar e logar no GitHub Desktop, clonar o repositório remoto para o local, trabalhar no projeto, commit e push para salvar o trabalho, deslogar do GitHub Desktop e excluir todos os arquivos do PC, caso necessário excluir o GitHub Desktop também.</p>

---

**Capítulo 19 - Aula 01 - Download das imagens do capitulo**

<p>Introdução sobre imagens de fundo e fazendo um commit para criar o repositório do exercicio.</p>

---

**Capítulo 19 - Aula 02 - Colocando uma imagem de fundo no seu site**

<p>Criando site teste com imagens no body e nas divs. Cuidado com o tamanho das imagens para o site não ficar muito pesado.</p>

---

**Capítulo 19 - Aula 03 - Imagens que se repetem no fundo de um site**

<p>Propriedades background size para ajustar o tamanho quando quiser e repeat para configurar o tipo de repetição.</p>

---

**Capítulo 19 - Aula 04 - Configurando a posição da imagem no fundo do site**

<p>Propriedade de background position é primeiro coluna e depois a linha, podemos colocar o ponto de ancoragem em todas as combinações.</p>

---

**Capítulo 19 - Aula 05 - Mudando o tamanho da imagem de fundo do site**

<p>Construindo um modelo de site com imagem de fundo. Usar contain (mostra 100% da imagem mas cria barras pretas ao redor) ou cover (cobre a tela, melhor) no background-size.</p>

---

**Capítulo 19 - Aula 06 - background-attachment e shorthand**

<p>Utilizar a propriedade backgrpund-attachment para fixar o fundo do site e não rolar junto com o conteúdo. É possível usar shorthand para incluir todas as propriedades do fundo, nessa ordem: color > image > position > repeat > size (apesar da especificação o navegador não aceita size no shorthand ainda) > attachment</p>

---

**Capítulo 19 - Aula 07 - Centralização vertical de caixas**

<p>Todo posicionamento é relativo inicialmente, mas faremos o container relativo e o conteúdo absoluto. Adicionar left e top de 50% no conteúdo para centralizar e depois transform e translate em -50% pra cada eixo para centralizar o conteúdo no centro do container.</p>

---

**Capítulo 20 - Aula 01 - Um projeto completo usando HTML e CSS**

<p>Apresentação do projeto que será desenvolvido.</p>

---

**Capítulo 20 - Aula 02 - Download e organização dos arquivos**

<p>Acessar o repositório do github do guanabara, baixar os arquivos e organizar a pasta de trabalho.</p>

---

**Capítulo 20 - Aula 03 - Ajustes no HTML do projeto**

<p>Feito os primeiros passos do HTML do projeto.</p>

---

**Capítulo 20 - Aula 04 - Ajustes no CSS do projeto**

<p>Feito os primeiros passos do CSS do projeto.</p>

---

**Capítulo 20 - Aula 05 - Ajustes no CSS do projeto**

<p>Feito os primeiros passos do CSS do projeto.</p>

---

**Capítulo 20 - Aula 06 - Imagens com efeito Parallax simples**

<p>Finalizando o projeto com o CSS e efeito parallax.</p>

---

**Capítulo 20 - Aula 07 - Hospedando o Projeto Cordel gratuitamente**

<p>Hospedando o desafio no github.</p>

---

**Capítulo 21 - Aula 01 - Ainda podemos usar tabelas em HTML?**

<p>Tabelas podem ser usadas no HTML mas não para fazer a estrutura do site.</p>

---

**Capítulo 21 - Aula 02 - Sua primeira tabela em HTML**

<p>A tabela é composta por uma hierarquia de table > tr (linha) > table header (cabeçalho) > td (dados). Usar border-collapse como collapse para a table quando quiser "juntar" as bordas dos dados.</p>

---

**Capítulo 21 - Aula 03 - Alinhando o conteúdo em tabelas**

<p>Para alinhar os dados da tabela utilizar em td as tags text-align para alinhamento horizontal e vertical-align para alinhamento vertical, nesse último o center deve ser substituído por middle.</p>

---

**Capítulo 21 - Aula 04 - Aprendendo a trabalhar com tabelas grandes**

<p>Contruindo uma tabela grande com head, body e foot para dar semântica aos dados. Aplicadas configurações básicas para as próximas aulas.</p>

---

**Capítulo 21 - Aula 05 - Caption e Escopo de títulos em tabelas**

<p>Caption é a legenda da tabela e vai em cima da tabela podendo ser configurado com CSS normalmente. TH - são títulos dentro da tabela (ex: estado, população e total de habitantes), pode ser inserido scope para col (coluna) ou row (linha).</p>

---

**Capítulo 21 - Aula 06 - Efeito Zebrado na tabela com HTML e CSS**

<p>Usar a pseudo-classe para nth-child() para inserir o efeito zebrado, colocar 2n para intercalar. É possível usar os parâmetros odd (ímpares) e even (pares).</p>

---

**Capítulo 21 - Aula 07 - Cabeçalho fixo para tabelas grandes**

<p>Usar position relative na tabela, sticky e top -1px no th. Adicionar background-color para trazer o fundo e não só as palavras.</p>

---

**Capítulo 21 - Aula 08 - Mesclagem de células**

<p>Usar colspan para expansão em coluna e rowspan para expansão em linha.</p>

---

**Capítulo 21 - Aula 09 - Desafios (parte 1)**

<p>Construído os dois desafios de tabela.</p>

---

**Capítulo 21 - Aula 10 - Exemplo de tabela completa**

<p>Montando um exemplo de tabela com informações de filmes.</p>

---

**Capítulo 21 - Aula 11 - Escopos de grupo**

<p>O escopo deve ser analisando para cada th e caso necessário, refencia mais de 1 linha ou coluna, deve ser usado colgroup ou rowgroup.</p>

---

**Capítulo 21 - Aula 12 - Desafios (parte 2)**

<p>Contrído o desafio de tabela 3.</p>

---

**Capítulo 21 - Aula 13 - Agrupando colunas com colgroup**

<p>Para configurar colunas utilizar a tag colgroup dentro da tabela e adicionar a classe a tag col, caso necessário é possível adicionar um span como no exemplo.</p>

---

**Capítulo 21 - Aula 14 - Tabelas responsivas**

<p>Envelopar a tabela em um container e usar a configuração overflow-x como auto e o scroll será aplicado somente para a tabela.</p>

---

**Capítulo 22 - Aula 01 - O iframe ainda pode ser usado?**

<p>O iframe é uma "janela" dentro do seu site que possibilita a apresentação de um site externo. Existem sites protegidos para exibição em iframes em sites de terceiros.</p>

---

**Capítulo 22 - Aula 02 - Configurando iframes**

<p>O tamanho padrão do iframe é 300x150. Mas é possível configurar os iframes individualmente ou via CSS, no caso a CSS se sobrepõe. Frameborder só aceita 0 ou 1, para configurar melhor devemos utilizar CSS.</p>

---

**Capítulo 22 - Aula 03 - Conteúdo local no iframe**

<p>É possível usar conteúdos locais dentro do iframe somente alterando o src, isso permite configurações de estilo diferentes. Para o caso das tabelas, caso o conteúdo da tabela esteja relacionado com o conteúdo da página, melhor fazer via div.</p>

---

**Capítulo 22 - Aula 04 - Navegação no iframe**

<p>Usando links para navegar no iframe, é necessário colocar um name no iframe e inserir o target do link como o nome do iframe.</p>

---

**Capítulo 22 - Aula 05 - Coteúdo no iframe por código**

<p>Usar srcdoc para inserir um html dentro da página como conteúdo estático que não voltará após selecionado outro. Para conteúdos complexos é recomendado um conteúdo externo e uso do src normal.</p>

---

**Capítulo 22 - Aula 06 - Inconvenientes do iframe**

<p>Frame e iframe não são as mesmas coisas, frame não se usa mais. O google bot tem problemas para indexar os conteúdos dentro dos iframes, use os conteúdos relevantes e sensíveis fora dos iframes. Existe problema de acessibilidade como erros nos leitores de tela. Problemas de segurança que o seu site abre uma porta para outros sites.</p>

---

**Capítulo 22 - Aula 07 - Tornando iframes mais seguros**

<p>Usar a tag sandbox recebendo o valor sandbox para bloquear os acessos perigosos e captura de dados, é possível setar algumas autorizações específicas. Adicionar também o referrerpolicy com o atributo no-referrer para bloquear captura de informações também.</p>

---

**Capítulo 22 - Aula 08 - Dicas para iframes melhores**

<p>É possível importar vídeos, mapas do google, mapas do waze, planilhas e arquivos do google docs via iframe para seu site, fazer via conteúdo original no link de compartilhamento.</p>

---

**Capítulo 23 - Aula 01 - Criando um projeto do zero**

<p>Introdução do projeto de redes sociais.</p>

---

**Capítulo 23 - Aula 02 - Vamos começar o projeto**

<p>Baixar os arquivos do repositório do Guanabara e organizar os arquivos em uma pasta para o projeto.</p>

---

**Capítulo 23 - Aula 03 - Criando a página inicial do projeto**

<p>Criado o arquivo inicial do index html e ajustado algumas configurações.</p>

---

**Capítulo 23 - Aula 04 - Posicionando o conteúdo do seu site**

<p>Posicionando os elementos na página e configurando o iframe.</p>

---

**Capítulo 23 - Aula 05 - Criando os botões para redes sociais**

<p>Configurando o menu e botões de redes sociais com animação.</p>

---

**Capítulo 23 - Aula 06 - Criando as páginas de cada rede social**

<p>Criando o estilo e as págias extras de cada rede social para o projeto. Para esconder a barra de rolagem utilizar o webkit-scrollbar com width e height 0 px.</p>

---

**Capítulo 23 - Aula 07 - Personalizando as imagens do projeto**

<p>Como criar as imagens das redes sociais do projeto usando gimp.</p>

---

**Capítulo 24 - Aula 01 - Como criar formularios com HTML5**

<p>Apresentando formulários e criando a primeira página com formulário de input de texto sem funcionalidades.</p>

---

**Capítulo 24 - Aula 02 - Usar Label vai melhorar seus formulários**

<p>Usar tag autocomplete com parâmetro off para o form para desligar as sugestões. Para enviar o dado, inserir o nome do arquivo na tag action do formulário. Para o html e php é necessário um name, no JS é utilizado o id. Colocar o label nos textos para ajudar os mecanismos de busca.</p>

---

**Capítulo 24 - Aula 03 - Métodos GET e POST para formulários**

<p>Normalmente os parâmetros do formulário são passados via url, no método GET (usar para dados não sensíveis, até 3000 bites e sem fotos). O método POST esconde o dado da url mas não oculta os dados, não é muito seguro (usar para os outros). Para uma segurança real precisamos utilizar o https (usar para dados sensíveis como senha, número de cartão, etc.).</p>

---

**Capítulo 24 - Aula 04 - Criando caixas de texto e senha**

<p>Usando campos de senha para esconder os textos e travando o envio via parâmetro required nos inputs que são necessários. É possível colocar número mínimo e máximo de caracteres dos textos dentro do input. Alterar tamanho via parâmetro size e incluir texto explicativo via placeholder. Usar autocomplete on no form e depois indicar o que seria o autocomplete de cada campo.</p>

---

**Capítulo 24 - Aula 05 - Elementos number, month, date e time em formulários HTML**

<p>Usando input number com parâmetros min, max e step. Sugerir valores via parâmetro value. Testando outros inputs.</p>

---

**Capítulo 24 - Aula 06 - Compatibilidade com navegadores**

<p>Testando o formulário em diferetes navegadores.</p>

---

**Capítulo 24 - Aula 07 - Formulários com telefone e e-mail**

<p>Os campos de e-mail e telefone não possuem muitos pré filtros para os inputs, mas podem ser melhorados. Estudar mais sobre RegEx (regular expression). É possível agrupar os campos via fieldset e depois confugirar os parâmetros via CSS.</p>

---

**Capítulo 24 - Aula 08 - Checkbox e Radio button em HTML**

<p>Usando checkbox e fazendo a relação para poder selecionar clicando nas palavras. Usar mesmo name para inputs do tipo radio para selecionar somente uma das opções. Adicionar value para os inputs radio para identificar qual seleção foi utilizada. Utilizar parâmetro checked para iniciar o input já marcado.</p>

---

**Capítulo 24 - Aula 09 - Elementos color, range e file em HTML**

<p>Input de cor envia o código da cor em hexadecimal e permite escolher qualquer cor. Input range pode ser configurado com max, min e value. Sempre que for utilizar o input file é necessário usar o método post em vez do get.</p>

---

**Capítulo 24 - Aula 10 - Select, datalist e textarea em HTML**

<p>Usando select com uma lista pré cadastradas. Para permitir texto do usuário junto com lista usar input de texto junto com datalist. Para adicionar menssagens e comentários utilizar o input textarea, é infinito então precisamos utilizar o método post no formulário.</p>

---
