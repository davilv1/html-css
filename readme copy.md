# aprendendo

git init
- inicia novo projeto com git

git add <nome-arquivo>/.(ponto)
- add os novos arquivos que estão prontos para serem commitados

git commit -m "mensagem de commit"
- commit os arquivos no histórico

git log
- mostra os ultimos commits, log de alterações

git status
- como esta os estados das alterações

git diff
- mostra o que foi alterado
- o que tem de alterado na ramificação

git merge
- faz o a mescla das ramificações

git branch
- mostra a branch atual

git branch -b <nome-da-branch>
- cria uma nova branch a partir do histórico atual da branch que estamos

git checkout <nome-branch>
- muda pra essa branch

git remote add <nome> <url>
- add um novo repositório remoto

git push <nome> <nome-da-branch>
- manda as alterações locais para o repositório remoto, pra cada branch

git pull <nome> <nome-da-branch>
- pega as alterações do repositório remoto e joga pra maquina

git fetch
- atualiza o histórico local de acordo com o histórico salvo no repositório remoto
- sincronização do local com o remoto

//

html e css

github.com/gustavoguanabara
gustavoguanabara.github.io

internet veio da arpanet (surgiu durante a guerra fria) que era utilizada para proteger centros militares
youtu.be/TNQsmPf24go
utf-8?

dominio = nome unico, pago anualmente, varios TLDs
hospedagem = espaço para armazenar os arquivos, pago mensalmente, escolha de espaço, memória, recursos

URL= sub-dominio, dominio, tld, caminho

     gustavoguanabara.  github.   io
URL   sub-dominio       dominio  tld 

11 html e css

html e css não são linguagens de programação, então "eu desenvolvo em html e css"

html = HyperTexet Markup Language
css = Cascading Style Sheets

html = é focada em conteudo, texto, imagens, videos, tabelas, listas
css = design, atrativos visuais, cores, tamanhos, sombras, posicionamento
JS = interações, menus, animações, popups, validações

Anatomia do conteúdo em HTML

abertura de tag <-<h1>exemplo de título -> conteúdo </h1> -> fechamento de tag
<p>exemplo de parágrafo</p>
abertura de tag<-<img src="foto.png" alt="exemplo de foto">(SRC e ALT são parâmetros) (FOTO e EXEMPLO são valores)

*Nem todas as tags tem fechamento como HR Meta e IMG*

Anatomia do Estilo em CSS

Seletor
h1{
    font-family: Arial; ->*Declaração*
    font-size: 20pt; *Toda declaração em CSS tem que ter ; no final*
    color: blue; *Color = propriedade, blue = valor*
}

Estrutura básica de um documento HTML

<!doctype html> *diz que vai ser feito em HTML5*
<html lang= "pt-br">
    <head>
        <meta charset="UTF-8"> *significa que o site vai ser compativel com caracteres utf-8, palavras com acentuações*
        <meta name="viewport"
        content="width=device-width,
        initial-scale=1.0">
        <title>Document</title>
    </head>
    <body>
        <h1>Olá, Mundo!</h1>
    </body>
</html>

Como funcionam a HTMl e as CSS

html e css dentro do servidor - digitar url no cliente - acesso ao DNS - DNS libera o ip - vai no servidor - copia é pega - html e css pegos vão ser disponibilizados no navegador - navegor analisa as linhas e envia o resultado visual pro cliente

12 front back e full stack

Front-end e Back-end

HTML CSS e JS -> tecnologias Client-side (Front-end) focado na parte visual e interativa do site
PHP JS C# PY RUBY e JAVA-> tecnologias Server-side(back-end) interação do código com o servidor

Front-end + Back-end = Full Stack

hr = faz uma linha
p = paragrafo
h1 = heading (titulo do body)

Marcações é que fazem tudo nos textos

colocar varis ENTER ou <br><br><br><br> para quebrar as linhas varias vezes seguidas é errado, vai ser mostrado como fazer no CSS

para fazer comentarios utilizar <!---->
&reg; *marca registrada*
&copy; *Copyright*
&trade; *TM - TradeMark*
Tudo no documento da aula que foi baixado (05) e só procurar misksymbols

👀 colar emojis no codigo a maior parte das vezes funciona, mas o melhor é colocar em codigo hexadecimal, pra colocar o emji sempre vai ser &#x(o X tem que ser minúsculo)

&#x = diz que vai ser colocado em hexadecimal

Site "emojipedia.org" funciona

Direitos autorias, buscar imagens no google mudando as ferramentas de pesquisa

sites como https://unsplash.com/ e https://www.pexels.com/

direitos autorais é a aula 06 e la da os sites para ver imagens de domínio público

tem varios formatos de arquivo para imagens, mas pra web normalmente se usa jpeg e png, raramente gif, tif, svg. Maior parte vai ser jpeg e png, sendo utilizado de acordo com a necessidade

jpeg consegue compactar uma imagem, quanto maior mais demorado

png foi criado pra substituir o gif, o gif é pesado e permite transparência e animação, o png só permite transparência e é compactado mas o jpeg é mais compacto porém não permite transparencia

jpeg = compacto sem transparência
png = menos compactor mas com transparência

tamanho para usar em site no maximo é 1500 de largura, 72 é uma boa resolução, as vezes pode estar 100 200 300, pode colocar menos como 50

como por imagem

img = <img src="" alt="">
ALT é uma explicação do que é a imagem
ctrl+espaço mostra os arquivos

preferencia em tirar bits do que colocar

Gimp, ferramenta de corte mostra tamanho dimensões

da pra carregar imagens externas colando links copiando o endereço da imagem, mas se o servidor colado cair, a imagem para de funcionar

favicon são os icones pequenos nas guias como o icone do youtube e google pequenos la no topo

Site bom é o iconarchive.com para pegar icones

favicon.cc da pra criar o icone

favicon.io cria icone utilizando outras coisas como txtos, emojis e imagens

o comando pra por o favicon é o comando link:favicon

aula 7 hierarquia de Títulos

niveis 1, 2, 3.. o 1 é o nivel mais alto(maior)
h1 é o titulo principal da página

Paginas podem ter mais que 1 h1

os Hs vão de h1 até h6

"p" para paragrafo e "lorem" pra escrever coisa aleatória

semântica na HTML5

Tags obsoletas do HTML5 dev.w3.org

tags obsoletas como bgcolor, center, font

HTML - signficado, semância
CSS - estilo, forma

video 22

negrito pode ser usado <b>*não semântica* ou <strong>*semântica*

ctrl+shift+p após selecionar algo, selecionar wrap with abbreviation, da pra colocar algo entre uma tag

itálico pode ser usando <i>*não semântica* ou <em>*semântica*

semântica = significado
não semântica = sem significado, apenas uma forma

forma é vista em css e sentido é em html

23 formatações adicionais em html

A tag <mark> é literalmente um marca texto igual as canetas marca texto

uma das maneiras pra colocar css é dentro da própria tag, como por exemplo colocar "Style" dentro de uma tag como <mark style="">

style colocado dentro de uma tag apenas altera aquela tag que até seu fechamento, outras não herdam a alteração

se por/criar uma tag <style></style> no head posso colocar todas as tags com a mesma alteração como por exemplo: <style>mark{background-color: lime}</style> vai fazer com que todos os marks daquela pagina fiquem da mesma cor

letras grandes utiliza o <big> e pequenas o <small>, o big é obsoleto pois é apenas forma, ja o small da sentido para as letras pequenas como nos contratos

texto excluído usa o <del>(é o texto com um risco no meio)
texto inserido é <ins>(sublinhado semântica) ou <u>(sublinhado não semântica)

texto sobrescrito usa a tag <sup> e subscrito usa <sub>

index.html é a pagina principal

24 citações e códigos

o comando <code> é uma fote monoespaçada(mesmo espaço pras caracteres) é boa para ver códigos

a tag <code> não faz identação(arruma as linhas do código), mas da pra utilizar a tag <pre>, que le os espaços de identação e espaços no geral como varios ENTERS

o Shift+tab faz com que tudo selecionado volte espaços TABulados no código

