# CFD

Cumulative Flow Diagram 

![image](https://user-images.githubusercontent.com/52088444/228836970-11c532aa-70fb-483b-ac03-769cd16f374f.png)

A distancia horizontal mostra o lead time do item.
A distancia vertical mostra o WIP working Progress, quantos itens tem no meu board

O cfd mostra quantos itens estamos entregando.
O backlog precisa crescer de forma saudável, ou seja lead times grandes são ruins para o projeto.

## Métricas 

Througput
O Throughput corresponde ao que uma empresa consegue entregar para o cliente em um determinado período de tempo. Isso vale tanto para produtos
quanto para serviços. 

Essa métrica indica o rendimento do negócio durante o processo de produção e desenvolvimento

 throughput ou vazão média é a quantidade de entregas que o seu time consegue realizar ao final de uma sprint ou um período de tempo.
 
 A sua vazão de tempo pode ser medida de acordo com a duração da sua sprint ou iteração. Podendo ela ser semanal, quinzenal ou mensal. É interessante notar que conforme a quantidade de projetos que o seu time for entregando, mais preciso será o seu cálculo de vazão. Isso acontece porque esses dados nos permitem 
 responder algumas questões que podem aparecer no início de um projeto. Por exemplo:
 
 Em um projeto com 16 demandas, quanto tempo eu levo para finalizá-lo?
Quantas demandas o meu time entrega por sprint?
Como anda o ritmo de entregas do meu time? Conseguimos melhorar a quantidade de entregas sem influenciar na qualidade do trabalho?
Entre outras perguntas que podem surgir durante o início de um projeto ou ao incluir uma história na sprint.

## QUAL A IMPORTÂNCIA DO THROUGHPUT PARA O GERENCIAMENTO DE FLUXO DE PROJETOS?
A vazão de entregas possui um papel fundamental na hora de se estabelecer o gerenciamento do fluxo de trabalho. É com ela que se responde duas grandes dúvidas que são: quando a tarefa será 
entregue e quantas tarefas poderão ser entregues na data determinada.

Aliando o throughput às métricas de tempo de ciclo e o WIP (work in Progress) no seu fluxo do seu Kanban, é possível dizer com clareza quanto tempo os nossos 
itens de trabalho gastam em produção.

Com ele, conseguimos ver também outros pontos importantes do gerenciamento de fluxo de projetos, como a produtividade, a confiabilidade e a eficiência do processo de produção, além de conseguir ver onde estão 
os gargalos no seu fluxo de trabalho e onde se perde mais tempo.

## OK, MAS COMO EU ESTIMO O TEMPO TOTAL DA DEMANDA PARA O MEU CLIENTE?

Com um processo de throughput implantado e conseguindo os números das métricas de tempo de ciclo e do WIP, conseguimos calcular o Lead Time. Ou seja, ele é o 
tempo que o projeto demora para atravessar o quadro do Kanban. A contagem inicia-se quando a tarefa é colocada no quadro e ela é finalizada quando é movida 
para a fase “done”.

## MOTIVOS QUE PODEM DIMINUIR O THROUGHOUT DE UMA EQUIPE

Compreender o que afeta o ritmo de nossas entregas é fundamental para conseguir alterar em pouco tempo os impedimentos que fizeram com que nosso throughput diminuísse e realizar as alterações necessárias para retomar o ritmo de entrega anterior e, aumentar esse número.

Alguns motivos que podem diminuir isso são:

Não respeitar o limite de WIP;
Iterações ou sprints muito longas;
Muita mudança de escopo da iteração;
Alguma falha no processo pré-definido;

Diagrama de Fluxo Cumulativo (CFD)
O Diagrama de Fluxo Cumulativo fornece informações e dados do fluxo de valor por meio de um gráfico de área. O CFD pode ser construído manualmente, onde os colaboradores do projeto registram os dados ou de forma automática por meio de softwares. 

Pelo diagrama é possível calcular três principais métricas:

• Lead Time: tempo médio em que os itens ficam dentro do fluxo, incluindo tempo de espera.

• Throughput: taxa média de vazão, a quantidade média de entregas.

• WIP (work in progress): trabalho em progresso, a quantidade de itens abertos.

Essas métricas são as variáveis do que chamamos de “Lei de Little”, uma lei criada pelo Dr. John Little na década de 60.

A Lei de Little é representada por: Lead Time = WIP / Throughput

![image](https://user-images.githubusercontent.com/52088444/228841459-e07a6215-d66b-495d-b88b-d4645ffed31e.png)

CUMULATIVE FLOW DIAGRAM
Um diagrama de fluxo cumulativo (CFD) é um gráfico de áreas que mostra os vários
status dos itens de trabalho para um aplicativo, versão ou sprint. O eixo x horizontal em
um CFD indica tempo e o eixo y vertical indica cartões (problemas). Cada área colorida
do gráfico equivale a um status de fluxo de trabalho (ou seja, uma coluna no seu
quadro).

O CFD pode ser útil para identificar gargalos. Se seu gráfico contiver uma área que está
aumentando verticalmente ao longo do tempo, a coluna que equivale à área de
aumento geralmente será um gargalo.

Todo o diagrama deve parecer suave da esquerda para a direita. Se houver alguma
lacuna ou bolha em qualquer cor, há gargalos e escassez. Então, procure maneiras de
suavizar as faixas de cores no gráfico.

![image](https://user-images.githubusercontent.com/52088444/228842669-a04ac063-139b-44df-8194-996029387cf4.png)
No exemplo acima, podemos destacar 2 momentos de gargalos. O primeiro, de 7 a 15 de
Maio, temos um acúmulo de issues paradas em TO DO (Roxo) e poucos itens em IN
PROGRESS (Vermelho). A partir da identificação de um gargalo, podemos realizar uma
análise no fluxo e entender quais são os fatores que levaram a isso e melhorarmos o
nosso processo. O segundo momento é a partir do dia 17 de Maio, onde o Backlog
cresceu muito, completamente fora de um padrão saudável para o time. O ideal é
conseguirmos evoluir o fluxo para algo mais linear como o exemplo abaixo:


![image](https://user-images.githubusercontent.com/52088444/228843083-805fa01f-f74a-421a-a7e5-9115ba873336.png)

## Visualizando o throughput 

![image](https://user-images.githubusercontent.com/52088444/228851060-eb72fba1-eeea-4593-90cd-8f8031f16426.png)
Reto = 0
Linhas quase sem diagonal, quer dizer que não tive entregas

![image](https://user-images.githubusercontent.com/52088444/228851720-b416d87d-f2e4-4d3f-97e6-8df23c1d93c3.png)
Baixo
linhas com poucas inclinações baixo volume de entrega

![image](https://user-images.githubusercontent.com/52088444/228852116-f153ff66-8830-47ff-89cf-4e0c4b77f8dc.png)
Alto
inclinação muito alta , alto volume de entrega

![image](https://user-images.githubusercontent.com/52088444/228852503-45965de8-8ffc-43a8-a55a-e0f4302aa8c0.png)
Nunca
Pelo o cfd ser cumulativo ele nunca será dessa forma pois as histórias vão sempre somando e nunca diminuindo.


Linha horizontal tempo
Linha vertical quantidade de itens

- Lead time conta do dia da criação até a entrega.
- cicle tyme tempo de desenvolvimento

## Cascata

![image](https://user-images.githubusercontent.com/52088444/228856024-9dd50846-486b-4638-9194-ddcb343577c6.png)
Uma fase só comçea após a outra ser concluída.
pode ser um gargalo.

## Observações

- Quando uma fase fica sem tasks/histórias ela não é exibida no cfd
- quando uma das cores deixa de aparecer no gráfico quer dizer que não foi feito a etapa


![image](https://user-images.githubusercontent.com/52088444/228857953-aeb5bc4c-0429-4b76-b910-386489c0ec0e.png)

Mesmo controle de wip, isso demonstra o CFD perfeito, baleia feliz, todas as faixas representadas, não ter linhas retas, ou seja maior eficiencia.

## CFD de scrum 
![image](https://user-images.githubusercontent.com/52088444/228858517-1cfb000c-da46-4349-a0df-e87a12f75b16.png)
é visivel as Sprints, é mais escalado.






























