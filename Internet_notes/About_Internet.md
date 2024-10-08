# About Internet

Alguns conceitos importantes sobre a internet:

- **Internet**. É a rede mundial de computadores que permite a comunicação de usuários do mundo todo através de um conjunto padronizado de protocolos.
  - A **intranet** é uma rede privada que permite ao usuário interagir com pessoas da mesma organização;
- _**World Wide Web**_. Também conhecida como _web_, é um sistema que une dados dos sistemas de internet. Ou seja, internet é algo referente ao componentes físicos da rede global, enquanto a _web_ ao conjunto de dados compartilhados por esta rede. As páginas w*eb* visitadas em sites são esses dados;
- **Servidores _web_**. São servidores robustos que processam pedidos recebidos dos navegadores;
- _**Home page**_. É a primeira página recebida de um site por um servidor _web_. Uma Home Page é normalmente chamada de index.htm ou de default.htm. Os arquivos também podem possuir a extensão .html como padrão;
- **URL** (_**Universal Resource Locator**_). É o sistema de endereçamento usado pelos navegadores para localizar redes, computadores e arquivos na internet.

## Sumário

1. [Protocolos](#protocolos);
   1. [Protocolo HTTP](#protocolo-http).
2. [Referências](#referências).
   1. [Referências em artigos na _web_](#referências-em-artigos-na-web);
   2. [Referências em vídeos](#referências-em-vídeos).

## Protocolos

A internet é regida por **protocolos** para comunicação em rede. Eles determinam a comunicação entre computadores: como iniciar, como manter e como encerrar a comunicação. Alguns deles são:

- **HTTP** (**_Hyper Text Transfer Protocol_**). É o protocolo usado pelos servidores _web_ para transmitir documentos HTML pela internet;
- **FTP** (**_File Transfer Protocol_**). É outro protocolo muito utilizado para transmitir arquivos, porém sua interface gráfica não é tão agradável como do HTTP;
- **TCP** (**_Transfer Control Protocol_**). É um conjunto de protocolos para a transmissão de informação pela _web_, com função de verificar se os dados são transferidos de forma correta, na sequência apropriada e sem erros;
- **IP** (**_Internet Protocol_**). É um protocolo de endereçamento, que fornece o endereço de computadores na rede;
- **Nome de Domínio**. Um nome de domínio é um endereço único e fácil de lembrar usado para acessar sites, como "google.com" e "facebook.com". Usuários podem conectar a sites usando os nomes de domínio graças ao Domain Name System (DNS);
- **Hosting**. _Web hosting_ é um serviço _online_ que permite publicar arquivos de sites na internet;
- **DNS** (**_Domain Name System_**). O DNS está para a internet assim como a agenda telefônica para o humano. Humanos acessam informação online pelos nomes de domínio, como "nytimes.com" ou "espn.com". Navegadores _web_ interagem pelos endereços IP (Internet Protocol). O DNS traduz os nomes dos domínios ao endereço do IP para que os navegadores possam carregar os recursos da internet;
- **Navegadores _web_**. Um navegador _web_ é um software que permite um usuário acessar e mostrar páginas _web_ ou outro conteúdo online pela sua interface gráfica.

### Protocolo HTTP

HTTP é uma camada base de comunicação que usa TCP/IP que padronizou como o client e o servidor comunicam entre si. Esse protocolo segue o modelo clássico "_Client-Server_" com um cliente abrindo uma requisição de conexão, e então espera a resposta do servidor.  
HTTP é um protocolo _stateless_, isso significa que o servidor não mantém nenhum dado (_state_) entre as requisições.

## Referências

1. [roadmap.sh/frontend](https://roadmap.sh/frontend);
2. [internetfundamentals.com/](https://internetfundamentals.com/);
3. [roadmap.sh/guides/what-is-internet](https://roadmap.sh/guides/what-is-internet);
4. [app.daily.dev/tags/dns?ref=roadmapsh](https://app.daily.dev/tags/dns?ref=roadmapsh);
5. [app.daily.dev/tags/browsers?ref=roadmapsh](https://app.daily.dev/tags/browsers?ref=roadmapsh).

### Referências em artigos na _web_

1. [cs.fyi/guide/how-does-internet-work](https://cs.fyi/guide/how-does-internet-work);
2. [vox.com/2014/6/16/18076282/the-internet](https://www.vox.com/2014/6/16/18076282/the-internet);
3. [web.stanford.edu/class/msande91si/www-spr04/readings/week1/InternetWhitepaper.htm](http://web.stanford.edu/class/msande91si/www-spr04/readings/week1/InternetWhitepaper.htm);
4. [roadmap.sh/guides/what-is-internet](https://roadmap.sh/guides/what-is-internet);
5. [cs.fyi/guide/how-does-internet-work](https://cs.fyi/guide/how-does-internet-work);
6. [developer.mozilla.org/en-US/docs/Learn/Common_questions/How_does_the_Internet_work](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/How_does_the_Internet_work);
7. [cs.fyi/guide/http-in-depth](https://cs.fyi/guide/http-in-depth);
8. [cloudflare.com/en-gb/learning/ddos/glossary/hypertext-transfer-protocol-http/](https://www.cloudflare.com/en-gb/learning/ddos/glossary/hypertext-transfer-protocol-http/);
9. [howhttps.works/](https://howhttps.works/);
10. [developer.mozilla.org/en-US/docs/Web/HTTP/Overview](https://developer.mozilla.org/en-US/docs/Web/HTTP/Overview);
11. [smashingmagazine.com/2021/08/http3-core-concepts-part1/](https://www.smashingmagazine.com/2021/08/http3-core-concepts-part1/);
12. [thenewstack.io/http-3-is-now-a-standard-why-use-it-and-how-to-get-started/](https://thenewstack.io/http-3-is-now-a-standard-why-use-it-and-how-to-get-started/);
13. [developer.mozilla.org/en-US/docs/Learn/Common_questions/What_is_a_domain_name](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/What_is_a_domain_name);
14. [cloudflare.com/en-gb/learning/dns/glossary/what-is-a-domain-name/](https://www.cloudflare.com/en-gb/learning/dns/glossary/what-is-a-domain-name/);
15. [www.cloudflare.com/en-gb/learning/dns/what-is-dns/](https://www.cloudflare.com/en-gb/learning/dns/what-is-dns/);
16. [messwithdns.net/](https://messwithdns.net/);
17. [howdns.works/](https://howdns.works/);
18. [html5rocks.com/en/tutorials/internals/howbrowserswork/](https://www.html5rocks.com/en/tutorials/internals/howbrowserswork/);
19. [browserstack.com/guide/browser-rendering-engine](https://www.browserstack.com/guide/browser-rendering-engine);
20. [developer.mozilla.org/en-US/docs/Web/Performance/How_browsers_work](https://developer.mozilla.org/en-US/docs/Web/Performance/How_browsers_work).

### Referências em vídeos

1. "[How does the INTERNET work? | ICT #2](https://youtu.be/x3c1ih2NJEg)" do canal [@Lesics](https://www.youtube.com/@Lesics);
2. "[How the Internet Works in 5 Minutes](https://youtu.be/7_LPdttKXPc)" do canal [@AaronTitus](https://www.youtube.com/@AaronTitus);
3. "[How does the internet work? - Glad You Asked T1](https://youtu.be/TNQsmPf24go)" do canal [@Vox](https://www.youtube.com/@Vox);
4. "[HTTP Crash Course & Exploration](https://youtu.be/iYM2zFP3Zn0)" do canal [@TraversyMedia](https://www.youtube.com/@TraversyMedia);
5. "[What is a Domain Name? - A Beginners Guide to How Domain Names Work!](https://youtu.be/Y4cRx19nhJk)" do canal [@CreateaProWebsite](https://www.youtube.com/@CreateaProWebsite);
6. "[What Is Web Hosting? Explained](https://youtu.be/htbY9-yggB0)" do canal [@pickaweb](https://www.youtube.com/@pickaweb);
7. "[Different Types of Web Hosting Explained! | Shared Hosting vs. VPS Hosting vs. Dedicated Server](https://youtu.be/AXVZYzw8geg)" do canal [@Craylor](https://www.youtube.com/@Craylor);
8. "[Where to Host a Fullstack Project on a Budget](https://youtu.be/Kx_1NYYJS7Q)" do canal [@bawad](https://www.youtube.com/@bawad);
9. "[DNS and How does it work?](https://youtu.be/Wj0od2ag5sk)" do canal [@roadmapsh](https://www.youtube.com/@roadmapsh);
10. "[DNS Records](https://youtu.be/7lxgpKh_fRY)" do canal [@roadmapsh](https://www.youtube.com/@roadmapsh);
11. "[When to add glue records to your nameservers](https://youtu.be/e48AyJOA9W8)" do canal [@PieterExplainsTech](https://www.youtube.com/@PieterExplainsTech);
12. "[DNS Records for Newbies - How To Manage Website Records](https://youtu.be/YV5tkQYcvfg)" do canal [@OffsproutTV](https://www.youtube.com/@OffsproutTV);
13. "[How Do Web Browsers Work?](https://youtu.be/WjDrMKZWCt0)" do canal [@DaveXiang](https://www.youtube.com/@DaveXiang).
