# Dicionários

## Exercícios

#### As orientações do(s) exercício(s) anteriores seguem.

1. Dado o dicionário `d = {'name': 'Raphael', 'age': 31, 'city': 'Campina Grande'}` execute as seguintes operações:
  - Adicionar um novo par de chave-valor, *profession*: *estudante* ao dicionário e imprima-o atualizado.
  - Modifique o valor da chave *age* para 19 e imprima o dicionário atualizado
  - Exiba o valor associado à chave *name*.

2. Dado o dicionário `d = {'name': 'Pedro', 'age': 26, 'city': 'Campina Grande', 'profession': 'Game Developer', 'nickname': 'papafigo'}` execute as seguintes operações:
  - Remova a chave *nickname* e exiba o resultado
  - Verifique se a chave *profession* existe.

3. Escreva um programa que leia duas listas, onde a primeira é correspondente as chaves e a segunda é correspondente aos valores. Em seguida transforme estas duas listas em um dicionário e exiba na tela o resultado.
Obs: Use o construtor `dict()` nessa solução.

4. Refaça a questão anterior usando o método `update()`.

5. Dado o dicionário da questão 1, remova todos os pares de chave-valor. Para resolver essa questão, utilize uma estrutura de repetição.

6. Resolva a questão anterior usando um método auxiliar para dicionário

7. Escreva um código para mesclar dois dicionários em um novo dicionário e imprimi-lo.

8. Dada uma string, crie um dicionário onde as chaves são caracteres e os valores são suas frequências na string.

9. Dado o dicionário abaixo, imprima o valor da chave *physics*.
```
sampleDict = {
    "class": {
        "student": {
            "name": "Mike",
            "marks": {
                "physics": 70,
                "history": 80
            }
        }
    }
}
```

10. Usando o dicionário da questão anterior, altere o valor da chave *history* para 75.

11. Escreva um programa que leia o nome de cinco estudantes e armazene-os em uma lista, em seguida, dado o dicionário `d = {'profissão': 'Desenvolvedor', 'salario': 7500}` inicialize cada chave (o nome de cada estudante) com o valor do dicionário d.
Exemplo de entrada:
```
estudantes = ['Raphael', 'Sâmara', 'Pedro']
```

Saída esperada:
```
{'Raphael': {'profissão': 'Desenvolvedor', 'salario': 7500}, 'Sâmara': {'profissão': 'Desenvolvedor', 'salario': 7500}, 'Pedro': {'profissão': 'Desenvolvedor', 'salario': 7500}}
```
Obs: Pode utilizar qualquer método que auxilie na resolução da questão

12. Dado o dicionário abaixo, crie um novo dicionário apenas com as chaves *name* e *salary* e seus respectivos valores:
```
sample_dict = {
    "name": "Raphael",
    "age": 19,
    "salary": 8000,
    "city": "Campina Grande"
}
```
Obs: Pra resolver essa questão tanto pode ser usada dict comprehension quanto `.update()`

13. Dado o dicionário acima, escreva um programa para invertê-lo, ou seja, o que é chave passa a ser valor e vice versa.
