# Desafios-Codigo-IntermediariosJs-Philips-Developer
> 1 / 3 - Idade em Dias

Desafio
Você terá o desafio de ler um valor inteiro correspondente à idade de uma pessoa em dias e informe-a em anos, meses e dias

Obs.: apenas para facilitar o cálculo, considere todo ano com 365 dias e todo mês com 30 dias. Nos casos de teste nunca haverá uma situação que permite 12 meses e alguns dias, como 360, 363 ou 364. 

Entrada
O arquivo de entrada contém um valor inteiro.

Saída
Imprima a saída conforme exemplo fornecido.

| Exemplo de Entrada | Exemplo de Saída |
| --- | --- |
| 400 | 1 anos(s) |
|  | 1 mes(es) |
|  | 5 dias(s) |
| * | * |
| 800 | 2 anos(s) |
|  | 2 mes(es) |
|  | 10 dias(s) |
| * | * |
| 30 | 0 anos(s) |
|  | 1 mes(es) |
|  | 0 dias(s) |

> 2 / 3 - Ordenando Números Pares e Ímpares

Desafio
Crie um programa onde você receberá valores inteiros não negativos como entrada.

Ordene estes valores de acordo com o seguinte critério:

Primeiro os Pares
Depois os Ímpares
Você deve exibir os pares em ordem crescente e na sequência os ímpares em ordem decrescente.

Entrada
A primeira linha de entrada contém um único inteiro positivo N (1 < N < 10000) Este é o número de linhas de entrada que vem logo a seguir. As próximas N linhas terão, cada uma delas, um valor inteiro não negativo.

Saída
Exiba todos os valores lidos na entrada segundo a ordem apresentada acima. Cada número deve ser impresso em uma linha, conforme exemplo de saída abaixo.

| Exemplo de Entrada | Exemplo de Saída |
| --- | --- |
| 10 | 4 |
| 4 | 32 |
| 32 |34 |
| 34 | 98 |
| 543 | 654 |
| 3456 | 3456 |
| 654 | 6789 |
| 567 | 567 |
| 87 | 543 |
| 6789 | 87 |
| 98 |  |


> 3 / 3 - Votação para Bobo da Corte
Desafio
O Império dos Artificialistas é governado por um generoso Monarca. A personalizada do Monarca é conhecida por todo o mundo, principalmente por sua forma como valoriza o bom humor de seu povo, que tem o direito a diversidade cultura. Um dos destaques fica a cargo do bobo da corte, eleito anualmente em um concurso internacional.

O jovem Rafael é um comediante promissor, que sonha em se tornar o bobo da corte nesse grande concurso. Para isso, ele vem se preparando com muita dedicação há vários meses. Chegada a época do concurso do bobo da corte, um total de N candidatos se inscreveram, e como Rafael sabia que ser o primeiro candidato a se inscrever torna-se critério de desempate, foi o primeiro a se inscrever! O concurso dará apenas 5 minutos para cada participante e no final cada cidadão dará seu voto ao futuro bob da corte que achar melhor.

Sendo assim, após a votação, resta apenas apurar os resultados, que será realizado por urna eletrônica com N inteiros, correspondentes ao total de votos em cada candidato, ordenado pela ordem de inscrição. Sua missão é determinar se o jovem Rafael foi eleito ou não.

Entrada
A primeira linha da entrada contém um inteiro N (2 ≤ N ≤ 104). As N linhas seguintes conterão N inteiros positivos v 1 , . . . , vN , um em cada linha, correspondentes ao número de votos recebido por cada um dos candidatos, em ordem de inscrição. Sabendo-se que a população total é de 100.000 pessoas, o número total de votos não será superior a este valor.

Saída
Seu programa produzirá apenas uma linha contendo o caractere ‘S’ se o jovem Rafael foi o eleito para bobo da corte, ou o caractere ‘N’ caso contrário.

 | Exemplo de Entrada | Exemplo de Saída |
| --- | --- |
| 3 | s |
| 1000 |  |
| 1000 |  |
| 1000 |  |
| * | * |
| 5 | N |
| 1 |  |
| 2 |  |
| 3 |  |
| 4 |  |
| 5 |  |
