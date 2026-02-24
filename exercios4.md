INTRODUÇÃO
Neste artigo vamos falar um pouco sobre o objeto Math da linguagem JavaScript. Este objeto é utilizado para realizar operações matemáticas, sejam elas aritméticas, funções trigonométricas, funções de arredondamento e comparações. A sintaxe de utilização dos métodos deste objeto é a seguinte:

Math.método(valor)

PROPRIEDADES DO OBJETO MATH
E: Constate de Euler e a base dos logaritmos naturais (próximo de 2,118);
LN2: Logaritmo natural de 2;
LN10: Logaritmo natural de 10;
LOG2E: Logaritmo na base 2 de E;
LOG10E: Logaritmo na base 10 de E;
PI: Equivalente numérico de PI, arredondado para 3,14;
SQRTI_2: Raiz quadrada de um meio;
SQRT2: Raiz quadrada de 2.
MÉTODOS DO OBJETO MATH
ABS: Este método tem a função de retornar o valor absoluto de um número, isto significa que o retorno será sempre positivo. Caso seja informado um valor negativo à este método., ele retornará o mesmo como positivo. Por exemplo, caso utilizemos o valor -1234, ele será convertido para 1234.

Essa operação é chamada também de módulo, e pode ser calculada matematicamente como a raiz quadrada do valor elevado ao quadrado.

<html>
<head>
<title>...</title>
</head>

<body>
  <script>
    var valor1 = Math.abs (-1234);
    alert (valor1);
  </script>
</body>
</html>
Listagem 1. Exemplo de uso do método Math.abs
Resultado do método  Math.abs
Figura 1. Resultado do método Math.abs
Neste exemplo definimos a variável "valor1" como o resultado do método abs que recebeu o valor negativo -1234, em seguida solicitamos através de uma caixa de alerta a exibição do conteúdo da variável valor1 que foi convertido em número positivo.

ACOS: Este método retornará o arco cosseno (em radianos) de um número.

<html>
<head>
<title>...</title>
</head>

<body>
  <script>
    var valor1 = Math.acos (0.14);
    alert (valor1);
  </script>
</body>
</html>
Listagem 2. Método Math.Acos
Com isso obteremos o resultado da Figura 2.

 Resultado do Math.Acos
Figura 2. Resultado do Math.Acos
ASIN: Este método retorna o arco seno (em radianos) de um valor.

<html>
<head>
<title>...</title>
</head>

<body>
  <script>
    var valor1 = Math.asin (0.14);
    alert (valor1);
  </script>
</body>
</html>
Listagem 3. Método Math.asin
O resultado que obteremos é o da Figura 3.

Resultado do Math.asin
Figura 3. Resultado do Math.asin
CEIL: Este método retorna um inteiro maior ou igual a um número. O resultado deste método é equivalente ao arredondamento de um número. A lógica do arredondamento de um número é que se um número é um valor positivo como 14,6 o resultado do arredondamento será 15, quando o número for um valor negativo, como-14,6 o resultado é -14. Vejamos isso em um exemplo pratico.

<html>
<head>
<title>...</title>
</head>

<body>
  <script>
    var valor1 = Math.ceil (14.6);
    alert (valor1);
  </script>
</body>
</html>
Listagem 4. Método Math.ceil com número positivo
Desse modo será arredondado para 15.

Resultado Math.ceil com número positivo
Figura 4. Resultado Math.ceil com número positivo
<html>
<head>
<title>...</title>
</head>

<body>
  <script>
    var valor1 = Math.ceil (-14.6);
    alert (valor1);
  </script>
</body>
</html>
Listagem 5. Método Math.ceil com número negativo
Veja que utilizamos o mesmo número do exemplo anterior, só que agora em modo negativo. O arredondamento será para -14, pois o retorno do método ceil é o menor número inteiro mais próximo ao valor superiormente, ou seja, o primeiro valor inteiro maior ou igual ao número informado. No caso, -14 é maior que -14,6.

Resultado de Math.ceil com número negativo
Figura 5. Resultado de Math.ceil com número negativo
COS: Este método retornará o cosseno (em radianos) de um número.

<html>
<head>
<title>...</title>
</head>

<body>
  <script>
    var valor1 = Math.cos (0.14);
    alert (valor1);
  </script>
