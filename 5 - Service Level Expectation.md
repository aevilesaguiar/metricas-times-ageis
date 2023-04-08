# Service Level Expectation (SLE) - Expectativa de nível de serviço

*SLA (ACORDO DE TEMPO DE SERVIÇO)

O que são expectativas de nível de serviço (SLEs)?
No Kanban, os SLEs podem ser definidos como previsões de metas de tempo de ciclo para quando um determinado serviço deve ser entregue a um cliente (interno ou externo). Em outras palavras, as Expectativas de Nível de Serviço representam o tempo máximo acordado que seus itens de trabalho devem gastar em um determinado processo. A ideia é rastrear se sua equipe está cumprindo seus SLEs e melhorar continuamente com base na análise de dados de tempo de ciclo anteriores. 

Service Level Expectation (SLE) é uma expectativa de quando você espera receber esse serviço/produto.

"A Expectativa de Nível de Serviço (Service Level Expectation), prevê quanto tempo um item
deve fluir do início ao fim do fluxo de trabalho do Time Scrum. O Time Scrum utiliza esse
SLE para encontrar problemas no seu fluxo ativo, inspecionando-os e adaptando-os em
casos de queda abaixo de suas expectativas. O SLE em si, possui duas partes: um período
de dias corridos e uma probabilidade associada a esse período (e.g., 85% dos itens de
trabalho devem estar finalizados em 8 dias ou menos). O SLE deve ser baseado no cycle
time histórico do Time Scrum e, uma vez calculado, o Time Scrum deve deixá-lo
transparente. Caso não haja um histórico de cycle time, o Time Scrum deverá fazer sua
melhor estimativa e então substituí-la quando houver dados históricos suficientes para
realizar um cálculo mais apropriado do SLE."

Por definição, o SLE serve para aprimorar a previsibilidade de prazos e identificar falhas no
fluxo (completo da Sprint) de itens que estejam ultrapassando a previsão.

Vamos agora entender uma definição que tem atrapalhado o entendimento de muitos.
Quem fez KMP I e KMP II entendem que CYCLE TIME é o período em que um item se
manteve dentro de uma faixa do Kanban (se manteve em um status no Jira) e LEAD TIME é
o tempo do fluxo completo, desde a criação até ficar DONE. Vocês estão corretos.

Porém, é importante ressaltar, que o SLE considera o período completo, mas no Guide trata
como CYCLE TIME. Isso tem gerado uma série de dúvidas e para quem procura certificação
PSK, o termo correto é CYCLE TIME mesmo, pois considera o período que compõe a Sprint
e não desde o momento em que o item é criado até ficar DONE.

Então, SLE trabalha com o que muitos entendem como LEAD TIME e em minha proposta,
eu adaptei as visibilidades e considerei o CYCLE TIME de cada uma das faixas, para
conseguir uma visão de cada etapa do meu Fluxo e poder melhorá-lo.

![image](https://user-images.githubusercontent.com/52088444/229181845-8db427de-0173-4822-94d7-e4a2ec0f5289.png)

O que é?
Upstream são as etapas do fluxo de trabalho que tem o objetivo de amadurecer e validar ideias antes de aplicá-las no mundo real.

Já o downstream se refere à todas as etapas seguintes do fluxo de trabalho a partir do backlog de itens gerados no upstream.

Podemos considerar um quadro kanban end-to-end, que contempla tanto o upstream como o downstream, como algo semelhante ao exemplo abaixo.

![image](https://user-images.githubusercontent.com/52088444/229182130-08270fe0-474f-4f25-8a22-55f5db6a8e37.png)

Obs: o quadro que representa o fluxo de downstream costuma ser chamado também de delivery kanban.

Um sistema de Kanban que enxerga somente o downstream, reduz o lead time e proporciona melhoria na previsibilidade. Isto deve ser visto como um benefício interno.

A utilização de um sistema Kanban end-to-end, que considera tanto o upstream quanto o downstream, tem como objetivo promover tanto benefícios internos como externos. Além da visão do time, a ideia é priorizar a integração com o cliente e o time de design de solução para promover um fluxo sustentável.

Este fluxo só consegue ser sustentado a longo prazo quando o cliente puxa valor ao invés de empurrar solicitações.

Um fluxo estável de demandas junto de um fluxo estável de trabalho, gera um fluxo estável de entrega.


Throughput Time (entendem como leadtime) o tempo que o item demora para ser produzido;
No scrum não se usa leadtime apenas cycleTime.
WIP quantidade trabalho estou produzindo, seja simultaneamente , numa faixa
Cycle time quanto tempo um item demora numa faixa.











## Referencias

- https://medium.com/@raphaelbatagini/upstream-e-downstream-no-kanban-d0d02c56f6b6#:~:text=O%20que%20%C3%A9%3F,de%20itens%20gerados%20no%20upstream.
- https://www.objective.com.br/insights/metricas-ageis/
- 
