# Kimi K2 vs Claude Code: Por que mais barato não é melhor

Recentemente, assisti a um vídeo e achei bastante perspicaz. Para entender melhor e compartilhar o conteúdo, usei **[Viddo](https://viddo.pro/)** para converter o vídeo em um artigo estruturado, que serviu como referência para esta análise.

**Vídeo Original:** [Assistir Vídeo](> - Um novo modelo open source, **Kimi K2**, foi recentemente lançado pela **Moonshot AI**.
> - O Kimi K2 está gerando muita expectativa devido ao seu desempenho em benchmarks.
> - O vídeo compara o Kimi K2 com **Cloud for Sont** usando **CLAU code** e **Gemi 2.5 Pro**.
> - Observações iniciais sobre autenticação de API indicam algumas discrepâncias nas configurações de conexão.
> - O Kimi K2 mostra potencial, mas enfrenta dificuldades com tarefas mais complexas em comparação com seu comparador, Cloud for Sont.

Há cerca de 2 dias, um novo modelo open source chamado **Kimi K2** foi lançado por um laboratório chinês chamado **Moonshot AI**. E basicamente, parece que ele está indo muito bem nos benchmarks aqui. E há muitos posts de hype sobre isso online. Como se **Kimi K2** tivesse pulverizado todos os benchmarks da indústria ou fosse o melhor modelo open source e superasse o **Cloud for Sont**.

Na verdade, muitos desses posts de hype são impulsionados por esses números de benchmark aqui. E não é surpresa que, até agora, muitas dessas empresas costumam manipular os benchmarks a seu favor ou empregam táticas engenhosas nos bastidores. Portanto, o modelo acaba se saindo muito bem nos benchmarks, mas ninguém realmente o utiliza em produção para suas bases de código.

Neste vídeo, vamos comparar com **Cloud for Sont**, usando **CLAU code** e também **Gemi 2.5 Pro** usando **CLI da Gemi**. Em um vídeo anterior, comparei **Cloud for Sont** usando **CLAU code** com **CLI da Gemi** aqui. Nesse vídeo, **CLAU code** teve um desempenho melhor do que **CLI da Gemi**.

Então, vou dar as mesmas instruções exatas a ele. E uma forma de fazer isso é que **Cloud code** agora pode, de fato, suportar Kimi. Então Kimi, se você for a este repositório específico aqui no GitHub e clicar no **read me em inglês** que está aqui, você pode, de fato, definir sua **base URL da Anthropic** e sua **chave da API da Anthropic** para usar a **Moonshot API** em vez disso. Assim, você usa um modelo Kimi e pode continuar usando o **Cloud code** normalmente.

Eu realmente fui à plataforma **Moonshot API** ou **Moonshot**. Você pode ir à **Plataforma Moonshot AI**, acessar a **console** e depois criar sua conta continuando com o Google e, em seguida, pode ir a **chaves de API** e criar uma **chave de API** aqui e copiá-la.

Depois de fazer isso, basicamente o que queremos fazer é voltar a este export aqui, pressionar copiar e ir para nosso terminal. Então, realmente gosto de usar o **Warp terminal** aqui. Vou trazer isso aqui e eu tenho meu app rodando. Então, vou substituir a **chave da API da Moonshot** pela **chave Kimi**.

Vou gerar uma nova chave e chamá-la de **YouTube**. E essa chave vai expirar quando você estiver assistindo a este vídeo, então não tente usá-la. Então, posso pressionar **Enter** aqui e se eu digitar **Claude**, ele vai me perguntar, oh, você tem uma chave de API personalizada no seu ambiente, deseja usá-la? Vou pressionar **cima** e depois **sim**.

E agora está usando a **chave Kimi** e você pode ver que diz que tem sobreposições aqui. Então, está sobrepondo a base URL e está sobrepondo a **chave da API**. Basicamente, agora precisamos recarregar nossas contas, pois eu não tenho dinheiro nessa conta. Então, vou **recarregá-la** com **$10**.

E parece que os preços são, na verdade, bastante baratos para este modelo. Eu acho que é mais barato do que **Cloud for Sont** e não sei por que, mas os modelos chineses parecem ser realmente baratos. Então talvez o governo esteja subsidiando os modelos ou algo assim, ou eles são realmente eficientes ou têm como alguns **GPUs** tipo **Huawei** ou algo assim.

Mas, basicamente, é uma tendência onde esses modelos chineses parecem ser mais baratos do que os modelos ocidentais. E agora eu recarreguei minha conta e parece que eles me deram um extra de **$5** por ter recarregado minha conta com **$10**. E agora essa **chave da API** deve estar funcionando, então posso apenas escrever "quem é você" para garantir que esse modelo funcione corretamente.

E agora diz gerando, pensando, o que for, e parece que diz autenticação inválida. Então, vai tentar novamente. Após fazer algumas investigações, parece que a razão foi porque, de fato, a **API** aqui não deve ser a **API CN**, deve ser a **API AI**. Então, deve ser **API Moonshot AI** aqui porque eu encontrei isso nesta página.

Parece que este artigo ou este artigo aqui é mais destinado ao público chinês. E as chaves de API que funcionam no mercado chinês não funcionam no mercado fora da China. De qualquer forma, podemos pressionar **Enter** aqui e tentar mais uma vez e então dizer "quem é você?"

Então parece que diz que é **Cloud for Sont**, mesmo que a base URL tenha sido sobreposta para a **Moonshot API**. Então, eu acho que isso se deve ao fato de que o prompt que **CLAU code** usa é ligeiramente diferente. Então talvez possamos verificar se as solicitações estão realmente indo aqui, então podemos atualizar a página.

Se eu for ao meu saldo aqui, você pode ver que está lentamente caindo, o que, na verdade, significa que isso está sendo utilizado. De qualquer forma, vamos continuar com o comando e o prompt que vou usar é exatamente o mesmo que o último vídeo duas semanas atrás, que é sobre **CLI da Gemi** e **Cloud code**.

E basicamente, este prompt diz se você pode, em primeiro lugar, adicionar um sistema no aplicativo **EXPT** que me permita deslizar para a esquerda e para a direita ao selecionar um artigo para deslizar para um artigo antigo e um novo, o deslizar deve estar na ordem em que os artigos aparecem na página inicial.

E você pode, em número dois, substituir o **modelo 11 labs** na geração de fala para **Daily Digest** por este modelo. Em vez de usar um ID de voz **Casual guy**, e basicamente este aplicativo é um aplicativo para se manter atualizado com as últimas notícias de IA chamado **Tenza AI** e você pode baixá-lo usando o link na descrição abaixo.

Mas, basicamente, ele tem mais artigos na versão real porque esta é uma versão de teste que estou executando localmente. De qualquer forma, podemos pressionar **Enter** aqui e ver o que ele produz.

Enquanto esperava, encontrei esta página da plataforma do **Kimi Moonshot AI** e você pode ver que todas as solicitações estão realmente indo aqui. Assim, quando vou para detalhes de cobrança e detalhes de solicitações aqui, então posso ver se há tokens de entrada, tokens de saída e também tokens em cache.

E parece que terminei de fazer todas as alterações aqui e levou cerca de **913 segundos** para fazer, o que é cerca de **15 minutos**. E da última vez que usei **CLAU code** **Sont** ou como **Cloud for Sont** no **Cloud code**, levou **13 minutos** para fazer, então levou **dois minutos a mais**.

Então vamos ver se aqueles **dois minutos** realmente resultaram em um resultado melhor. Então, vou fechar o aplicativo aqui e depois reabri-lo para dar um novo início. Então, reiniciei a oferta de desenvolvimento e abri o aplicativo novamente e deslizando para a esquerda, deslizando para a direita.

O deslizar, na verdade, não funciona. Ele adicionou um deslizar para a esquerda para a próxima história, deslizar para a direita, e agora o rolar para baixo também não funciona. Então parece que o modelo realmente não fez um bom trabalho aqui. Talvez se eu clicar nisso, deslizar para a esquerda, deslizar para a direita. Adicionou as setas, mas não fez o deslizar funcionar por algum motivo.

Então, talvez se eu disser que o deslizar não funciona na verdade, fica na mesma página aqui. Se eu colocar nisso, vamos ver quais mudanças ele faz. Mas de qualquer forma, vamos verificar se ele fez as mudanças minimax corretamente.

Então, ele realmente substituiu por **replica**. Em vez disso, colocou um **token replica**. Na verdade, não conseguiu obter a versão correta, mas disse que substituiu pela versão real, mas este é um espaço reservado neste momento e ele conseguiu adicionar uma seção de emoção aqui, o que me surpreendeu bastante.

Então, podemos ir ao arquivo e corrigir o espaço reservado que adicionei por enquanto e ver se isso realmente funciona, assim podemos corrigir esse espaço reservado. Então, um pequeno problema feito aqui é que não utilizou a chave, então não checou nossas variáveis de ambiente corretamente.

Então, podemos apenas substituir a parte do token pela chave aqui e, se eu invocar a função aqui, podemos ver se realmente gera o resumo em áudio. Então, na verdade, depois de estender a janela de retrocesso aqui, parece que gerou algum áudio e vamos só ver se este é o que queremos e sim, e o resto da função continua normalmente.

E a coisa mais importante é que usou **replica** para gerar o áudio desta vez e então o carregou para nosso **bucket R2Real** aqui. Então, sim, está realmente muito bom aqui. Basicamente, tudo o que tivemos que fazer foi mudar o espaço reservado e depois corrigir o **token da API** para **chave da API**.

Agora vamos ver como ele se saiu. No problema do deslizar, parece que diz que terminou, então vamos apenas fechar o aplicativo e reiniciar o aplicativo novamente. E o deslizar ainda não está funcionando.

Então, sim, parece que ele tem dificuldades com tarefas relacionadas a **UI**. Parece que é melhor em tarefas mais simples onde está apenas trocando uma coisa por outra, em vez de adicionar novos recursos em grande escala.

E sim, basicamente **Cloud for Sont** fez um trabalho muito melhor ao implementar o deslizar para a esquerda e para a direita e não precisou de tanta orientação, e sabia adicionar o **gesto de manipulador de visualização** também que eu tive que instruí-lo a adicionar explicitamente.

Então, sim, acho que **Kimi K2** talvez **Kimi K3** será ainda melhor. Se você realmente quiser usá-lo, então pode usá-lo para tarefas muito mais simples, como trocar uma coisa por outra.

Mas eu acho que ainda não é adequado para bases de código de produção. Se você estiver interessado em quantos tokens foram usados até agora. Se formos para a visão geral aqui, diz que usou cerca de **40 centavos** do meu como, significa **39 centavos** e se eu fechar **Cloud code** e depois usar um contador de tokens.

Sim, então hoje basicamente disse que usou **250.000 tokens de entrada** e estou certo de que utiliza muitos tokens em cache, mas mostra zero porque talvez não esteja configurado ou configurado corretamente. Diz que se eu usar uma **API do Cloud code** em vez disso, teria sido **$1,24** porque esta está realmente configurada para uma **API do Cloud code**.

A precificação aqui, mas **Kimi K2** usou **$0,40** em vez disso, então está cerca de três vezes mais barato para esta tarefa específica. Mas não completou a tarefa e também levou muito mais tempo.

Então uma coisa que você pode considerar fazer para economizar tempo e custos é você pode seguir este artigo aqui e basicamente ensina como configurar um **Cloud code** com **Open Router** aqui e então usar o **Kimi K2** como modelo padrão com **Open Router** e então você pode definir regras de roteamento personalizadas, de modo que possa direcionar a um modelo diferente dependendo da complexidade da tarefa.

Então, diz que você pode adicionar mais modelos aqui você pode do **Open Router** e outros fornecedores no seu arquivo de configuração e criar regras de roteamento personalizadas para usar o melhor modelo para cada tarefa.

Então, talvez você possa configurar um sistema onde automaticamente vai para **Cloud for Sont** para tarefas específicas que são muito mais difíceis e então vai para **Kimi K2** para quaisquer tarefas mais fáceis. Mas novamente, para simplicidade, talvez você queira apenas usar **Cloud for Sont** para tudo.)
**Artigo de Referência:** [Ver no Viddo](https://viddo.pro/zh/video-result/759799b4-ff99-42d0-9077-1ab4e1fe63f4)

---


Eu recentemente assisti a um vídeo que falava sobre um novo grande modelo open source - **Kimi K2**, lançado pela Moonshot AI da China. Este modelo gerou bastante discussão online, então eu me certifiquei de assistir a toda a avaliação e o processo de comparação, organizando o seguinte conteúdo, na esperança de que ajude você a entender melhor as capacidades reais do Kimi K2.

---

**✨ Kimi K2 parece forte, mas também tem muitos pontos problemáticos.**

**🧠 Resumo Principal**

Kimi K2 se destaca em vários testes de benchmark, é de baixo custo e fácil de integrar, por isso foi uma vez exaltado como o melhor modelo open source. No entanto, em tarefas de desenvolvimento real, seu desempenho é claramente inferior ao Cloud for Sont: a implementação de funcionalidades de interação complexas não está à altura e a configuração da API é propensa a erros. Atualmente, ele é mais adequado para tarefas de substituição simples, e não para atender a demandas de produção complexas.

**💬 Frases de Destaque**

- “Modelos chineses são realmente baratos, pode ser que o governo subsidie, ou pode ser que sejam realmente eficientes.”
- “Kimi se destaca em tarefas de substituição, mas parece fraco ao adicionar novas funcionalidades.”
- “Cloud for Sont é não apenas mais rápido, mas também entende melhor o que os desenvolvedores realmente desejam.”

**🤔 Impressões Pessoais**

Sendo sincero, o que mais ressoa em mim ao assistir a tais vídeos é que sempre temos a tendência de sermos enganados por “classificações” e “números”. Kimi K2 é, de fato, impressionante no papel, mas uma vez que é colocado em projetos reais, problemas surgem um após o outro: variáveis de ambiente, falhas na configuração de roteamento da API, interação de interface não funcionando... Esses pequenos problemas aparentemente insignificantes são, na verdade, cruciais para determinar se um modelo pode ser implementado.

Lembro-me de que quando entrei em contato pela primeira vez com alguns grandes modelos open source, fui “enganado” pela documentação oficial várias vezes, e acabei dependendo do feedback da comunidade para resolver os problemas. A sensação atual é que, **não basta ver se ele pode executar benchmarks, é preciso ver se ele consegue executar suas funcionalidades.** O Kimi K2 pode ser monitorado, mas colocá-lo em produção agora ainda é um pouco cedo.

---

**🌟 Se você também deseja experimentar o Kimi, pode começar com tarefas simples, mas não deve esperar que ele seja uma “substituição universal”. O Cloud for Sont pode ser um pouco mais caro, mas pelo menos você sabe que é confiável.**

---

**Quer converter seus próprios vídeos em artigos?** Experimente **[Viddo](https://viddo.pro/)** - a plataforma impulsionada por IA que transforma conteúdo de vídeo em artigos envolventes e legíveis em minutos. Perfeito para criadores de conteúdo, educadores e profissionais que desejam reaproveitar seu conteúdo de vídeo para blogs, redes sociais ou documentação.

[🚀 Comece a Converter Vídeos com o Viddo](https://viddo.pro/)