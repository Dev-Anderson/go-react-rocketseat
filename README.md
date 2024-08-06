# Sobre o projeto

## como rodar 
Se não tiver a imagem baixada, precisa rodar o seguinte comando

```
docker compose up 
```

Se tiver a imagem baixada, pode rodar o seguinte comando

```
docker compose start
```

## Como acessar o banco de dados
Depois de rodar o comando, basta acessar o seguinte link

```
localhost:8081
```

Logo depois vai pedir o usuário e senha por padrão está com a seguinte configuração

```
login: admin@admin.com
password: 1234
```

Essa configuração fica dentro do arquivo env

## O que precisa verificar

- Não está criado as tabelas no banco de dados

verificar se o problema não é por causa do pacote "godotenv" fazer um teste sem essa lib depois