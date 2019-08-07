# SUMÁRIO
   
1. INTRODUÇÃO
2. CONCEPÇÃO
3. DESENHO
4. IMPLEMENTAÇÃO
5. OPERAÇÃO
6. REFERÊNCIAS


# 1. INTRODUÇÃO
O THEREMIN é um instrumento musical inventado  por Lev Sergeivitch Termen que após a guerra trocou seu nome para Leon Theremin. 
Provavelmente um dos primeiros -senão o primeiro – instrumento musical eletrônico do mundo foi inventado em 1919.

Para tocar o THEREMIN não é necessário encostar no instrumento, nele existem 2 antenas uma responsável pelo ajuste do volume e a outra pelo ajuste da tonalidade. Para utilizar o instrumento basta que o indivíduo aproxime ou afaste as mãos dessas antenas.


![theremin](IMG/theremin.jfif)

para tocar o instrumento, geralmente, a mão direita controla frequência do som (tonalidade) enquanto que a esquerda controla a amplitude do som (volume). Movimentos rápidos com a mão direita próximos à antena vertical, que controla a frequência, produzem efeitos de vibrato. Movimentos rápidos com a mão esquerda na antena circular, que controla o volume, produzem efeitos de trêmolo. 



# CONCEPÇÃO
A antena de tonalidade o conectada a um circuito oscilador, que tem sua frequência de oscilação alterada conforme o campo elétrico formado entre a mão a antena.

O circuito oscilador fixo, conforme o próprio nome evidencia, trata  de um circuito oscilador referência.

O Mixer é responsável por pegar as frequências do Circuito oscilador fixo e do circuito oscilador variável e fazer a diferença entre essas frequências.

Circuito oscilador de volume é responsável por ajustar o volume conforme a aproximação ou afastamento da mão a antena do volume.

Amplificador de áudio é responsável por amplificar os sinais produzidos para a reprodução disso em um alto falante. 

