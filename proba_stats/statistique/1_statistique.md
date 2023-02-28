# Statistiques

La statistique est la discipline qui étudie des phénomènes à travers la collecte de données, leur traitement, leur analyse, l'interprétation des résultats et leur présentation afin de rendre ces données compréhensibles par tous. C'est à la fois une branche des mathématiques appliquées, une méthode et un ensemble de techniques. 

## Définition

Commençons par préciser que donner une définition de la statistique n'est pas chose facile : comme expliqué dans la section précédente, les définitions de la statistique évoluent en fonction de l'époque ou de son utilisation. En 1935, le statisticien Walter F. Willcox dénombrait entre 100 et 120 définitions différentes.

    « Parmi les thèmes à propos desquels les statisticiens ne sont pas d'accord, se trouve la définition de leur science. »
    — Maurice Kendall
   
Donnons en premier lieu, la définition la plus classique actuellement utilisée, au moins depuis 1982 : « La statistique est l'ensemble des méthodes qui ont pour objet la collecte, le traitement et l'interprétation de données d'observation relatives à un groupe d'individus ou d'unités. » Par cette définition, la statistique apparaît comme une science autonome, orientée vers les données, comme la physique l'est vers la matière et la biologie vers la vie. Mais comme elle s'appuie sur la théorie des probabilités, étant elle-même une science de l'aléatoire, (voir Interconnexions entre la théorie des probabilités et la statistique pour plus de détails), elle apparaît souvent, en particulier d'un point de vue universitaire, comme une branche des mathématiques appliquées. Aujourd'hui, elle s'inscrit dans un champ disciplinaire plus transverse que les anglo-saxons nomment « Data Science » et dans lequel par ailleurs, l'informatique a elle aussi une place importante. Les différents aspects de la statistique sont regroupés en différents domaines ou concepts : la statistique descriptive, plus couramment appelée aujourd'hui statistique exploratoire, l'inférence statistique, la statistique mathématique, l'analyse des données, l'apprentissage statistique, etc. 

John Tukey prétend qu'il y a deux approches en statistiques, entre lesquelles on jongle constamment : les statistiques exploratoires et les statistiques confirmatoires (exploratory and confirmatory statistics) :

-  on explore d'abord les données pour avoir une idée experte du fonctionnement du système qu'elles représentent, ce qui permet de formuler des hypothèses cognitives sur les phénomènes mis en jeu, de leurs propriétés ;
- puis à partir de ces hypothèses de comportement, on élabore des expériences permettant de les confirmer ou de les infirmer en recourant à d'autres techniques statistiques.

## Domaines d'application

En 1982, le statisticien Pierre Dagnelie propose trois grandes tendances de la statistique9 :

- la statistique qualifiée d'« administrative » ou « gouvernementale » faite dans les instituts de statistique à propos de grands ensembles de données, ;
- la statistique dite « mathématique » ou « universitaire » faite avec peu de données et qui a pour but la novation ;
- enfin la statistique « appliquée » ou « de terrain » faite dans les instituts de sondage d'opinion ou les facultés de médecine pour des problèmes concrets.

Dans la pratique, les méthodes et outils statistiques sont utilisés dans des domaines tels que :

