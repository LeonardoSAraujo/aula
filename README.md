# ARQUIVOS DO ERP UNINTER

Repositório da API da UNINTER ERP

## PRÉ-REQUISITOS

- Docker instalado na máquina [DOCKER](https://www.docker.com/)

- TERMINAL DE SUA PREFERÊNCIA [CMADER](https://cmder.net/)

- COMPOSER [COMPOSER](https://getcomposer.org/)

## INSTRUÇÕES DE INSTALAÇÃO
Clonagem do diretório:
```
git clone 
```
Atualização das dependências (VENDOR):
```
composer update
```
Com o DOCKER instalado, acessar a pasta raiz do projeto, vamos construir a imagem primeiro.
```
$ docker-compose build
```
Quando a compilação é feita,  podemos iniciar o contêiner com o comando abaixo:

```
$ docker-compose up -d
```

### Ambiente de Produção
Para acessar o projeto
```
http://localhost:5000/
```

Acesar ao banco de dados
```
host: localhost
user: root
pass: root
db: base
```
