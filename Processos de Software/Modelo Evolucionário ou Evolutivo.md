
Modelos Evolucionários de desenvolvimento de software são baseados na ideia de que um processo na qual o software a ser desenvolvido deve evoluir a partir de uma implementação inicial, que pode ser um protótipo. Tal abordagem também visa obter feedback de usuários durante o processo de desenvolvimento. Podendo refinar versões até que seja desenvolvido o sistema adequado. Essa abordagem é mais indicada para sistemas de pequeno a médio porte.

O Modelo espiral proposto por Boehm(1998) é um modelo de processo de software evolucionário. O processo de software nesse modelo é representado como se fosse uma espiral, e não como uma sequencia de atividades como em outros modelos. Casa volta na espiral representa uma fase do processo de desenvolvimento de software. Assim, a volta mais interna pode ser um protótipo para validar a viabilidade do sistema, por exemplo; o ciclo seguinte voltado para a definição dos requisitos; o seguinte para o projeto do sistema e assim por diante.

O modelo espiral foi desenvolvido combinando as melhores práticas e características dos modelos lineares e prototipação. Porém, como destaque nesse modelos, foi acrescentado um novo recurso: a análise de riscos. Entende-se como risco qualquer coisa que possivelmente ocasionará algum erro ou problema durante o desenvolvimento de software.

A principal diferença entre o modelo espiral e outros modelos de processo de software é o reconhecimento explicito do risco. Um Ciclo espiral começa coma definição de objetivos, como desempenho e funcionalidade. Em seguida, são enumeradas *formas alternativas de alcançar tais objetivos e lidar com as restrições de cada um deles*. Cada **alternativa** é avaliada em função de cada **objetivo**, e as **fontes de risco do projeto são identificadas**. O próximo passo é resolver esses riscos por meio de atividades de coleta de informações, ==como uma análise mais detalhada, prototipação e simulação==. 

![[Pasted image 20251002104841.png]]

De acordo com Sommerville, cada volta da espiral é dividida em quatro setores:
1.  **Definições de objetivos:** objetivos específicos para essa fase do projeto são definidos, restrições ao processo e ao produto são identificados e um plano de gerenciamento detalhado é elaborado identificando riscos para poderem planejar estratégias em função desses riscos.
2. **Avaliação e Redução de Riscos:** para cada um dos riscos identificados do projeto é feita uma análise e, então medidas são tomadas para a redução dos riscos.
3. **Desenvolvimento e validação:** após a avaliação dos riscos é selecionado um modelo de desenvolvimento para o sistema.
4. **Planejamento:** o projeto é revisado e uma decisão é tomada a respeito da continuidade do modelo com mais uma volta da espiral. Caso seja decidido pela continuidade, planos são elaborados para próxima fase do projeto.
##### São consideradas vantagens do Modelo Espiral (Evolucionário)
 - Estimativas são mais reais
 - Maior versatilidade para lidar com mudanças.
 - Mais fácil para testar e definir quando testar.
 - Melhora no tempo de implementação do sistema.
 - Não há distinção do que é desenvolvimento e o que é manutenção.
##### Já as desvantagens são:
 - Muita ênfase na parte funcional.
 - Avaliação dos riscos exige experiência
 - Sua aplicação é melhor somente em sistemas de larga escala.
 - Modelo relativamente novo, porém não muito utilizado.