- géophysique, pour les prévisions météorologiques, la climatologie, la pollution, les études des rivières et des océans ;
- démographie : le recensement permet de faire une photographie à un instant donné d'une population et permettra par la suite des sondages dans des échantillons représentatifs ;
- sciences économiques et sociales, et en économétrie : l'étude du comportement d'un groupe de population ou d'un secteur économique s'appuie sur des statistiques. C'est dans cette direction que travaille l'Insee. Les questions environnementales s'appuient également sur des données statistiques ;
- sociologie : les sources statistiques constituent des matériaux d'enquête, et les méthodes statistiques sont utilisées comme techniques de traitement des données ;
- marketing : le sondage d'opinion devient un outil pour la décision ou l'investissement ;
- dans les jeux de hasard et les paris tels que le loto ou les paris équestres, pour « prévoir » les résultats ;
- physique : l'étude de la mécanique statistique et de la thermodynamique statistique (cf Physique statistique) permet de déduire du comportement de particules individuelles un comportement global (passage du microscopique au macroscopique) ;
- métrologie, pour tout ce qui concerne les systèmes de mesure et les mesures elles-mêmes ;
- production industrielle, avec des outils comme la Maîtrise Statistique des Procédés ;
- médecine et en psychologie, tant pour le comportement des maladies que leur fréquence ou la validité d'un traitement ou d'un dépistage ;
- archéologie, appliquée aux vestiges (céramologie, archéozoologie...) ;
- écologie, pour l'étude des communautés végétales et des écosystèmes ;
- assurance et en finance (calcul des risques, actuariat, etc.) ;
- informatique, surtout en algorithmique (anti-crénelage, interpolation numérique) ;
- génomique : le problème de détection de ruptures sert à étudier différents types de cancers.

## Statistique descriptive et statistique mathématique

Le but de la statistique est d'extraire des informations pertinentes d'une liste de nombres difficile à interpréter par une simple lecture. Deux grandes familles de méthodes sont utilisées selon les circonstances. Rien n'interdit de les utiliser en parallèle dans un problème concret mais il ne faut pas oublier qu'elles résolvent des problèmes de natures totalement distinctes. Selon une terminologie classique, ce sont la statistique descriptive et la statistique mathématique. Aujourd'hui, il semble que des expressions comme analyse des données et statistique inférentielle soient préférées, ce qui est justifié par le progrès des méthodes utilisées dans le premier cas.

Considérons par exemple les notes globales à un examen. Il peut être intéressant d'en tirer une valeur centrale qui donne une idée synthétique sur le niveau des étudiants. Celle-ci peut être complétée par une valeur de dispersion qui mesure, d'une certaine manière, l'homogénéité du groupe. Si on veut une information plus précise sur ce dernier point, on pourra construire un histogramme ou, d'un point de vue légèrement différent, considérer les déciles. Ces notions peuvent être intéressantes pour faire des comparaisons avec les examens analogues passés les années précédentes ou en d'autres lieux. Ce sont les problèmes les plus élémentaires de l'analyse des données qui concernent une population finie. Les problèmes portant sur des statistiques multidimensionnelles nécessitent l'utilisation de l'algèbre linéaire. Indépendamment du caractère, élémentaire ou non, du problème il s'agit de réductions statistiques de données connues dans lesquelles l'introduction des probabilités améliorerait difficilement l'information obtenue. Il est raisonnable de regrouper ces différentes notions :

- statistique descriptive pour les notions élémentaires ;
- analyse en composantes principales ;
- analyse factorielle des correspondances ;
- analyse discriminante ;
- visualisation des données ;
- etc.

Un changement radical se produit lorsque les données ne sont plus considérées comme une information complète à décrypter selon les règles de l'algèbre mais comme une information partielle sur une population plus importante, généralement considérée comme une population infinie. Pour induire des informations sur la population inconnue il faut introduire la notion de loi de probabilité. Les données connues constituent dans ce cas une réalisation d'un échantillon, ensemble de variables aléatoires supposées indépendantes (voir Loi de probabilité à plusieurs variables). La théorie des probabilités permet alors, entre autres opérations :

- d'associer les propriétés de l'échantillon à celles qui sont prêtées à la loi de probabilité, inconnue en toute rigueur, c'est l'échantillonnage ;
- de déduire inversement les paramètres de la loi de probabilité des informations que donne l'échantillon, c'est l'estimation ;
- de déterminer un intervalle de confiance qui mesure la validité de l'estimation ;
- de procéder à des tests d'hypothèse, le plus utilisé étant le test du χ² pour mesurer l'adéquation de la loi de probabilité choisie à l'échantillon utilisé ;
- etc.

## La démarche statistique

### Recueil des données

L'enquête statistique est toujours précédée d'une phase où sont déterminés les différents caractères à étudier.

