#### Unoesc Chapecó
#### Pós-graduação em Desenvolvimento Web, Cloud e Dispositivos Móveis - WebMob
#### Disciplina: HTML5+CSS3
#### Professor: Jean Carlo Nascimento
#### Acadêmico: Marcelo Garbin
### Artigo de revisão de CSS3
##### Funcionalidade: text-shadow
##### O que é?
A propriedade CSS3 text-shadow destina-se a obter um efeito de sombreamento em textos. O efeito de sombreamento no texto é feito através de uma cor e três medidas. Sendo que a medida-1 é o valor para o deslocamento da sombra para a direita (valor positivo) ou para esquerda (valor negativo), a medida-2 é o valor para o deslocamento da sombra para baixo (valor positivo) ou para cima (valor negativo) e a medida-3 é o raio para um efeito blur na sombra. No valor cor é definido a cor da sombra. Os valores de medida-3 e de cor são opcionais.
A propriedade text-shadow admite a aplicação de várias sombras declarando uma lista de grupo de valores separados por vírgula.
##### Onde usar:
Aplica-se a todos os elementos e conteúdos gerados.
##### Como usar:
A sintaxe geral para aplicar esta funcionalidade é mostrada a seguir.

```css
seletor {
	text-shadow: medida-1 medida-2 medida-3 cor;
}
```
##### Exemplo de uso
1. Sombra única
```css
seletor { 
	text-shadow: 3px 3px 3px blue; 
} 
```

