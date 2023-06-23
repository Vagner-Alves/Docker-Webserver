# Docker-Webserver
Container de Aplicação Web, utilizando apache httpd + docker compose. 

Neste container está armazenada um front-end de um site que serviu como apresentação de um projeto de faculdade , na disciplina de empreendedorismo. Program.me é o protótipo de uma plataforma onde será possível estudar as mais variadas linguagens de programação através de quizes e mini jogos interativos.

## instrução de instalação

Baixar os arquivos desse repositório utilizando git clone , em uma pasta de sua escolha dentro de um servidor , nesse caso foi utilizando  Ubuntu 22.04.2 LTS.

usar comandos ( na mesma pasta onde estão os arquivos)

``` apt install docker-compose ```

``` docker-compose up -d```

esperar o processo de criação do container , isso pode levar alguns  minutos dependendo de sua conexão com a internet.
Após terminar o processo verificar se está tudo funcionando corretamente.

``` docker container ls ```

![Captura de tela 2023-06-23 201216](https://github.com/Vagner-Alves/Docker-Webserver/assets/58148520/ade2a209-dbb8-4298-97fc-dfc0a846391a)

em seguida verificar o IP de sua maquína utilizando o comando
``` ip a ``` copiar e colar o endereço IP ( Exemplo 192.168.0.121)  em uma aba do seu navegador web de preferencia , seja em um computador ou smartphone.

## Resultado
Se todas as instruções foram seguidas de forma correta será possivel ver a seguinte pagína no seu navegador.

![Captura de tela 2023-06-23 201918](https://github.com/Vagner-Alves/Docker-Webserver/assets/58148520/f58d65f6-299b-4776-855d-ddbb802bc771)

![Captura de tela 2023-06-23 201950](https://github.com/Vagner-Alves/Docker-Webserver/assets/58148520/84595a57-de14-4879-b243-0266205033fd)

![Captura de tela 2023-06-23 202007](https://github.com/Vagner-Alves/Docker-Webserver/assets/58148520/e97d3e47-c5c0-4eb3-8f66-3e6fc6f59849)

![Captura de tela 2023-06-23 202153](https://github.com/Vagner-Alves/Docker-Webserver/assets/58148520/41644a65-dc93-4b46-ad3b-b40fa8ebaea9)

Esse website foi criado utilizando templates disponíveis no "https://teleporthq.io/"
