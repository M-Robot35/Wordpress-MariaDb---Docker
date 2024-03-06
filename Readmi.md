# Projeto WordPress com Docker Compose

Este projeto utiliza Docker Compose para configurar um ambiente de desenvolvimento local para WordPress, usando MariaDB como banco de dados.

## Requisitos

Certifique-se de ter Docker e Docker Compose instalados em sua máquina.

## Configuração

1. Clone este repositório em sua máquina local:

2. Navegue até o diretório do projeto:

## Executando o projeto

    -  docker-compose up -d

    Execute o seguinte comando para iniciar o ambiente:

    O WordPress estará disponível em `http://localhost:8080`.

## Parando o projeto

Para parar o ambiente, execute:

    - docker-compose down

## Personalização

- O diretório `mariadb_vol` é usado para armazenar os dados do MariaDB.

- O diretório `wordpress_vol` é usado para armazenar os arquivos do WordPress.

Você pode personalizar esses diretórios conforme necessário, alterando o caminho no arquivo `docker-compose.yml`.

## Contribuindo

Sinta-se à vontade para enviar pull requests, sugestões ou relatar problemas.

## Licença

Este projeto está licenciado sob a [MIT License](LICENSE).
