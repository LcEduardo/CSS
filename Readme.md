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