O programa prova1.c organiza os dados do código, processa um arquivo e nele contém diversas leituras no formato: <TIMESTAMP> <ID_SENSOR> <VALOR>, o programa também trata o arquivo indicado como argumento
da linha de comando de execução do programa.
Diz os diferentes sensores presentes
Separa os dados em arquivos distintos
Em cada arquivo, ordena as leituras por timestamp, data e hora em ordem crescente.


O programa prova2.c recebe da linha de comanda o nome de um sensor e uma data e uma hora posta o programa localiza usando busca binária, e sempre achando a busca mais próxima das horas colocadas no
programa


O programa prova3.c gera um arquivo de teste gerando todas as horas minutos segundos dias meses e anos de acordo com que colocados no aplicativo, caso colocado uma informação que não existe o programa
não executará corretamente e dará erro o programa utiliza 2000 leituras aleatórias com valores numéricos.
Exemplo de execução deste código ./sensor_generator.exe 01 01 2024 00 00 00 01 01 2025 23 59 59 S1 CONJ_Z S2 BINARIO S3 CONJ_Q S4 TEXTO
