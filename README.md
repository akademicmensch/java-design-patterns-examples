# java-design-patterns-examples
Repositorio com exemplos dos padrões da Gang of Four utilizando a linguagem Java


## Creation
### Singleton
Garantir que uma determinada classe tenha uma, e somente uma instância, matendo um ponto gobal de acesso para a mesma.
Geralmente o construtor é privado deixando ao desenvolvedor acesso ao método getInstance para obter uma unica instancia do objeto criado quando a aplicacao é inicializada.

### Factory
Definir uma interface para criar um objeto, mas deixar subclasses decidirem que classe instanciar.
Cria uma instância de várias classes derivadas.
Passagem -> abstrata
PassagemOnibusInterstadual e PassagemOnibusUrbano -> concretas estendendo de Passagem.
Empresa e EmpresaOnibusInterestadual - Fabricas concretas.
- Uma fabrica para cada tipo de produto.
