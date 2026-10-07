## De quoi l'IA est-elle le nom ?

### Modéliser et automatiser l’écriture : de la combinatoire aux llm et IAG

![](img/stratchey-Monfort.png)<!-- .element: style="width:400px" -->

===




§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§

### Le malentendu des IA

Les IA génératives produisent un effet de fascination, qui tend à faire passer les outils grand public pour des "oracles". Comme le poète antique, les IAG produiraient des textes de manière magique. Au contraire, les générateurs de texte, depuis la combinatoire pionnière jusqu'aux IAG comme ChatGPT, reposent entièrement sur un principe de _modélisation_. C'est-à-dire sur l'idée que le langage, et plus encore certaines applications du langage (écrire une lettre d'amour, par exemple), peuvent être décomposés en un ensemble de règles précises, reproductibles à l'infini. Étudier les principes modélisants devient de fait un enjeu épistémologique et esthétique majeur. 

<!-- .element: style="font-size:1.9rem; text-align:justify" -->

===

Les IAG produisent un effet de fascination, qui tend à faire passer les outils grand public pour des "oracles". Comme le poète antique, les IAG produiraient des textes de manière magique. Au contraire, les générateurs de texte, depuis la combinatoire pionnière jusqu'aux IAG comme ChatGPT, reposent entièrement sur un principe de _modélisation_. C'est-à-dire sur l'idée que le langage, et plus encore certaines applications du langage (écrire une lettre d'amour, par exemple), peuvent être décomposés en un ensemble de règles précises, reproductibles à l'infini. Étudier les principes modélisants devient de fait un enjeu épistémologique et esthétique majeur. 



Les nouvelles générations d'IA reposent sur un système que l'on va qualifier de probabiliste. C'est-à-dire que lorsque vous poser une question à un chatbot, la réponse ne se base pas sur un raisonnement modélisé en amont, mais sur la probabilité de la réponse. Cela ne veut pas dire que les IAG n'ont pas de modèle, mais que le modèle se trouve ailleurs, dans les LLM, les vastes modèles de données entraînées, des modèles de langage. La modélisation est moins évidente, moins contrôlée et plus difficile à maîtriser ou discuter.


§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§

### IA : un terme qui ne veut rien dire 

L'émergence d'outils grand public comme ChatGPT a créé un emballement autour du terme "IA", qui renvoie à un concept théorique et pratique en vérité très ancien. Aujourd'hui, une grande confusion existe entre le terme "IA" et des outils de type chatbot servant d'interface à des systèmes génératifs (Chat GPT, Midjourney, etc.) qui créent du contenu (son, texte, image, code...).

<!-- .element: style="font-size:1.5rem; text-align:justify" -->


![](img/googleNgramIA.png)<!-- .element: style="width:600px" -->


===

On ne peut répondre à cette question est impossible sans comprendre préalablement de quoi on parle vraiment. J'imagine qu'ici vous avez toutes et tous utilisé un outil comme Chat GPT. Chat GPT est la pire chose pour comprendre ce qu'est une IA. 

L'émergence d'outils grand public comme ChatGPT a créé un appel d'air autour du terme "IA", qui renvoie à un concept théorique et pratique en vérité très ancien. Aujourd'hui, une grande confusion existe entre le terme "IA" et des outils de type chatbot servant d'interface à des systèmes génératifs (Chat GPT, Midjourney, etc.) 

De fait, je vous encouragerait à utiliser plutôt les termes d'IAG (Intelligence artificielle générative), qui désignent des technologies de création de contenu, de génération de contenus (texte, images, sons), aujourd'hui implémentées dans des outils grand public : copilot, chatGPT, etc. 

§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§

### D'accord, mais c'est quoi l'IA-G ?

===

Cette précision est intéressante, mais elle ne résoud pas le problème, c'est quoi une IA-G, comment ça marche ?

Le pb de l'IA c'est sans doute son nom, "IA", qui prête à bien des confusions et des fantasmes. 

§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§

#### "Intelligence artificielle" </br>une expression problématique et polémique

### Qu'est-ce que l'intelligence ? 

(vous avez 2h)

===

Le principal problème, c'est d'ailleurs l'intelligence, qui est un concept que l'on a du mal à saisir. 


