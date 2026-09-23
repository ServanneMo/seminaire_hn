##### Chapitre 2

## De la datafication à l'algorithmisation de la culture

### Calculer, modéliser, prédire, prescrire les usages et les goûts du public  

![](img/tousCalcules.gif)<!-- .element: style="width:400px" -->

===
Nous allons poursuivre notre portrait du récepteur moderne : l'internaute ou usager des medias numériques.

L'angle que j'ai choisi d'aborder avec vous aujourd'hui, est celui de l'influence des algorithmes sur la constitution de l'offre culturelle, mais également des choix des usagers. Je vais poser quelques éléments de définition tout à l'heure, mais je voudrais d'abord justifier ma démarche : pourquoi est-ce si important de comprendre le fonctionnement d'un algorithme ?

Tout simplement parce que ce sont les algo qui structurent l'ensemble des espaces numériques, qu'il s'agisse du web, des applications ou des plateformes de contenus. On pourrait comparer les algo à des "architectes" des espaces numériques. Les algo structurent les environnements numériques en établissement des règles d'organisation valables pour traiter la masse des données qui circulent chaque jour.

Concrètement, il s'agit de répondre aux questions suivantes : pourquoi, lorsque je tape un mot sur mon moteur de recherche, c'est tel résultat qui tombe en premier ? Est-ce que mon voisin aura exactement le même résultat ? Comment Netflix ou Youtube ou Deezer élaborent-ils une sélection de contenus adaptés à mes goûts ? Comment mesure-t-on le succès d'une page web ?

Et, surtout, question subsidiaire : dans quelle mesure les contenus qui me sont proposés automatiquement par un moteur de recherche ou un service en ligne sont-ils fiables ? Dois-je aller chercher plus loin, et si oui comment ?

Objectif : vous faire comprendre les enjeux d'une bonne indexation et le fonctionnement de base des principales familles d'algo, puisqu'il y a fort à parier que vous serez confrontés un jour à ces questions dans le cadre de votre carrière, où vous serez par exemple amenés à décrire les contenus que vous publiez, à optimiser l'indexation d'un site web-vitrine (ce que l'on appelle couramment le SEO [search engine optimisation]). Une petite intro théorique ne fait donc pas de mal, ne serait-ce que pour savoir, globalement, ce dont on parle.


§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§
<!-- .slide: data-background-image="img/StatCounter-2024.png" data-background-size="contain" -->

===

Je commencerai par relier cette problématique à celle de l'hégémonie des grandes industries numériques, ce que l'on a rangé pendant un temps sous l’acronyme GAFAM : Google, Apple, Facebook, Amazon et Microsoft, avant de les rebaptiser GAMMA ou GAMAM suite au changement de nom de Facebook en Meta. Ces géants dominent aujourd’hui le monde numérique et ont une influence majeure sur leur secteur d’activité, participant aux effets nocifs de la surcharge informationnelle dont on a parlé ces dernières semaines. 

Cette hégémonie se manifeste par l'uniformisation des contenus, on l'a dit, mais surtout par l'uniformisation de nos pratiques numériques et, avec elles, l'uniformisation de notre boîte à outil numérique. 

J'ai déjà relevé, par exemple, que la plupart d'entre nous utilisaient sans trop se poser de question Word. 

C'est un peu la même chose avec les moteurs de recherche sur le web. Les données sont sans appel: à travers le monde, on utilise tous Google. Cela ne serait pas si grave si nous ne l'utilisions pas si mal : la paresse, le manque de littératie numérique (cad de connaissance de la façon dont fonctionne vraiment ces outils) nous pousse à ne consulter que les premiers résultats de la première page, sans aller plus loin.

Si je dis que nous utilisons mal Google, ce n'est pas parce que nous ne savons pas le faire fonctionner (tout le monde est capable de taper une requête), mais parce que nous ne savons pas bien comment lui, fonctionne vraiment. Nous le pensons trop souvent comme un outil objectif, ce qu'il n'est pas du tout.

§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§
<!-- .slide: data-background-image="img/ernaux-2022-10-10.png" data-background-size="contain" -->

===

Qu'est-ce qu'un moteur de recherche ? Un moteur de recherche, fondamentalement, a pour fonction de faire le tri entre une masse d'informations, afin de sélectionner les plus pertinentes pour un sujet donné (une requête) : par exemple, vous allez taper dans Google Annie Ernaux, et le moteur va afficher une succession de pages distinctes : généralement l'actualité sur le sujet + Wikipédia + un encart "À propos" (Femme de lettres) + des contenus liés (personnes, médias, oeuvres).

§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§
<!-- .slide: data-background-image="img/GoogleErnaux.png" data-background-size="contain" -->


===

La particularité du moteur de recherche propre à un service numérique (Google, mais aussi des moteurs de recherche propres à des plateformes dédiées -- Youtube, Netflix, Twitter...), c'est qu'ils organisent des contenus sans cesse en mouvement.

La problématique est double : comment ce tri est-il effectué ? Pourquoi certains contenus sont-ils mis en avant, pourquoi d'autres sont-il au contraire relégués aux oubliettes ? Mais également, à l'inverse : comment ce tri va-t-il exercer une influence sur les comportements des usagers en ligne ?

C'est à cette double question que l'on va s'attaquer aujourd'hui, en proposant un panorama des différents algorithmes de structuration du web.

§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§


### Structuration du web, structuration du réel ?
* Si je cherche un service, une information ou un objet sur un moteur de recherche (Google, Amazon, le catalogue de la BU, etc.), j'ai tendance à ne considérer que la liste des résultats fournis par l'outil...
* Je ne consulte souvent que les premiers résultats de ma recherche... (cf. la bataille du référencement pour certains sites sensibles, ou commerciaux, etc.)
* Des questions peu posées : quelles sont les bases de données et les types de données utilisées ? Qui a écrit l'algorythme de classement ? Selon quels critères&nbsp;?

<!-- .element: style="font-size:1.7rem; text-align:justify" -->


===

Mais revenons d'abord à la base du problème : le web, un espèce de grand fourre-tout auquel on ne comprendrait plus rien s'il n'y avait pas les algorithmes (qui sont indispensables).

Le web, c'est un amas de données, sans cesse en train de s'augmenter de manière exponentielle, des contenus en tous genre en quantités astronomiques, ce que l'on appelle le big data, tellement gigantesque qu'il n'est pas appréhendable par l'esprit humain.


Comme il n'est pas appréhendable, il faut l'organiser. Et comme nous ne sommes pas capable de l'organiser nous-mêmes directement, nous laissons les algorithmes le faire pour nous.

>Les big data ne sont rien sans outils pour les rendre intelligibles, pour transformer les données en connais-
sances. Face aux données massives, nous avons besoin d’algorithmes. [Dominique Cardon]

Sauf que nous n'avons pas toujours bien conscience des règles de cette organisation. Et, surtout, nous n'avons pas conscience du tri drastique et radical opéré par les algos. 

>aujourd’hui, on ne sait plus calculer la taille du web, on considère que 95 % de nos navigations se
déploient sur seulement 0,03 % des contenus numériques disponibles.
C'est une manifestation de l'économie de l'attention : nous ne voyons que la partie immergée de l'Iceberg.

Il ne s'agit pas de dire que les algorithmes sont mauvais, il s'agit de dire que ceux-ci doivent être transparents, doivent exposer les règles qui les régissent, afin que nous sachions exactement quels sont les biais auxquels nous sommes soumis lorsque nous réalisons des recherches en ligne.

* Des questions peu posées : quelles sont les bases de données et les types de données utilisées ? Qui a écrit l'algorythme de classement ? Selon quels critères ?

§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§
<!-- .slide: data-background-image="img/streetview.png" data-background-size="contain" -->


===