</body>
</html>
Listagem 6. Método Math.cos
Resultado do Math.cos
Figura 6. Resultado do Math.cos
EXP: Este método retornará o valor da constante de Euler elevada ao número informado, ou seja, E elevado ao parâmetro.

<html>
<head>
<title>...</title>
</head>

<body>
  <script>
    var valor1 = Math.exp (0.0007);
    alert (valor1);
  </script>
</body>
</html>
Listagem 7. método Math.exp
Resultado Math.exp
Figura 7. Resultado Math.exp
FLOOR: Este método retorna o maior inteiro menor ou igual a um número.

<html>
<head>
<title>...</title>
</head>

<body>
  <script>
    var valor1 = Math.floor (100.25);
    var valor2 = Math.floor (-100.25);
    alert (valor1);
    alert (valor2);
  </script>
</body>
</html>
Listagem 8. Método Math.floor
Resultado de Math.floor(100.25)
Figura 8. Resultado de Math.floor(100.25)
Resultado de Math.floor(-100.25)
Figura 9. Resultado de Math.floor(-100.25)
LOG: Este método retorna o logaritmo natural de um número (base E).

<html>
<head>
<title>...</title>
</head>

<body>
  <script>
    var valor1 = Math.log (2.2);
    alert (valor1);
  </script>
</body>
</html>
Listagem 9. Método Math.log
Resultado de Math.log
Figura 10. Resultado de Math.log
MAX: Este método retorna o maior valor entre dois números.

<html>
<head>
<title>...</title>
</head>

<body>
  <script>
    var valor1 = Math.max ( 3,9);
    alert (valor1);
  </script>
</body>
</html>
Listagem 10. Método Math.max
Resultado Math.max
Figura 11. Resultado Math.max
MIN: Este método retorna o menor valor entre dois números.

<html>
<head>
<title>...</title>
</head>

<body>
  <script>
    var valor1 = Math.min ( 3,9);
    alert (valor1);
  </script>
</body>
</html>
Listagem 11. Método Math.min
Resultado Math.min
Figura 12. Resultado Math.min
POW (base, expoente): Este método retorna a base elevada à potência do expoente. Por exemplo, 2 elevado a décima potência é 1024.

<html>
<head>
<title>...</title>
</head>

<body>
  <script>
    var valor1 = Math.pow ( 1024,2);
    alert (valor1);
  </script>
</body>
</html>
Listagem 12. Método Math.pow
Resultado Math.pow
Figura 13. Resultado Math.pow
RANDOM: Este método retorna um número aleatório entre 0 e 1 com até 15 dígitos. Este número aleatório é definido através do relógio do computador.

<html>
<head>
<title>...</title>
</head>

<body>
  <script>
    alert (Math.random ());
  </script>
</body>
</html>
Listagem 13. Método Math.random
Resultado Math.random
Figura 14. Resultado Math.random
ROUND: Com este método é possível arredondar um valor. O arredondamento segue a regra de arredondamento que vimos anteriormente.

<html>
<head>
<title>...</title>
</head>

<body>
  <script>
    var valor1 = Math.round (121.6);
    alert (valor1);
  </script>
</body>
</html>
Listagem 14. Método Math.round
Resultado de Math.round
Figura 15. Resultado de Math.round
SIN: Este método retorna o seno de um número.

<html>
<head>
<title>...</title>
</head>

<body>
  <script>
    var valor1 = Math.sin (1.4);
    alert (valor1);
  </script>
</body>
</html>
Listagem 15. Método Math.sin
Resultado de Math.sin
Figura 16. Resultado de Math.sin
SQRT: Retorna a raiz quadrada de um número.

<html>
<head>
<title>...</title>
</head>

<body>
  <script>
    var valor1 = Math.sqrt (9);
    alert (valor1);
  </script>
</body>
</html>
Listagem 16. Método Math.sqrt
Resultado de Math.sqrt
Figura 17. Resultado de Math.sqrt
TAN: Retorna a tangente de um número, que é equivalente a divisão do seno pelo cosseno deste mesmo valor.

<html>
<head>
<title>...</title>
</head>

<body>
  <script>
    var valor1 = Math.tan (1.5);
    alert (valor1);
  </script>
</body>
</html>
Listagem 17. Método Math.tan
CONCLUSÃO
Nesse artigo tivemos como objetivo conhecer brevemente os métodos do objeto Math da linguagem JavaScript. Espero que o tema tenha sido de agrado de todos os leitores.

Abraço a todos e até o próximo.
