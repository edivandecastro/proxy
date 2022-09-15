# Proxy

## Tipos de proxy
* Forward Proxy
* Reverse Proxy

### Forward Proxy
É um servidor que fica entre um cliente ou um conjunto de clientes e outro servidor ou servidores. Para ser mais especifico um Forward Proxy age em nome do cliente ou clientes. Ele representa o(s) cliente(s) em um interação com outros servidores. Isso permite omitir a identidade do(s) cliente(s) nas requisições realizadas a outro(s) servidor(es).

Um Forward Proxy pode ser utilizado para manter o anonimato de clientes ou burlar bloqueios.

### Reverse Proxy
É um servidor que fica entre um servidor ou um conjunto de servidores e os clientes. Para ser mais especifico um Reverse Proxy representa o(s) servidor(es) em uma interação com os clientes. Isso permite omitir a identidade do(s) servidor(es) nas requisições realizadas pelos clientes.

Um Reverse Proxy pode ser utilizado para filtrar e ignorar requisições que são feitas aos servidores, realizar logs e métricas de acesso, fornecer cache de arquivos como páginas html, e o seu melhor uso é para realizar balanço de carga entre os servidores.


## Implementação de Reverse Proxy

## Dependências

Ter instalado o docker em sua máquina

## Passos para executar

execute em ordem:

```
docker-compose build
```

```
docker-compose up
```
depois acesse:

http://localhost:3000/hello

nessa página é mostrado o IP do servidor de APP

e depois

http://localhost/hello

nessa página é mostrado o IP do servidor de Proxy