2. Várias sombras
```css
seletor { 
	text-shadow: 3px 3px 3px blue, 5px 0px 4px green; 
} 
```
[Clique Aqui para ver o exemplo funcionando](http://www.marcelogarbin.com.br/unoesc/htmlecss/exemplos-css3.html)

### Referência:
[http://www.maujor.com/tutorial/css3-text-shadow.php](http://www.maujor.com/tutorial/css3-text-shadow.php)

##### Funcionalidade: transform – rotate
##### O que é?
A propriedade CSS3 transform:rotate() destina-se a obter um efeito de rotação de um elemento. O efeito de rotação de um elemento é feito através de um valor para o ângulo fornecido em deg, grad, rad e turn.
Valores positivos causam rotação no sentido horário e valores negativos no sentido anti-horário.
##### Onde usar:
Aplica-se a qualquer elemento transformavel.
##### Como usar:
A sintaxe geral para aplicar esta funcionalidade é mostrada a seguir.

```css
seletor {
	transform: rotate(angulo);
}
```
##### Exemplo de uso
```css
seletor { 
	transform: rotate(15deg);
} 
```
[Clique Aqui para ver o exemplo funcionando](http://www.marcelogarbin.com.br/unoesc/htmlecss/exemplos-css3.html)

### Referência:
[https://developer.mozilla.org/pt-BR/docs/Web/CSS/transform#rotate](https://developer.mozilla.org/pt-BR/docs/Web/CSS/transform#rotate)

##### Funcionalidade: transform – scale
##### O que é?
A propriedade CSS3 transform:scale() destina-se a alterar o tamanho de um elemento. Esta propriedade pode ser usada para aumentar ou reduzir proporcionalmente o elemento em relação ao seu tamanho original atráves de 2 parâmetros. Os valores de x ou y, maiores que 1 expressam aumento e valores entre 0 e 1 diminuição das dimensões. Se o valor de y não for definido, o valor de x é assumido na posição de y.

##### Onde usar:
Aplica-se a qualquer elemento transformavel.
##### Como usar:
A sintaxe geral para aplicar esta funcionalidade é mostrada a seguir.

```css
seletor {
	transform: scale(x, y);
}
```
##### Exemplo de uso
```css
seletor { 
	transform: scale(1.2, 2);
} 
```
[Clique Aqui para ver o exemplo funcionando](http://www.marcelogarbin.com.br/unoesc/htmlecss/exemplos-css3.html)

### Referência:
[https://developer.mozilla.org/pt-BR/docs/Web/CSS/transform#scale](https://developer.mozilla.org/pt-BR/docs/Web/CSS/transform#scale)

##### Funcionalidade: box-shadow
##### O que é?
A propriedade CSS3 box-shadow permite adicionar múltiplas sombras a elementos. Existem dois tipos de sombras, externas e internas. Sendo que a sombra externa é setada como padrão e para definir a sombra interna é setado inset na propriedade. O efeito de sombreamento é feito através de uma cor, três medidas e se a mesma é externa ou interna. Sendo que a medida-1 é o valor para o deslocamento da sombra para a direita (valor positivo) ou para esquerda (valor negativo), a medida-2 é o valor para o deslocamento da sombra para baixo (valor positivo) ou para cima (valor negativo) e a medida-3 é o raio para um efeito blur na sombra. No valor cor é definido a cor da sombra. Os valores de medida-3 e de cor são opcionais.
A propriedade box-shadow como a propriedade text-shadow, admite a aplicação de várias sombras declarando uma lista de grupo de valores separados por vírgula.

##### Onde usar:
Aplica-se a qualquer elemento.
##### Como usar:
A sintaxe geral para aplicar esta funcionalidade é mostrada a seguir.

```css
seletor {
	box-shadow: inset medida-1 medida-2 medida-3 cor;
}
```
##### Exemplo de uso
1. Sombra Interna
```css
seletor { 
	box-shadow: inset 0 0 1px gold;
} 
```
2. Sombra Externa
```css
seletor { 
	box-shadow: 0 0 1px gold;
} 
```
[Clique Aqui para ver o exemplo funcionando](http://www.marcelogarbin.com.br/unoesc/htmlecss/exemplos-css3.html)

### Referência:
[https://developer.mozilla.org/pt-BR/docs/Web/CSS/box-shadow](https://developer.mozilla.org/pt-BR/docs/Web/CSS/box-shadow)

##### Funcionalidade: @font-face
##### O que é?
A propriedade CSS3 @font-face destina-se a especificar um tipo de fonte para uso em determinadas partes de uma página ou na página toda (ou no site todo) e ter a garantia que a fonte especificada será renderizada no navegador do usuário independentemente de ele ter ou não a fonte instalada em seu sistema operacional. A idéia central do @font-face é informar ao navegador do usuário que a fonte especificada na folha de estilo deve ser procurada primeiramente no sistema operacional local e caso não seja encontrada ela deverá ser baixada para a máquina local de um determinado endereço da web informado nas CSS.
O navegador do usuário fará download da fonte no endereço constante do descritivo src e utilizará a fonte para renderizar os parágrafos do documento. Caso o arquivo não seja encontrado no endereço especificado ou o navegador não entenda a diretiva (retro-compatibilidade) será utilizada a fonte genérica Cursive.

##### Onde usar:
Aplica-se a qualquer elemento.
##### Como usar:
A sintaxe geral para aplicar esta funcionalidade é mostrada a seguir.

```css
@font-face {
  font-family: 'nome da fonte';
  src: local('nome_fonte_no_computador'), url('local_da_fonte') format('formato_da_fonte');
}

```
##### Exemplo de uso
```css
@font-face {
  font-family: 'Roboto Condensed';
  font-style: normal;
  font-weight: 400;
  src: local('Roboto Condensed'), local('RobotoCondensed-Regular'), url(https://fonts.gstatic.com/s/robotocondensed/v13/Zd2E9abXLFGSr9G3YK2MsDAdhzWOYhqHvOZMRGaEyPo.woff2) format('woff2');
}

p { font-family: "Roboto Condensed", Cursive; }
```

[Clique Aqui para ver o exemplo funcionando](http://www.marcelogarbin.com.br/unoesc/htmlecss/exemplos-css3.html)

### Referência:
[http://www.maujor.com/tutorial/css3-@font-face.php](http://www.maujor.com/tutorial/css3-@font-face.php)

##### Funcionalidade: linear-gradient
##### O que é?
linear-gradient é uma funcionalidade das CSS3 para criar degrades entre 2 ou mais cores em linha. Diz-se que um gradiente é linear quando a transição das cores se faz segundo um eixo (linha reta) que possui um sentido (por exemplo: horizontal) e uma direção (por exemplo: da esquerda para a direita).

##### Onde usar:
Aplica-se a qualquer elemento.
##### Como usar:
A sintaxe geral para aplicar esta funcionalidade é mostrada a seguir.

```css
seletor {
  background: linear-gradient(direção, cor-stop1, cor-stop2, ...);
}

```
##### Exemplo de uso
```css
seletor {
  background: linear-gradient(to right, white, purple);
}
```

[Clique Aqui para ver o exemplo funcionando](http://www.marcelogarbin.com.br/unoesc/htmlecss/exemplos-css3.html)

### Referência:
[http://www.maujor.com/tutorial/css3-gradientes-lineares.php](http://www.maujor.com/tutorial/css3-gradientes-lineares.php)


##### Funcionalidade: animation
##### O que é?
Com CSS3 Animation conseguimos criar animações que podem substituir imagens animadas, animações em Flash e JavaScript. Permite que um elemento gradualmente mude de um estilo para outro. Para usar animação CSS3, você deve primeiro especificar alguns keyframes para a animação.

##### Onde usar:
Aplica-se a qualquer elemento.
##### Como usar:
A sintaxe geral para aplicar esta funcionalidade é mostrada a seguir.

```css
@keyframes exemplo {
  from {background-color: cor;}
  to {background-color: cor;}
}

seletor {
  background-color: cor;
  animation-name: exemplo;
  animation-duration: tempo;
  animation-iteration-count: quantidade;
}
```
##### Exemplo de uso
```css
@keyframes exemplo {
  from {background-color: red;}
  to {background-color: yellow;}
}

div {
  width: 100px;
  height: 100px;
  background-color: red;
  animation-name: exemplo;
  animation-duration: 4s;
  animation-iteration-count: 4;
}
```

[Clique Aqui para ver o exemplo funcionando](http://www.marcelogarbin.com.br/unoesc/htmlecss/exemplos-css3.html)

### Referência:
[http://www.w3schools.com/css/css3_animations.asp](http://www.w3schools.com/css/css3_animations.asp)

##### Funcionalidade: rgba
##### O que é?
O Módulo CSS3 para Cores estendeu o uso de RGB criando RGBA (red, green, blue, alpha-opacity) acresentando mais um argumento na declaração da cor, que permite definir a opacidade em uma escala decimal de 0 a 1. Os valores RGB podem ser declarados em escala numérica de 0 a 255 ou percentual de 0 a 100%.

##### Onde usar:
Aplica-se a qualquer elemento.
##### Como usar:
A sintaxe geral para aplicar esta funcionalidade é mostrada a seguir.

```css
seletor {
  background: rgba(cor1, cor2, cor3, opacidade);
}
```
##### Exemplo de uso
```css
div {
  background: rgba(0, 0, 0, 0.5);
}
```

[Clique Aqui para ver o exemplo funcionando](http://www.marcelogarbin.com.br/unoesc/htmlecss/exemplos-css3.html)

### Referência:
[http://www.maujor.com/tutorial/css3-modulo-para-cores.php](http://www.maujor.com/tutorial/css3-modulo-para-cores.php)

##### Funcionalidade: resize
##### O que é?
Utilizando a propriedade resize é possível permitir que um determinado elemento seja redimensionado pelo usuário. Por exemplo, uma caixa de texto ou uma div de conteúdo ter essa propriedade setada e com isso ser modificada de acordo com o gosto do usuário.

##### Onde usar:
Aplica-se a qualquer elemento.
##### Como usar:
A sintaxe geral para aplicar esta funcionalidade é mostrada a seguir.

```css
seletor {
  resize: none|both|horizontal|vertical|initial|inherit;
}
```
##### Exemplo de uso
```css
div textarea{
  resize: vertical;
}
```

[Clique Aqui para ver o exemplo funcionando](http://www.marcelogarbin.com.br/unoesc/htmlecss/exemplos-css3.html)

### Referência:
[http://www.w3schools.com/cssref/css3_pr_resize.asp](http://www.w3schools.com/cssref/css3_pr_resize.asp)

##### Funcionalidade: transition
##### O que é?
O objetivo da CSS3 transition é fornecer mecanismos que permitam a mudança de estilização de um elemento HTML de uma forma suave e controlada no tempo. Podemos adicionar um efeito quando o navegador troca de um estilo para outro, sem usar animações em Flash ou JavaScript.

##### Onde usar:
Aplica-se a qualquer elemento.
##### Como usar:
A sintaxe geral para aplicar esta funcionalidade é mostrada a seguir.

```css
seletor {
  seletor { transition: |property| |duration| |timing-function| |delay|; }
}
```
##### Exemplo de uso
```css
a {
  color: blue;
  transition: 0.5s ease-in;
}

a:hover {
  color: red;
  transition: 0.5s ease-in;
}
```

[Clique Aqui para ver o exemplo funcionando](http://www.marcelogarbin.com.br/unoesc/htmlecss/exemplos-css3.html)

### Referência:
[http://www.maujor.com/tutorial/css3-modulo-transition.php](http://www.maujor.com/tutorial/css3-modulo-transition.php)