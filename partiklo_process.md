!["logo"](/logo_Partiklo_fundo_branco.png)
# partiklo process
## Objective Oriented Software Development Process

## Processo de desenvolvimento Partiklo

*Um processo de desenvolvimento baseado em funcionalidades.*

O projeto Partiklo deverá utilizar um processo de desenvolvimento próprio, que fuja dos "métodos ágeis", mas seja organizado e flexível o suficiente.

### Partículas

O cerne do Processo Partiklo é uma "partícula" de funcionalidade. A cada ciclo iterativo, uma partícula é produzida e integrada ao "átomo", que é o sistema completo. 

### WBS

O sistema e as partículas são descritos em WBS (Estruturas Analíticas de Projeto). O nível zero especifica os "entregáveis", cada um formando uma árvore de atividades. Se isto foi alcançado, então a partícula pode ser desenvolvida. 

Se o nível zero precisa ser decomposto, então a WBS se refere a um átomo, e cada elemento do nível zero será uma nova partícula, sendo criado seu próprio WBS.

### Cronogramas

O Partiklo é baseado em cronogramas. A partir do WBS de uma partícula é gerado um cronograma de atividades e de recursos, com estudo CPM, ou seja, caminho crítico.

O cronograma detalha um Ciclo iterativo do Partiklo.

### Ciclos

Cada ciclo iterativo do Partiklo é estimado e controlado por um cronograma, e se refere a uma "partícula" do projeto. Não há prazo pré fixado, como no Scrum. Um CI não é um "Sprint", e seu produto é claramente especificado pela WBS, com cada "partícula", "entregável" e "atividade" bem especificados. 

Durante o ciclo as atividades de Análise, Projeto e Construção são mescladas Sempre visando a integração entre as atividades e o cronograma. As estimativas podem ser feitas utilizando-se "Pontos de função" ou qualquer outra técnica FUNDAMENTADA, exceto tolices, como: Planning Poker. 

### Comunicação e status

Cada "entregável" possui um VA (Valor agregado), estimado em horas de esforço ou pontos de função. Conforme o andamento do projeto, é responsabilidade do GP (Gerente do Projeto) calcular o VA de cada "entregável", evitando atrasos. A comunicação do status à equipe deve ser periódica, mas jamais diária. Periodicidade semanal pode ser apropriada, assim como quinzenal. Essa periodicidade pode ser ajustada. Relatórios de status, com gráficos de VA, podem ser enviados para diminuir a necessidade de reuniões. 

Todos os artefatos, de código ou não, deverão ser mantidos em um repositório com controle de versionamento. A verdadeira medida de progresso são os commits e o resultado dos testes de integração.

### Métricas

Métricas palpáveis e reais são a base do controle do Processo Partiklo e não histórias da "carochinha" como "postits" ou gráficos de "burndown". 

Commits e testes de integração são métricas importantes e relacionadas. A quantidade de commits vs falhas em testes podem apontar nós do desenvolvimento. 