L'étape suivante consiste à choisir la population à étudier. Il se pose alors le problème de l'échantillonnage : choix de la population à sonder (au sens large : cela peut être un sondage d'opinion en interrogeant des humains, ou bien le ramassage de roches pour déterminer la nature d'un sol en géologie), la taille de la population et sa représentativité.

Que ce soit pour un recueil total (recensement) ou partiel (sondage), des protocoles sont à mettre en place pour éviter les erreurs de mesures qu'elles soient accidentelles ou répétitives (biais).

Le pré traitement des données est extrêmement important, en effet, une transformation des données initiales (un passage au logarithme, par exemple), peuvent considérablement faciliter les traitements statistiques suivants. 

### Traitement des données

Le résultat de l'enquête statistique est une série de données quantitatives (tailles, salaires) ou de données qualitatives (langues parlées, marques préférées). Pour pouvoir les exploiter, il va être nécessaire d'en faire un classement et un résumé visuel ou numérique. Il sera parfois nécessaire d'opérer une compression de données. C'est le travail de la statistique descriptive. Il sera différent selon que l'étude porte sur une seule ou sur plusieurs variables. 

#### Étude d'une seule variable

Le regroupement des données, le calcul des effectifs, la construction de graphiques permettent un premier résumé visuel du caractère statistique étudié. Dans le cas d'un caractère quantitatif continu, l'histogramme en est la représentation graphique la plus courante. 

Les valeurs numériques d'un caractère statistique se répartissent dans R, il est nécessaire de définir leurs positions. En statistiques, on est en général en présence d'un grand nombre de valeurs. Or, si l'intégralité de ces valeurs forme l'information, il n'est pas aisé de manipuler plusieurs centaines voire milliers de données, ni d'en tirer des conclusions. Il faut donc calculer quelques valeurs qui vont permettre d'analyser les données : c'est le rôle des réductions statistiques. Celles-ci peuvent être extrêmement concises, réduites à un nombre : c'est le cas des valeurs centrales et des valeurs de dispersion. Certaines d'entre elles (comme la variance) sont élaborées pour permettre une exploitation plus théorique des données (voir Inférence statistique). 

On peut aussi chercher à comparer deux populations. On s'intéressera alors plus particulièrement à leurs critères de position, de dispersion, à leur boîte à moustaches ou à l'analyse de la variance.

#### Étude de plusieurs variables

Les moyens informatiques permettent aujourd'hui d'étudier plusieurs variables simultanément. Le cas de deux variables va donner lieu à la création d'un nuage de points, d'une étude de corrélation éventuelle entre les deux phénomènes ou d'une étude de régression linéaire.

Mais on peut rencontrer des études sur plus de deux variables : c'est l'analyse multidimensionnelle dans laquelle on va trouver l'analyse en composantes principales, l'analyse en composantes indépendantes, la régression linéaire multiple et l'exploration de données (appelée aussi « knowledge discovery » ou « data mining »). Aujourd'hui, l'exploration de données s'appuie, entre autres, sur la statistique pour découvrir des relations entre les variables de très vastes bases de données. Les avancées technologiques (augmentation de la fréquence des capteurs disponibles, des moyens de stockage, et de la puissance de calcul) donnent à l'exploration de données, un réel intérêt.

### Interprétation et analyse des données

L'inférence statistique a pour but de faire émerger des propriétés d'un ensemble de variables connues uniquement à travers quelques-unes de ses réalisations (qui constituent un échantillon de données).

Elle s'appuie sur les résultats de la statistique mathématique, qui applique des calculs mathématiques rigoureux concernant la théorie des probabilités et la théorie de l'information aux situations où on n'observe que quelques réalisations (expérimentations) du phénomène à étudier.

Sans la statistique mathématique, un calcul sur des données (par exemple une moyenne), n'est qu'un indicateur. C'est la statistique mathématique qui lui donne le statut d'estimateur dont on maîtrise le biais, l'incertitude et autres caractéristiques statistiques. On cherche en général à ce que l'estimateur soit sans biais, convergent (ou consistant) et efficace.