Pour de nombreux spécialistes de la culture numérique, comme le canadien Marcello Vitali-Rosati ou encore le britanique Luciano Floridi, le développement des technos numériques nous a conduit vers un changement de paradigme, dans lequel une fusion s'opère désormais entre notre réalité physique et sa représentation informatique.

Pour comprendre leur argument, reprenons l'exemple des logiciels cartographiques numériques. Sur les cartes numériques, désormais, sont agrégées une série d'informations qui ne relèvent plus seulement de la simple cartographie :
  - des adresses de magasins
  - des adresses de restaurants
Toutes ces adresses font l'objet d'une évaluation et de commentaires. On peut connaître aussi l'achalandage en fonction des heures. Tant et si bien que lorsque je décide, par exemple, de me promener dans le quartier de la Sorbonne, je vais avoir en même temps une série de suggestions de cafés où me rendre : c'est une façon de faire de la publicité - ou plus précisément pour reprendre un autre terme est souvent avancé dans le domaine des économies numérique : c'est une manière d'exercer une influence...

La carte de la ville s'est aujourd'hui superposée à toute une série d'information, d'évaluations, de services, qui exercent une influence directe sur les comportements des usagers. Je peux décider de modifier mon chemin pour éviter une rue trop encombrée. Je vais préférer la pizzeria notée 4,3\* plutôt que le resto de sushi noté 2,5\*, même si je préfère les sushis (et l'on comprend que déjà une influence s'opère), uniquement parce que je me fie à la note qui a été donnée par mes pairs.

Auparavant, une carte imprimée n'était qu'une représentation statique de la ville, désormais la carte numérique est "intelligente" ou "augmentée" : elle donne une série d'information en temps réel ; elle est immersive, participative, interactive : je peux connaître l'affluence d'une station de métro sans y entrer, me faire une idée de la qualité d'un commerce, réagir et partager mon expérience avec les autres pour modifier des éléments de la carte.

Tout cela pour dire que si la question de la structuration du web est aussi problématique, c'est parce qu'elle structure en fait le réel. Elle a un impact effectif sur notre monde et notre manière de l'habiter, d'y vivre. C'est pour cela que les chercheurs défendent l'idée d'une fusion entre ce qui relevait traditionnellement de l'espace physique et ce qui relevait plutôt de l'espace numérique. Vitali-Rosati parle ainsi d'éditorialisation, Floridi, mentionné plus tôt, parle "d'infosphère" pour qualifier notre nouvelle environnement médiatique.


§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§
<!-- .slide: data-background-image="img/" data-background-size="contain" -->

Comment le web est-il formé, structuré, organisé ? Comment se structure le media qui constitue notre fenêtre sur le monde contemporain et qui donc participe à structurer notre monde ?

===

Je vais expliciter la question du jour dans un instant, mais avant cela, je tiens à rappeler l'un des fondements du cours : ce cours est un cours en théorie des media. Un media, au sens général du terme, c'est ce qui est "entre" les choses. Notre accès au réel, au monde, est ainsi dans 90% des cas médié : les choses du monde me parviennent par le biais d'un livre, d'un journal, d'une écriture... mais aussi d'une voix, par exemple.

De fait, Médier le réel, c'est le construire, et c'est le construire en le modélisant, en le rendant appréhendable, compréhensible - au sens étymologique du terme, "prendre avec soi". Représenter le monde, c'est chercher à le prendre avec soi, à s'en saisir, afin de mieux y habiter. Or comment représenter, comment comprendre et donc comment habiter le monde aujourd'hui ?

Cette question résonne tout particulièrement dès lors que l'on s'intéresse au web. Pour utiliser une métaphore propre à la représentation, le web est aujourd'hui une fenêtre sur notre monde. Mais il n'est pas seulement cela : comme on vient de le voir, il a tendance à le structurer largement, en influençant notre accès à l'information et par conséquent nos comportements. Du coup, la question à se poser est la suivante : comment le web est-il lui-même formé et lui-même structuré ? Comment, pour compléter la problématique, est construit, est structuré le media qui constitue notre fenêtre sur le monde contemporain et qui donc participe à structurer notre monde ?


§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§
<!-- .slide: data-background-image="img/bookshop.jpg" data-background-size="contain" -->


===

Ce qui est intéressant, c'est de constater combien des usages numériques désormais très courants nous paraîtraient totalement inconcevables dans d'autres sphères d'action.

Comparez un peu vos pratiques avec, par exemple, celle du flânage en libraire, ou dans un magasin de vêtements. Vous arrêtez-vous toujours seulement sur ce qui est présenté en vitrine ? Vous contentez-vous seulement de choisir les livres mis en évidences sur les présentoirs ? Ce goût que nous avons pour le flanage, la fouille dans les rayons d'une librairie, d'une boutique quelconque, nous le perdons la plupart du temps lors de nos recherches sur Google. Peu d'utilisateurs vont explorer les 100aines de résultats...

§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§
<!-- .slide: data-background-image="img/amazon1.png" data-background-size="contain" -->


===

Chez Amazon aussi j'ai un "tri".

Possibilité d'une personnalisation : par exemple, des filtres thématiques.
Avec même l'illusion que le tri est fait par mes semblables, les autres internautes.


§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§
<!-- .slide: data-background-image="img/amazon2.png" data-background-size="contain" -->


===
Le problème qui se pose ici est notamment celui de l'autorité, de la légitimité. CHez mon libraire, même si je me contente de regarder les livres sélectionnés sur un présentoir, je peux identifier la personne qui est à l'origine de ce tri, de cette sélection. C'est d'ailleurs pour cela que nous finissons par avoir des "libraires" préférés : on sait que nous pouvons faire confiance en une personne qui aura du goût, parfois le même que le nôtre mais pas toujours. On se fie au jugement d'un professionnel du livre. C'est aussi de cette façon que l'on va choisir notre journal ou notre magazine préféré : nous identifions un groupe de journalistes, avec lesquels nous partageons des valeurs, notamment.

Le problème d'un moteur de recherche comme celui d'Amazon, équivalent de mon libraire en ligne, c'est qu'il nous propose également un tri, mais sans que l'on sache très bien 1) qui se cache derrière ce tri 2) sur quels critères ce tri s'est opéré.

Cette question résonne de fait avec une problématique que nous avons étudiée il y a quelques semaines : celle la crise de la vérité. On a vu en effet que cette crise résidait d'abord dans la remise en cause profonde d'un modèle de légitimation qui ne fonctionne plus comme avant. Mais sur le moteur de recherche Google, par exemple, qui légitimise les contenus ?

On voit bien ici que la question est complexe : déjà, le moteur de recherche que nous utilisons est avant tout une machine qui, en tant que telle, nous semble dénuée de "volonté". Il y a là une illusion d'objectivité qui se dégage de la nature informatique de l'outil : une série de calcul, dans lesquels personne n'interviendrait.
Sauf que ces calculs ont été déterminés par des être humains... et que ces être humains ont, de leur côté, importés leurs biais. Le fait que les programmeurs de chez Google soient majoritairement des hommes blanc a souvent été dénoncé : on s'appercevait que certains algorithmes avaient tendance à reproduire des comportement racistes ou sexistes. Autre problème : le code, l'algorithme utilisé par les grands monopoles du web - GOogle, FB, etc - ne sont pas public, ou du moins pas complètement publics. C'est-à-dire que l'on e sait pas, globalement, comment ils fonctionnent.

Sans aller jusqu'à l'échelle des GAFAM, ce problème de la transparence du code a été posée pour des algorithmes qui vous concerne directement : notamment celui de parcours sup, dont personne (à part le ministère), ne sait vraiment comment il fonctionne. N'est-ce pas là problématique ? Ce manque de transparence est ce que dénoncent les organisation (institutions ou assos) en faveur d'une plus grande démocratie numérique :
- la CNIL
- la Quadrature du net