a tag <q> é utilizado para citações simples(é o aspas" mas dando sentido de citação)

ja a tag <blockquote> é usado para citações mais completas do autor, deixado a frase deslocada, também da pra colocar um parametro chamado "cite=" para colocar o URL da citação, exemplo <blockquote cite="">

da pra colocar o que significa as abreviações utilizando a tag <abbr>, passando o mouse por cima fala o que significa, quando coloca o mouse no título de um video no youtube ele mostra a mesma coisa

texto invertido/espelhado se usa <bdo dir="rtl">

25 listas OL e UL

Listas ordenadas = a ordem faz diferença

para fazer uma lista ordenada utiliza o comando <ol> entre a tag coloca a tag <li> por item para listar exemplo <ol><li>acordar</li></ol>, o </li> é opicional e não obrigatório

da pra mudar a forma que é listado colocando o parâmetro "type=" dentro do <ol> e mudar onde começa com o parâmetro "start="

Listas não Ordenadas não faz sentido a sequência, não precisa enumerar, apenas demarcar

para fazer lista não ordenada usa <ul>

26 listas mistas e de definição

aninhamento = uma dentro da outra

ao criar uma lista ordenada <ol> e por o <li> dentro, da pra colocar outro <ol> dentro do <li> para separar por categoria como antigo e novo, exemplo <ol><li>Antigo</li><ol></ol></ol>

o parâmetro "start=" é um parâmetro numérico, então se eu colocar para marcar com letras utilizando "A" ou "a" e quiser que começe na letra "E" ou "e", preciso colocar o número que começa e não a letra, exemplo o "e" é a 5º letra então colocaria "start="5""

para mudar/escrever em varias tags ao mesmo tempo da pra segurar o ALT e ir clicando no lugar exato

Para fazer uma lista de definições(estilo dicionário), se utiliza o <dt> parar o termo e o <dd> para a descrição do termo

27 links e âncoras em HTML5

link externo aponta pra um outro site que não é nosso

Para adicionar uma âncora(link externo) ao texto para abrir, utiliza o comando <a href="">, ele sobrepõe a pagina aberta sobre a sua.
Colocando os parâmetros *"target="_blank"* *rel="external"*(target=_blank indica que o ALVO é uma pagina em branco e o ref=external significa que é um link que vai pra fora do meu site) o link sera aberto em uma nova guia em branco

links dentro do próprio site, não se abre uma aba nova

28 link internos

links internos fazem a ligação com outra pagina dentro do nosso servidor

links internos não precisam da URL inteira, posso só dizer vá para certo local

Para colocar o link é o mesmo comando, <a href=""> e não precisa utilizar o url completo no href, mas o parâmetro "rel="" muda para *rel="next"* para próximo e *rel="prev"* para anterior, isso diz pro sistema de busca qual é a proxima e anterior do site

o *rel="nofollow"* fala pro mecanismo de busca que você não da um aval pra essa busca

sempre usar o ctrl+espaço para adicionar arquivos que o caminho vai para outra pasta

existe um "target=" específico para abrir na própria pagina que é o "*target="_self"*", ou pode apenas não colocar target

para voltar a uma pasta anterior se utiliza dentro do "<a href=>" o "*../*", ficando então por exemplo: estou na pagina 3 dentro de "atividade/jornal/pagina3", para volta na pagina 1 que está em "atividade/pagina1", utilizo o comando <a href="../pagina1>

o *./* significa a própria pastar e *../* significa a pasta anterior

29 links para download

enquanto não tiver link para colocar no <a href=>, coloca uma # para falar que é vazio

o site https://www.iana.org/assignments/media-types, mostra o comando para por no parâmetro "type=" para baixar o tipo de arquivo específico

normalmente colocando os parâmetros dentro do <a href>"*download="nome-do-arquivo.tipo" type="application.tipo"* os navegadores vão baixar ao inves de abrir no navegador.

32 imagens que se adaptam sozinhas

o google utiliza o bounce rate para medir quantas pessoas saem do site, sempre se preocupar com o usúario

o comando <picture> fala que dentro dele vai ter uma imagem

*tudo dentro do <picure>*

usar o <img> para colocar a imagem

o comando <source media> permite adicionar outra imagem para substituir a que está no <img> caso chegue em uma determinada marca

no parâmetro "media=" podemos escolher definir o tamanho minimo ou maximo da tela para fazer a mudança, exemplo "media="(max-width: 1050px) srcset="*nova imagem*" type="*tipo/da imagem*"

a imagem principal é coloca a grande, acima dela colocamos o <source media> da imagem média e acima da média colocamos o <source media> da imagem pequena, *tem que ser acima*

imagem base do <img> é a imagem padrão que deve ser colocado, acima dela colocar os sources em ordem de tamanho do maior ao menor

    <picture>
        <source media="(max-width: 750px)" srcset="imagens/foto-p.png" type="image/png">
        <source media="(max-width: 1050px)" srcset="imagens/foto-m.png" type="image/png">
        <img src="imagens/foto-g.png" alt="Imagem flexivel">
    </picture>

33 colocando aúdio no seu site

pastas e arquivos sempre com letra minuscula e sem acento

direitos autoriais

Para por Áudios no site, se utiliza a tag <audio>, colocando o parâmetro "*autoplay*" dentro da tag, a musica comaça automaticamente dependendo do navegador, porém sem botão para começar e pausar, para colocar o botão se utiliza o parâmetro "*controls autoplay*", que adiciona o botão.

tem muitos navegadores que não suportam diversos formatos.

    <audio src="midia/audioteste.mpeg" controls autoplay></audio>
    <!-- MP3, WAV, OGG -->

criando a tag de apenas <audio></audio> podemos colocar a tag <source:src> dentro para colocar o mesmo audio varias vezes porém em formatos diferentes, para que caso o site não consiga carregar uma versão ele tente outras na ordem que foi programado como por exemplo:    
<audio>
        <source src="midia/audioteste.mpeg" type="audio/mpeg">
        <source src="midia/guanacast-33.ogg" type="audio/ogg">
        <source src="midia/guanacast-33.wav" type="audio/wav">
 </audio>

 ele vai carregar em ordem que foi colocado, mpeg, ogg e depois wav

 o parâmetro "*preload*" tem 3 tipos, sendo eles: auto, metadata e none.
 o *preload auto* ele só vai considerar que o site terminou de carregar quando depois que carregar todo o áudio, o *preload metadata* só vai carregar o nome do arquivo e algumas informações sobre o arquivo sem apertar no botão play, e *preload none* não vai carregar nada até o usuário clicar no botão play

 o parâmetro *loop* faz a música ficar reiniciando ao chegar no final

 evitar arquivos .WAV pois são muito pesados

 34 formatos de vídeo para seu site

 Os padrões mais utiliados e suportados no HTML5 são os formatos: .mp4 .m4v .webm e os arquivos .ogv

 então igual aos áudios, devemos ter varios arquivos de formatos diferentes para caso o navegador não carregue algum tente carregar outro

 programa *handbrake* é um programa open source(testa em casa)

 35 videos em hospedagem própria

 para por um vídeos em HTML5, utilizamos a tag <video src="">

 não adianta ficar baixando videos gigantes, pois as vezes é necessario diminuir sua largura, e se diminuir por código o tamanho continua igual e a qualidade diminui

 para por o play, se utiliza o parâmetro "*controls*"

 sempre coloque todos os formatos para tentar garantir que o vídeo funcione

 colocar vídeos é da mesma forma que se coloca aúdio e imagens adaptaveis:
   <video width="500" controls>
        <source src="midia/meu-video.mp4" type="video/mp4">
        <source src="midia/meu-video.m4v" type="video/mp4">
        <source src="midia/meu-video.webm" type="video/webm">
        <source src="midia/meu-video.ogv" type="video/ogg">
        <p>Seu navegador não tem compatibilidade com reprodução de vídeos.</p>
    </video>

o parâmetro "poster" permite colocar imagens/thumbnail nos vídeos antes que de play, ex: <video width="500" poster="imagens/limoes-capa.png" controls>

quanto mais pessoas acessando, maior o consumo de banda, videos hospedados no próprio servidor utilizando a tag videos podem e vão consumir muito trafego de dados, o que pode deixar muito caro

 da pra usar os parametros "*autoplay e loop*" também

36 incorporação de vídeos externos

da pra por qualquer vídeo do youtube no site de maneira simples, indo em compartilhar e na opção "incorporar", o próprio youtube ja vai gerar o código html do vídeo, precisando apenas copiar e colar no código

usando dessa forma, o usuário não consume dados do meu servidor, mas sim do servidor onde o vídeo está hospedado, que no caso é no Youtube

para deixar vídeos exclusivos para usuários que queremos, o Youtube não nos ajuda, mas tem outros sites como o Vimeo.com que deixa escolher quem pode ver o vídeo e também deixa compartilhar com "incorporação"

o Vimeo é mais profissional que o Youtube, pausa no youtube pode aparece vídeo de outras pessoas

Servidor local = consumo maior do próprio serviço de hospedagem

servidor externo = consumo maior do site onde o vídeo esta hospedado

vimeo é bom, mas é limitado a quantidade de vídeos

youtube o vídeo é liberado para todos, e não perdoa os direitos autorias

37 desafio de fazer site com videos

38 estilos CSS inline

não utilize comandos e parâmetros de estilo como "bgcolor e font" no HTML5, utilize as CSS

da pra por em cada tag um parâmetro "*style=*", o CSS inline é estilizar manualmente no código, da pra por dentro do style, backgroundcolor, color, font-family, text-align, font-size

o HTML5 trabalha com semântica (significado) e fazer as coisas dessa forma não da significado, apenas aparência

fazer isso acaba poluindo o código HTML5

o CSS inline é um metodo que não é utilizado no dia a dia, mas sim em coisas pontuais

então da pra fazer, mas é ruim fazer tudo dessa forma

39 estilos CSS internos

colocando a tag <style></style> tudo que for colocado dentro da tag será considerado CSS, configuração de estilo selecionada em seletores

tudo que antes no INLINE era feito linha por linha, podemos apenas configurar tudo de uma vez na tag <style></style> dentro do head, colocando background-color, font-famility, font-size, etc..

esse modelo é melhor que o inline

desvantagens do interno, o estilo é muito mais que o conteúdo, então pode atrapalhar na hora de ler o código pra achar algo

a outra é que se tiver varias páginas, vai ter que copiar e colar em todas, e caso a cor precise ser trocada, vai ter que ir em todos os documentos e alterar

40 Estilos CSS externos

se não tiver criado um arquivo, da pra usar CTRL+click no nome do arquivo

colocar a regra @charset "UTF-8"; no CSS para ser o mesmo modelo de acentuação

tudo que são regras começam com "@" e ficam no começo do arquivo CSS

é melhor usar a tag <link css> e usar arquivo css para estilizar as coisas

da pra utilizar mais de um link de CSS, ele faz a soma dos estilos

evitar usar inline a não ser que seja algo muito específico e pontual, usar as vezes interno para estilos pequenos, e a maior parte externo que deve ser usado sem moderação e se precisar aplicar em varias páginas

no mesmo arquivo da pra usar css externo, interno e inline

o inline tem um poder maior de configuração final, depois o local e por último o externo, mas o externo ajudar a botar configs pro projeto todo

CSS aula 3

da pra por cor das seguintes formas: por nome, por código hexadecimal, por RGB  e por HSL (tudo em letras minúsculas)

da pra mudar a cor passando o mouse por cime da cor no código e também alterar o modo que tá, tipo rgb pra hexadecimal

aula 18

3 tipos de alinhamento: esquerda, direita e centralizado(text-align)

font escolhe tamanho, tipo da letra, peso

text-indent faz o espaço de inicio do parágrafo(identação)

css 19 Usando o ID com CSS

colocando o parâmetro *id=""* da pra separar dos outros e fazer uma config diferente nele

a "#" identifica o id, então se coloca colado, exemplo *h1#principal* é o H1 do texto com a ID com nome "principal"

Tudo em HTML que é ID = vira # no CSS
Tudo em HTML que é class = vira . no CSS

css 20 as diferenças entre id e class

adobe colors é bom

dentro de um doc html só se pode ter 1 elemento com ID, funciona mas é errado colocar mais de 1 elemento com a mesma ID

Quando for aplicar a mesma config nos 2, não usa id, se usa *class*

não de nome para as class e ID de acordo com a forma, mas sim com a função

no CSS colocamos o "." e o nome da classe, não precisa por o h2 ou o que for antes

a tag <span> dentro do html permite que o que estiver dentro possa ser estilizado pelo css separadamente

da pra por mais de uma config de classe em um elemento, exemplo: config="avancado destaque", não precisa por virgula

posso colocar um ID e uma classe no mesmo elemento, mas o ID sobrepõe a classe

css 23 modelo de caixa primeiros passos

aninhamento é uma coisa dentro da outra

height = altura

width = largura

border = borda

padding = acolchoamento ou preenchimento(espaço interno)

Margin = margem(espaço externo)

outline = contorno/traçado(fora do elemento e dentro da margem)

todo parágrafo é uma caixa

tipos de caixas: box-level e inline-level

elemento do tipo box-level sempre se inicia em uma linha nova desenhando a caixa, sempre ocupa a largura total da tela que estiver disponivel e vai pular pra próxima linha antes de continuar o conteúdo

elemeno do tipo inline-level ele não vai pular pra próxima linha, se sobrar espaço no conteúdo ele vai desenhar a caixa pra conter o conteúdo do elemento no lado que faltou e ocupar o espaço que falta, ele não quebra linha e não ocupa a largura inteira, ele continua o contéudo

a tag <div> é um box-level e a tag <span> ele não quebra linha, quando quero iniciar uma nova linha se usa div e se quiser que continue no lado se usa span

tags box-level: div, h1-h6, p, main, header, nav, article, aside, footer, form, video

tags inline-level: a, code, small, strong, em, sup-sub, label, button, input, select

div é o box mais usado e span o inline mais usado

CSS 24 modelo de caixa na prática parte 1

display: block é sempre um box-level

margem é da borda pra fora e padding é da borda pra dentro

css 25 caixa parte 2

da pra configurar todas as partes das caixas, para colocar algo no meio da pra colocar "*margin: auto;*", pra colocar algum elemento no meio da tela é com isso

se for uma caixa = margin auto, se for um texto = text-align center

o *OUTLINE* é a linha que fica fora da borda mas dentro da margem, os limites são definidos pela margem, ele pode vazar mas não aumenta a margem

para não precisar configurar tudo, podemos usar shorthands que são os atalhos como por exemplo:

    border-width: 10px;
    border-style: solid;
    border-color: darkslategray;

    border: 10px solid darkslategray;

o *border* final pegou substitui as 3 linhas necessárias por apenas 1, lembrando que segue a ordem colocada, então sempre vai ser na ordem de largura(widht), estilo(style) e cor(color)

para o padding temos também o seu shorthand:

            padding-top: 10px;
            padding-right: 10px;
            padding-bottom: 10px;
            padding-left: 10px;

            padding: 10px 10px 10px 10px;

lembrando que é em sentido horário começando de cima, então a ordem sempre vai ser, *top, right, bottom e left*. Se os valores forem iguais como no exemplo que é 10px em tudo, podemos simplificar apenas informando uma vez ao invés das 4 posições

Se colocarmos 2 valores, o primeiro valor sera o top/bottom e o segundo valor vai ser right/left

então 4 valores = um pra cada lado, 2 valores = primeiro cima/baixo e segundo direita/esquerda, 1 valor = todos

podemos substituir um valor por auto para deixar centralizada:

margin: 20px auto 40px auto;

no exemplo foi substituido os valores da direita e esquerda

box size é o tamanho da caixa que pode ser mudado usando height e width

h1{
            background-color: lightgreen;
            height: 300px;
            width: 300px;
}

da pra mudar um elemento box-level para inline-level usando *display: inline;*, quando se coloca um elemento inline não se faz altura e largura porque ele é inline

o contrário também funciona, então para transformar um inline-level em box-level podemos usar *display: block;*

largura ideial é entre 1000 a 1200px de largura

border-radius faz arredondamento de borda

pode colocar minimo e maximo de largura e altura usando min- e max- o que queremos mudar, isso deixa mais responsivo

para imagens colocamos normalmente o max-

podemos configurar o border radius dos cantos separados usando border-radius-bottom/top-right/left

tag <aside> para conteúdos a parte/periféricos

aula de pseudoclasses 21 css

a id é "#", "." é classe e ":" é pseudoclasse

a pseudoclasse :hover, quando passar o mouse por cima dele ele ativa

para mexer em algo específico dentro de uma tag, como por exemplo um *p* dentro de uma *div*, usamos *div > p {}*, isso fala que só vai mexer no parágrafo dentro da div, "div tem um filho que é o parágrafo"

da pra colocar coisas escondidas como por exemplo: 

div > p {
            display: none;
        }

        div:hover > p {
            display: block;
            color: white;
            background-color: red;
        }

no exemplo colocamos que o parágrafo dentro da div não tem display, mas que quando o mouse estiver por cima de qualquer parágrafo dentro da div ele mude seu display para block e sua coloração

pseudo-elementos em css 22

da pra usar a pseudoclasse "visited" para coisas ja visitadas

da pra tirar o sublinhado e algumas coisas usando no estilo o "decoration: none"

quando é clicado e segurado da pra usar a pseudoclasse "active" para mudar

pseudo elementos mexem no conteúdo periférico do elemento

pseudo classes são apenas ":" e pseudo elementos são "::"

os pseudo elementos *after* e *before* deixam adicionar coisas na frente ou atras do que foi selecionado como textos

         . = class
         : = pseudo-classe
         :: = pseudo-element
         > = children
        */

grouping tags 26

cabeçalho = <header>

conteúdo principal = <main>

rodapé = <footer>

essas tags são semânticas e são <div>, mas com outro nome pra ficar melhor

novas tags semânticas são: *article* que é para artigos, *aside* que é um conteúdo relativo ao conteudo que foi colocado, *section* que são seções

pode organizar as tags da maneira que quiser

aula de sombras 27

não exagerar nas sombras

sombra de caixa se colocar *box-shadow*, dentro dele colocamos os seguintes parâmetros em ordem, 1px(deslocamento horizontal) 1px(descolamento vertical) 1px(espalhamento) black(cor sombra)

vértices arredondadas 28

usamos o border-radius e podemos usar medidas para as 4 pontas separadas, 2 para mexer apenas em duplas como superior esquerda e inferior direita e superior direita e inferior esquerda, e 1 valor para todas as pontas

border radius de 50% faz as coisas ficarem redondas, da pra usar porcentagem também como medida

bordas decoradas 29

da pra por bordas decoradas usando imagens com border-image-source url,
da pra cortar ela usando border-image-slice e repetir puxando ou repetir varias vezes com border-image-repeat "repeat ou stretch"

da pra diminuir os 3 comandos em 1, usando apenas border-image e colocando as coisas na ordem de source url, slice e repeat

para usar o border image precisa er um border feito antes

planejar o site é muito importante, deixar tudo feito para ter uma visão e depois programar

usando o que foi aprendido pra começar a fazer o site do desafio 10 ep 35

36 variáveis em css

pseudo classe "root" é a raiz da arvore do documento, tudo que for colocado ali vai servir pro documento inteiro

usando min e max deixamos o site responsivo com limites, exemplo colocar minimo de 300px em width e maximo de 1000px width, o site vai parar de crescer em 1000px e quando tiver menos ele vai adaptando até 300px

no desafio 10, todo aquele verde do cabeçado é um padding e não uma margem, se colocar margem vai quebrar, se quiser ver é só mudar e ver

quando se coloca a largura em um item, ele vira um bloco, e para colocar no meio precisa colocar a margem auto

usando *background-image: linear-gradient* podemos fazer um efeito "do mais forte pro mais fraco" em cores, de modo linear escolhendo a direção como "to bottom" que é de cima pra baixo etc..

da pra por efeito usando "transition-duration" que é aquele efeito de acender e desligar(tipo a transição do OBS)

colocando max-width na imagem define o max que ela vai se adaptar

se não colocar o sinal >, por exemplo "*main p*" isso significa que vai alterar os Ps em qualquer nivel que estiver dentro do main, se colocasse *main > p* ele apeans alteraria os Ps que estivesse no main, então se estivesse "*main> article> p*" ele não iria alterar

espaço de inicio de paragrafo usa text-indent

espaço entre linhas se usa line-height, colocando 1em não deixa espaço

caso tenha algo entre uma tag strong, da pra alterar também no css colocando o local que ele está e usando strong, exemplo "*main strong{}*"  e fazer alterações

normalmente as listas colocam as marcações do lado de fora, podemos colocar dentro usando "*list-style-position: inside;*", exemplo:
aside > ul{
    list-style-position: inside;
}

isso diz que todos os itens da lista dentro do aside tem a posição dentro e não fora

para quebrar uma lista muito grande podemos usar *colums: nº* e colocar a quantidade de colunas que queremos

da pra por emoji como marcador da lista usando 

 list-style-type: '\2714'; (tem que usar *'\código'*)

colocando mais um *\00A0* podemos colocar espaço da marcação pro texto, é o NBSP, espaço sem quebra

lembrando que 
    list-style-type: '\2714\00A0\00A0';
nem sempre é compátivel com os navegadores

quando colocamos a margem negativa ela vaza e podemos conectar por exemplo o padding para que fique reto e colado na margem

usando *content* no css, podemos adicionar pequenas imagens ao texto, como por exemplo colocar aquele simbolo de corrente pra links, como por exemplo adicionar o emoji de corrente depois do link: 

a.externo::after{(link da classe externo vai ter algo depois da escrita)
    content: '\00A0\1F517';(emoji)
}

3º modulo

2 git e github

git = repositório local

github = repositório remoto

push = atualizar repositório remoto

5 fazendo o primeiro repositório git e github

13 colocando uma imagem de fundo no seu site

usando background image podemos fazer degrade nas paginas e elementos: *background-image: linear-gradient()* podemos fazer com cores e *background-image: url()* podemos colocar padrões que baixamos

14 imagens que se repetem no fundo do site

background-size deixa por tamanho na imagem

a repetição sempre acontece quand ousa um background-image

mas da pra personalizar a repetição com background-repeat e escolher como vai ser repetido ou se não vai ser repetido, sempre começa no superior esquerdo

15 configurando a posição da imagem no fundo do site

configuramos a posição da imagem usando background-position, colocando a partir de qual parte ela vai ser puxada, exemplo left top(vai puxar o canto superior esquerdo), center center(vai puxaro meio do meio) etc..

vh(viewheight)= é a altura da view port, que é a parte branca/tela do site

16 mudando o tamanho da iamgem de fundo do site

dentro de background-size temos as opções de colocar manualmente o tamanho com valores ou com : contain(foca em mostrar a imagem completa, podendo gerar barras pretas), auto(que é o padrão), e o cover(que cobre a tela inteira mesmo que tenha que corta a imagem, fazendo caber ela no tamanho da janela)

17 background-attachment e shorthand

rolar pagina e deixar fundo travado é chamado de vínculo e se usa o *background-attachment*

usando o *background-size: cover, e o background-attachment: fixed* podemos deixar uma imagem de fundo fixa e rolar para baixo na pagina sem quebrar a imagem

Shorthand - background
                color > image > position > repeat > /[size]
                > attachment

Mas o [size] não está funcionando, então tem que tirar e colocar separado
Na verdade é só colocar uma / entre repeat/size que funciona

aula 18 Centralização vertical de caixas

forma mais facil de centralizar um conteudo horizontalmente é com *margin: auto*, margin só funciona para alinhamentos horizontais

todo posicionamento de um box em html é relativo *"position: relative"*

colocando um elemento com posicionamento absoluto, "*position: absolute*" podemos mexer em mais duas propriedades do elemento, o *left e top*, que é a distancia do elemento para essas duas partes, o topo e o lado esquerdo, da pra usar *porcentagem como medida também além de px*

*transform* é mexer em qualquer caixa aplicando alguma alteração de transformação nela

transform: translate(-20px, -20px)
(deixa mexer a caixa em alguma direção, sendo o + para a direta e baixo, e - para esquerda e cima)

então para deixar um elemento vertical centralizado, colocamos ele com *position absolute*, para podermos mexer nas caracteristicas *left 50% e top 50%* e depois *transform: translate(-50%, -50%)*, fazendo com que a posição absoluta seja o meio

aula 22 ajustes do desafio 12

novo: *text-transform: uppercase*, coloca tudo em caixa alta
novo: *font-variant: small-caps;*, coloca em caixa alta menor, e a primeira letra é maior

aula 23 fontes

enquanto ainda não aprendemos sobre media queree, podemos fazer os textos diminuirem dependendo da largura que a pagina está aberta, utilizando a medida *vw*(view width)

aula 27 tabelas em html

todas as tabelas simples em html são na seguinte hierarquia: table, table row, table header, table data

tags de tabela: <table> <tr> <td>

novo: *border-collapse: collapse;* tira o espaço entre as caixinhas da tabela

o w3c, fala que na HTML5 o fechamento das tags </tr> e </td> não são obrigatórios, mas é bom ter

text-align faz o alinhamento horizontal

e o vertical-align faz o alinha vertical para células(<td>)

text-align: left center right

vertical-align: top middle bottom

todas as infos ficam dentro do *tbody*

 30 caption e escopo de títulos em tabelas

 Caption é a legenda das tabelas

 scope serve pra falar onde está localizado as informaçoes da tabela se é na mesma coluna ou na mesma linha (col e row)

 31 efeito zebrado na tabela

 para criar o efeito zebrado dentro das linhas, usamos *tbody > tr:nth-child()*, e definimos de quantas em quantas linhas vai ser aplicada a mudança exemplo:

 tbody > tr:nth-child(2n){ (vai aplicar na segunda linha toda vez então, 2º, 4º etc..)
            background-color: lightgray;
        }

da pra usar também impar ou par ao invés de números, odd ou even(impar ou par)

32 cabeçado fixo em tabelas grandes

*position: sticky;* faz com que o topo seja arrastado para baixo ao descer a página, indo embora ao acabar a tabela

mas não funciona em todos os navegadores

33 mesclagem de células

formas de mesclagem, expansão em coluna e expansão em linha

36 escopos em grupo

a semantica de row rowgroup e col colgroup serve para casos onde 1 titulo via ter mais de 1 coluna ou linha abaixo que é seu, exemplo ter 3 colunas de filme, se colocarmos *scope: col* o código entende que o TITULO "FILMES" só é de 1 coluna ao invés das 3, por isso colocamos *scope: colgroup*

ou seja, se 1 th(titulos) tem mais de 1 elemento abaixou ou ao lado, deve ser usado colgroup para colunas ou rowgroup para linhas, se for apenas 1, usamos apenas col e row

38 agrupando colunas em colgroup

nova tag <colgroup> permite colocar a quantidade de colunas que temos, assim caso seja preciso marcar uma coluna completa, ao invés de ir em um por um, da pra criar uma classe pra cada coluna e aplicar nela toda

<colgroup>
            <col class="cnome">
            <col class="csexo">
            <col class="cidade">
            <col class="cprof">
</colgroup>

Também da pra fazer coluna em grupo e usar somente *span* pra definir a quantidade de colunas:

<colgroup>
            <col class="cnome">
            <col class="cgrupo" span="2">
            <col class="cprof">
</colgroup>

39 tabelas responsivas

 tabelas grandes podem ser colocadas dentro de uma <div></div> e serem alteradas no css utilizando o *overflow: "auto" "hidden" "scroll"*, overflow cuida das coisas que "transbordam da tela", da pra alterar X e Y ou separadamente

módulo 4

aula 3 iframes

tamanho padrão de um iframe é de 300x150

css é soberano ao código do html

novo parâmetro: *scolling= "auto" "yes" "no"*

Auto = se o conteudo exceder o tamanho do frame ele vai criar a barra de rolagem

yes = mesmo se o conteudo caber todo dentro do frame ele ainda vai criar a barra de rolagem

no = mesmo que o conteudo exceder o tamanho do frame ele NÃO vai criar a barra de rolagem (mas depende do navegador)

frameborder é a borda do frame, podendo colocar 0 e qualquer outra coisa

4 conteúdo local no iframe

só colocar no src o item local

5 navegação no iframe

da pra por nome nas coisas utilizando o parâmetro *name*

usando a tag <a> podemos colocar no parâmetro *target=""* e o nome que colocamos no parâmetro *name* em outro lugar, podendo carregar aquilo que queremos dentro do iframe, exemplo 

<a href="paginas-extras/pag001.html" target="frame">Primeira Página</a></li>

<iframe src="" frameborder="0" id="tela" name="frame"><p>Infelizmente seu navegador não é compatível com isso</p>
    </iframe>

Isso vai fazer que clicando no link <a>, ao invés de carregar uma nova aba ou na mesma página, carregue o conteúdo dentro do iframe

6 conteúdo no frame por código

novo parâmetro, *srcdoc*, diferente do *src* o *srcdoc* permite colocar código HTML5 dentro dele para aparecer no <iframe> como h1, p, etc..

7 incovenientes do iframe

frame e iframe são diferentes, frame é evitado

mecanismos de buscas fazem análises do site, existem alguns problemas para que o google bot entre nos iframes, e faça index ou identificação das coisas dentro de iframes

usabilidade e acessibilidade, softwares leitores de tela tem problemas para acessar os iframes, e problemas de usabilidade é coisas onde o computador se confunde ou o usuário se confunde, exemplo voltar pagina no iframe, o computador se confunde para "voltar iframe" ou "voltar pagina", também sites que tentam abrir coisas em novas abas, alguns navegadores não entendem que tem que abrir uma nova aba e não dentro do iframe, sites que não são responsivos podem apareecer quebrado dentro do iframe

segurança, iframes abrem uma porta do seu site para outro site, então cuidado pra quem vai abrir a porta, então colocar sites que foram invadidos, e estão tendo dados roubados, o seu site começa a fazer isso pro outro site

use e não abuse

8 tornando iframes mais seguros

novo parâmetro *sandbox="sandbox"* faz com que todo site/acesso que tente pegar dados dentro do iframe seja bloqueado, ele ativa tudo no maximo que ele consegue fazer

*referrerpolicy="no-referrer-when-downgrade"* é o padrão, para deixar mais limitado o que é carregado no iframe, se usa o *referrerpolicy="no-referrer"* que liga o maximo de segurança dentro do iframe

da pra configurar o *sandbox* e coloca aquilo que vamos precisar, exemplo: *sandbox="allow-same-origin allow-forms allow-scripts"* para permitir coisas da mesma origem, permitir fomulários e scripts.

*referrerpolicy="no-referer" sandbox="sandbox"* = bloqueio maximo

9 dicas para iframes melhores

usar mapas, videos, docs, etc.. usando link de incorporação

    border-radius: 50%; = redondo

    box-sizing: border-box; = borda fica na caixa, mesmo se for redonda

    transform: translate(-3px, -3px);
    box-shadow: 5px 5px 10px rgba(0, 0, 0, 0.61);
    transition: transform 0.3s, border .6s;

    efeito, sombra, animação


    ::-webkit-scrollbar{
            width: 0px;
            height: 0px;
        }

esconde barra de rolagem