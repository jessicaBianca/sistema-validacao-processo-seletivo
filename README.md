# Desafio Controle de Fluxo

# Explicação do Código

### Entrada dos Parâmetros:
O programa recebe dois números inteiros via terminal usando o `Scanner`.

### Exceção Customizada:
Caso o primeiro número seja maior ou igual ao segundo, o programa lança a exceção `ParametrosInvalidosException`

### Contagem de Interações:
Se os parâmetros forem válidos, o programa calcula a diferença entre o segundo e o primeiro parâmetro. Esse valor determina a quantidade de interações (impressões no console), e um laço `for` imprime "Imprimindo o número X", onde X varia de 1 até o valor da diferença.

---

# Exemplo de Funcionamento:

**Entrada**:
```plaintext
Digite o primeiro parâmetro: 12
Digite o segundo parâmetro: 30


Saída:
Imprimindo o número 1
Imprimindo o número 2
Imprimindo o número 3
...
Imprimindo o número 18

```
**Conclusão**:
Esse código atende ao cenário proposto no exercício de Controle de Fluxo, fazendo uso de validações com exceções e utilizando o laço for para imprimir as ocorrências desejadas no console.