§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§
<!-- .slide: data-background-image="img/CNIL.png" data-background-size="contain" -->

===

Parenthèse sur les contre-pouvoirs : La CNIL et la Quadrature

La Commission nationale de l'informatique et des libertés (CNIL) est une autorité administrative indépendante française. La CNIL est chargée de veiller à ce que l’informatique soit au service du citoyen et qu’elle ne porte atteinte ni à l’identité humaine, ni aux droits de l’homme, ni à la vie privée, ni aux libertés individuelles ou publiques.

Date de création = 1978

Le 21 mars 1974, le journal *Le Monde* révèle un projet gouvernemental tendant à identifier chaque citoyen par un numéro afin d'interconnecter les fichiers nominatifs de l'administration française.

L'affaire fait craindre des dérive de fichage général des citoyens, et expose les dangers de certaines utilisations de l'informatique. Pour répondre aux inquiétudes, le gouvernement fonde la CNIL, commission indépendante chargée de proposer des mesures garantissant que le développement de l'informatique en France se réalise dans le respect de la vie privée, des libertés individuelles et publiques.


§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§
<!-- .slide: data-background-image="img/DRE351OXkAAJHxU.jpg" data-background-size="contain" -->

===

La Quadrature du Net (abrégé LQDN) est une association de défense et de promotion des droits et libertés sur Internet, fondée en 2008. Elle intervient dans les débats concernant la liberté d'expression, le droit d'auteur, la régulation du secteur des télécommunications, ou encore le respect de la vie privée sur Internet. En France, elle s'est notamment fait connaître par sa forte opposition aux lois HADOPI (lois sur le téléchargement et les échanges numériques) et LOPPSI (télésurveillance).

L'asso existe depuis 2008. Elle est plus militante, ce n'est pas un organisme d'état.

