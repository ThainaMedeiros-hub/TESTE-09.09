QUESTÃO 1:
Verificador de Fibonacci: http://127.0.0.1:5500/TESTE1.html

QUESTÃO 2:
Contador de letras: http://127.0.0.1:5500/TESTE2.html

QUESTÃO 3:
Iteração	K	SOMA
1	2	2
2	3	5
3	4	9
...	...	...
11	12	78
RESPOSTA: VALOR DA VARIÁVEL SOMA 78

QUESTÃO 4:
Respostas:

a) 9 -Sequência de números ímpares consecutivos.
b) 128 - Sequência de potências de 2.
c) 49 - Sequência de quadrados perfeitos (0², 1², 2², ...).
d) 100 - Sequência de quadrados de números pares (2², 4², 6², 8²).
e) 13 - Sequência de Fibonacci (cada número é a soma dos dois anteriores).
f) Não é possível identificar uma sequência lógica.

QUSTÃO 5:

Solução:criar um cenário único para cada lâmpada, de forma que, ao retornar à sala dos interruptores, você possa identificar qual interruptor controla cada lâmpada.
    Primeira Visita:
        Ação: Ligue o primeiro interruptor e aguarde alguns minutos para que a lâmpada correspondente aqueça (se for uma lâmpada incandescente).
        Ação: Ligue o segundo interruptor e entre imediatamente na sala das lâmpadas.
        Observação:
            Lâmpada quente: Corresponde ao primeiro interruptor.
            Lâmpada fria: Corresponde ao terceiro interruptor (já que nenhum dos dois foi ligado).
            Lâmpada morna: Corresponde ao segundo interruptor (foi ligada por último e ainda não esfriou completamente).

    Segunda Visita:
        Ação: Desligue o segundo interruptor e o terceiro interruptor.
        Observação: A lâmpada que estava morna na primeira visita, agora estará fria ou morna. Se estiver fria, o segundo interruptor controla a lâmpada. Se estiver morna, o terceiro interruptor controla a lâmpada.

    Lâmpada quente na primeira visita: Primeiro interruptor.
    Lâmpada fria na primeira visita: Terceiro interruptor.
    Lâmpada morna na primeira visita: Segundo ou terceiro interruptor (definido na segunda visita).

    Criando diferenças: Ao ligar e desligar os interruptores em momentos diferentes, criamos diferenças de temperatura nas lâmpadas, permitindo a identificação.
    Eliminando possibilidades: A cada visita, eliminamos possibilidades e nos aproximamos da solução.
