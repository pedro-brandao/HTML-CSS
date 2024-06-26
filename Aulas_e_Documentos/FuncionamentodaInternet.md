# HTML-CSS
 Repositorio Baseado nas aulas que estou refazendo para lembrar o conteudo de HTML e CSS

# Algumas anotações para que eu não esqueça.
- [**Manual Markdown Github**](https://docs.github.com/pt/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)<br>

## Cap. 01 Aula 04 - Como a internet Funciona?

Neste video o funcionamento da internet é bem esplicado e são mostradas as formas que a internet chega nas casas das pessoas.
[**Como funciona a Internet?**](https://www.youtube.com/watch?v=TNQsmPf24go)<br>

Aprimeira rede de computadores do mundo foi fundada em 1949 nos estados unidos. E se chamava ARPANET e continham apenas 4 computadores, sendo eles um SDS SIGMA 7, IBM 370/75, DEC PDP-10, SDS 90.<br>
Pelos nomes das marcas podemos notar que eram computadores distintos, portanto foi necessario criar um protocolo de comunicação.
a UCL foi quem criou o primeiro protocolo de comunicação, o NCP.<br>
E em 1972 os pontos da rede ficaram tão grandes que os pesquisadores BOB Kah e Vint Cerf criaram o protocoloque usamos até hoje o TCP/IP.
TCP - Protocolo de transmissão de dados.<br>
IP - Protocolo de endereçamento de maquinas.<br>
Abaixo irei deixar um site onde mostra como esta a internet atualmente, com transmissão via cabo nos oceanos.<br>
[**Internet via cabos submarinos**](https://www.submarinecablemap.com)


## Cap. 02 Aula 01 - Como os dados são representados?
A primeira coisa que precisamos aprender quando falamos sobre o computador é que ele NÃO é inteligente, o computador apenas obedece comandos e podemos dizer que ele é um "Burro muito rapido", pois ele executa as tarefas que foi programado muito rapidamente.<br>
O computador é um equipamento eletronico e como todo equipamento eletronico ele responde a sinais e estes sinais são representados por **0** e **1**, mas na verdade estes sinais são chamadas de ondas quadradas ou sinais eletricos onde o **0** reresenta "sem sinal" e **1** com sinal.<br>
Só que este conjunto de numeros tem um nome tecnico que é Digitos Binário ou do inglês (Binary Digit), mas estes binarios nós abreviamos e utilizamos a nomeclatura de ***bit***, e a porção minima para representar um dado seria 8 bits.<br>
Apartir destas informações nós conseguimos conhecer o ***Byte***, que nada mais é o nome desta porção de 8 bits, abaixo deixo um exemplo da letra A em byte.<br>
**01000001** = A<br>
E para eu saber mais sobre os dados que podem ser representados por bytes eu posso olhar a tabela de [**Código Multibyte UTF-8**](https://www.ibm.com/docs/pt-br/aix/7.3?topic=8-utf-ucs-transformation-format)<br>

> [!TIP]
> Apenas para titulo de curiosidade, este codigo Multibyte ele usa de 1 a 4 bytes para representar letras, simbolos, caracteres acentuados e até emoji.<br>

### Multiplos de Byte.
Assim como temos conversões de peso, medida e etc. Também temos conversões de multiplos de bytes.<br>
Estes multiplos são representados por 1024 Byte. Há esta difereça para 1024 e não 1000, pois 1024 seria 2^10 que da 1024.<br>

#### Os multiplos de Bytes são:
- 8 Byts = 1 Byte **BT**
- 1024 Bytes = 1 Kilobyte **KB**
- 1024 Kilobyte = Megabyte **MB**
- 1024 Megabyte = Gigabyte **GB**
- 1024 Gigabyte = Terabyte **TB**
- 1024 Terabyte = Petabyte **PB**
- 1024 Petabyte = Exabyte **EB**
- 1024 Exabyte = Zetabyte **ZB**
- 1024 Zetabyte = Yotabyte **YB**


## Como nos conectamos?
Agora que sei como o computador funciona, já posso estudar sobre como nós nos conectamos.<br>
Para entendermos como funciona a conexão, quando nos conectamos o meu computador é chamdo de Cliente! Cliente pois seria o usuario de um serviço, tudo oque navegamos na internet são serviços, desta forma somos todos clientes deles.<br>
Agora falando dos serviços, eles estão na internet (Rede mundial de computadores). Mas como fazemos esta conexão? Geralmente quando fazemos a instalação da internet nós recebemos um aparelho, este aparelho serve para transformar as ondas senoidal que são as ondas transmitidas pela internet para as ondas quadradas que são as ondas reconhecidas pelo computador.<br>
Este processo de transformação das ondas é chamado de Modulação (Modulation) e Demodulação (Demodulation), por isso o nome do aparelho é **MODEM**


## Alguns Protocolos e seus significados.
**FTP** - Protocolo de transferencia de arquivos.<br>
**SMTP/POP3/IMAP**- Protocolos de e-mails.<br>
**GOPHER** - Transferencia de Hiper texto simples (via terminal).<br>
**HTTP** - Protocolo de transferencia de hiper texto (textos com links).<br>
**WWW** - Wold Wide Web - rede de alcance Mundial, é a abreviação e a forma de mencionar o HTTP.<br>


## Estrutura basica de HTML e CSS.
Todo o conteudo em HTML tem uma abertura de tag com couchete angular (<>) e um fechamento com couchete e a barra (</>), como no exemplo abaixo.

~~~html
<h1> Exemplo de titulo </h1>
<p> Exemplo de paragrafo</p>
~~~

- Acima conseguimos ver que o conteudo da tag "Exemplo de Titulo".
- A tag de abertura começa com ```<h1>``` (sem os espaços).
- A tag de fechamento termina ```</h1>``` (sem os espaços).


###### Agora vou analisar uma estrutura de uma tag.
~~~html
<img src="foto.png" alt="Exemplo de Foto">
~~~

No codigo acima posso ver que se trata de uma tag que carrega uma imagem, nela tenho a seguinte estrutura.
- ```<img>``` Seria a abertura da tag
- ```src=``` Seria um parametro e o caminho onde a imagem está.
- O ```alt=``` também é um parametro e seria um texto alternativo para auxiliar leitores de tela.
- **foto.png** seria o valor do parametro.

~~~css
h1 {
	 font-family: arial;
	 font-size: 12pt;
	 font-color: blue;
}
~~~

