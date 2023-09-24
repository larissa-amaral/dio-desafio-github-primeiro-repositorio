# HTML

## Entendendo Comunicação Client X Server

**História da Web**



**O que são Clients**

Cliente é quando você consome a informação de algum lugar. Baseado na internet é o dispositivo que está consumindo a internet (seu próprio notebook, celular)

A internet é conhecida como uma rede mundial de computadores, são basicamente computadores interligados.

> **Conceito Client**
>
> Notebook > Internet > Servidor
> (cliente)  (HTTP)    (Servers)

Quando se cria um site você hospeda num servidor para que outras pessoas possam acessar. O servidor recebe o pedido e retorna a informação, que nesse caso seria o site que o dispositivo em questão solitou.

O servidor retorna arquivos estáticos (HTML, CSS, JavaScript, Imagens...) para o cliente depedendo da conexão dele e também arquivos muito grandes, podendo afetar muito a experiência do usuário.

Na requesição do servidor ele processa as informações e envia e aí sim o navegador utiliza o *cache* que pega essas infomações e armazena no computador do cliente para caso ele chegue a visitar de novo seu site não percorra de novo esse caminho.

> O botão F5 apaga os caches ques estão no seu computador e faz a requisição de novo para o servidor

Outra preocupação é a questão da resposividade, que seria a visualização do websites em dispositvos e resoluções diferentes. Também temos a preocupação dos navegadores (Firefox, Chrome, Safari..) e cada um deles interpreta as informações vindas do servidor de forma padronizada, mas pode acontecer de infomações se comportarem de formas diferentes uma da outra.

- Navegadores

São programas intalados nos dispositivos e serve para interpretar os arquivos que vem do servidor.

Para sempre mante um padrão existe a W3C, que é conjuntos de várias pessoas de várias empresas que definem o padrão para o comportamento dessas instruções.

Link para [Suporte dos Navegadores](https://www.w3schools.com/tags/ref_html_browsersupport.asp)

- Aplicação Web

São soluções criadas que possuem a internet como meio de comnicação entre Client X Server não sendo necessário instalação.

**O que são Servers**

Um servidor não necessariamente precisa ser acessado pela internet ele pode ser local (LAN), mais conhecido como computador central numa empresa.

Existem servidores de:

- Arquivos
- Segurança (Firewall)
- Streaming
- E-mail
- Web

Todos os computadores tem duas partes, a lógica e física. A parte lógica são os softwares como sistema operacional, aplicativos para monitoramento, servidores de web. A parte física é o aramazenamento (disco rígido, SSDs), memória e processadores

Servidores:

**Proxy**
O servidor Proxy serve para filtrar a conexão, por exemplo quando se quer limitar ou previnir que funcionários de uma empresa acessem sites que sejam considerados maliciosos. Um intermediário que apartir de algumas regras te retorna ou não a opção desejada.
Pode acontecer de ele passar pelo Proxy e passar pela internet para baixar no servidor, mas quando bate no Proxy na volta ele bloqueia

- **Firewall**
O firewall também serve para fazer essa segurança, mas ele é mais voltado para o acesso externo. Quando alguém tenta enviar um arquivo malicioso para a rede o firewall é o que protege. É um servidor mas é um sistema instalado dentro

- **Web Server**
Um site que bate na internet que bate no web server

- **Email**
O mesmo do anterior mas é um servidor voltado para servidores de email para armazenar os emails

- **Database Server**
Pode ser que sua aplicação esteja instalada no servidor e essa aplicação se conecta num banco de dados, geralmente instalado em outro servidor

- **Intranet**
Você pode criar um site que só é acessado dentro da sua rede, ele não se conecta a internet

- **DNS**
É um servidor que tem uma lista de nomes e IP, que seria basicamente um RG da máquina. Ele serve para redirecionar um nome para um IP específico.

**Hospedagem de sites**
Nesse caso vamos contratar um servidor. Quando temos um conexão segura ela teria um HTTPS no endereço do site, o que significa que de ponta a ponta essa informação é criptografada e esse certificado que vai embaralhar toda a informação.

Depois de você registrar e registrou o DNS você precisa subir seu site para o servidor. Por isso temos a conexão FTP (File Transfer Protocol), ela não uma conexão para acessar uma página web e sim para enviar e receber arquivos. 

*Ex: FileZilla*

**Lógica da Programação**

Conjunto de instruções e regras usadas para gerar programas (software)

**Server-side**

Essa parte é que vai cuidar da parte da lógica e processamento

Ex: JavaScript, Php, Ruby. Java, C#

Cada uma dessas tem uma sintaxe própria
Prefira aquela em que a comunidade é mais engajada
Experimente!

**Client-side**

Lado do usuário final. O navegador roda Html, CSS, JavaScript

Ex: JavaScript

O navegador é um programa de computador que é instalado na máquina do cliente para ele usar. Por baixo dele tem um mecanismo de leitura d interpretação de JavaScript (V8), com isso eles criaram o NodeJs que é uma programa que  dar o V8 por baixo e esse node você instala no servidor.

Então ele vai rodar tanto no lado do servidor quanto cliente