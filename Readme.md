# Inicializando CSS:
Essa é uma continuação do repositório HTML...

## EX001:
Inicializando em CSS, como primeiro passo aprendemos o "Estilo Inline" (os estilos são feito na mesma linha) onde aplicamos as cores e estilos localmente em cada tag. Atenção: não é o melhor jeito, desse jeito polui seu código.

## EX002:
Continuamos com o CSS e exploramos outra maneira de utilizá-lo. Neste exercício, empregamos "Estilos Locais", onde no cabeçalho do nosso código utilizamos a tag 'style'. Em seguida, criamos marcações, como no exemplo de 'h1', e fechamos a chave. Tudo o que definirmos como estilo será aplicado a todos os elementos 'h1', ou seja, é uma abordagem mais prática do que anterior.

## EX003:
O terceiro modo é, "Estilos Externo" onde criamos um arquivo 'style.css' (que é o lugar onde criamos as marcações de estilo) e ai conectamos com nosso arquivo index.html com link css. Conectando os arquivos e assim podendo mudar com uita mais organização e menos trabalho.

## EX004:
Aprofundando-nos nos estilos, podemos iniciar a discussão sobre o modelo RGB (Red, Green, Blue), que representa as cores em pixels. Ao modificar as tonalidades desses componentes, podemos criar uma vasta gama de cores. Existem várias formas de representação, como intervalos de 0 a 255, códigos hexadecimais e nomes de cores. Isso é ilustrado no exemplo 'cor01.html'.

