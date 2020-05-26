# Imagem Docker para o PHP 5.2
Imagem Docker para projetos legados que utilizam o PHP 5.2

   -   Ubuntu 12.04
    -  Apache
    -  PHP 5.2.17
    -  Zend Optimizer

## Iniciar Container
Para iniciar o container, basta utilizar o seguinte comando:

    docker run -d -p 8000:80 -v /endereço/para/projeto:/project domingosjunior87/php5.2.17

Para acessar pelo navegador, é só acessar:

    http://localhost:8000
