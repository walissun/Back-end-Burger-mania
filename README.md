# Burger Mania - Backend

## Funcionalidades

- **API RESTful**: Fornece endpoints para gerenciar pedidos, cardápios e categorias de hambúrgueres.
- **Documentação com Swagger**: Integração com Swagger para documentação interativa da API.
- **Autenticação e Autorização**: Implementa segurança para proteger os endpoints sensíveis.
- **Conexão com Banco de Dados**: Utiliza [Nome do Banco de Dados] para persistência de dados.
- **Validação de Dados**: Garantia de integridade e consistência dos dados recebidos e enviados.

## Organização do Projeto

- **src/controllers**: Contém os controladores responsáveis pela lógica das rotas.
- **src/routes**: Define as rotas da API e suas respectivas associações com os controladores.
- **src/models**: Modelos de dados que representam as entidades do sistema.
- **src/middleware**: Middlewares para autenticação, logging, tratamento de erros, etc.
- **src/config**: Configurações do projeto, como variáveis de ambiente e configurações de banco de dados.
- **docs**: Documentação da API com Swagger.

## Requisitos do Projeto

- **Endpoints de Pedido**: Permite criar, ler, atualizar e deletar pedidos.
- **Endpoints de Cardápio**:
  - Listar categorias de hambúrgueres.
  - Gerenciar itens disponíveis em cada categoria.
- **Autenticação de Usuários**: Registro e login de usuários para acesso seguro.

## Configuração Inicial

1. **Clone o repositório**:
   
   ```bash
   git clone https://github.com/seu-usuario/Back-end-Burger-mania.git
   cd burger-mania-backend
2. **Front-End repositório**:
   ```bash
   https://github.com/walissun/Burger-Mania-Desafio-Final
