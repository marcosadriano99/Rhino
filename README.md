# Rhino

<b>Componentes:</b><br/>
Marcos Adriano Rocha de Oliveira - <b>GitHub nickname:</b> marcosadriano99 - <b>Matrícula:</b> 20141011110298<br/>
Paulo Victor Freire Ribeiro Damasceno - <b>GitHub nickname:</b> pvictorfreitas - <b>Matrícula:</b> 20141011110085

<h2>Resumo</h2>

<p> O Rhino é uma implementação open source do JavaScript baseada na linguagem Java. A função dessa implementação é possibilitar o reaproveitamento de um código JavaScript dentro do código Java. A utilização do Rhino é bem simples e prática, ele foi criado com a intenção de reaproveitar códigos, assim ganhando produtividade, por não precisar fazer dois códigos idênticos em linguagens diferentes. </p>
<p> O principal mantenedor do Rhino é o Mozilla e seu projeto foi iniciado em 1997, na Netscape. Sua programação é em Java e é orientado a objetos. 
</p>

<h2>Instalação e uso</h2>

<p>Para fazer o download do <b>Rhino</b>, o seu mantenedor, a <i>Mozzila Foundation</i>, disponibiliza um site onde é possível encontrar várias versões da linguagem que podem ser baixadas para o computador. Após terminar o download e descompactar o arquivo, é necessário setar as variáveis de ambiente, abrindo as propriedades do computador, procurando pelas configurações avançadas do sistema e clicando em "Variáveis de Ambiente..." Então, nas opções "Variáveis do Sistema", procure pela variável chamada "CLASSPATH" (caso não exista, crie) e adicione o local onde foi descompactado o arquivo baixado. Confirmando a operação, estão concluídas as variáveis de ambiente para o <b>Rhino</b>.</p>
<p>Para criar um arquivo <i>bat</i> para abrir o <b>Rhino</b>, é preciso abrir o prompt de comando e ir para o diretório do arquivo baixado. Então, crie um arquivo em lotes digitando "copy con Rhino.bat" Depois disso, digite o seguinte código:</p>

~~~~
@echo off

java -jar js.jar

^Z
~~~~

<p>Agora você criou um arquivo em lotes e pode iniciar o <b>Rhino</b>.

<h2>Sintaxe básica</h2>

<h3>Variáveis e constantes - inicialização e comandos de atribuição</h3>

<p>Para declarar variáveis, é utilizado o comando <i>var</i>, e, para atribuir, o símbolo de <i>=</i>, da mesma forma que no JavaScript.</p>

~~~~
var x = "hello, world"

print (x)
hello, world
~~~~

<h3>Operadores relacionais e lógicos</h3>

| Operador  | Descrição |
| ------------- | ------------- |
| ==  | Igual a  |
| <> ou !=  | Diferente de  |
| ===  | Idêntico  |
| !==  | Diferente  |
| > | Maior que  |
| < | Menor que  |
| >=  | Maior ou igual  |
| <=  | Menor ou igual  |
| &&  | E  |
| ||  | Ou  |

<h3>Operadores aritméticos</h3>

| Operadores  | Descrição |
| ------------- | ------------- |
| + | Adição  |
| - | Subtração  |
| *  | Multiplicação  |
| /  | Divisão  |
| %  | Módulo |
| ++  | Incremento  |
| --  | Decremento  |

<h3>Estruturas de controle condicional</h3>

É usado o <i>if</i> e <i>else</i>.

~~~~
var x = "hello world";

if (x === "hello, world") print ("true");
else print ("false");
~~~~

<h3>Estruturas de repetição</h3>

<h5>While</h5>

~~~~
var x = 0;

while (x <= 5){x++; print("teste")}
teste
teste
teste
teste
teste
teste
~~~~

<h5>Do while</h5>

~~~~
var x = 0;

do{print(x); x++;} while(x <= 5);
0
1
2
3
4
5
5
~~~~

<h5>For</h5>

~~~~

~~~~

<h3>Vetores, matrizes e strings</h3>

<h3>Funções</h3>

<h2>Sintaxe OO</h2>

<h3>Classes</h3>

<h3>Objetos</h3>

<h3>Atributos (visibilidade: privado e público, escopo: classe e objeto)</h3>

<h3>Métodos (visibilidade: privado e público, escopo: classe e objeto)</h3>

<h3>Construtores</h3>

<h3>Herança</h3>

<h3>Polimorfismo</h3>

<h3>Sobrecarga</h3>

<h3>Categorias de exeções</h3>

<h3>Captura e lançamento de exceções</h3>

<h3>Criar novas exeções</h3>
