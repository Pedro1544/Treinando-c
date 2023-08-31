# Aprendendo  Linguagem C

## Variaveis
Nesse Repositorio atual, estou treinando os tipos primitivos de variaveis:

<!DOCTYPE html>
<!--Tabela dos tipos de variaveis C em html -->
<html>
<head>
</head>
<body>

<table>
  <tr>
    <th>Tipo</th>
    <th>Descrição</th>
    <th>Exemplo</th>
  </tr>
  <tr>
    <td>int</td>
    <td>Números inteiros</td>
    <td>int idade = 25;</td>
  </tr>
  <tr>
    <td>float</td>
    <td>Números de ponto flutuante (precisão simples)</td>
    <td>float altura = 1.75;</td>
  </tr>
  <tr>
    <td>double</td>
    <td>Números de ponto flutuante (precisão dupla)</td>
    <td>double salario = 50000.75;</td>
  </tr>
  <tr>
    <td>char</td>
    <td>Caractere individual</td>
    <td>char letra = 'A';</td>
  </tr>
  </tr>
</table>

### Imprimindo as variaveis :
Para imprimir elas, para que apareçam no seu terminal, você usa o comando printf no seu code. Por Exemploo:
```c
printf("idade: %d\n", idade);
```
Basicamente aconteceu que para  que essa declaração da variavel funcione, você coloca %d, que o TIPOK que declara  o tipo  de dado correspondente.

<!DOCTYPE html>
<html>
<head>
</head>
<body>
<table>
  <tr>
    <th>Tipo de Dado</th>
    <th>Porcentagem</th>
    <th>Descrição</th>
  </tr>
  <tr>
    <td>Inteiro</td>
    <td>%d</td>
    <td>Números inteiros</td>
  </tr>
  <tr>
    <td>Ponto Flutuante</td>
    <td>%f</td>
    <td>Números de ponto flutuante (precisão simples)</td>
  </tr>
  <tr>
    <td>Ponto Flutuante Duplo</td>
    <td>%lf</td>
    <td>Números de ponto flutuante (precisão dupla)</td>
  </tr>
  <tr>
    <td>Caractere</td>
    <td>%c</td>
    <td>Caractere individual</td>
  </tr>
</table>

</body>
</html>

### Exemplo:
```c
 #include <stdio.h>

int main() {
    // Declaracoes de variaveis
    int idade = 26;
    float valorDoPgto = 12.42;
    double velParticular = 2.9258756;
    char tipoHabMotor = 'A';

    // instrucoes
    printf("idade: %d\n", idade);
    printf("Valor do pagamento: %f \n", valorDoPgto);
    printf("Velocidade da particula: %lf \n", velParticular);
    printf("Tipo de habilitação: %c", tipoHabMotor);
    return 0;
}

``````
