# curso_em_video_HTM5_CSS3
 Curso de HTML5 and CSS3 do canal Curso em Video

<h1>Anotações</h1>

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

**Capitulo 6 - Aula 2 - Quais são os formatos para imagens na Web?**
<p>Formatos: JPEG (mais compacto) ou PNG (permite transparência).</p>

**Capítulo 6 - Aula 3 - O tamanho das imagens importa para um site?**
<p>Tomar cuidado com tamanho da imagem para o site não ficar pesado demais. Gimp para ajustar e redimensionar. Grande = 1500, Média = 600, lateral = 400, rodapé = 200.</p>

**Capítulo 6 - Aula 4 - A tag img em HTML5**
<p>Construindo ex003 com imagens na mesma pasta, em subpastas e via URL externa (salvo na pasta de exercícios desse repositório)</p>

**Capítulo 6 - Aula 5 - Como mudar o favicon de um site**
<p>Formato .ico, acessar favicon.io para converter ou criar um favicon. Para adicionar, no campo head digitar link, escolher a opção favicon e selecionar o arquivo desejado. Criado ex004 com o favicon (salvo na pasta de exercícios desse repositório).</p>


