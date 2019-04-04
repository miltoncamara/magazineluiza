# Exemplo de lSite

Projeto desenvolvido em Angular na versão 7

## Development server

Para rodar o projeto basta executar `ng serve` e abrir no navegador o endereço `http://localhost:4200/`

## Docker

Para dockerizar o projeto precisa seguida os passos `ng build --prod` para gerar o dist do projeto, em seguida executar o comando padrão para criar uma imagem docker `docker build -t 'nome da sua imagem' .` e para executar 
`docker run -d -p uma_porta:80 'nome da sua imagem'`