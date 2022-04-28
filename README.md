# Curso_HTML5_CSS3

Curso de HTML5 e CSS3 com Gustavo Guanabara

# Modulo 1

## Referências

### Referências Online e Documentação

* MDN (Mozilla Developer Network)
* W3C Standarts (World Wide Web Consortion)
* WHATWG Living Standart (Web Hypertext Application Technology Working Group)
* W3Schools (Refsnes Data)

### Livros

* HTMLL: Up and Running, Mark Pilgrim (O'Reilly)
* CSS: The Definitive Guide, Eric Meyer (O'Reilly)
* Flexbox in CSS, Estelle Weyl (O'Reilly)
* Grid Layout in CSS, Eric Meyer (O'Reilly)
* HTML5 e CSS3: Guia Prático e Visual, Elizabeth Castro e Bruce Hyslop (Alta Books)
* HTML & CSS: Projete e Construa Websites, Jon Duckett (Alta Books)
* Use a Cabeça! HTML e CSS, Elisabeth Robson e Eric Freeman (Alta Books)
* Crie Seu Proprio Site: Um Guia Em Quadrinhos Pra HTML, CSS e Wordpress, Nate Cooper e Kim Gee (Novatec)
* HTML5, Mauricio Samy Silva (Novatec)
* CSS3, Mauricio Samy Silva (Novatec)
* Fundamentos de HTML5 e CSS3, Mauricio Samy Silva (Novatec)
* CSS Grid Layout, Mauricio Samy Silva (Novatec)
* Curso de Design Gráfico: Princípios e Práticas, David Dabner e Outros (GG)
* Design: O Essencial do Design Gráfico, Bob e Maggie Gordon (Senac)
* A Psicologia das Cores: Como as Cores Afetam a Emoção e a Razão, Eva Heller (GG)
* Pensar Com Tipos, Ellen Lupton (GG)
* Flexbox Explained, Jorge Montoya e Stephen Burge (OSTRaining)
* CSS Grid Explained, Jorge Montoya e Stephen Burge (OSTRaining)

## Capítulo 2 (Aula 1) - Como a Internet Funciona?

### Representação de Dados

* Os aparelhos eletrônicos funcionam a base de **bits** (0 ou 1) e um tipo de onda chamada **Onda Quadrada** ou **Binaria**
* O conjunto de **8 bits** denomina-se **Byte**, que é a porção minima de representação de um dado
* A tabela **Codigo Multibyte UTF-8** é a tabela onde contém os dados em bytes para serem convertidos para Alfanuméricos, Símbolos e Acentuações

### Multiplos de Byte

* 8 bits = 1 byte
* 1024 bytes = 1 KB
* 1024 KB = 1 MB
* 1024 MB = 1 GB
* 1024 GB = 1 TB
* 1024 TB = 1 PB
* 1024 PB = 1 EB
* 1024 EB = 1 ZB
* 1024 ZB = 1 YB

### Notação

* Byte (B) != Bit (b)
* **Byte** normalmente usado para representar **Armazenamento**
* **Bit** normalmente usado para representar **Transmissão**

### Como nos conectamos?

* Cliente: Maquina do Usuário
* Internet: Rede mundial de redes distribuidas (Rede de redes)
* O intermédio do cliente e a internet é uma linha telefonica ou rede televisiva que funcionam com tipo de onda chamada **Onda Senoidal**
* Para o cliente se conectar a internet é necessário um Modem (Aparelho **Mo**dulador e **Dem**odulador)
* Modulação: Conversão de ondas Quadradas em Senoidais
* Demodulação: Converção de ondas Senoidais em Quadradas
* Servidor: Maquina onde estão instalados os serviços
* Toda maquina, seja cliente ou servidor, que está conectada na internet tem um numero de identificação chamado IP
* DNS (Domain Name System): Servidor onde é requisitado um **Dominio**(Nome) e é devolvido o **IP**(Número)
* Pacotes: Pedaços do arquivo que são enviados por diferentes rotas em diferentes tempos

## Capítulo 2 (Aula 2) - O que é Domínio e Hospedagem?

* Dominio: **Nome Unico** que refere ao endereço do servidor
* TLD (Top Level Domains):
  * GTLD (Generic Top Level Domains): Dominios de Alto Nivel Genéricos (.com para instituições comerciais, .gov para governamentais, etc)
  * CCTLD (Country Code Top Level Domains): Dominios de Alto Nivel para Codigos de País (.br para brasil, .us, .pt, .uk, etc)
* Hospedagem: Espaço para armazenar arquivos
* URL (Uniforme Resource Locator):
  * *<https://www.github.com/gustavoguanabara>*
  * github.com = Dominio
    * .com = TLD
  * www = sub-domínio
  * https:// = Protocolo
  * /gustavoguanabara = caminho

## Capítulo 3 (Aula 1) - A Diferença entre **HTML**, **CSS** e **JavaScript**

* HTML (HyperText Markup Language) = Linguagem focada em **Conteúdo** (Textos, Imagens, Videos, Tabelas, etc)
* CSS (Cascading Style Sheets) = Liguagem focada em **Design** (Cor, Sombras, Posicionamento, Tamanho, etc)
* JavaScript (JS) = Liguangem de **Programação** focada em **Interação** (Menus, Animações, Popups, Valdações, etc)

### Conteúdo em HTML

* Desenvolvido a partir de **tags**
* Simbolizadas com *<>* para abertura e *</>* para fechamento
* Algumas tags não possuem fechamento

### Estilo em CSS

* Desenvolvido a partir de **seletores**
* Simbolizadas com **seletor** (*tag, id ou nome*), seguido por *{}* onde dentro estão **Declarações**, compostas por **propriedades** com **valores** terminadas **SEMPRE** em *;*

### Estrutura Básica de um Documento HTML

~~~html
<!DOCTYPE html>
<html lang="pt-br">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Document</title>
    </head>
    <body>
        <h1>Olá Mundo!</h1>
    </body>
</html>
~~~

## Capítulo 3 (Aula 2) - Front-end, Back-end e Full Stack

* Front-end (Client-side): Desenvolve tecnologias do lado do cliente
* Back-end (Server-side): Desenvolve tecnologias do lado do servidor
* Tecnologias Front-end
  * HTML
  * CSS
  * JavaScript
* Tecnologias Back-end
  * PHP
  * NodeJS
  * C#
  * Python
  * Ruby
  * Java
* Full Stack: Desenvolvedor tanto Front-end tanto Back-end

## Capítulo 4 (Aula 2) - Seu Primeiro Código HTML

* `<!DOCTYPE html>`: Indica que o documento é HTML5
* `<html lang="pt-br"></html>`: Abre e  fecha documento HTML e indica a língua
* `<head></head>`: Área de configuração do site
* `<body></body>`: Área do conteúdo do site
* `<meta charset="UTF-8">`: Indica os caracteres do padrão UTF-8
* `<meta name="viewport" content="width=device-width, initial-scale=1.0">`: Indica que o site utilizara 100% do espaço da pagina
* `<title></title>`: Título do site
* `<h1></h1>`: Título de nivel 1
* `<p></p>`: Parágrafo
* `<hr>`: Linha horizontal (Horizontal Row)

## Capítulo 5 (Aula 1) - Parágrafos e Quebras

* `<br>`: Quebra de Linha (Break Row)

## Capítulo 5 (Aula 2) - Símbolo e Emoji no seu site

* `&lt;`: Símbolo de Menor (Less Than)
* `&gt;`: Símbolo de Maior (Greater Than)
* `&reg;`: Símbolo de Marca Registrada
* `&copy;`: Símbolo de Copy Mark
* `&trade;`: Símbolo de Trade Mark
* `&euro;`: Símbolo de Euro
* `&pound;`: Símbolo de Libra
* `&yen;`: Símbolo de Yen
* `&cent;`: Símbolo de Cents
* `&delta;`: Símbolo de Delta Minusculo
* `&Delta;`: Símbolo de Delta Maiusculo
* `&uarr;`: Símbolo de Seta para Cima
* `&darr;`: Símbolo de Seta para Baixo
* `&rarr;`: Símbolo de Seta para Direita
* `&larr;`: Símbolo de Seta para Esquerda
* `&#x...`: Codigo para colocar emoji sem **U+**

## Capítulo 6 (Aula 4) - A tag img em HTML5

* `<img src="" alt="">`: Adiciona Imagens ao site 
  * src: caminho da imagem
  *alt: texto alternativo/explicativo da imagem

## Capítulo 6 (Aula 5) - Como mudar o favicon de um site

* `<link rel="shortcut icon" href="favicon.ico" type="image/x-icon">`: Muda o Favicon (Icone do site)
  * href: caminho do icone