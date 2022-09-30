# Path to become a FullStack Dev

Conceitos base

- Clean Architecture e Clean Code
- DRY
- Solid
- GIT
- Git Flow
- Scrum
- Database
  - SQL
  - Relational
  - Non-relational
- YAML
- JSON
- HTTP Protocol
- Docker
  - Container
  - Image
  - Deploy
  - Database
    - postgres
    - mysql_client
    - mongo_dart
- API
  - Rest
  - Restfull

Dart

- Tipos de dados primitivos
  - Int, Float, Num
  - String
  - Dynamic
  - Dicionarios
    - Map/Dict {Chave}
    - Anatomia: Map nome = { corpo }
    - Pode ter tipagem dupla: Map<Type, Type>
    - Procura por nome da chave: nome[’chave’]
    - Pode ser transformado em lista com nome.keys.toList() para acesso via index
  - List [colchete]
    - Pode ser tipado: List<Type> nome = []
  - Enum
- Tipos de variáveis
  - Final = Valor é atribuído apenas uma vez, o tipo do dado é inferido automaticamente
  - Var = Valor é atribuído pode ser alterado desde que seja do mesmo tipo, o tipo do dado é inferido automaticamente
    - Lazy keyword = A variável só é criada quando necessário
  - Dynamic = Valor é atribuído pode ser alterado para qualquer tipo, o tipo do dado é inferido automaticamente. Comumente utilizado para trabalhar com Dicionários
- Init - deinit
- Funções
  - Anatomia
    - Retorno Nome (Parametros) { Corpo }
  - Posicional
  - Nomeada
  - Tipos de retorno
- Classes
  - Características:
    - Variáveis sao chamadas de propriedades
  - Heranca
    - Keyword: Extends
  - Implementação (interface/protocolo)
    - Keyword: Implements
  - Injeção de dependencia
  - Extensões
- Map/Reduce
- Keywords específicas

Back End: Dart Shelf

- Rotas
  - shelf_modular
  - shelf_router
- Injeção de dependência
  - shelf-modular
  - get_it
- JWT
  - jose
  - dart_jsonwebtoken
- WebSocket (real time)
  - shelf-web-socket
- CI/CD
- Documentação
  - shelf-swagger-ui

Front End: Flutter

- State
- Widget types
- Flutter Three
- Design Pattern
- Gerenciamento de estado
- Testes unitários
- Play Store e App Center