L'idée d'une intelligence artificielle repose sur un projet scientifique et technique : être capable de modéliser les comportements humains afin de construire des outils, des machines, capable d'opérer les mêmes réalisations que les humains. 

C'est tout le principe des sciences de l'information et de la communication : comprendre comment fonctionne l'humain pour créer des machines qui permettent à celui-ci de mieux communiquer avec ses semblables. 


§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§

#### Générative ?
* Automatiser la production du texte
* Le mythe du texte qui s'écrit tout seul
* Une quête formaliste, poétique, ludique... 

<!-- .element: style="font-size:1.7rem; text-align:left" -->


...qui n'a pas attendu ChatGPT !

<!-- .element: style="font-size:1.7rem; text-align:right" -->


===



§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§
<!-- .slide: data-background-video="img/queneau.mp4" data-background-size="contain" -->


===


On a tjrs généré des textes.

L’OULIPO et la contrainte... 


§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§

### Définition générale

>GENERATEUR DE TEXTE : Un générateur de texte est un programme qui crée du texte à partir d’un ensemble de règles qui constituent une grammaire et d’un ensemble d’éléments préconstruits qui forment un dictionnaire. Le terme « texte » est pris, dans toute cette section sur la génération, dans le sens le plus classique de « tissu de mots».

>Philippe Bootz, *La littérature numérique*, 2007.

§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§

### Les générateurs combinatoires et automatiques

La génération de texte repose initialement sur un principe *combinatoire*. Un générateur combinatoire est un générateur de texte qui combine selon des règles algorithmiques spécifiques des fragments de textes préconstruits. Le générateur va ainsi tenter d’épuiser toutes les possibilités d’une structure à partir de différentes combinaisons des fragments entre eux. 

===



§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§
<!-- .slide: data-background-image="img/stratchey-Monfort.png" data-background-size="contain" -->



