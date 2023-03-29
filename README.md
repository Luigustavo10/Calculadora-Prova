# Calculadora

A classe `Calculadora` é uma classe simples que contém métodos para realizar operações matemáticas básicas, como soma, subtração, multiplicação, divisão, média e mediana, bem como para calcular derivadas e integrais.

## Tecnologia Utilizada

A linguagem de programação utilizada é o C#, e o projeto foi desenvolvido usando a versão 7.0 do .NET. Além disso, foram utilizados testes unitários com o framework xUnit na versão 2.4.2.


### Cenários Esperados

> Aqui estão alguns cenários esperados que você pode testar para cada método da classe Calculadora:

    Soma()
        Somando dois números positivos
        Somando um número positivo e um número negativo
        Somando dois números negativos

    Subtracao()
        Subtraindo dois números positivos
        Subtraindo um número positivo e um número negativo
        Subtraindo dois números negativos

    Multiplicacao()
        Multiplicando dois números positivos
        Multiplicando um número positivo e um número negativo
        Multiplicando dois números negativos

    Divisao()
        Dividindo dois números positivos
        Dividindo um número positivo e um número negativo
        Dividindo dois números negativos
        Dividindo por zero

    Media()
        Calculando a média de dois números positivos
        Calculando a média de um número positivo e um número negativo
        Calculando a média de três números reais

    Mediana()
        Calculando a mediana de um conjunto ímpar de números

### Cenários Não Esperados

> Aqui estão alguns cenários não esperados que você pode testar para cada método da classe Calculadora:

    Soma()
        Somando dois números que resultam em um valor maior que o tipo de dados permite
        Somando dois números em que um deles é NaN (Not a Number)

    Subtracao()
        Subtraindo dois números que resultam em um valor menor que o tipo de dados permite
        Subtraindo dois números em que um deles é NaN (Not a Number)

    Multiplicacao()
        Multiplicando dois números que resultam em um valor maior que o tipo de dados permite
        Multiplicando dois números em que um deles é NaN (Not a Number)

    Divisao()
        Dividindo dois números em que um deles é NaN (Not a Number)

    Media()
        Calculando a média sem argumentos

    Mediana()
        Calculando a mediana de um conjunto vazio de números

Lembre-se de que é importante testar a classe com vários valores de entrada e cenários diferentes para garantir que ela esteja funcionando corretamente.