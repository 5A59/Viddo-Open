# QWEN 3 CODER é Lançado... melhor que KIMI K2

Recentemente, assisti a um vídeo e achei bastante esclarecedor. Para entender melhor e compartilhar o conteúdo, utilizei **[Viddo](https://viddo.pro/)** para converter o vídeo em um artigo estruturado, que serviu como referência para esta análise.

**Vídeo Original:** [Assistir Vídeo](> - A Alibaba revelou o Quin 3 coder, um poderoso novo modelo de codificação de código aberto.
> - Ele possui um gigantesco modelo de 480 bilhões de parâmetros chamado Powerful1.
> - O Quin 3 coder se destaca em vários benchmarks e supera os concorrentes.
> - Uma ferramenta de linha de comando para codificação ageentica, Quin Code, agora está disponível.
> - Novos métodos em aprendizado por reforço melhoram o desempenho em tarefas de codificação do mundo real.

A Alibaba acaba de lançar a próxima grande novidade. **Quin 3 coder**. Assim que o mundo começa a se acostumar com **Kimi K2**, o outro grande modelo de codificação de código aberto, a Alibaba apresenta o **Quin 3 coder**, que está disponível em vários tamanhos.

Mas o grande modelo, o **Powerful1**, é o Quin 3 Coder 480B A35B instruct, o que significa que este é um **modelo de 480 bilhões de parâmetros**. Ele é construído com uma mistura de especialistas, então apenas **35 bilhões de parâmetros estão ativos durante qualquer chamada**. Instruct significa que é o nosso modo de assistente amigável e útil, em oposição ao modelo base que é um pouco mais parecido com um modelo de conclusão de texto.

O Nataly suporta **256k de contexto** e escala até **1 milhão**. E como você pode ver aqui, os benchmarks parecem ótimos agora. Não podemos sempre confiar apenas nos benchmarks, então dê um tempo enquanto todos experimentam e testam.

Mas **Kimi K2**, por todas as contas, foi extremamente impressionante. O **Gwin 3 coder** supera facilmente o Kimi K2. Não só isso, mas é comparável. Está competindo com **Cloud Sounded** e também supera **OpenAI's GPT 4.1** e pontua muito bem em **uso de navegador ageentic**, bem como uso de ferramentas ageentic. Novamente, apenas o Cloud Sounded 4 o supera em alguns casos.

A equipe do **Gwin** promete que funciona perfeitamente com as melhores ferramentas de desenvolvimento da Comunidade e pode ser usado em qualquer lugar do mundo digital. Codificação agegenica no mundo e eles não estão brincando com isso.

Junto com o modelo, eles estão disponibilizando uma ferramenta de linha de comando para codificação ageentic chamada **Quin Code**. É uma bifurcação do **código Gemini do Google**. Como você pode ver aqui, está open source sob a **licença Apache 2.0 do GitHub**. Parece muito com o código claw e foi adaptado com prompts personalizados e protocolos de chamada de função para liberar totalmente as capacidades do Quin 3 coder em tarefas de codificação ageentic.

Então, basicamente, **Quin code** é apenas um **Gemini cli** adaptado. Foi modificado para usar os modelos Quwin. Você também pode usar os **modelos do Quin 3 coder** com **cloud code**. Muitas pessoas preferem o cloud code, então você pode facilmente usar os modelos do Quin 3 Codder com o Cloud code. Você pode usá-los com **K Clin**. Vou deixar esses links abaixo.

Um dos grandes assuntos de discussão agora é **aprendizado por reforço**. Pegando esses modelos e levando-os para um ginásio de RL para ensiná-los como realizar várias habilidades, como codificação, matemática, etc. Como eu digo aqui, escalando o código, o aprendizado por reforço é difícil de resolver, fácil de verificar, como você pode ver aqui.

À medida que eles aumentam os passos de treinamento ao treinar este modelo, ele cresce e se destaca em todas as diferentes áreas de desempenho, como geração de código, desenvolvimento de software, codificação competitiva, **seguimento de instruções SQL**, etc. Eles fazem uma crítica ao outro laboratório de fronteira, dizendo que, ao contrário do foco predominante na geração de código em nível de competição na comunidade, acreditamos que todas as tarefas de código são naturalmente bem adequadas para execução em grande escala por aprendizado por reforço.

É por isso que escalamos o treinamento de RL do código em um conjunto mais amplo de tarefas de codificação do mundo real. Basicamente, eles estão dizendo que, em vez de tentar maximizar esses testes e quizzes, essas perguntas de estilo competitivo, eles estão realmente treinando este modelo para fazer **trabalho real no mundo real**.

Ao escalar automaticamente os casos de teste de tarefas de codificação diversas, criamos instâncias de treinamento de alta qualidade e desbloqueamos com sucesso todo o potencial do aprendizado por reforço. Isso não só aumentou significativamente as taxas de sucesso na execução de código, mas também trouxe ganhos para outras tarefas.

Isso significa que essa abordagem generaliza. Vimos em outros artigos publicados que, por exemplo, treiná-lo para fazer código melhora sua capacidade de resolver problemas matemáticos, mesmo que não tenha sido explicitamente treinado para isso. Certamente, parece que sua abordagem generaliza em várias tarefas diferentes. Espero que publiquem um artigo mais tarde que vá descrever como eles abordaram isso.

Mas aqui mencionaram que sua abordagem utiliza tarefas difíceis de resolver e fáceis de verificar como terreno fértil para aprendizado por reforço em grande escala.

Então aqui está um gráfico de seu desempenho no **SUI bench Verified**, então este é o tamanho do modelo. Modelos à direita são maiores, modelos à esquerda são menores e quanto mais alto você vai, melhor é a pontuação no subench verificado. SWbench é composto por **500 problemas de Python confirmados e verificados por humanos no GitHub**, revisados por humanos e confirmados como solucionáveis.

Como você pode ver aqui, **Quin 3 coder** está acima da maioria dos outros modelos que vimos, incluindo **Kimmy K2**, **GPT 4.1**, até mesmo **Gemini 2.5 Pro Preview**. Apenas **Cloud Sont 4** o supera levemente sendo um modelo muito maior. Por ser um modelo de tamanho moderado, nada chega perto dele em termos de desempenho. **Kimmik K2** é muito maior, mas não tão bom.

Importante, com **tarefas reais de engenharia de software** como aquelas do **SUI bench verified**, o Quin 3 coder deve se envolver em interações de múltiplas etapas com o ambiente, envolvendo planejamento, uso de ferramentas, recebendo feedback e tomando decisões. Assim, isso não é um formato simples de pergunta-resposta. Essa é uma tarefa de longo prazo que inclui planejamento e feedback.

Qual foi o truque deles para fazer este modelo ser tão bom em tarefas de longo prazo? Apenas mencionando que na fase de pós-treinamento do **Quint threeoder**, eles introduziram **Long Horizon rl**. Eles se referem a isso como **Agent rl**. Isso foi para incentivar o modelo a resolver essas tarefas do mundo real através de interações de múltiplas etapas usando ferramentas.

Isso é interessante. O grande desafio em fazer algo assim com **Agent rl** reside na escalabilidade do ambiente. Para resolver isso, eles construíram um **sistema escalável** capaz de rodar **20.000 ambientes independentes em paralelo**. Eles fizeram isso usando a **infraestrutura de nuvem da Alibaba**.

Isso lhes permitiu a escala necessária para executar este gigantesco pipeline de aprendizado por reforço. E isso é o que permitiu que o **Coin 3 Coder** alcançasse o **estado da arte** entre os modelos de código aberto sem—e isso é importante notar—sem escalonamento de tempo de teste. Este não é um modelo de raciocínio. Ao contrário do **DeepSeq R1** ou do **Gemini 2.5 Pro Preview**, este é não-raciocínio.

Algumas das demonstrações que eles postaram incluem demolição de construções e demonstrações. Aqui usando **Quinn com Klein**, eles montaram uma explosão de cores interativa. Parece muito legal.

Então, teremos que testar algumas dessas coisas: **visualização de terreno 3D no Google Earth**, um pequeno aplicativo para testar sua velocidade de digitação, bola saltitante em rotação, um hipercubo, simulação super psicodélica do sistema solar e um jogo de dueto. Está disponível no como você enfrenta e conversa com **Quen AI**.

Então, vou realizar uma série completa de testes sobre isso, mas por enquanto, aqui estão apenas alguns testes rápidos que eu fiz. Um é fazer uma simulação de um prédio de escritório com mesas e salas dentro. Então, eu tentei fazer com que ele criasse algum tipo de **janelas transparentes** do lado de fora, mas não conseguiu fazer a transparência. Elas eram muito opacas ou completamente não transparentes.

Mas ele conseguiu criar, você sabe, os ambientes internos com mesas e computadores e o que quer que seja. Uma luz parece uma luz em cada sala. Até agora, desde o começo, não está tão mal. Quero dizer, isso é bem bom para a primeira tentativa.

Eu também criei um pequeno **jogo de drone**, onde você pode voar um drone pela cidade. Não posso reclamar. Está bem bom. Quero dizer, os controles são um pouco estranhos, mas estou gostando até agora. Leva um tempo para se acostumar, mas uma vez que você consegue apenas controlar o acelerador, consegue voar por aí e não é ruim por ser uma tentativa única.

Temos um **clone de Minecraft**. Onde estaríamos sem um clone de Minecraft? Você pode colocar blocos e construir e se mover. Nada mal, consegui fazer isso com facilidade.

Então, confira, me avise o que você pensa sobre isso. Mais testes e casos de uso estão chegando muito, muito em breve. Além disso, alguém fez esse pequeno hack para **clot code** e por que não tivemos isso o tempo todo?

Através da lista de tarefas. Criando a **lista de afazeres**. Senhor. Começando ajustes no código Python. Faça isso como prioridade. Trabalhando pela lista de tarefas. Na verdade, isso pode se tornar meio irritante rapidamente.

E tenho que dizer, não esperava que a IA de código aberto fosse tão boa. Acho que esperávamos que ela estivesse, digamos, no máximo alguns anos atrás dos laboratórios de fronteira. Agora, parece que está apenas meses atrás. **Que época para estar vivo.**  
**Artigo de Referência:** [Ver no Viddo](https://viddo.pro/zh/video-result/de3fa85b-5156-4186-a39d-60c839fb0371)