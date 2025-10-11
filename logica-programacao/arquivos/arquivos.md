# Arquivos

## Exercícios

#### As orientações do(s) exercício(s) anteriores seguem.

1. Faça um programa que leia um arquivo texto contendo uma lista de endereços IP e gere um outro arquivo, contendo um relatório dos endereços IP válidos e inválidos.

Exemplo de entrada:
```
200.135.80.9
192.168.1.1
8.35.67.74
257.32.4.5
85.345.1.2
1.2.3.4
9.8.234.5
192.168.0.256
```

Exemplo de saída:
```
[Endereços válidos:]
200.135.80.9
192.168.1.1
8.35.67.74
1.2.3.4

[Endereços inválidos:]
257.32.4.5
85.345.1.2
9.8.234.5
192.168.0.256
```

2. O Apache registra tentativas de invasão nos logs de acesso (access.log) e de erros (error.log). Dependendo da configuração, ele pode capturar detalhes importantes sobre ataques comuns, como tentativas de exploração de vulnerabilidades, escaneamento de
diretórios e ataques de força bruta. Um ataque de força bruta ocorre quando um invasor tenta acessar um sistema testando
repetidamente diferentes combinações de usuário e senha, geralmente com ferramentas automatizadas. O objetivo é encontrar credenciais válidas para invadir o sistema.
Analise o arquivo “access.log” contendo os registros de ataques de força bruta detectados em janeiro desse ano em um sistema web. Segue o formado do registro:
` 223.232.77.238 - - [06/Jan/2025:16:35:11 +0000] "POST /login HTTP/1.1" 403 512 `

Onde:

| Valor         | Significado |
| ------------- | ----------- |
| 223.232.77.238 | Endereço IP do requisitante |
| - -           | Dados para autenticação do usuário |
| [06/Jan/2025:16:35:11 +0000] | Data e hora |
| "POST /login HTTP/1.1" | POST realizado em /login |
| 403           | Código HTTP (acesso negado) |
| 512           | Tamanho da resposta do servidor |

Escreva um programa para descobrir:
- Quantos IPs diferentes foram detectados.
- Qual dia houve maior número de ataques.
- Qual dia houve menor número de ataques.

Para isso, desenvolva as seguintes funções:
- def ip(registro:str) -> str:
- def dia(registro:str) -> int:
- def ips(registros:list) -> list:
- def dia_maior_ataque(registros: list) -> list:
- def dia_menor_ataque(registros: list) -> list:
