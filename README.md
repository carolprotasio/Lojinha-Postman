# Lojinha-Postman

## Coleção do Postman

Esta é a coleção do Postman utilizada para testar e documentar a Lojinha-API. A coleção inclui todas as requisições HTTP necessárias para interagir com a API de maneira eficiente.
A Lojinha API foi criada por Júlio de Lima para apoiar seus alunos na aprendizagem de técnicas e ferramentas de teste de software. Esta API permite a gestão de usuários, produtos e componentes, fornecendo endpoints para adicionar, consultar, atualizar e remover esses itens.

![Postman](https://github.com/carolprotasio/Lojinha-Postman/blob/main/postman.png)

Versão
Versão: 2.0.0

# Documentação da API Lojinha

## Introdução
Este documento descreve as operações disponíveis na API da Lojinha, que permite interações com usuários e produtos através de endpoints específicos.

## Host e Base Path
 - Host: 165.227.93.41
 - Base Path: /lojinha

## Tags
* usuario: Adição, login e restauração ao estado inicial
* produto: Gestão dos produtos de um usuário
* componente: Gestão dos componentes de um determinado produto

# Resultado dos testes com o Postman

![Postman](https://github.com/carolprotasio/Lojinha-Postman/blob/main/postman-test.png)

# Especificações da API Lojinha

A documentação completa da API, incluindo todos os endpoints, parâmetros e respostas, pode ser encontrada no arquivo swagger.yml incluído no projeto. Utilize esse arquivo para obter detalhes completos sobre como interagir com a API.

# Testando com Postman
Você pode utilizar o Postman para testar os endpoints da Lojinha API. Siga os passos abaixo para realizar os testes:

## Importe o arquivo YML:
- Abra o Postman.
- Clique em Importar.
- Selecione o arquivo https://github.com/carolprotasio/Lojinha-Postman/blob/main/Lojinha%20API.postman_collection.json do projeto.
- Configuração do Token de Autenticação:

## A maioria dos endpoints requer um token de autenticação.
- Obtenha o token realizando uma solicitação POST para o endpoint /v2/login com suas credenciais de usuário.
- Copie o token retornado e adicione-o no cabeçalho de suas solicitações como Authorization: Bearer {seu_token}.
- Realizando Solicitações:
  * Utilize os endpoints importados para realizar as solicitações desejadas (GET, POST, PUT, DELETE).
  * Preencha os parâmetros necessários conforme descrito na documentação importada.

## Swagger da Lojinha API
A documentação da API foi elaborada utilizando o Swagger, uma ferramenta amplamente reconhecida para documentação de APIs. O Swagger oferece uma interface interativa que permite visualizar e testar as operações da API diretamente no navegador.

![Postman](https://github.com/carolprotasio/Lojinha-Postman/blob/main/swagger.png)

# Conclusão do Projeto
Este projeto foi desenvolvido como parte da Mentoria com Julio de Lima, proporcionando uma experiência de testes com o Postman. Os testes realizados abrangeram diversas funcionalidades da plataforma Lojinha-API, incluindo validações de usuários, produtos e componentes.
Este projeto contribuiu significativamente para a melhoria das habilidades de testes com o Postman e os estudos sobre a Garantia da Qualidade do Software.