### OBS: 
É necessário ter um breve conhecimento de desing, para isso existe alguns site que nos ajuda a decidir uma paleta de cor adequada (ATENÇÃO: tenha em mente que é necessário ter um breve conhecimento em harmonia das cores). Sites como [Adobe](https://color.adobe.com/pt/create/color-wheel) e [Palleton](https://paletton.com/#uid=33v080kQ1i5BiqIJDmrV6d0Z76L).

### COR02:
Aqui aprendemos a fazer degrades, então ciramos style local, onde colocamos dentro do body 'background-image: linear-gradient()'. Dentro desse comando, podemos estabelecer a direção que o degrade ira começar  (direita: to right, esquerda: to left, cima: to top, baixo: to bottom, angulo:45deg) e usando o Adobe definir a paleta de cor (separados por ',') e assim estabelecer as cores que eu quero no meu degrade.

Mais uma obs: eu utilizo '*' no style para definir uma configuração global.

### COR03:
Aqui damos uma leve aprofundada, utilizando as ferramentas aprendidas e explorando mais o style das CSS. 

## EX005:
Dando um destaque maior às fontes, é crucial reconhecer a relevância que elas desempenham na estética do seu site, assim como no âmbito da psicologia das cores. No contexto de estilo ('style'), é possível ajustar a fonte por meio do comando 'font-family'. Este comando permite a definição de uma combinação de fontes, considerando que alguns dispositivos podem aceitar determinadas fontes enquanto outros não. Portanto, você pode adicionar alternativas que o site poderá usar para representar a mesma fonte. Se necessário, consulte o site [w3schools](https://www.w3schools.com/cssref/css_websafe_fonts.php).

Nesse mesmo cenário, podemos usar 'font-size' para especificar o tamanho (ATENÇÃO: utilize px ou em) 16px é o padrão (o mesmo que 1em). Também, podemos utilizar 'font-weigth' para a intensidade da fonte (dependendo da fonte que escolher pode variar de 100 - 900). 

### Font02:
Proseguindo dentro do exemplo 5 e a questão das fontes. Podemos verificar, que o alinhamento é muito importante, aprendemos então alguns estilos em CSS para alinhar as tags. 

## EX006:
Dando continuidade ao nosso aprendizado. Entramos no mundo das fonts...

### Fonte01:
Podemos utilizar o [Google Fonts](https://fonts.google.com/specimen/Silkscreen) para obter fontes alternativas.

### Fonte02:
Seguindo a mesma lógica do exemplo anterior, mas com uma pequena alteração. Nesse exemplo, baixamos as fontes de um site (não o Google Fonts) e com isso utilizamos alguns mecanismos para poder utiliza-las.

## EX007:
Saindo de fonts e entrando em 'seletores'...

### Seletor01:
Nesse exemplo, aprendemos a usar 'id' e 'class' para identificar uma tag especifica e modifica-la. Ou seja, colocando 'id' como atributo da tag eu posso especificar com um nome e no style eu posso apartir do '#nome' modificala (só ela vai receber aquela configuração). O outro jeito é por 'class', nesse cenário conseguimos dicionar mais de uma tag em uma mesma classe e todos que receberen o nome da classe vai receber a modificação, sendo assim, dentro de style eu posso usar '.nome' e fazer minhas alterações. 

## EX008:
Continuando no contexto de seletores, vamos nos apronfundar em 'pseudo-classes' aqui entramos em seletores especiais. São seletores que especificam um estado especial de um elemento. Para acessa-los utilize (':'). 

### houver:
O seletor 'houver', por exemplo, seleciona um elemento quando o mouse está sobre ele. Além de outros mecanismos apredidos. 

### links: 
Aqui usamos 'pseudo-elementos' que modifica o elemento sem precisar alterar no html. Como no exemplo, consigo adicionar a palavra link em todas as tags 'links' sem precisar ir em cada tag especificamente. Para acessa-lo, utilize ('::').

## EX009:
Começamos a trabalhar com o conceito de 'box' para nós ajudarmos em nossos projetos...

### BOX 01:
Começamos a explorar o termo 'modelagem de caixas'. Nesse contexto, a modelagem de caixa em HTML/CSS refere-se à representação de elementos HTML como caixas retangulares, cada uma contendo conteúdo, preenchimento, borda e margens. Isso é fundamental para controlar o layout e o design em páginas web. As propriedades CSS, tais como largura (width), altura (height), preenchimento (padding), borda (border) e margem(margin), são utilizadas para estilizar essas caixas e criar layouts visualmente atraentes. 

Além de tudo mencionado, buscamos maneiras de simplificar as configurações. Vale ressaltar que elementos como 'border', por exemplo, seguem uma lógica específica para serem adicionados, conforme demonstrado no exemplo. Adicionalmente, temos a capacidade de converter uma caixa de nível box para inline e vice-versa.

### BOX 02:
Exploramos, ainda, as tags de agrupamento semântico. Estas tags têm a finalidade de realizar uma separação semântica da estrutura do nosso site. Em outras palavras, fragmentamos o HTML de forma a distinguir claramente o cabeçalho (header) da parte principal (main). Dentro da seção principal, segmentamos o conteúdo em sessões (section), artigos (article), laterais (aside) e, por último, o rodapé (footer). Essa distinção não apenas contribui significativamente para a organização e clareza do código, mas também desempenha um papel crucial em termos de otimização para mecanismos de busca (SEO) e no ranqueamento por parte de crawlers, como os utilizados pelo Google.

Vimos também como adicionar sombras (box-shadow) às nossas caixas e arredondar os vértices das caixas (border-radius). Vale ressaltar que, normalmente, as sombras são de cor preta e não são totalmente sólidas, ou seja, não precisam chamar tanta atenção.

## DESAFIO 01:
Neste desafio, embarcamos na construção de um pequeno projeto dedicado à criação de um site que explora a fascinante história por trás da evolução do logotipo do Android. Empregamos todo o conhecimento adquirido até o momento, incluindo o uso de repositórios HTML. Abordamos aspectos relacionados às cores, mergulhando na psicologia das mesmas, implementando sombras, degradês e assimilando a aplicação de variáveis em CSS. O ponto de partida envolveu a estruturação inicial em HTML do nosso website, aproveitando as funcionalidades oferecidas pelo [MockFlow](https://wireframepro.mockflow.com/). Posteriormente, dedicamo-nos à prática efetiva com HTML, explorando também o manuseio de imagens e vídeos, incorporando novas tags como 'anside', 'nav', entre outras. Além disso, implementamos uma abordagem de responsividade para o site, uma versão básica, mas eficaz em garantir uma experiência consistente em diferentes dispositivos. 
