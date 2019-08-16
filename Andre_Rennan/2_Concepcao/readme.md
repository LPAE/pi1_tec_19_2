CURSO: Eletrônica Industrial

TURMA: PIN20303 - Projeto integrador 1

Professor: Luis Carlos Martinhago Schlichting e Luiz Alberto de Azevedo

Aluno: André Luiz e Rennan Gonçalves da Silva

# Concepção do projeto - Theremin 

Aqui apresentaremos a definição e concepção de cada bloco a ser usado no desenvolvimento do theremin e diagrama de bloco conceitual do projeto. A seguir a definição dos blocos:

- Oscilador fixo de referência: oscilador com ajuste na frequência de oscilação através de um potenciômetro;
    - Entradas: Alimentação de tensão DC; Potenciômetro.
    - Saída: Senoide (referência). 
- Circuito oscilador para controle de frequência: é um circuito oscilador sensível a uma capacitância gerada pela antena e a mão do operador;
    - Entradas: Alimentação de tensão DC; Capacitância gerada pela antena e a mão do operador.
    - Saída: Senoide (tom). 
- Circuito oscilador para controle de amplitude: é um circuito semelhante ao anterior, mas que possui um potenciômetro para ajuste da frequência de oscilação;
    - Entradas: Alimentação de tensão DC; Potenciômetro; Capacitância gerada pela antena e a mão do operador.
    - Saída: Senoide (volume). 
- Mixer: Tem como função misturar sinal de dois ou mais blocos; 
    - Entradas: Alimentação de tensão DC; Senoide (referência e tom);
    - Saída: Senoide composta. 
- Amplificador controlado por Tensão: é um amplificador que possui seu ganho alterado quando aplicado diferentes tensões DC;
    - Entradas: Alimentação de tensão DC; Senoide composta; Sinal DC para controle de amplificação;
    - Saída: Senoide audível.
- Estágio de amplificação: Amplificador de potência diretamente para a carga;
    - Entradas: Alimentação de tensão DC; Som audível.
    - Saída: Som audível para carga;
- Fonte interna: Alimentação de todos os blocos apresentados anteriormente;
    -  Entradas: Tensão da rede (tomada); Chave de liga/desliga.
    -  Saída: LED de circuito ligado; alimentação DC pro circuito.
-  Circuito ressonante para volume: um nível de de tensão DC variável com a frequência de entrada.
    -  Entrada: Senoide (volume).
    -  Saída: Sinal DC para controle de amplificação.
    • Gabinete: destinado a alojar o produto eletroeletrônico;

![blocotheremin](IMG/blocotheremin.jpg)