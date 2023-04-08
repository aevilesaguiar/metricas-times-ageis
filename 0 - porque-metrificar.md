# Métricas times ageis

Qual o propósito que quero com aquela métrica

- O que eu vou medir?
- Por que eu vou medir?
- Como eu vou medir?

As métricas nunca devem ser feitas para pessoas e sim para o time.

A média é calculada somando-se todos os valores e dividindo a soma pelo número total de valores. 

A mediana pode ser calculada listando-se todos os números em ordem crescente para localizar todos os números em ordem crescente e depois localizá-lo centro dessa distribuição.

Toda vez que sua media for maior que a sua mediana significa que você tem a tendencia a descer mais rápido, entregando com menos tempo.
Toda vez que a sua media for menor que a sua mediana significa que você tem uma tendencia de levar mais tempo para fazer a sua entrega.
O desvio padrão é uma medida que expressa o grau de dispersão de um conjunto de dados. Ou seja, o desvio padrão indica o quanto um conjunto de dados é uniforme. Quanto mais próximo de 0 for o desvio padrão, mais homogêneo são os dados.

Qual a importancia de reduzir o lead time? vou ter mais entregas, no melhor tempo

Reduzir o numero de desperdícios? quer dizer que eu estou entregando melhor, reduzindo retrabalho, não entregar com problemas.

Leadtime - O tempo que o item demora para ser construído. Devo chamar o tempo a partir do tempo de inicio onde atinjo o ponto de compromisso até a conclusão do trabalho do time, para frente disso podemos ter customer time, tempo de deploy... Cycle time para o o tempo dentro da etapa, customer time o tempo todo. Persiga o
leadtime no fator de entrega, aonde que o valor estar? 


Defintion of Ready (DoR) é um acordo de trabalho entre o time de Desenvolvimento e o Product Owner, aplicado a todas as Histórias de Usuário, com a intenção de que os itens do Backlog não cheguem para a reunião de planejamento com granularidade ruim, pouco ou nenhum detalhamento.

Antes que um item do Backlog entre para a Sprint o time deve garantir que ele esteja atendendo aos critérios de “Ready”, em termos de estarem suficientemente bem descritos e compreendidos por todo time de desenvolvimento, para que eles tenham condições suficiente para planejá-lo em uma Sprint e estabelecer um compromisso em relação à sua implementação.

É preciso disciplina para reservar até 10% do tempo da Sprint para que o Product Backlog seja preparado adequadamente com a finalidade de reduzir o impacto de itens mal especificados, que muitas vezes fazem com que os times façam um planejamento de baixa qualidade e que sejam surpreendidos ao longo da sprint com descobertas sobre um item, gerando necessidade de mudanças na implementação e impactando os objetivos da sprint.

![image](https://user-images.githubusercontent.com/52088444/230694857-8dfdde23-828c-4886-977e-dcc665b2274e.png)


Definition of Done (DoD) é um acordo genérico, definido pelos membros do time Scrum (Desenvolvedores e Product Owner), aplicável a todas as Histórias de Usuário, com o intuito de que todos os membros do time tenham um entendimento compartilhado do que significa “Done” para garantir a transparência. Ou seja, uma lista de verificação de atividades necessárias para que um incremento de software seja considerado como completo.

Definition of Done (DoD) é um acordo genérico, definido pelos membros do time Scrum (Desenvolvedores e Product Owner), aplicável a todas as Histórias de Usuário, com o intuito de que todos os membros do time tenham um entendimento compartilhado do que significa “Done” para garantir a transparência. Ou seja, uma lista de verificação de atividades necessárias para que um incremento de software seja considerado como completo.

![image](https://user-images.githubusercontent.com/52088444/230694891-18db2455-d363-4505-8874-354d1a89b8ae.png)

⭐️Já, os critérios de aceite são específicos e diferentes para diferentes Histórias de Usuário.

Simples, não é!?

Ok, mas pode ficar mais simples ainda com alguns exemplos:

Definition of Ready
◻️ Histórias de Usuário devem ter sido escritas com o padrão de escrita INVEST;
◻️ Histórias de Usuário devem possuir ao menos um critério de aceite;
◻️ Histórias de Usuário devem possuir wireframe de baixa fidelidade.

Definition of Done
◻️ Funcionalidades devem ter sido testadas;
◻️ Testes unitários devem ter sido criados;
◻️ Funcionalidades devem ter atendido a todos os critérios de aceite;
◻️ Todas as funcionalidades devem ter sido testadas no Chrome, IE e Firefox;
◻️ O código deve ter sido revisado por outro desenvolvedor.
Critérios de Aceite
✔️[Iniciante]: Descrição simples de como a funcionalidade deve funcionar.

⟹Exemplo: Exibir apenas os dois últimos e-mails não lidos ao acessar pela primeira vez.

✔️[Avançado]: Dado (pré condição), Quando (cenário), Então (resultado esperado).

⟹Exemplo: Dado que o cliente ainda não recebeu nenhum email, quando o cliente abrir o painel, a seguinte mensagem “nenhum email anterior” é exibida.

⟹ Quando o time deve criar a sua DoR e DoD?
Idealmente, o time deve criar antes da primeira sprint. Porém, caso o seu time ainda não tenha uma definição de ready e/ou done criada, ou que não esteja clara para todos, uma boa oportunidade é levantar o assunto sobre a oportunidade de criarem a sua DoR e/ou DoD durante a retrospectiva.

⟹ Uma vez criada a DoR e DoD, elas nunca mais poderão ser alteradas?
Elas poderão ser alteradas sempre que fizer sentido para o time. Utilize a retrospectiva para inspeção e adaptação.

⟹ Cada time deve ter a sua própria DoR e DoD?
Idealmente sim, cada time cria seus próprios critérios de pronto, embora muitas vezes alguns itens da DoR e DoD possam ser similares a todos os times por ser algum requisito da área/setor/empresa.

⟹ De quem é a responsabilidade de tornar o item “Ready”?
É de responsabilidade do Product Owner, embora ele(a) possa envolver outras pessoas do time nessa atividade.

⟹ Quando deve ser feito o trabalho de refinamento para deixar os itens “Ready”?
Idealmente, na Sprint anterior a que se deseja incluir o item.


## Referencias

https://medium.com/guma-rs/n%C3%A3o-confunda-dod-com-crit%C3%A9rios-de-aceite-d030b9a812d9