Source : [Émulateur de _Love Letters_ (1952), based on a work by Christopher Strachey, code by Nick Montfort](https://nickm.com/memslam/love_letters.html)


<!-- .element class="source"-->

===

§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§

## Atelier : étudier la modélisation de l'échange épistolaire amoureux chez Christopher Stratchey

![](img/atelier-love-letters.png)<!-- .element: style="width:200px" -->

§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§

![](img/balpe-name-4.jpg)<!-- .element: style="width:35%;float:right;margin-right:-1em;" -->


>Ce qui m’intéresse dans la génération, ce n’est pas le texte qui s’affiche. Ce texte-là est un moment comme un autre, on s’en fout. […] Ce qui m’intéresse, c’est cette capacité à produire à l’infini et à générer un univers que je ne suis pas capable de faire. C’est donc un autre substitut qui transmet une pensée qui dit. Peut-être est-ce un fantasme d’éternité. </br>Jean-Pierre Balpe

<!-- .element: style="width:40%;float:left;margin-left:-1em; font-size:1.4rem; text-align:justify" -->


===

Oeuvre dans un paradigme "contemporain" (emprunté à l'art contemporain)

Ce qui compte, c'est l'idée, c'est le projet. Oeuvres très réflexives. 

Comment on analyse ce type d'oeuvre ? 




§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§

### Les intelligences artificielles : 70 ans d'histoire

![](img/frise_ia_genially.png)<!-- .element: style="width:600px" -->



Source : [Carte interactive Histoire de l'IA (Ministère EN)](https://view.genially.com/64e486d0efc8e200198a554b)

<!-- .element class="source"-->



§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§

## Déjà trois printemps et deux hivers </br>(bientôt trois ?)

* Une proposition théorique (1950-60)
* Les systèmes "experts" (1980-1999)
* Les systèmes connexionnistes (2020)

<!-- .element: style="font-size:1.7rem; text-align:center" -->


#### </br>Autant de modélisations distinctes de "l'intelligence"

===


§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§

### Première vague : les années 1950 et les développements de l'informatique


![](img/turing.jpg)<!-- .element: style="width:40%;float:left;margin-right:-1em;" -->

![](img/MachineTuring-schemaCardon.png)<!-- .element: style="width:40%;float:right;margin-right:-1em;" -->

===

On peut poser pour date de naissance de l'IA les années 1950, avec les travaux du mathématicien Alan Turing souvent considéré comme le véritable père de l’informatique. Dans un article fondateur publié en 1936, il pose les bases théoriques d’une machine capable de tout calculer en décomposant l’information en deux valeurs, 0 et 1, qui constituera le langage en base binaire de l’informatique. Cette machine deviendra plus tard l'ordinateur.

Rappel : Turing n'a quasiment joué aucun rôle dans la construction effective des ordi. Mais il a conceptualisé une machine dite de Turing, une machine "abstraite" ou "théorique" qu’il a inventée pour expliquer la notion de "procédure mécanique" ou algorithme.

La machine de Turing = un automate imaginaire muni d’un programme et pouvant lire et écrire des caractères sur un ruban de longueur illimitée.


§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§

Le *test de Turing* (1950) : une définition de l'intelligence au miroir de la machine

Dans son article ["Computing Machinery and Intelligence" (*Mind*, 1950)](https://archive.org/details/MIND--COMPUTING-MACHINERY-AND-INTELLIGENCE), Alan Turing, considéré comme le "père de l'informatique", propose l'équation suivante : si un humain interragit avec une machine pendant 5 minutes, sans réaliser qu'il a en face de lui une machine, alors cette machine peut être qualifiée d'"intelligente". Son test est basé sur un jeu d'imitation, qui conduit à simuler, donc à modéliser l'intelligence humaine.


<!-- .element: style="width:40%;float:left;margin-left:-1em; font-size:1.4rem; text-align:justify" -->


![](img/Turing_intelligence.png)<!-- .element: style="width:35%;float:right;margin-right:-1em;" -->


=== 

Un peu plus tard, en 1950, Turing publie un article dans lequel il évoque le premier l’intelligence des machines
et invente un test, le test de Turing ou jeu de l’imitation.

>Dans ce test, une machine est dite intelligente quand elle parvient à tromper pendant cinq minutes un utili-
sateur discutant avec elle sans que cet utilisateur se rende compte qu’il échange avec une machine : la
machine imite si intelligemment le raisonnement des humains que ceux-ci s’y laissent prendre. Cardon



Évidemment, ce test -- qui ne pose pas encore le concept d'IA à proprement parler -- pose de nombreux problèmes philosophiques : on définit ici l'intelligence de la machine en fonction de celle (présupposée) de l'humain. Il y a fort à parier que d'un humain à l'autre, l'illusion d'interragir avec un humain est très variable.


§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§

### La conférence de Dartmouth et la proposition de John McCarthy (1956)

On doit l'invention du terme Intelligence artificielle à John McCarthy qui le propose tout d'abord lors de la Conférence de Dartmouth en 1956.

<!-- .element: style="width:45%;float:left;margin-left:-1em; font-size:1.4rem; text-align:justify" -->


![](img/dartmouth.jpeg)<!-- .element: style="width:40%;float:right;margin-right:-1em;" -->


===

On doit l'invention du terme Intelligence artificielle à John McCarthy qui le propose tout d'abord lors de la Conférence de Dartmouth en 1956.

La conférence de Dartmouth (Dartmouth Summer Research Project on Artificial Intelligence) est un atelier scientifique organisé durant l'été 1956, qui est considéré comme l'acte de naissance de l'intelligence artificielle en tant que domaine de recherche autonome : elle réuni vingt chercheurs dont Claude Shannon, Nathan Rochester (en), Ray Solomonoff, Trenchard More (en), Oliver Selfridge (en), Allen Newell et Herbert Simon.

Considéré comme l'un des pères de l'IA, John McCarthy développe dans son Laboratoire de l'Université Standford une conception particulièrement optimiste (ou effrayante, c'est selon) de l'IA : McCarthy considère que l'on peut rendre les machines intelligentes, qu'elles seront un jours capable de parler, raisonner, de nous remplacer dans des tâches complexes. Selon lui, elles pourraient même se voir dotées d'une conscience... 

Cette utopie que l'on a souvent moquée, qui a été longtemps considérée comme impossible, revient aujourd'hui sur le devant de la scène.


§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§

### Une approche "symbolique"
Les premières conceptions de l'IA s'emploient à programmer la machine pour qu'elle puisse reproduire les formes symboliques et logiques du raisonnement dit naturel. La notion d'"intelligence" est alors elle-même située : il s'agit de transférer à la machine une capacité à raisonner calquée sur le modèle humain. 

<!-- .element: style="font-size:1.7rem; text-align:justify" -->


Mais savons-nous vraiment comment nous pensons ? 

<!-- .element: style="font-size:1.7rem; text-align:justify" -->


===

Le projet d’intelligence artificielle des deux premières vagues, celle des années 1960 et celle des années 1980
était d’ordre « symbolique ». 

Chez les premiers concepteurs et chercheurs ayant travaillé autour de l’intelligence artificielle, tous les efforts ont été mis en oeuvre afin de transférer vers la machine une capacité à raisonner calquée sur le modèle humain. On voulait vraiment que la machine puisse penser comme nous (ou, plus exactement et plus intéressant, quoi que plus tordu : comme nous pensons penser). 

Selon cette première stratégie, il s'agissait alors de programmer la machine pour qu'elle puisse reproduire les
formes symboliques et logiques du raisonnement dit naturel. 

Dans ce modèle, on a une définition de l'intelligence qui est en fait totalement calquée sur celle de l'humain, et son raisonnement logique séquentiel.


§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§

### Seconde vague : les années 1980 et le développement des "systèmes experts"

Un système expert est un outil informatique d’intelligence artificielle, conçu pour simuler le savoir-faire d’un spécialiste, dans un domaine précis et bien délimité, grâce à l’exploitation d’un certain nombre de connaissances fournies explicitement par des experts du domaine.

<!-- .element: style="width:45%;float:left;margin-left:-1em; font-size:1.4rem; text-align:justify" -->


![](img/deepBlueKasparov.jpeg)<!-- .element: style="width:40%;float:right;margin-right:-1em;" -->


====

Concrètement, cette approche s'est traduite dans les années 1980 par la conception et l'expérimentation de « systèmes-experts ».

Un système expert est un programme informatique conçu pour simuler le savoir-faire d’un spécialiste, dans un domaine précis et bien délimité, grâce à l’exploitation d’un certain nombre de connaissances fournies explicitement par des experts du domaine.

Concrètement, des programmeurs font ingérer au programme des ensembles très sophistiqués de règles de raisonnement, afin qu'ils solutionnent des problèmes.

Il s'agit plus précisémment de scénariser très finement dans un programme l'ensemble des aspects possibles d'un processus, afin de l'automatiser.

L’IA symbolique utilise le **raisonnement formel et la logique** ; c’est une approche cartésienne de l’intelligence, où les connaissances sont encodées au départ à partir d’axiomes desquels on déduit des conséquences.


Voyons ensemble l'un des exemples de système expert les plus médiatisés : celui de Deep Blue, l'ordinateur joueur d'échec.

§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§
<!-- .slide: data-background-video="img/GasparovDeepBlue.mp4" data-background-size="contain" -->


§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§

### Deep blue, système-expert du jeu d'échec

![](img/ModeleExpertSchema.png)

===

Deep blue est un système expert conçu pour gagner aux échecs: il simule le raisonnement et le savoir-faire du joueur d'échec, en piochant dans un ensemble de règles et de connaissances préétablies concernant le jeu d'échec.

Comme tout système expert, Deep blue est composé de trois éléments :
- base de faits à disposition = une banque de scénarios comprenant le déroulement de différentes parties (ici, un joueur a déplacé sa tour, puis son fou, puis il a gagné)
- base de règles imposées = les règles du jeu d'échec (une tour peut se déplacer horizontalement ou verticalement, en longue portée, mais sans pouvoir sauter au-dessus d'une autre pièce)
- le moteur d'inférence = outil permettant au système d'appliquer les règles et de trier les faits afin de résoudre le problème.


§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§
<!-- .slide: data-background-video="img/GasparovBattu.mp4" data-background-size="contain" -->

===

Que s'est-il passé ? 

Dans un article de *The Conversation*, Nicolas Sabouret revient sur cet épisode décisif de l'histoire des relations homme-machine, qui fût également un grand moment de télévision.

>Garry Kasparov a toutes ses chances et il le prouve en remportant la première manche. Mais dans la deuxième, tout bascule. La machine prend l’avantage après un 36e coup qui empêche Kasparov de menacer son roi. Le champion d’échec est alors mis en difficulté, la machine prend progressivement l’ascendant. Mais soudain, au 44e coup, Deep Blue commet une erreur. Une erreur terrible, inexplicable, qui aurait pu sauver Kasparov en lui assurant une partie nulle ! La machine déplace son roi sur la mauvaise case et, au lieu de s’assurer une victoire, elle offre à son adversaire une porte de sortie.

>Pourtant, Kasparov ne croit pas à l’erreur de la machine. Il pense qu’il n’a pas vu quelque chose, que la machine ne peut pas se tromper. Pas si grossièrement. Il ne saisit pas cette opportunité qui lui est donnée. Il se dit peut-être qu’il a loupé quelque chose. Au 45e coup, il abandonne la partie.

>La réaction de Garry Kasparov immédiatement après ce match est intéressante. Il accuse l’équipe de Deep Blue d’avoir triché, d’avoir fait appel à un joueur humain pour le battre. Pour le champion du monde, aucune machine n’aurait pu à la fois jouer l’excellent 36e coup et commettre cette erreur grossière au 44e. C’est donc forcément un joueur humain qui a dicté ce coup à Deep Blue. Comme beaucoup de non-spécialistes, Kasparov ne croit pas que la machine puisse être à ce point faillible. Il est à mille lieues de la vérité.

§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§

>La réaction de Garry Kasparov immédiatement après ce match est intéressante. Il accuse l’équipe de Deep Blue d’avoir triché, d’avoir fait appel à un joueur humain pour le battre. Pour le champion du monde, aucune machine n’aurait pu à la fois jouer l’excellent 36e coup et commettre cette erreur grossière au 44e. C’est donc forcément un joueur humain qui a dicté ce coup à Deep Blue. Comme beaucoup de non-spécialistes, Kasparov ne croit pas que la machine puisse être à ce point faillible. Il est à mille lieues de la vérité.

<!-- .element: style="font-size:1.7rem; text-align:justify" -->


Source : Nicolas Sabouret, "Pourquoi l’intelligence artificielle se trompe tout le temps", *The Conversation*, 2020.

<!-- .element: class="source" -->


§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§

### La théorie de la complexité et l'approche heuristique

>s’il est impossible d’avoir une solution exacte en un temps raisonnable, rien n’interdit d’écrire un programme qui ne calcule pas la solution exacte, mais une autre solution, a priori moins bonne. Les chercheurs en intelligence artificielle appellent ce type de calcul une « heuristique ». L’objectif de ces programmes est alors de calculer une solution raisonnablement correcte au problème, dans un temps de calcul qui reste acceptable. 

<!-- .element: style="font-size:1.7rem; text-align:justify" -->


Source : Nicolas Sabouret, "Pourquoi l’intelligence artificielle se trompe tout le temps", *The Conversation*, 2020.

<!-- .element: class="source" -->


===

Kasparov, comme la plupart d'entre nous, est victime d'un paradoxe d'objectivation de la machine : parce que la compétence de la machine est située dans le domaine du calcul (un ordi est une sorte de super calculateur), on a l'impression qu'elle ne peut se tromper, qu'elle n'a pas de limite à sa puissance de calcul. Cette croyance est paradoxale, car en même temps on cherche, comme Kasparov, à "battre" la machine sur son propre terrain, celui du calcul. 

Pourtant, la machine est bien faillible, et si elle l'est, c'est en raison de sa limite à pouvoir tout calculer : cette limite renvoie à ce que les chercheurs appellent la théorie de la complexité.

La théorie de la complexité est le domaine des mathématiques, et plus précisément de l'informatique théorique, qui étudie formellement le temps de calcul, l'espace mémoire (et plus marginalement la taille d'un circuit, le nombre de processeurs, l'énergie consommée…) requis par un algorithme pour résoudre un problème algorithmique. 

Dans le cas des échecs :
>Pour déterminer à coup sûr le coup gagnant, il faudrait regarder toutes les parties possibles, chaque joueur jouant alternativement l’une de ses 16 pièces sur le plateau de 64 cases. Au milieu du XXe siècle, le mathématicien Claude Shannon a estimé qu’il y a environ 10 puissance 120 parties d’échecs possibles. Cela s’écrit avec un 1 suivi de 120 zéros. [...] Même avec des machines dont la puissance de calcul continuerait de doubler tous les deux ans, comme le stipule la loi de Moore, nous sommes encore très loin de construire un ordinateur qui serait capable d’énumérer toutes ces parties avant de tomber en ruine (sans même parler de les jouer). (Sabouret) 

En d'autres terme, pour trouver comment gagner à coup sûr une partie d'échec, la complexité est trop grande : "il est impossible, quelle que soit la méthode utilisée, de construire un programme informatique qui y réponde sans y passer des millénaires." (Sabouret) 

§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§

>Le principe des programmes d’IA est donc de calculer des solutions pas trop mauvaises à des problèmes dont on sait, mathématiquement, qu’ils ne peuvent pas être résolus de façon exacte dans un temps de calcul raisonnable. Et pour cela, il faut accepter de faire parfois des erreurs. De ne pas avoir toujours la meilleure réponse, ou une réponse complètement correcte. C’est pourquoi tout programme d’IA fait forcément des erreurs. C’est inévitable et c’est même ce qui les caractérise. 

<!-- .element: style="font-size:1.7rem; text-align:justify" -->


Source : Nicolas Sabouret, "Pourquoi l’intelligence artificielle se trompe tout le temps", *The Conversation*, 2020.

<!-- .element: class="source" -->


===

Pour Sabouret, les solutions imparfaites sont donc le propre de L’intelligence artificielle 

>Le principe des programmes d’IA est donc de calculer des solutions pas trop mauvaises à des problèmes dont on sait, mathématiquement, qu’ils ne peuvent pas être résolus de façon exacte dans un temps de calcul raisonnable. Et pour cela, il faut accepter de faire parfois des erreurs. De ne pas avoir toujours la meilleure réponse, ou une réponse complètement correcte. C’est pourquoi tout programme d’IA fait forcément des erreurs. C’est inévitable et c’est même ce qui les caractérise. 


§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§

### La limite des systèmes experts, ou le second hiver de l'IA

>Qu’est-ce qui n’allait pas dans l’idée d’une machine raisonnant logiquement ? Tout simplement, que le fonctionnement de la pensée humaine est impossible à reproduire. Nous prenons très rarement des décisions à partir de règles de raisonnement que nous saurions expliciter. Nos jugements sont aussi faits d’émotions, d’éléments irrationnels, de spécifications liées au contexte et de toute une série de facteurs implicites ; bref, la décision ne se laisse pas capturer par des règles formalisables. 

>Pour jouer aux échecs ou au go, la machine raisonne dans un monde clos, borné, simple et n’a pas à être attentive à la variabilité des situations. Mais la société ne ressemble pas à un échiquier sur lequel se déplacent des pièces.

<!-- .element: style="font-size:1.5rem; text-align:justify" -->


Source : Dominique Cardon, *Culture numérique*, Presses de Science Po, 2019.

<!-- .element: class="source" -->



===

La piste des systèmes experts, très en vogue dans les années 1980, va peu à peu prendre du plomb dans l'aile. En raison de leur coût de développement, les systèmes experts resteront cantonnés à certains domaines industriels: système de signalisation des trains, système de guidage des avions... Mais ne feront pas l'objet d'une adoption massive dans l'ensemble des secteurs industriels, des services et de la société.

Deep blue reste une curiosité des années 1990, développée par IBM qui s'en sert comme une vitrine médiatique autant que comme une expérimentation.


>L’idée de faire raisonner la machine n’a cependant jamais fonctionné correctement.
Les promesses des systèmes-experts n’ont pas été tenues, les entreprises qui les ont développés ont fait faillite, les financements de recherche se sont taris. L’intelligence artificielle est entrée dans son second hiver et, à partir des années 1990, elle était moribonde.


>Qu’est-ce qui n’allait pas dans l’idée d’une machine raisonnant logiquement ? Tout simplement, que le fonctionnement de la pensée humaine est impossible à reproduire. Nous prenons très rarement des décisions à partir de règles de raisonnement que nous saurions expliciter. Nos jugements sont aussi faits d’émotions, d’éléments irrationnels, de spécifications liées au contexte et de toute une série de facteurs implicites ; bref, la décision ne se laisse pas capturer par des règles formalisables. 


§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§

## Troisième vague : le modèle connexionniste des années 2020

Contrairement à la méthode symbolique qui s'évertuait à vouloir reproduire l'intelligence humaine en faisant ingérer à la machine des programmes complexes, à partir d'une modélisation toujours insatisfaisante (car le propre de l'humanité est d'être imprévisible, pour le meilleur ou pour le pire), la méthode connexionniste consiste à **laisser la machine "apprendre tout seule" à partir d'un immense jeu de données**. Cet entraînement peut être "supervisé", ou réalisé en autonomie (_deep learning_). 


<!-- .element: style="font-size:1.7rem; text-align:justify" -->

![](img/ia-symboliqueVSconnexionniste.jpg)


===

Mais une autre conception, très différente, de la machine intelligente a aussi pris forme au cours de l’histoire de l’informatique : au lieu d’essayer de la rendre intelligente en lui faisant ingérer des programmes, il serait préférable de la laisser apprendre toute seule à partir des données. La machine apprend directement un modèle des données, d’où le nom d’apprentissage artificiel (machine learning) donné à ces méthodes.

C'est là le fondement de la méthode dite "connexionniste".

Là où le modèle symbolique s’appuie sur de la logique formelle et l’exploitation de connaissances existantes pour résoudre des problèmes (inspiration = logique aristotélienne), l'approche connexionniste se veut plus empirique, basée sur l’observation et l’exploitation des sens, sur des méthodes statistiques, sur la reconnaissance de formes.

Ce qu'il est important de retenir ici, c'est le changement profond d'approche et de paradigme, parfaitement résumé par l'informaticien Luc Julia dans son ouvrage *L’intelligence artificielle n’existe pas* paru en 2019 aux Éditions First : ce n’est pas l’intelligence qui caractérise les systèmes d’IA d’aujourd’hui, mais leur capacité de reconnaissance grâce à l’apprentissage machine.
L'apprentissage profond (*deep learning*) est une approche possible du *machine learning*, à laquelle on doit les récents progrès de l'IA. Il s'agit d'une approche dite "connexionniste", inspirée de la structure et du fonctionnement des réseaux de neurones biologiques. 

§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§

Cette méthode, dite par apprentissage, repose sur une technologie appelée les "réseaux de neurones". L'approche connexionniste a été formulée dès 1943 par Warren McCulloch et Walter Pitts, mais elle était restée marginale en raison de limitations techniques. Le développement de machines plus rapides et puissantes ces dernières années, mais surtout l'accumulation de données (ce que l'on appelle aussi le _big data_) a changé la donne. 

<!-- .element: style="width:55%;float:right;margin-right:-1em; font-size:1.7rem; text-align:justify" -->


![](img/Neural_network.svg)
<!-- .element: style="width:40%;float:left;margin-right:-1em;" -->


§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§


#### Le modèle connexionniste provoque un changement de paradigme, en nous faisant passer d'une approche _modélisante_ à une approche statistique et probabiliste (fondées sur des modèles malgré tout : les llm)


===



<!--

si j'utilise chatGPT et que je lui dis pas content, il prend ça comme une donnée de renforcement.

Bouton like = donnée de renforcement.

embedding = vectorisation des mots. Positionnement d'un mot par rapport aux autres. Plus les mots sont proches, plus ils ont des chances d'avoir des significations similaires, ou de s'inscrire dans un même contexte sémantique (une même relation contextuelle). 

un réseau de neurone est capable de trouver les relations + compresser tt.

Transformer Attention is all you need.
Transformer = ajouter du poids aux éléments pertinents pour réduire le flou du gradient (= effondrement du sens).
Transformer introduit de l'info pertinente, en déterminant le degré d'importance (donc des biais?).

-->

Un générateur fondé sur un modèle place les mots les uns à la suite des autres, en choisissant le terme qui, statistiquement, a le plus de chance d'apparaître après celui qui le précède. Le modèle connexionniste est fondé sur une logique **probabiliste**, elle-même rendue possible par un principe de *vectorisation* de quantités massives de données (textuelles, graphiques, etc.).

§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§

### La vectorisation : vers une modélisation spatiale des termes (*vs* sens)

Il ne s'agit pas de "comprendre" (c'est-à-dire de saisir l'articulation entre référent/signifié/signifiant), mais de positionner les mots dans un espace et d'évaluer des distances. Plus des mots sont proches, plus on peut dire qu'ils signifient quelque chose de similaire.

<!-- .element: style="width:35%;float:left;margin-left:-1em; font-size:1.4rem; text-align:justify" -->


![](img/Word-Vectors.webp)<!-- .element: style="width:65%;float:right;margin-right:-1em;" -->


===

embedding = vectorisation des mots. Positionnement d'un mot par rapport aux autres. Plus les mots sont proches, plus ils ont des chances d'avoir des significations similaires, ou de s'inscrire dans un même contexte sémantique (une même relation contextuelle). 

Là où le système expert partait de l'essence d'un concept, et pouvait être capable de remonter la chaîne de décision et de description (via l'algo notamment), le llm ne sait pas ce qu'est le concept. Il repart du terme (par exemple un chat), et le place dans un environnement spatial dans lequel il sera entouré d'autres termes. 

Là où le système expert cherche à encoder le sens, le llm manipule de l'espace, de la dimension.


§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§

En conséquence, lorsque vous utilisez une IAG, vous lui posez une question ou vous lui donnez une instruction en vous inscrivant dans un régime de signification. La réponse de l'IAG, en revanche, s'appuiera sur des probabilités, soit sur un calcul de proximité entre des objets vectorisés.  

§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§

### Comment aimez-vous apprendre ?  

* Approche symbolique : vous préférez que l'on vous donne des consignes précises, après avoir suivi un cours magistral en amont vous présentant des règles de composition d'une dissertation, que vous allez ensuite vous-même appliquer.
* Approche connexionniste : vous préférez lire plusieurs exemples de dissertations, en tâchant de comprendre vous-mêmes comment elles fonctionnent pour les imiter.


§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§

## La problématique des outils fondés sur les IAG

Et si le problème n'était pas l'IAG, mais plutôt les entreprises qui produisent aujourd'hui les IAG les plus utilisées ?

>La représentation de ce que serait l’« IA » se trouve fréquemment façonnée par quelques applications emblématiques et fortement médiatisées. Le terme en vient alors à désigner moins la pluralité des approches, des techniques et des usages qu’un nombre limité de produits développés par de grandes entreprises technologiques. La compréhension d’un phénomène complexe se trouve ainsi largement structurée par les stratégies de visibilité et de communication d’acteurs privés. </br>(Marcello Vitali-Rosati)

===

MVR : 

>Dans de nombreux discours médiatiques, politiques et parfois académiques, l’expression « IA » tend à fonctionner comme un raccourci pour désigner un ensemble très hétérogène de transformations contemporaines : mutations du travail, nouvelles pratiques culturelles, reconfigurations économiques, enjeux géopolitiques ou encore transformations des régimes de connaissance. Le terme est souvent mobilisé pour nommer et interpréter des phénomènes qui dépassent largement les technologies auxquelles il renvoie au sens strict. Cette extension sémantique n’est pas sans conséquence. En faisant de l’« IA » la catégorie privilégiée pour penser notre époque, on risque de réduire la diversité des acteurs, des pratiques et des infrastructures qui participent à ces transformations.

Par ailleurs, de façon symétrique la représentation de ce que serait l’« IA » se trouve fréquemment façonnée par quelques applications emblématiques et fortement médiatisées. Le terme en vient alors à désigner moins la pluralité des approches, des techniques et des usages qu’un nombre limité de produits développés par de grandes entreprises technologiques. La compréhension d’un phénomène complexe se trouve ainsi largement structurée par les stratégies de visibilité et de communication d’acteurs privés