# Biblioteca

## Exercícios

#### As orientações do(s) exercício(s) anteriores seguem.
#### Não devem ser usados métodos auxiliares na resolução dos exercícios a não ser que seja expressamente solicitado.

1. O governo federal decidiu criar dados gerados de pessoas fictícias para criar cenários de teste para suas aplicações reais a fim de aumentar a confiabilidade dos seus sistemas e prevenir o aparecimento de bugs antes do lançamento da feature. Para isso, foi contratada a empresa Dois Papafigos S.A. que terá como missão desenvolver uma biblioteca para uso geral no governo federal e esta biblioteca terá as seguintes funcionalidades:
  - Gerador de nomes `def gerar_nome(file: str) -> str `
  - Gerador de nomes em lote `def gerar_nome_lote(file: str) -> List[str]`.
  - Gerador de CPF `def gerar_cpf() -> str`
  - Gerador de endereços `def gerar_endereco(cep: str) -> dict`
  - Gerador de idade `def gerar_idade() -> int`
  - Gerador de sexo `def gerar_sexo() -> str`
  - Validar idade `def validar_idade(idade: int) -> bool`
  - Validar pessoa `def validar_pessoa(pessoa: dict) -> bool`
  - Gerar pessoa `def gerar_pessoa() -> dict`
  - Gerar pessoas em lote `def gerar_pessoa_lote(quantidade_pessoas: int) -> List[dict]`

Obs: No gerador de idade, deve se utilizar valores entre 1 e 99. 
No gerador de nomes, será lido um arquivo de texto de nomes e sobrenomes e deve ser escolhido aleatoriamente se a pessoa terá nome composto e 1 ou 2 sobrenomes.
O gerador de endereço irá ter parte do algoritmo já pronto.
Antes de gerar a pessoa seja uma apenas ou em lote, deverá ser possível (validar) verificar se a pessoa pode ser criada.
Podem ser usadas outras bibliotecas/métodos para apoio, porém é vedado o uso de outras bibliotecas que GEREM PESSOAS.