## História
bla bla bla

Eis o principal legado deste framework
> Adote e adapte-se

## Relevância
Pessoas, tecnologias e processos. Esses três compõem um serviço de TI. Serviços de TI dependem de recursos para que possam ser entregues. Eficiência e eficácia.

## Modelo de referência e processos da ITIL v2

#### Suporte ao serviço (service support)
Os processos desta área concentram-se nas tarefas de execução diária, necessária para a manutenção dos serviços de TI já entregues e em utilização pela organização.
São eles:

1. Gerenciamento de configuração (configuration management).
2. Gerenciamento de incidente (incident management).
3. Gerenciamento de problema (problem management).
4. Gerenciamento de mudança (change management).
5. Gerenciamento de liberação (release management).

#### Entrega do serviço (service delivery)
Os processos desta área concentram-se nas atividades de planejamento a longo prazo dos serviços que serão demandados pela organização e na melhoria dos serviços já entregues e em utilização pela organização. 
São eles:

1. Gerenciamento do nível de serviço (service level management).
2. Gerenciamento de capacidade (capacity management).
3. Gerenciamento da disponibilidade (availability management).
4. Gerenciamento da continuidade dos serviços de TI (IT service continuity management).
5. Gerenciamento financeiro (financial management).

#### Gerenciamento de configuração
É importante para toda organização controlar os seus meios de produção, pois eles são a chave para a criação de produtos ou serviços a serem oferecidos aos clientes, pelos quais se pode criar valor para a organização. Como todos os demais meios de produção, os da área de TI devem ser controlados e gerenciados.

O processo de gerenciamento de configuração é o responsável pela criação da base de dados do gerenciamento de configuração, __CMDB__, a qual é constituída pelos detalhes dos `itens de configuração`, __CI__, empregados para o aproveitamento e o gerenciamento dos serviços de TI.

Um item de configuração é um componente que faz parte ou está diretamente relacionado com a infra-estrutura de TI. Um item de configuração pode ser um componente físico ou lógico (hardware ou software!), bem como pode também ser composto por outros itens de configuração.

Exemplos de itens de configuração:
* Microcomputador.
* Placa de rede.
* Software.
* Manual técnico de um equipamento.
* Procedimento de trabalho.

#### Gerenciamento de incidente
O processo de gerenciamento de incidente é responsável pelo tratamento e pela resolução de todos os incidentes observados nos serviços de TI, visando ao restabelecimento dos serviços no menor prazo possível. Para a sua operacionalização, ele se apóia na estrutura da `Central de Serviços`.

A Central de Serviços (service desk) é um importante componente do aprovisionamento de serviços de TI para a organização. Ela é frequentemente o primeiro ponto de contato dos usuários que, ao utilizarem um serviço de TI, percebem alguma coisa diferente do previsto. 

Os dois principais focos de uma Central de Serviços são o __gerenciamento__ e a __comunicação__ de incidentes. Há diferentes tipos de central de serviços, a seleção do mais apropriado para uma dada organização dependerá das necessidades para a implementação de sua estratégia de negócio. Algumas Centrais de Serviço provêm apenas o registro das chamadas e quando detectam ser um incidente, transferem a chamada para uma outra equipe mais experiente e capacitada para o atendimento. Outras provêm um alto nível de serviço, possibilitando a resolução de grande parte dos incidentes reportados durante o período do atendimento, enquanto o usuário o está reportando.

Na terminologia ITIL, um incidente é uma interrupção não planejada de um serviço de TI ou uma redução da qualidade de um serviço de TI. Falha de um Item de Configuração que ainda não tenha impactado um serviço de TI é também um incidente. 

#### Gerenciamento de problema
O processo de gerenciamento de problema é o responsável pela resolução definitiva e prevenção das falhas por trás dos incidentes que afetam o funcionamento normal dos serviços de TI. Isto inclui assegurar que as falhas serão corrigidas, prevenir a reincidência das mesmas e realizar uma manutenção preventiva que reduza a possibilidade de que venham a ocorrer.

#### Gerenciamento de mudança
O processo de gerenciamento de mudança tem a finalidade de assegurar que todas as mudanças necessárias nos itens de configuração, __CI__, serão realizadas conforme planejado e autorizado, o que inclui assegurar a existência de uma razão do negócio subjacente a cada mudança a ser realizada, identificar os itens de configuração envolvidos, testar o procedimento de mudança e garantir a existência de um plano de recuperação de serviço, caso algum imprevisto venha a ocorrer, como, por exemplo, o bloqueio inesperado de um item de configuração.

