# VA2 - Testes com Arquitetura em Camadas

## Objetivo
A atividade teve como objetivo compreender o funcionamento da arquitetura em camadas e identificar a responsabilidade de cada camada do sistema.

Também foi realizada uma alteração no projeto adicionando o campo telefone no cadastro de usuários.

## Alterações Realizadas
Camada de Dados:
Foi adicionada a coluna telefone na tabela do banco de dados.

Camada de Domínio:
Foi adicionado o atributo telefone na entidade Usuario, incluindo validação do número.

Camada de Repositório:
As operações de banco de dados foram atualizadas para salvar e buscar o telefone.

Camada de Serviço:
Os métodos de criação e atualização de usuário passaram a trabalhar com o campo telefone.

Camada de Apresentação:
As rotas da API foram atualizadas para receber e retornar o telefone nas requisições e respostas.

## Tecnologias Utilizadas
Python
Flask
SQLite
VSCode

## Execução do Projeto
Instalar dependências:
pip install flask

Executar aplicação:
python app.py

## Resultado
A aplicação foi executada com sucesso e as alterações foram implementadas corretamente em todas as camadas da arquitetura.