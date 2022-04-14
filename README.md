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
## Aula 1 (Capítulo 2) - Como a Internet Funciona?
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
* Modulação: Conversão de ondas Quadradas em Sonoidais
* Demodulação: Converção de ondas Senoidais em Quadradas
* Servidor: Maquina onde estão instalados os serviços
* Toda maquina, seja cliente ou servidor, que está conectada na internet tem um numero de identificação chamado IP
* DNS (Domain Name System): Servidor onde é requisitado um **Dominio**(Nome) e é devolvido o **IP**(Numero)
* Pacotes: Pedaços ddo arquivo que são enviados por diferentes rotas em diferentes tempos
## Aula 2 (Capítulo 2) - O que é Domínio e Hospedagem?
* Dominio: **Nome Unico** que refere ao endereço do servidor
* TLD (Top Level Domains):
    * GTLD (Generic Top Level Domains): Dominios de Alto Nivel Genéricos (.com para instituições comerciais, .gov para governamentais, etc)
    * CCTLD (Country Code Top Level Domains): Dominios de Alto Nivel para Codigos de País (.br para brasil, .us, .pt, .uk, etc) 
* Hospedagem: Espaço para armazenar arquivos
* URL (Uniforme Resource Locator): 
    * *https://www.github.com/gustavoguanabara*
    * github.com = Dominio
        * .com = TLD
    * www = sub-domínio
    * https:// = Protocolo
    * /gustavoguanabara = caminho
