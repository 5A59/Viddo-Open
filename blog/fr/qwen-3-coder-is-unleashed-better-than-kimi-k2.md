# QWEN 3 CODER est Dévoilé... meilleur que KIMI K2

J'ai récemment regardé une vidéo et je l'ai trouvée assez instructive. Pour mieux comprendre et partager le contenu, j'ai utilisé **[Viddo](https://viddo.pro/)** pour convertir la vidéo en un article structuré, qui a servi de référence pour cette analyse.

**Vidéo Originale :** [Regarder la Vidéo](> - Alibaba a dévoilé le modèle de codage open-source Quin 3 coder, un nouveau modèle puissant.
> - Il dispose d'un modèle massif de 480 milliards de paramètres appelé Powerful1.
> - Le Quin 3 coder excelle dans divers benchmarks et surpasse les concurrents.
> - Un outil en ligne de commande pour le codage agentique, Quin Code, est maintenant disponible.
> - De nouvelles méthodes d'apprentissage par renforcement améliorent la performance dans des tâches de codage du monde réel.

Alibaba vient de lancer la prochaine grande innovation : **Quin 3 coder**. Juste au moment où le monde s'habitue à **Kimi K2**, l'autre grand modèle de codage open-source, Alibaba annonce le **Quin 3 coder**, qui est disponible en plusieurs tailles. 

Mais le modèle phare, le **Powerful1**, est le Quin 3 Coder 480B A35B instruct, ce qui signifie qu'il s'agit d'un **modèle de 480 milliards de paramètres**. Il est construit avec un mélange d'experts, donc seulement **35 milliards de paramètres sont actifs lors de chaque appel**. "Instruct" signifie qu'il s'agit de notre mode assistant amical et utile par rapport au modèle de base qui ressemble un peu plus à un modèle de complétion de texte.

Nataly prend en charge **256k de contexte** et peut monter jusqu'à **1 million**. Et comme vous pouvez le constater ici, les benchmarks semblent excellents maintenant. On ne peut pas toujours faire confiance aux benchmarks, alors laissez-lui quelques jours à mesure que tout le monde met la main dessus et le teste. 

Mais **Kimi K2** était, de toutes les sources, extrêmement impressionnant. Le **Gwin 3 coder** surpasse facilement Kimi K2. Non seulement cela, mais il est comparable et compétitif avec **Claud Sounded**. Il bat également **GPT 4.1 d'OpenAI** et obtient un score très solide sur l'utilisation de navigateurs agentiques ainsi que sur l'utilisation d'outils agentiques. Encore une fois, seul Cloud Sounded 4 parvient à le devancer dans certains cas.

L'équipe **Gwin** promet qu'il fonctionne de manière transparente avec les meilleurs outils de développement de la communauté et qu'il peut être utilisé partout dans le monde numérique. Le codage agentique dans le monde, et ils ne plaisantent pas à ce sujet. 

En parallèle du modèle, ils mettent en open source un outil en ligne de commande pour le codage agentique appelé **Quin Code**. Il est dérivé du **code de Google Gemini**. Comme vous pouvez le voir ici, il est open source sous **licence GitHub Apache 2.0**. Cela ressemble beaucoup au code de claw et a été adapté avec des invites personnalisées et des protocoles d'appel de fonctions pour libérer pleinement les capacités du Quin 3 coder sur des tâches de codage agentiques. 

Donc, fondamentalement, **Quin code** est juste le **Gemini CLI** adapté. Il a été modifié pour utiliser les modèles Quwin. Vous pouvez également utiliser les **modèles Quin 3 coder** avec le **cloud code**. Beaucoup de gens préfèrent le cloud code, donc vous pouvez facilement utiliser les modèles Quin 3 Codder avec le Cloud code. Vous pouvez l'utiliser avec **K Clin**. Je laisserai ces liens ci-dessous.

L'un des grands sujets de discussion en ce moment est **l'apprentissage par renforcement**. Prendre ces modèles et les emmener dans un gymnase RL pour leur apprendre à effectuer diverses compétences comme le codage, les mathématiques, etc. Comme je le dis ici, faire évoluer l'apprentissage par renforcement du code est difficile à résoudre, mais facile à vérifier comme vous pouvez le voir ici.

Alors qu'ils augmentent les étapes de formation à mesure qu'ils forment ce modèle, il progresse dans tous les domaines de performance différents, comme la génération de code, le développement de logiciels, le codage compétitif, le **suivi des instructions SQL**, etc. Ils critiquent un peu le laboratoire frontier en disant que contrairement à la focalisation prédominante sur la génération de code de niveau compétition dans la communauté, nous croyons que toutes les tâches de code sont naturellement bien adaptées à un apprentissage par renforcement à grande échelle, axé sur l'exécution. 

C'est pourquoi nous avons élargi la formation RL du code sur un ensemble plus large de tâches de codage du monde réel. Fondamentalement, ils disent que plutôt que d'essayer de maximiser ces quiz et tests, ces questions de style compétition, ils forment réellement ce modèle à faire **du vrai travail dans le monde réel**. 

En automatisant l'échelle et les cas de test de diverses tâches de codage, nous avons créé des instances de formation de haute qualité et avons réussi à débloquer le plein potentiel de l'apprentissage par renforcement. Cela a non seulement considérablement boosté les taux de succès d'exécution de code, mais a également entraîné des gains pour d'autres tâches. 

Cela signifie que cette approche se généralise. Nous avons vu dans d'autres documents publiés que par exemple, le fait de le former à faire du code améliore sa capacité à résoudre des problèmes mathématiques, même s'il n'a pas été explicitement formé à cela. Il semble certainement que leur approche se généralise à travers beaucoup de tâches différentes. Espérons qu'ils publieront un document plus tard qui décrira comment ils abordent cela. 

Mais ici, ils mentionnent que leur approche utilise des tâches difficiles à résoudre et faciles à vérifier comme un terrain fertile pour l'apprentissage par renforcement à grande échelle.

Voici un graphique de sa performance sur le **SUI bench Verified**, donc c'est la taille du modèle. Les modèles à droite sont plus grands, les modèles à gauche sont plus petits et plus vous montez, meilleur est le score sur le subench vérifié. SWbench contient **500 problèmes Python vérifiés par des humains sur GitHub** examinés par des humains et confirmés comme résolvables. 

Comme vous pouvez le voir ici, **Quin 3 coder** est au-dessus de la plupart des autres modèles que nous avons vus, y compris **Kimmy K2**, **GPT 4.1**, même **Gemini 2.5 Pro Preview**. Seul **Cloud Sont 4** les devance légèrement, tout en étant un modèle beaucoup plus grand. Pour un modèle de taille modérée, rien n'est même proche de lui en termes de performance. **Kimmik K2** est beaucoup plus grand bien qu'il ne soit pas aussi bon.

Il est important que, pour des **tâches d'ingénierie logicielle du monde réel** comme celles dans le **SUI bench verified**, le Quin 3 coder doit s'engager dans des interactions multi-tours avec l'environnement impliquant la planification, l'utilisation d'outils, la réception de retours et la prise de décisions. Ce n'est pas un simple format question-réponse. C'est une tâche à long terme qui inclut la planification et les retours.

Quel était leur truc pour amener ce modèle à exceller dans ces tâches à long terme ? Ils indiquent qu'au cours de la phase post-formation du **Quint threeoder**, ils ont introduit **l'RL à long terme**. Ils s'y réfèrent comme **Agent RL**. C'était pour encourager le modèle à résoudre ces tâches du monde réel à travers des interactions multi-tours utilisant des outils.

C'est intéressant. Le défi clé dans quelque chose comme cet **Agent RL** réside dans l'échelle de l'environnement. Pour y remédier, ils ont construit un **système évolutif** capable de faire fonctionner **20 000 environnements indépendants en parallèle**. Ils ont fait cela en utilisant **l'infrastructure cloud d'Alibaba**. 

Cela leur a permis d'avoir l'échelle nécessaire pour faire tourner ce pipeline d'apprentissage par renforcement massif. Et c'est ce qui a permis au **Coin 3 Coder** d'atteindre des performances à la pointe parmi les modèles open source, sans—et c'est important de le noter—sans mise à l'échelle du temps de test. Ce n'est pas un modèle de raisonnement. Contrairement au **DeepSeq R1** ou au **Gemini 2.5 Pro Preview**, c'est non-raisonnement.

Certaines des démonstrations qu'ils ont publiées incluent la démolition et la démonstration de bâtiments. Voici comment utiliser **Quinn avec Klein**, ils ont réalisé une explosion interactive de couleurs. Ça a l'air plutôt sympa. 

Nous allons devoir tester certaines de ces choses : **visualisation de terrain 3D Google Earth**, une petite application pour tester votre vitesse de frappe, une balle rebondissante en rotation, un hypercube, une simulation de système solaire super frénétique, et un jeu de duo. C'est disponible sur comment vous faire face et discuter avec **Quen AI**.

Je vais faire un tour complet de tests sur cette chose, mais pour l'instant, voici juste quelques tests rapides que j'ai réalisés. L'un d'eux est de faire une simulation d'un immeuble de bureaux avec des bureaux et des pièces à l'intérieur. J'ai essayé de lui faire créer des **fenêtres transparentes** à l'extérieur, mais il n'a pas pu effectuer la transparence. Elles étaient soit très opaques, soit complètement non transparentes.

Mais il a réussi à créer, vous savez, les pièces à l'intérieur avec des bureaux et des ordinateurs et tout ce qui s'ensuit. Une lumière semble être une lumière dans chaque pièce. Donc jusqu'à présent, au début, ce n'est pas si mal. Je veux dire, c'est plutôt bon pour le premier essai.

J'ai également créé un petit **jeu de drone volant** où vous êtes capable de piloter un drone autour de la ville. Je ne peux pas me plaindre. C'est plutôt bien. Je veux dire, les touches sont un peu étranges, mais je l'aime bien jusqu'à présent. Ça prend un peu de temps pour s'y habituer, mais une fois que vous êtes capable de gérer l'accélération, vous pouvez voler et ce n'est pas mal pour un premier essai.

Nous avons un **clone de Minecraft**. Où serions-nous sans un clone de Minecraft ? Vous êtes capable de placer des blocs et de construire et de vous déplacer. Pas trop mal, j'ai pu le faire assez facilement. 

Alors regardez ça, faites-moi savoir ce que vous en pensez. Plus de tests et de cas d'utilisation arrivent très bientôt. De plus, quelqu'un a fait ce petit hack pour **clot code** et pourquoi n'avons-nous pas eu ça tout le temps ? 

À travers la liste de tâches. Création de la **liste de choses à faire**. Monsieur. Début des ajustements de code Python. Faites-le ainsi numéro un. Travaillant à travers la liste de tâches. En fait, cela pourrait devenir ennuyeux assez rapidement. 

Et je dois dire que je ne m'attendais pas à ce que l'IA open source soit si bonne. Je pense que nous espérions qu'elle serait, disons, au maximum quelques années derrière les laboratoires de pointe. Maintenant, cela ressemble à des mois. **Quelle époque pour être en vie.**
**Article de Référence :** [Voir sur Viddo](https://viddo.pro/zh/video-result/de3fa85b-5156-4186-a39d-60c839fb0371)