Actions : engager des poursuites contre la télésurveillance (y compris qd elle vient de l'état).

Faire bcp de com pour avertir des dangers liées aux données.

§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§

### Le web à l'heure du "big data"
* "big" : un explosion quantitative
* "data" : des informations sur-mesure

===

Je commencerai par une première définition, que je vous encourage à retenir, mais surtout à bien comprendre : le *big data*. Nul besoin d'être traducteur de Shakespeare pour comprendre qu'il s'agit ici de désigner la masse des données produites et diffusées chaque jour en ligne. Souvent citée, la notion de *big data* demeure cependant mal maîtrisée dès lors qu'on demande une définition claire, notamment parce que les propres termes qui la composent sont faussement simples.

"Big", tout d'abord, est un adjectif quantitatif, il vient désigner une quantité de contenus, de données et donc d'information, particulièrement grande, grosse ou conséquente. Mais que veut dire "grand ou conséquent" aujourd'hui ? À partir de quand devient-on "Big"? Ce qui caractérise ce "big data", c'est que sa masse est tellement importante, et qui plus est exponentielle, qu'elle n'est désormais plus appréhendable par l'esprit humain. Elle dépasse complètement les capacités humaines d'analyse (et d'ailleurs même celles des outils informatiques classiques, c'est pour cette raison d'ailleurs que l'on va avoir recours à des outils algorithmiques.


§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§

### Donnée
* Donnée (élément réputé "brut") *vs* information (interprétation)
* Renommer la donnée en régime numérique : *obtenues*, *capta*, etc.

===

Une seconde difficulté tient dans le terme de "data", que l'on traduit en français par "donnée", et qui est en quelque sorte un faux-ami, puisqu'il nous laisse croire en une certaine objectivité qui serait propre à ladite donnée.

Il faut ici rappeler plusieurs choses, et prendre le soin de distinguer *donnée* de *donnée numérique* -- car on emploie les deux termes de manière indissociable, alors qu'en fait il faut rétablir quelque nuances.

En effet, dans sa définition la plus générale, pré-numérique, la donnée se définit par opposition à l'information. Ainsi, une donnée désigne un fait ou un élément "brut", qui n'a pas encore été traité ou mise en contexte - c'est ce qui la distingue d'ailleurs de l'information. Une information sera une donnée interprétée et médiatisée, recontextualisée.

Un exemple très simple : si je suis météorologue, je vais m'appuyer sur un ensemble de données telles que la température, la puissance et le sens du vent, la pression atmosphérique. les précipitations, etc. Tous ces éléments peuvent être considérés comme des données. Si je décide de faire un bulletin météo, je vais alors mettre ces données en relation pour tenter d'en tirer une synthèse voire une interprétation. Afin de diffuser ma synthèse au public, je vais l'organiser avec des visualisations, une narration. Mes données deviennent alors une information.

Si la distinction entre donnée brute et information interprétée et contextualisée est donc importante, il faut tout de même se méfier d'une tendance qui attribue à la donnée une objectivité pure. La donnée, justement, n'est pas toujours "donnée" : elle est construite, arbitraire. Pour savoir que je dois connaître la pression atmosphérique afin de faire un bon bulletin météo, cela exige des connaissances préalables. Une donnée s'appuie donc toujours sur un choix, une connaissance en amont, qui exige que l'on choisisse d'analyser tel aspect du réel plutôt qu'un autre. C'est la première objection que l'on peut émettre envers ce terme de données, qui a fait l'objet de plusieurs discussions, j'y reviens dans un instant avec les exemples de "obtenues" et des "capta".


§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§
<!-- .slide: data-background-image="img/" data-background-size="contain" -->
<!-- .slide: class="hover"-->


### Données numériques
* Donnée numérique : représentation d'une information dans un programme informatique
* *Big data* : explosion quantitative de la production / stockage des données



===

Dans le domaine précis de l'informatique, une donnée est la représentation d'une information dans un programme : une donnée peut donc être du texte, du son, une image, etc.

Avec le développement et la démocratisation des outils numériques, en particulier du web, l'ensemble des données produites et stockées sur les serveurs est devenu si volumineux qu'il dépasse de loin les capacités humaines d'analyse et même celles des outils informatiques classiques. Cette masse d'informations, de données, est appelée le *big data*.

>L’explosion quantitative (et souvent redondante) de la donnée numérique contraint à de nouvelles manières de voir et analyser le monde. De nouveaux ordres de grandeur concernent la capture, le stockage, la recherche, le partage, l'analyse et la visualisation des données. (Wikipédia)

Parce qu'elle se décline sur un modèle essentiellement quantitatif, la donnée nous renvoie vers un monde calculable : les phénomènes, les opinions, les actions des individus seraient formalisable grâce à de l'analyse statistique qui, de plus, permettrait de dessiner des prévisions. En d'autres termes, les algo d'aujourd'hui sont des outils météo qui nous calculent nous : nous sommes devenus le temps de demain qu'il faut prévoir.

Tout calcul, toute prédiction, doit servir un but : pour la météo, je veux savoir si je peux partir en balade demain, si je peux faire un bbcue... Dans le cas des données numériques, ce sont les industries, les entreprises, qui ont intérêt à connaître et prévoir les attitudes de leurs client.

Ainsi, les données collectées sont nécessairement déjà orientées. Ce manque d'objectivité du matériaux par excellence de notre époque (nos données = notre attention), a été dénoncé par de nombreux chercheurs, qui ont proposé des alternatives.

Il est important de comprendre le statut ontologique problématique des données numériques, qui sont fondamentalement des éléments extraits du réel de manière arbitraire, mais qui ont tendance à se substituer au réel, ou du moins à en tenir lieu dans notre imaginaire.


§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§


### Les "obtenues" de Bruno Latour

>La tentation de l’idéalisme vient peut-être du mot même de *données* qui décrit aussi mal que possible ce sur quoi s’appliquent les capacités cognitives ordinaires des érudits, des savants et des intellectuels. Il faudrait remplacer ce terme par celui, beaucoup plus réaliste, d’*obtenues* et parler par conséquent de bases d’*obtenues*, de *sublata* plutôt que de *data*.
<!-- .element: style="font-size:1.7rem; text-align:justify" -->

>Bruno Latour, « Pensée retenue, pensée distribuée », Lieux de savoir, 1. Espaces et communautés, Albin Michel, 2007

<!-- .element: style="font-size:1.7rem; text-align:justify" -->
===

Afin de lever l'ambiguité entre la notion de donnée et celle de réel, afin de séparer le mot donnée du réel dont il est en fait une remédiation, Plusieurs alternatives ont été proposées dans le champ des SHS.

Fondamentalement, ces alternatives visent à déconstruire l'illusion d'objectivité de la donnée, en la réintégrant dans un paradigme représentationnel -- la donnée n'est pas un échantillon du réel, elle en est déjà une remédiation. 

Parmi les premiers, les sociologues dès les années 1990.
Avec Latour, qui propose le terme d'obtenues.

§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§

### Les "capta" de Johanna Drucker

>[...] l'abandon de l'interprétation au profit d'une approche naïve de la statistique fausse certainement le jeu dès le départ en faveur de la croyance que les données sont intrinsèquement quantitatives - évidentes, sans valeur et indépendantes de l'observateur. Cette croyance exclut les possibilités de concevoir les données comme qualitatives, constituées de manière co-dépendante - en d'autres termes, de reconnaître que les data sont d'abord des capta.

<!-- .element: style="font-size:1.7rem; text-align:justify" -->

>Johanna Drucker, "Humanities Approaches to Graphical Display", DHQ, 2011.

<!-- .element: style="font-size:1.7rem; text-align:justify" -->

===

§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§

### Données personnelles

>"toute information relative à une personne physique identifiée ou qui peut être identifiée, directement ou indirectement, par référence à un numéro d'identification ou à un ou plusieurs éléments qui lui sont propres" (définition légale)

<!-- .element: style="font-size:1.7rem; text-align:justify" -->


===

Une donnée à caractère personnel ou DCP (couramment « données personnelles ») correspond en droit français à toute information relative à une personne physique identifiée ou qui peut être identifiée, directement ou indirectement, par référence à un numéro d'identification ou à un ou plusieurs éléments qui lui sont propres : Loi n° 78-17 du 6 janvier 1978 relative à l'informatique, aux fichiers et aux libertés, article 2.

On voit donc les problèmes poindre : sur le web, aujourd'hui, les contenus et les données sont publiés et circulent en masse. Il y a trop de données, potentiellement d'Ailleurs des données personnelles, dont on ne maîtrise plus les flux et dans lesquelles on peut se perdre.

§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§


### Indexation et métadonnées
* Qu'est-ce qu'une métadonnée ?
  * Une métadonnée est littéralement une donnée sur une donnée. Il s'agit d'un ensemble structuré d'informations décrivant une ressource quelconque, en vue de retrouver cette ressource parmi d'autres.

===
De manière générale, pour s'y retrouver dans une masse d'informations ou de document, de données (informatique ou non), nous avons recours à un processus d'indexation.
Le mot « indexation » fait référence à des processus de représentation de l'information. Pour indexer des contenus, documents ou données, nous avons donc créé les métadonnées. Une métadonnée est littéralement une donnée sur une donnée. Il s'agit d'un ensemble structuré d'informations décrivant une ressource quelconque, en vue de retrouver cette ressource parmi d'autres.

Les métadonnées sont la carte d’identité d’un document. Elles permettent de l’identifier, de le décrire, d’expliquer l’origine de sa création, son utilité et ses destinataires.

Au-delà de cette seule description, elles facilitent la recherche et le partage des ressources, la gestion de collections, leur préservation autant que la gestion des droits et l’authentification des documents.


§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§
<!-- .slide: data-background-image="img/metadonneePage.png" data-background-size="contain" -->
<!-- .slide: class="hover"-->


===

* Métadonnées embarquées (balise d'une page web)


Dans un contexte numérique, les métadonnées sont présentes soit de manière embarquée : elles font partie du document, en étant incluses par exemple dans un fichier informatique : photo, logiciel, document, ….

**La métadonnée est ce qui permet de retrouver la données dans l'océan Big DATA.**


Il faut envisager le web comme une sorte de grosse bibliothèque : comment retrouver des contenus ? Tt simplement grâce à leur indexation. Il est important, ainsi, de façonner des contenus qui soient toujours bien indexés. Cette indexation permet aussi d'assurer la pérennité des contenus.

§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§
<!-- .slide: data-background-image="img/" data-background-size="contain" -->

### Les types de métadonnées :
* métadonnées de gestion permettant d’accéder au document (auteur, titre, date de création, date de modification, langue…) ;
* métadonnées de description, pour en comprendre le contenu (sujet, description) ;
* métadonnées de préservation, pour garantir la pérennité de l’accès et de la compréhension du document (droits, format du fichier, source, résolution, relation, couverture…).

<!-- .element: style="font-size:1.7rem; text-align:justify" -->


§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§
<!-- .slide: data-background-image="img/" data-background-size="contain" -->
<!-- .slide: class="hover"-->

## Données et métadonnées : une gestion qui nous échappe
* Les données collectées à notre insu
* Les données personnelles dont nous ne sommes pas propriétaires

===

Sachant que ces métadonnées d'indexation sont, parfois, créées à notre insu : d'où un certain nombre de problèmes potentiels.

§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§
<!-- .slide: data-background-image="img/tweetmetadata.png" data-background-size="contain" -->

===
Vous serez surpris par tout ce que vos tweets peuvent révéler de vous et de vos habitudes
Une analyse de l’activité des comptes Twitter

Comme tous les réseaux sociaux, Twitter sait beaucoup de choses sur vous, grâce aux métadonnées. En effet, pour un message de 140 caractères, vous aurez plus de 30 métadonnées, plus de 20 fois la taille du contenu initial que vous avez saisi ! Le texte d’un tweet représente moins de 10% de l’information.

Et vous savez quoi ? Presque toutes les métadonnées sont accessibles par l’API ouverte de Twitter.
Voici quelques exemples qui peuvent être exploités par n’importe qui (pas seulement les gouvernements) pour pister quelqu’un et en déduire son empreinte numérique :

Fuseau horaire et langue choisie pour l’interface de twitter
Langues détectées dans les tweets
Sources utilisées (application pour mobile, navigateur web…)
Géolocalisation
Hashtags les plus utilisés, utilisateurs les plus retweetés, etc.
Activité quotidienne/hebdomadaire

§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§
<!-- .slide: data-background-image="img/" data-background-size="contain" -->
<!-- .slide: class="hover" -->

## L'organisation algorithmique
* Dominique Cardon :
  * *La démocratie Internet* (2010)
  * "Dans l'esprit du PageRank. Une enquête sur l'algorithme de Google" (2013)
  * *À quoi rêvent les algorithmes ?* (2015)
  * *Culture numérique* (2019)

<!-- .element: style="font-size:1.7rem; text-align:justify" -->

===


§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§


### Qu'est-ce qu'un algorithme ?
Un algorithme désigne une suite d’instructions qui, une fois exécutée correctement, conduit à un résultat donné...
Une recette de cuisine est, en un sens, un algorithme. En informatique, les algorithmes s’efforcent de nous suppléer dans de nombreuses tâches en réalisant à notre place une série d'opérations fastidieuses, notamment la sélection, le tri et la hiérarchisation de l’information.

<!-- .element: style="font-size:1.7rem; text-align:justify" -->

===

§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§
<!-- .slide: data-background-image="img/recette.JPG" data-background-size="contain" -->


===

Avez-vous déjà ouvert un livre de recettes de cuisine ? Avez vous déjà déchiffré un mode d’emploi traduit directement du coréen pour faire fonctionner un magnétoscope ou un répondeur téléphonique réticent ? Si oui, sans le savoir, vous avez déjà exécuté des algorithmes.
Plus fort : avez-vous déjà indiqué un chemin à un touriste égaré ? Avez vous fait chercher un objet à quelqu’un par téléphone ? Ecrit une lettre anonyme stipulant comment procéder à une remise de rançon ? Si oui, vous avez déjà fabriqué – et fait exécuter – des algorithmes.

§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§

>Au sein du code informatique, les algorithmes sont donc ces procédures ordonnées qui permettent de transformer les données initiales en un résultat. Sans ces techniques calculatoires, nous sommes incapables de trouver les informations pertinentes, de transformer les données en connaissances.

>Dominique Cardon, *Culture numérique*, 2019.

<!-- .element: style="font-size:1.7rem; text-align:justify" -->


===

Les résultats
d’un moteur de recherche, la liste des vidéos les plus
vues, des trending topics, des contenus les plus likés,
retweetés ou partagés, les recommandations d’achat de
séries télévisés ou de musique : toutes ces informations
sont issues d’un processus de sélection automatique.
Elles n’ont pas été choisies par des humains, mais par
des automates.

§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§
<!-- .slide: data-background-image="img/" data-background-size="contain"-->
<!-- .slide: class="hover"-->

### Les biais algorithmiques
* Un algorithme n'est pas neutre
* Un algorithme n'est pas une émanation machinique : il a été programmé par les humains

===

* De nombreux travaux montrent combien les algorithmes ont tendance à :
  - reproduire les préjugés
  - encourager des comportements sociaux discriminants (sexisme, racisme)

§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§
<!-- .slide: data-background-image="img/" data-background-size="contain" -->
<!-- .slide: class="hover"-->

>Les algorithmes qui permettent de hiérarchiser les informations enferment des principes de classement et des visions du monde. Ils structurent très profondément la manière dont les internautes voient les informations et se représentent le monde numérique dans lequel ils se promènent, sans toujours soupçonner le travail souterrain qu’exercent les algorithmes sur leur itinéraire.

<!-- .element: style="font-size:1.7rem; text-align:justify" -->


Source : Dominique Cardon, *À quoi rêvent les algorithmes ?*

<!-- .element: class="source" -->

===
Représenter, c'est structurer, en particulier dans le cas de l'algorithme

§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§

### Les quatre familles d'algorithmes
* *à côté du web* (mesure d'audience et popularité des sites)
* *au-dessus du web* (algorithme de hiérarchisation de l’autorité)
* *dans le web* (algorithme de mesure de réputation)
* *au-dessous* (algorithme prédictif)

<!-- .element: style="width:45%;float:left;margin-left:-1em; font-size:1.4rem; text-align:justify" -->


![](img/systemeCardon.png)<!-- .element: style="width:50%;float:right;margin-right:-1em;" -->


===

Cardon distingue quatre familles de calcul numérique, différenciées à la fois selon leur positionnement figuratif par rapport à l’objet du calcul et selon leur principe de référence

* *à côté du web* (ordonnent la popularité des sites)
* *au-dessus du web* (hiérarchisent l’autorité des sites)
* *dans le web* (les mesures de réputation des personnes et des choses)
* *au-dessous*, les calculs qui cherchent à déchiffrer le comportement d’un internaute à travers une prédiction déduite du comportement d’un autre internaute.

La popularité, l’autorité, la réputation, la prédiction, voilà les quatre valeurs fondamentales qui sont à la fois productrices et produits des différents types d’algorithmes qui, dans les plateformes actuelles, s’intègrent l’un à l’autre et dont Cardon esquisse l’histoire.



§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§

### Algorithme de mesure d'audience
* dit "à côté du web"
* calcule le nombre de "clics" ou de "vues"
* exemple : médiamétrie, affichage publicitaire, google analytics
* deux méthodes de calcul : *user centric* ou *site centric*

===

>La famille de la popularité, qui émerge lorsqu’on place l’algorithme à côté des données, correspond à la forme traditionnelle de la mesure d’audience. Du point de vue des mondes numériques, elle n’est pas très originale : les acteurs du web se sont contentés de transposer sur internet une métrique inventée par les médias traditionnels, presse, radio et télévision, pour mesurer leur audience. Le calcul est très simple : il consiste à compter les clics des visiteurs en considérant que tous ont le même poids. Afin d’éviter de dénombrer plusieurs fois le même internaute, la notion de « visiteur unique » est l’unité de compte de la popularité des sites.

Source : Cardon, culture numérique

§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§

* Mesure user-centric (ex : Google Analytics)

<!-- .element: style="width:45%;float:left;margin-left:-1em; font-size:1.4rem; text-align:justify"-->


![](img/userMetric.png)<!-- .element: style="width:40%;float:right;margin-right:-1em;" -->


===

Il existe deux façons de mesurer l’audience des sites web. Avec la première, dite *user centric*, on installe une sonde dans l’ordinateur ou le téléphone portable d’un panel représentatif de la population afin d’enregistrer les navigations de ses membres. Il est ainsi possible de classer l’audience des sites les plus consultés. Tous les mois, comme le fait Médiamétrie pour les audiences de la télévision en France depuis 1985, le palmarès des sites les plus populaires est publié, et ce classement détermine le tarif des bannières publicitaires.

Ces mesures côté utilisateur utilisent la même approche probabiliste que les médias traditionnels. On fabrique un échantillon représentatif de la population à mesurer, on effectue les mesures sur cet échantillon et on l’extrapole à l’ensemble de la population. 

Évidemment des biais : difficile d'avoir un échantillon représentatif, surtout en face du flux du web.


§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§
<!-- .slide: data-background-image="img/" data-background-size="contain" -->

* Mesure cite-centric (ex : Google Analytics)

Google Analytics : 80 % du marché mondial

<!-- .element: style="width:45%;float:left;margin-left:-1em; font-size:1.4rem; text-align:justify" -->


![](img/GoogleAnalytics.png)<!-- .element: style="width:40%;float:right;margin-right:-1em;" -->



===

La seconde manière, dite site centric, recourt à des outils de supervision dont le plus célèbre est Google Analytics, qui mesure le nombre de visiteurs arrivant sur le site. Seul l’éditeur du site en a connaissance et, lorsqu’il la rend publique, il est souvent tenté de publier des chiffres avantageux ou de les gonfler au moyen de techniques logicielles assez simples d’emploi.


Note: Il y a deux ans, la CNIL avait reproché à Google Analytics d’être illégal, car non conforme au Règlement général sur la protection des données (RGPD). En cause : l'outil Analytics transférait des données hors Union européenne, tout en étant incapable d’anonymiser complètement les données collectées.


§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§

![](img/HomeRevueHN.png)<!-- .element: style="width:50%;float:left;margin-right:-1em;" -->

![](img/analyticsHN_Carte.png)<!-- .element: style="width:50%;float:right;margin-right:-1em;" -->

===

Exemple de la revue HN

Dimension francophone encore à travailler pour l'Afrique.

§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§

![](img/HomeRevueHN.png)<!-- .element: style="width:50%;float:left;margin-right:-1em;" -->

![](img/analyticsHN_Origine_appareil.png)<!-- .element: style="width:45%;float:right;margin-right:-1em;" -->

===

De quel appareil on nous consulte : plutôt de l'ordinateur. Pratique de lecture en "mode travail". 

§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§

![](img/analyticsHN_telechargements.png)<!-- .element: style="width:50%;float:left;margin-right:-1em;" -->

![](img/analyticsHN_TelechargementComplet.png)<!-- .element: style="width:50%;float:right;margin-right:-1em;" -->

===

stats de téléchargement : on constate avec une certaine surprise la permanence de la notion de revue dans les pratiques de téléchargement. Les téléchargement les plus nombreux concernent les numéros complets, et non des articles singuliers.

Mais cela étant dit, le "portrait" ou la personna de mes utilisateurs reste floue...

§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§

* De la visite au "visiteur" unique (adresse IP)

>Déjà imparfaite dans le monde de la télévision, cette mesure révèle de redoutables imprécisions lorsqu’elle est appliquée au web. Car cette méthode ne sait jamais très bien qui se trouve derrière l’ordinateur familial. Elle suppose que les parcours multiples, rapides et enchevêtrés d’une navigation sur le web équivalent à une information lue, vue ou entendue dans les médias traditionnels.

<!-- .element: style="font-size:1.7rem; text-align:justify" -->

Source : Dominique Cardon, *À quoi rêvent les algorithmes ?*

<!-- .element: class="source" -->

===

La mesure d'audience, dans son modèle traditionnel hérité de la médimétrie de la TV et de la radio, a rapidement montré ses limites. 


>Déjà imparfaite dans le monde de la télévision, cette mesure révèle de redoutables imprécisions lorsqu’elle est appliquée au web. Car cette méthode ne sait jamais très bien qui se trouve derrière l’ordinateur familial. Elle suppose que les parcours multiples, rapides et enchevêtrés d’une navigation sur le web équivalent à une information lue, vue ou entendue dans les médias traditionnels.


§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§
<!-- .slide: data-background-image="img/clickbait-quiz-1.jpg" data-background-size="contain" -->


===

Mais cette métrique présente, pour les annonceurs, un autre défaut. Comme l’affichage publicitaire classique, elle enregistre la fréquentation des sites et non l’efficacité des messages.

Cette course au clics est à l'origine de la pollution numérique : toutes les click-baits qui sont destinés à générer de l'audience, totalement vide car les contenus sont sans intérêts et la lecture sera elle aussi très vite abandonnée. 

>En l’absence d’une véritable régulation du secteur – qui ne se met en place que très progressivement –, il est assez facile de manipuler de telles mesures d’audience, et les chiffres diffèrent sensiblement selon les méthodes et les instituts. Les sites d’actualité, par exemple, ne cessent de créer des jeux-concours attractifs afin de gonfler leurs chiffres. Soumis aux pressions concurrentielles d’un marché publicitaire qui paie peu, ils attirent l’audience avec des contenus divertissants, ou clickbaits.


En fait, ce qui est utile dans l'environnement numérique et dans l'économie de l'attention qui nous occupe, ce n'est pas tant de savoir quel site ou quelle page a été le plus consulté, mais de connaître comment cette page a suscité des actions / comment elle est le fruit d'une série d'action. 

Comment, en d'autres termes, elle s'inscrit dans le flux du web et de l'économie de l'attention.

C'est pour cette raison que le calcul algorithmique de l'audience n'a cessé d'être amélioré avec d'autres systèmes de calculs.

-->

§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§

### Algorithme de hiérarchisation de l'autorité
* dit "au-dessus" du web
* établit l'autorité d'un site en fonction du nombre d'hyperliens qui pointent vers lui
* Exemple : PageRank (moteur de recherche Google) ; Wikipédia (plus une page est "*linkée*", plus elle est considérée comme fiable)
* Du classement lexical (recherche par mot-clés) à l'indice de citation (force sociale de la page)

===
Ce type d'algo est typiquement celui des moteurs de recherche, et son exemple le plus important est PageRank. Problème : comment trouver un document sur le web, qd des millions de documents sont publiés chaque jour ?


Avant Google, les premiers moteurs de recherche (Lycos, Alta Vista) étaient lexicaux : ils classaient mieux les sites qui contenaient le plus de fois le mot-clé de la requête de l’utilisateur dans leurs pages.

La qualité n'était toujours pas au rv : les textes répétitifs, svt mal écrits, apparaissaient en premier. Le système était surtout très facile à truquer.

Les créateurs de Google vont opter pour une tout autre stratégie : plutôt que de demander à l’algorithme de comprendre ce qui dit la page, ils vont proposer de mesurer la force sociale de la page dans la structure du web.


§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§
<!-- .slide: data-background-image="img/PageRank-hi-res.png" data-background-size="contain" -->


===

L’algorithme du moteur de recherche ordonne les informations en considérant qu’un site qui reçoit d’un autre un lien reçoit en même temps un témoignage de reconnaissance qui lui donne de l’autorité.
il classe les sites à partir d’un vote censitaire au fondement méritocratique.

Quelle autre communauté a développé un système d'autorité fondé sur l'indice de citation ?

§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§

* De la sagesse des foules à l'intelligence collective ?

>Dans son principe initial, le PageRank, l’algorithme qui a fait la fortune de Google, considère que les liens hypertextes enferment la reconnaissance d’une autorité : si le site A adresse un lien vers le site B, c’est qu’il lui accorde de l’importance. Qu’il dise du bien ou du mal de B n’est pas la question ; ce qui importe est le fait que A ait jugé nécessaire de citer B comme une référence, une source, une preuve, un exemple ou un contre-exemple.

<!-- .element: style="font-size:1.7rem; text-align:justify" -->


Source : Dominique Cardon, *À quoi rêvent les algorithmes ?*

<!-- .element: class="source" -->

§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§

* Les limites de la méritocratie

>Les lecteurs silencieux sont oubliés et le dénombrement des liens n’a rien du vote démocratique. Plus un site est cité par les autres, plus la reconnaissance qu’il adresse à d’autres a de poids dans le calcul d’autorité. Empruntée au système de valeurs de la communauté scientifique et notamment aux classements des revues scientifiques qui donnent plus de poids aux articles les plus cités par les autres, cette mesure de reconnaissance a spectaculairement prouvé qu’elle constituait l’une des meilleures approximations possible de la qualité des informations.

<!-- .element: style="font-size:1.6rem; text-align:justify" -->

Source : Dominique Cardon, *À quoi rêvent les algorithmes ?*

<!-- .element: class="source" -->


===

Limites de cette méritocratie : fondée que sur les usagers qui participent de manière "éditoriale": ceux qui ont un site ou éditent des sites. Finalement très aristocratique. D'autres types de contributions ou de participation ignorées : le like, la republication, etc. Ces contributions sont d'autant plus importantes qu'elles sont générationnelles (ce sont les public jeunes qui likent ou republient en masse). 

Autre limite : ce que le sociologue Robert Merton appellel’« effet Mathieu » (d’après l’Évangile selon saint Mathieu : « Car on donnera à celui qui a, et il sera dans l’abondance, mais à celui qui n’a pas on ôtera même ce qu’il a »). À force d’être cités par tous, les sites les mieux classés deviennent aussi les plus populaires et reçoivent en conséquence le plus de clics.

§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§

>Alors que les journalistes filtrent l’information sur la base d’un jugement humain avant de la publier, les moteurs de recherche (ainsi que Google News) filtrent a posteriori une information déjà publiée sur la base des jugements humains émis par l’ensemble des internautes qui publient sur le web.

<!-- .element: style="font-size:1.7rem; text-align:justify" -->

Source : Dominique Cardon, *À quoi rêvent les algorithmes ?*

<!-- .element: class="source" -->

§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§

#### SEO et stratégies de contournement des algos

>Le marché florissant du référencement, le SEO (search engine optimization), est constitué d’entreprises qui proposent aux sites d’améliorer leur classement dans les résultats de Google. Certains améliorent le design et le contenu du site pour que les robots du moteur de recherche le comprennent mieux, mais beaucoup tentent de produire une autorité artificielle.

<!-- .element: style="font-size:1.7rem; text-align:justify" -->


Source : Dominique Cardon, *Culture numérique*

<!-- .element: class="source" -->



§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§


### Algorithmes de réputation et de prédiction : vers une personnalisation des résultats
- une individualisation de l'utilisateur, une offre "sur mesure"
- des algorithmes qui viennent exploiter les données personnelles

===

>Les troisième et quatrième familles de principe de classement de l’information, la réputation et la prédiction, ont pour caractéristique de rompre avec l’idée de fournir le même classement pour tous, qui était celle des classements par la popularité et l’autorité.

Ces algo répondent à un besoin croissant d'individualisation des publics, et donc de l'usager, auquel il est désormais nécessaire, dans notre économie de l'attention fondée sur l'abondance des contenus, de proposer une offre toujours davantage "sur mesure". Cela va dans le sens d'une autonomisation des publics, qui s'est aujourd'hui relativement émancipé du modèle de consommation basé sur la "grille de programme", et qui va décider par lui-même de ce qui est pertinent ou non.

Dans le même temps, 
>Ce déplacement correspond à une dynamique qui s’exerce de plus en plus puissamment au sein des
mondes numériques et suscite des questions cruciales touchant à la protection des données personnelles.
Plateformes et internautes se sont conjugués pour saper l’idée d’un classement commun et permettre une navigation plus individualisée dans les informations disponibles. Cependant, pour pouvoir personnaliser les
résultats de recherche, l’algorithme a besoin de données individuelles – ce qui n’était pas nécessaire lorsqu’il
produisait le même classement pour tous.

§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§


### Algorithme de mesure de réputation
* dit "dans le web" (ou dans les données)
* utilise les compteurs valorisant la réputation des personnes et des choses (les "*like*")
* exemple : les réseaux sociaux

===

Le premier algo de cette seconde famille est celui qui s'appuie sur les mesures de réputation. typiquement, il s'agit des algo qui sont au coeur des réseaux sociaux classiques. 

"les réseaux sociaux d’Internet gd’éclater les classements, afin de les réorganiser par affinités autour du cercle d’« amis » ou de followers que s’est choisi l'internaute"

Ces algo ont pris en compte une mutation profonde du web social, ou "web 2.0", à savoir l'émergence de micro-communautés regroupées sur les réseaux, des micro-communautés qui deviennent en vérité des niches informationnelles, construites selon des principes affinitaires :

>en s’abonnant à des amis, les usagers définissent un périmètre, une fenêtre, un écosystème informationnel. Les informations auxquelles ils sont exposés sur leur fil d’actualité dépendent de ce choix initial. L’espace informationnel n’est plus le grand espace lisse du public général, mais une suite de niches informationnelles qui se superposent les unes aux autres en fonction des choix des utilisateurs. (Culture num.)

§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§


* Je suis donc je "like"
Lorsqu’un internaute apprécie un contenu par un like, il donne une qualité à l’information en ajoutant une valeur au compteur de l’article. Dans le même temps, l’utilisateur se like lui-même puisque cette information sera visible sur le fil de ses amis. Les enquêtes montrent que les informations partagées sur les réseaux sociaux ne le sont pas par hasard. Elles façonnent la réputation, l’image que l’on cherche à donner aux autres. Elles participent au modelage de l’identité numérique. Le choix des informations mises en circulation sur le web social suit une logique réputationnelle. Et celle-ci se calcule.
<!-- .element: style="font-size:1.7rem; text-align:justify" -->

Source : Dominique Cardon, *Culture numérique*

<!-- .element: class="source" -->

===

Tout l'intérêt de ces algos, c'est qu'ils jouent en vérité sur un double plan : d'une part, la valeur du contenu, mais également d'autre part la valeur de la personne qui va publier ou plus encore re-publier et relayer un contenu. 

>objectif d’associer les informations en circulation et le profil des utilisateurs
pour en faire une mesure chiffrée. 

C'est là que se mettent en place des véritables stratégies de communication. Sur Twitter, si l’on partage un lien sans ajouter de commentaires, ce lien sera beaucoup moins retweeté que si l’on ajoute un petit mot pour dire ce que l’on en pense. De même, il est plus efficace de publier des contenus texte + image. D'ajouter des mentions ou des pokes pour attirer directement l'attention de ceux que l'on cherche à capter de notre côté.

Nous ne sommes pas tous égaux sur les réseaux : il y a des super-utilisateurs, et un système de recommandation fondé sur la popularité. Pensez-y : pour obtenir un stage, vous pouvez aussi bien demander une lettre de recommandation à votre prof ou, plus efficacement sans doute, poster sur LinKedIn un CV-video qui sera relayé par votre communauté et, avec un peu de chance, par une personne "influente". 

L'influence sur les réseaux ne dépend pas forcément de votre activité dans la vie civile et du poste que vous occupez dans une entreprise, mais de votre **capital de visibilité**.

§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§


* Le sacre de l'"influenceur"
>Le web social de Facebook, Twitter, Pinterest, Instagram, etc., s’est ainsi couvert de chiffres et de petits compteurs, des « gloriomètres », pour reprendre une expression de Gabriel Tarde. Alors que dans le monde de l’autorité, la visibilité se mérite, dans celui des affinités numériques, elle peut se fabriquer. Façonner sa réputation, animer sa communauté d’admirateurs ou anticiper la viralité de ses messages constitue même un savoir-faire valorisé. (Dominique Cardon, *À quoi rêvent les algorithmes*)

<!-- .element: style="width:45%;float:left;margin-left:-1em; font-size:1.4rem; text-align:justify" -->


![](img/NicolasMathieuPostInsta.png)<!-- .element: style="width:50%;float:right;margin-right:-1em;" -->


§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§
<!-- .slide: data-background-image="img/NicolasMathieuPostInsta.png" data-background-size="contain" -->

===

Ce système qui opère en même temps sur la visibilité / réputation de l'info et la visibilité / réputation de celui qui fait suivre l'info, est ce qui explique sans doute l'un des phénomènes contemporains les plus redoutables : le buzz ou le bad buzz. 
Difficulté de soigner son identité numérique.
Cf. la mésaventure de N. Mathieu.

>Ici aussi, un nouveau marché s’est constitué, le social media listening ou social media monitoring, afin de permettre aux entreprises de mesurer sur de grands tableaux de bord la répercussion de leurs messages sur les réseaux, d’identifier des influenceurs et surtout d’observer les messages qui viennent des internautes, notamment en cas de bad buzz.

§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§

* Le règne de l'évaluation

>Dans le cas des biens culturels, comme l’évaluation des films cinématographiques, les notes ont plus d’importance qu’une collection d’avis singuliers. Lorsque l’évaluation du bien comporte des aspects techniques, la parole d’experts est préférée à l’agrégation des notes de consommateurs peu compétents. La démocratisation de l’évaluation profane associe l’idée de pouvoir tout noter à celle de faire noter tout le monde. 

<!-- .element: style="font-size:1.4rem; text-align:justify" -->


Source : Dominique Cardon, *À quoi rêvent les algorithmes ?*

<!-- .element: class="source" -->

===

En conséquence : un bouleversement de l'autorité, mais plus généralement de notre système de valeur, de notre manière d'évaluer et d'accorder notre confiance à l'évaluation. 

L'évaluation populaire : le nombre d'étoiles d'un film sur AllôCiné et SensCritique, la note d'un bouquin sur BookNode, aura sans doute plus d'impact sur le succès d'une oeuvre que sa critique dans un quotidien national ou sur le Masque Et la Plume. On peut sans doute le déplorer, ou pas, mais c'est un fait à prendre en compte dans la stratégie communicationnelle mise en oeuvre autour d'un produit culturel.

L'autorité, sur ces réseaux, est plus que jamais "fabriquée" (là où sur Google elle doit être en principe "méritée").

§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§

* Tous dans sa bulle (de filtres) ? (Eli Pariser)
  - filtrage de l'information en fonction de notre "profil"
  - isolement intellectuel et culturel
  - un bulle construite par nos choix + les algorithmes


===
La bulle de filtres ou bulle de filtrage (de l’anglais : filter bubble) est un concept développé par le militant d'Internet Eli Pariser. Selon Pariser, la « bulle de filtres » désigne à la fois le filtrage de l'information qui parvient à l'internaute par différents filtres ; et l'état d'« isolement intellectuel » et culturel dans lequel il se retrouve quand les informations qu'il recherche sur Internet résultent d'une personnalisation mise en place à son insu.

§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§
<!-- .slide: data-background-image="img/filtre.png" data-background-size="contain" -->



===

Anesthésie de l'esprit critique : pas de confrontation à d'autres pensées.

Même si le phénomène de bulles de filtre est sans doute exagéré, sur les réseaux, On reste souvent dans une zone de confort. Il y a un biais de confirmation.

>La bulle de filtrage, c’est ça. Ce sont les multinationales Facebook, Twitter et les autres qui fidélisent leur clientèle en concevant des algorithmes qui éliminent, toujours plus efficacement, les avis contraires et les dissonances.

Les études approfondies tendent à montrer que nous sommes en fait relativement exposés à des avis différents. Le problème de fond tendrait plutôt à la variété des informations que l'on peut nous présenter. Facilité à se faire enfermer : conspirationnisme.

§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§
<!-- .slide: data-background-image="img/predictif.jpeg" data-background-size="contain" -->
<!-- .slide: class="hover"-->

### Algorithme prédictif
* dit "sous le web"
* utilise des méthodes statistiques pour calculer / prédire, à partir des traces de nos navigations comparée à celles des internautes ayant effectué le même parcours que nous, nos comportements (= filtrage collaboratif)
* exemple : recommandation Netflix, Amazon, sites d'achat en ligne, publicité ciblée

===

Dernière famille : les mesures prédictives destinées à personnaliser les informations présentées à l’utilisateur déploient quant à elles des méthodes statistiques d’apprentissage pour calculer les traces de navigation des internautes et leur prédire leur comportement à partir de celui des autres.

>Les algorithmes de prédiction personnalisée se proposent de comparer les traces d’activité d’un inter-
naute à celles d’autres internautes qui ont effectué la même action que lui, afin de calculer la probabilité
qu’aura cet internaute d’effectuer telle ou telle nouvelle activité du fait que d’autres qui lui ressemblent
l’auront, eux, déjà effectuée. Dans le monde des algorithmes, on appelle ces méthodes le « filtrage collaboratif ».

§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§
<!-- .slide: data-background-image="img/predictif.jpeg" data-background-size="contain" -->
<!-- .slide: class="hover"-->


* Collecte de données / traces disséminées par l'internaute
* Machine learning (personnalisation du calcul à partir de la comparaison des comportements des internautes)


====

Cet algo est sans doute celui qui utilise le plus nos données perso afin de les comparer à celles des autres. Comprenez l'enjeu : plus vous avez un jeu de données massif, plus vous avez de "comparable", plus votre modèle et votre prédiction seront efficaces.

Les services qui utilisent ce type d'algo sont donc particulièrement gourmand en données. 
Et savent faire un usage parfois inattendu de nos données.


§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§
<!-- .slide: data-background-image="img/effetDarcy.png" data-background-size="contain" -->


===

>Amazon, par exemple, ne se contente pas de savoir quels livres ses clients achètent
sur sa plateforme, il analyse aussi les traces de la
vitesse de lecture sur la liseuse : lire le livre en entier
ou non, sauter des chapitres, etc. 


Une étude a montré que les lecteurs d’Orgueil et Préjugés, de Jane Austen,
lisent plus rapidement les chapitres où apparaît Darcy.

Cette analyse est intéressante à plusieurs titres : organiser la communication autour du livre, choix des couvertures, mais également réécriture du scénario lors d'une adaptation...

§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§
<!-- .slide: data-background-image="img/youtube.png" data-background-size="contain" -->
<!-- .slide: class="hover"-->

* Les algorithmes prédictifs : outils marketing des industries culturelles
* Prédiction ou prescription ?


§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§
<!-- .slide: data-background-image="img/" data-background-size="contain" -->
<!-- .slide: class="hover"-->

### Comprendre la structuration du web : un enjeu ontologique et politique
* Toute médiation joue un rôle structurant et déterminant dans la construction du réel
* Nous construisons des outils pour calculer, structurer, organiser le web...
* Ces calculateurs, en retour, nous construisent à leur tour...

===
En résumé, comprendre le web est un enjeu ontologique et politique.
Je me répète : Le Réel est toujours médié - il n'est donc pas question de dire ici que le numérique est une médiation pire que les autres... Mais puisque toute médiation cherche par nature à se faire oublier, à se rendre transparente, on oublie qu'elles ont un rôle structurant et même déterminant sur le réel. C'est la fonction performative des médias et des représentations.
En raison même de cette tendance à la superposition entre le monde tel qu'il est représenté et ses conceptions, il nous faut au moins être capable de comprendre comment la représentation du monde contemporain s'effectue.


§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§


### Maîtrise de la déprise
* Bien structurer les contenus (en vue de leur organisation / appropriation) = métadonnées
* Comprendre les logiques de recherche / indexation = algorithmes

===
Alors évidemment, un premier comportement pourrait nous pousser vers un rejet total des nouvelles technos... Mais bon, nous n'avons pas tout à fait le choix : on voit bien aujourd'hui qu'elles sont très utiles. Et surtout, la technophobie ne semble pas être une solution sage au long terme.

L'enjeu sera plutôt de maîtriser la déprise imposée par certains outils. La déprise, c'est le fait que nécessairement le fonctionnement de certains outils nous échappe. La maîtrise de cette déprise, c'est de trouver de quoi compenser cette déprise. La première chose : c'est l'éducation ! La connaissance des outils que l'on utilise.s

La fameuse littératie numérique : non pas savoir coder, mais comprendre les présupposés épistémologiques qui guident la construction des outils que nous utilisons chaque jour.

Première leçon, sorte de pré-requis à l'algorithme, c'est la métadonnée.


§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§


>Comme les GPS dans les véhicules, les algorithmes se sont silencieusement glissés dans nos vies. Ils ne nous imposent pas la destination. Ils ne choisissent pas ce qui nous intéresse. Nous leur donnons la destination et ils nous demandent de suivre "leur" route. La conduite GPS s'est si fortement inscrite dans les pratiques des conducteurs que ceux-ci ont parfois perdu toute idée de la carte, des manières de la lire, de la diversité de ses chemins et des joies de l'égarement.
Les algorithmes [procèdent] d'un désir d'autonomie et de liberté. Mais ils contribuent aussi à assujettir l'internaute à cette route calculée, efficace, automatique, qui s'adapte à nos désirs en se réglant secrètement sur le désir des autres. Avec la carte, nous avons perdu le paysage. Le chemin que nous suivons est le "meilleur" pour nous. (Dominique Cardon, *À quoi rêvent les algorithmes*)

<!-- .element: style="font-size:1.7rem; text-align:justify" -->


Source : Dominique Cardon, *À quoi rêvent les algorithmes ?*

<!-- .element: class="source" -->

§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§

## Conclusion
Comment le web est-il construit ? Comment, en d'autres termes, se structure le media qui constitue aujourd'hui notre fenêtre sur le monde, et qui participe à structurer le réel ? L'organisation des contenus sur le web passe par des outils - métadonnées, algorithmes - dont les concepteurs, humains, laissent une signature. Le résultat d'une recherche, d'une navigation, n'est donc jamais neutre. Connaître le fonctionnement de l'indexation est essentiel pour être conscient des biais dans l'organisation des contenus sur les moteurs de recherche ou les grandes plateformes. C'est tout le sens d'une littératie numérique : utiliser en toute conscience, en connaissance de cause, des outils qui font désormais partie de notre quotidien. C'est enfin le sens d'une "maîtrise" de la "déprise".

<!-- .element: style="font-size:1.7rem; text-align:justify" -->
