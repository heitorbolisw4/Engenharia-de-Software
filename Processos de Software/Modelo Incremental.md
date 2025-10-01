O desenvolvimento incremental, de acordo com Sommerville (2001), é Baseado na ideia de desenvolver uma implementação inicial, apresenta-las aos usuários ou clientes para que possam receber feedbacks e assim, continuar o desenvolvimento de outras versões até que um sistema adequado seja desenvolvido. Entende-se por sistema adequado, aquele que atende os requisitos do cliente e/ou dos usuários, de maneira que satisfaçam da melhor forma possivel. Uma característica dos modelos incrementais é a forma como as atividades de especificação, desenvolvimento e validação são intercaladas obtendo a vantagem de um feedback mais assertivo e rápido entre todas as atividades.

Uma grande vantagem do uso do modelo incremental é a sua abordagem em relação a resolução de problemas, que se assemelha muito como a forma em que resolvemos problemas reais. Sommerville explica que "Desenvolvimento incremental reflete a maneira como resolvermos os problemas pois raramente elaboramos uma solução completa do problema com antecedência. Geralmente movemo-nos em direção a solução, recuando quando percebemos que cometemos um erro".  Além disso, desenvolver software de forma incremental facilita alterações, inclusões de funcionalidades, mudanças durante o desenvolvimento são mais fáceis e tem menor impacto, com isso podem ocorrer reduções no custo de desenvolvimento, comparado a execução das mesmas mudanças em uma abordagem sequencial.

São varias as vantagens do modelo incremental quando comparado ao modelo cascata:

 - O custo para adaptar as mudanças nos requisitos do cliente é reduzido, diminuindo o retrabalho em alterar a documentação ou em refazer o processo de análise.
 - Facilidade em obter feedback com clientes, pois há maior participação desses desde o começo. Assim, os clientes podem fazer comentários sobre demonstrações do software e acompanhar o quanto já foi implementado. Apenas com documentações e relatórios de status, repport, os clientes sentem dificuldades de acompanhar a evolução do que está sendo feito.
 - Mesmo se toda a funcionalidade não for incluída é possivel obter uma versão de entrega e implementação rápida de um software útil ao cliente. Desta forma, o software começa a ser utilizado bem mais rápido em comparação com o Modelo Cascata.


O Desenvolvimento incremental é uma das abordagens mais utilizadas para o desenvolvimento de sistemas. Tal abordagem pode ser dirigida a planos por meio de combinação das atividades. Em uma abordagem dirigida a planos, os incrementos do sistema são identificados, previamente, se uma abordagem ágil for utilizada, os incrementos iniciais são identificados, mas o desenvolvimento de incrementos posteriores dependo do progresso e das prioridades dos clientes.

Do ponto de vista de gerenciamento, a  abordagem incremental tem dois problemas:
1.  Processo não é visível:
	- O que é "Concluído"? O trabalho é dividido em pequenos incrementos ( pedaços de funcionalidades). Para um gerente, pode ser difícil avaliar o **progresso real** do projeto geral. O time está entregando funcionalidades, mas a data de conclusão do sistema completo pode parecer incerta.
	
	- A falta de Marcos Rígidos: Como as atividades se sobrepõem ( você está projetando o incremento 3 enquanto testa o incremento 2), não há um marco de "100% dos Requisitos Feitos" ou "100% do projeto Feito" para todo o sistema. Isso Dificulta a **medição de progresso** e o **planejamento de cronogramas** de longo prazo.
	
	- **Foco no Código vs. Foco no Planejamento**: O foco está na **entrega do código funcional** a cada incremento e não na conclusão grandes pacotes de documentação de gerenciamento. Se a equipe não for disciplinada em documentar cada incremento e atualizar o plano mestre, o gerenciamento do projeto pode perder o controle

2. A estrutura do sistema tente a se degradas com a adição de novos incrementos.
	Este é um problema puramente técnico e arquitetural que se manifesta sob a pressão da entrega incremental.
	O desenvolvimento incremental exige que você comece com uma **arquitetura de sistema** que será a base para todos os incrementos futuros.
	 - **O conhecimento é Limitado no Início:** Quando você projeto o incremento 1, você não tem uma compreensão completa dos requisitos finais (que serão adicionados ao longo do projeto.)
	 - **Decisões Arquiteturais Incorretas:** As decisões tomadas no início (por exemplo, sobre como estruturar a comunicação entre componentes) podem ser ótimas para o incremento 1, mas se tornam **restritivas ou inadequadas** para um incremento posterior.
	 - **Remendos e "Gambiarra"**: Sob pressão do *Time to Market* ( que é o motor para abordagens incrementais ), em vez de refatorar ( reestruturar ) a arquitetura para suportar o novo incremento de forma limpa, a equipe pode optar por "**remendar**" o código existente.
	 - **Dívida Técnica:** Cada "remendo" não planejado se acumula, gerando uma chamada **Dívida Técnica.** Eventualmente, o custo de manter e adicionar novos recursos ao sistema se torna proibitivamente alto, e a estrutura do código se torna frágil e difícil de entender.
	O Desafio do **Gerenciamento de Arquitetura** em modelos incrementais é garantir que a equipe dedique tempo e recursos em cada ciclo para **refatorar e evoluir a arquitetura, evitando que a estrutura de degrade.**


Durante o processo de desenvolvimento de software incremental se faz necessário adaptar e refinar o sistema, e com isso, softwares grandes e complexos podem ser finalizados diferentes do que projetados inicialmente. Especialmente se as partes dos sistemas forem desenvolvidas por equipes diferentes. Outra desvantagem comum são as diversas alterações no escopo que podem surgir a cada incremento, aumentando ou diminuindo requisitos, ou até mesmo alterando funcionalidades já criadas.

O Modelo incremental apresenta diversas vantagens para o desenvolvimento de um software, especialmente se os requisitos não estão claros inicialmente. Nesse modelo, as versões do software são fornecidas após cada interação e, dessa forma, o usuário pode perceber mudanças necessárias antes da finalização do projeto. Além disso, é um modelo flexível e fácil de gerenciar, especialmente os riscos, pelo fato do cliente ( usuário ) participar a cada versão e validar se está de acordo com o que está sendo feito. As inconformidades são corrigidas antes da entrega da próxima versão. Outras vantagens são:
 - Quando ocorre um erro em um incremento, os demais (anteriores) nem sempre são diretamente afetados. Em casos de erros graves, apenas o último incremento seria ajustado ou no pior caso descartado.
 - Reduzindo o tempo de desenvolvimento de um sistema, é esperado que se reduzisse as chances de mudanças nos requisitos do usuário final, visto que esse já participa validando cada versão.
 - A quantidade de análise e documentação a ser refeita é menor quando comparada ao modelo de desenvolvimento em Cascata
 - Nesse modelo é previsto que os clientes ( usuários ) façam comentários/feedbacks sobre o que foi desenvolvido. Normalmente as pessoas tem dificuldades de avaliar a evolução apenas por meio de documentação. 