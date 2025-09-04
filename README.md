Este projeto implementa o cálculo de fatorial de um número inteiro não negativo utilizando a classe BigInteger do Java, permitindo trabalhar com números muito grandes sem risco de overflow.

Funcionalidades

Calcula o fatorial de qualquer número inteiro não negativo.

Suporte a valores grandes com BigInteger.

Entrada do usuário via Scanner.

Código limpo e fácil de entender.

Tecnologias

Linguagem: Java 17+

Biblioteca: java.math.BigInteger

Como Executar

Clone o repositório:

git clone https://github.com/SEU-USUARIO/NOME-REPOSITORIO.git
cd NOME-REPOSITORIO


Compile o código:

javac Fatorial.java


Execute o programa:

java Fatorial

Exemplos de Uso
Exemplo 1:

Entrada:

5


Saída:

120

Exemplo 2:

Entrada:

100


Saída:

93326215443944152681699238856266700490715968264381621468592963895217599993229915608941463976156518286253697920827223758251185210916864000000000000000000000000

Observações

O fatorial cresce muito rápido, então mesmo com BigInteger, números muito grandes podem levar alguns segundos para calcular.