#### Gerenciamento de liberação ou atualização
O gerenciamento de liberação é o processo responsável pela implementação das mudanças no ambiente de infra-estrutura de TI, ou seja, pela colocação no ambiente de produção de um conjunto de itens de configuração novos e/ou que sofreram alterações, os quais foram testados em conjunto. Uma vez que uma ou mais mudanças são desenvolvidas, testadas e empacotadas para implementação, o processo de gerenciamento de liberação é responsável por introduzi-las na infra-estrutura de TI e gerenciar as atividades relacionadas com tal liberação.

O processo de gerenciamento de liberação também contribui para aumentar a eficiência da introdução de mudanças no ambiente de infra-estrutura de TI, combinando-as em uma única liberação e realizando a implementação das mesmas em conjunto.

#### Gerenciamento do nível de serviço
O processo de gerenciamento do nível de serviço é a base para o gerenciamento dos serviços que a área de TI aprovisiona para a organização. Sua responsabilidade é assegurar que os serviços de TI, dentro dos níveis de serviço acordados, serão entregues quando e onde as áreas usuárias o definirem. Tal processo depende de todos os demais processos de entrega de serviços, e seu gerente deralmente é o próprio gerente da área de TI, haja vista a sua importância para a imagem da área de TI perante toda a organização.
O processo de gerenciamento do nível de serviço pode ser dividido nos seguintes subprocessos:

* Revisão dos serviços disponibilizados.
* Negociação com os clientes.
* Revisão dos contratos de serviços com fornecedores externos.
* Desenvolvimento e monitoração dos acordos de nível de serviço.
* Implementação das políticas e dos processos de melhoria contínua.
* Estabelecimento de prioridades.
* Planejamento do crescimento dos serviços.
* Definição do custo dos serviços em conjunto com o gerencimento financeiro e da forma de ressarcimento destes custos.

#### Gerenciamento de capacidade
O processo de gerenciamento da capacidade é responsável pela disponibilização no tempo certo, no volume adequado e no custo apropriado dos recursos de infra-estrutura de TI necessários ao atendimento das demandas do negócio em termos de serviços de TI, garantindo que os recursos disponíveis sejam utilizados da forma mais eficiente possível.

Para atingir seus objetivos, é imprescindível a identificação dos serviços de TI que serão requeridos pelas áreas de negócio da organização, a definição de qual infra-estrutura de TI e o `nível de contingência` serão necessários, além de calcular o custo desta infra-estrutura.
O processo de gerenciamento de capacidade pode ser dividido nos seguintes subprocessos:

* Monitoração do desempenho.
* Monitoração da carga de trabalho/demanda.
* Dimensionamento da aplicação.
* Projeção de recursos.
* Projeção da demanda.
* Estabelecimento de modelos.

#### Gerenciamento de disponibilidade
O gerenciamento da disponibilidade é o processo da ITIL que visa determinar os níveis de disponibilidade dos serviços de TI a partir dos requerimentos do negócio. Uma vez definidos os níveis de disponibilidade, estes devem ser discutidos com as áreas-cliente, passando o resultado a constar dos acordos de nível de serviço assinados. A disponibilidade é, em geral, calculada com base em um modelo que considera a disponibilidade média e os impactos decorrentes dos `pontos de falha` mapeados com a utilização de uma técnica chamada *Fault Tree Analysis* (TCA).

#### Gerenciamento da continuidade dos serviços de TI
O processo de gerenciamento da continuidade dos serviços de TI é o responsável pela validação dos planos de contingência e recuperação dos serviços de TI após a ocorrência de acidentes. Ele não trata apenas de medidas reativas, mas também de medidas proativas decorrentes de ações de mitigação dos riscos de ocorrência de um desastre em primeira instância.

O plano de continuidade do negócio é desenvolvido atualmente não apenas para garantir a recuperação e a disponibilização dos serviços de TI, mas também com uma visão de recuperação do processo de negócio, utilizando uma visão fim-a-fim, de modo que a organização volte o mais rápido possível a operar e a atender seus clientes finais, após a ocorrência de um desastre.

#### Gerenciamento financeiro
O processo de gerenciamento financeiro é aquele cujo objetivo é determinar o verdadeiro custo de todos os serviços de TI e demonstrá-lo de maneira que a organização possa entendê-lo e utilizá-lo para o processo de tomada de decisão. Posteriormente, é responsável pelo estabelecimento dos mecanismos que viabilizem a cobrança do custo dos serviço de TI e seus respectivos clientes.

#### Gerenciamento da segurança


#### Gerenciamento de aplicação

#### Gerenciamento da comunicação

#### Gerenciamento do relacionamento
