# Algumas anotações para que eu não esqueça.

## Como a internet Funciona?

Neste video o funcionamento da internet é bem esplicado e são mostradas as formas que a internet chega nas casas das pessoas.
[Como funciona a Internet?](https://www.youtube.com/watch?v=TNQsmPf24go)

Aprimeira rede de computadores do mundo foi fundada em 1949 nos estados unidos. E se chamava ARPANET e continham apenas 4 computadores, sendo eles um SDS SIGMA 7, IBM 370/75, DEC PDP-10, SDS 90.
Pelos nomes das marcas podemos notar que eram computadores distintos, portanto foi necessario criar um protocolo de comunicação.
a UCL foi quem criou o primeiro protocolo de comunicação, o NCP.
E em 1972 os pontos da rede ficaram tão grandes que os pesquisadores BOB Kah e Vint Cerf criaram o protocoloque usamos até hoje o TCP/IP.
TCP - Protocolo de transmissão de dados.
IP - Protocolo de endereçamento de maquinas.
Abaixo irei deixar um site onde mostra como esta a internet atualmente, com transmissão via cabo nos oceanos.
[Internet via cabos submarinos](https://www.submarinecablemap.com)


## Como os dados são representados?



## Alguns Protocolos e seus significados.
**FTP** - Protocolo de transferencia de arquivos.
**SMTP/POP3/IMAP**- Protocolos de e-mails
**GOPHER** - Transferencia de Hiper texto simples (via terminal)
**HTTP** - Protocolo de transferencia de hiper texto (textos com links).
**WWW** - Wold Wide Web - rede de alcance Mundial, é a abreviação e a forma de mencionar o HTTP.


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

~~~html
h1 {
    font-family: arial;
    font-size: 12pt;
    font-color: blue;
}
~~~
