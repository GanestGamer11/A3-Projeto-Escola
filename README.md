# A3-Projeto-Escola
Esse é um projeto realizado como atividade na minha disciplina de Programação orientada a serviços (2023)

## Como usar
Para executar essa aplicação/api você precisa conter na sua máquina o laravel instalado. Para realizar a instalação basta ler da documentação oficial do Laravel
https://laravel.com/docs/10.x/installation

Após isso, para testar uma de nossas rotas ou utilizalas, basta executar o comando: php artisan server --port=[portaEscolhida]
Dessa forma, você poderá utilizar das diversas rotas da api enquanto ela estiver sendo executada com o caminho:
localhost:[portaDefinida]/

Exemplo de uso:
localhost:8000/hello

## Rotas
Esse serviço possui atualmente duas rotas
'/' => retorna uma lista de todas as rotas disponiveis
'/hello' => retorna Hello, World!

### Notas adicionais
Esse projeto ainda está em desenvolvimento, ao final, teremos um sistema maior com uma serié de informações e funções que podem ser utilizadas