On peut aussi émettre des hypothèses sur la loi générant le phénomène général, par exemple « la taille des enfants de 10 ans en France suit-elle une loi gaussienne ? ». L'étude de l'échantillon va alors valider ou non cette hypothèse : c'est ce qu'on appelle les tests d'hypothèses. Les tests d'hypothèses permettent de quantifier la probabilité avec laquelle des variables (connues seulement à partir d'un échantillon) vérifient une propriété donnée.

Enfin, on peut chercher à modéliser un phénomène a posteriori. La modélisation statistique doit être différenciée de la modélisation physique. Dans le second cas, des physiciens (c'est aussi vrai pour des chimistes, biologistes, ou tout autre scientifique), cherchent à construire un modèle explicatif d'un phénomène, qui est soutenu par une théorie plus générale décrivant comment les phénomènes ont lieu en exploitant le principe de causalité. Dans le cas de la modélisation statistique, le modèle va être construit à partir des données disponibles, sans aucun a priori sur les mécanismes entrant en jeu. Ce type de modélisation s'appelle aussi modélisation empirique. Compléter une modélisation statistique par des équations physiques (souvent intégrées dans les pré traitements des données) est toujours positif.

Un modèle est avant tout un moyen de relier des variables à expliquer Y Y à des variables explicatives X X, par une relation fonctionnelle :

    Y = F ( X ) Y=F(X)

Les modèles statistiques peuvent être regroupés en grandes familles (suivant la forme de la fonction F F):

    les modèles linéaires ;
    les modèles non linéaires ;
    les modèles non paramétriques.

Les modèles bayésiens (du nom de Bayes) peuvent être utilisés dans les trois catégories. 

### Statistique mathématique

Cette branche des mathématiques, très liée aux probabilités, est indispensable pour valider les hypothèses ou les modèles élaborés dans la statistique inférentielle. La théorie mathématiques des probabilités formalise les phénomènes aléatoires. Les statistiques mathématiques se consacrent à l'étude de phénomènes aléatoires que l'on connaît via certaines de ses réalisations.

Par exemple, pour une partie de dés à six faces :

    le point de vue probabiliste est de formaliser un tel jeu par des probabilités p 1 , p 2 , … , p 6 p_{1},p_{2},\ldots ,p_{6} associées aux événements la première, deuxième..., sixième face est tirée. La théorie des probabilités nous dit par exemple que pour que ces probabilités forment une loi de probabilité, il est nécessaire que ∑ n = 1 6 p n = 1 \sum _{{n=1}}^{6}p_{n}=1. On peut alors étudier différentes propriétés de ce jeu ;
    une fois cela fixé, les statistiques s'intéressent alors à ce genre de question : « Si au bout de 100 parties, chaque face n n a été tirée f n f_n fois, puis-je avoir une idée de la valeur des probabilités p 1 , p 2 , … , p 6 p_{1},p_{2},\ldots ,p_{6} ? Avec quel degré de confiance ? »

Une fois la règle établie, elle peut être utilisée en statistique inférentielle. 

## Sources

- https://fr.wikipedia.org/wiki/Statistique
- https://fr.wikipedia.org/wiki/Inf%C3%A9rence_statistique
- https://fr.wikipedia.org/wiki/Statistique_math%C3%A9matique
- https://fr.wikipedia.org/wiki/Statistique_descriptive
- https://fr.wikipedia.org/wiki/Interconnexions_entre_la_th%C3%A9orie_des_probabilit%C3%A9s_et_la_statistique
- https://fr.wikipedia.org/wiki/Th%C3%A9orie_des_probabilit%C3%A9s
- https://fr.wikipedia.org/wiki/Loi_de_probabilit%C3%A9
- https://fr.wikipedia.org/wiki/Anticr%C3%A9nelage
- https://fr.wikipedia.org/wiki/Interpolation_num%C3%A9rique
