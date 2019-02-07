# Graph visualization

## Academic context
I created these graphs for **Franck Ghitalla**'s network science course. In these graphs, each edge is a hyperlink and a node is a web entity. To create these graphs, I just needed to realize few simple crawls.

Thanks to this kind of graph, we can visualize and analyze strategies for occupation of web territory. We can also consider social organizations thanks to the web content production.

I studied the strategy of occupation of several groups : far right, Scientology and Jehovah's Witnesses. I choosed to show only the graphe about Scientology because I consider it as the most clean and atypical.

## Graph on Scientology's strategy of web occupation
Sur le graphe ci-dessous, on peut visualiser une occupation du territoire numérique très bien conçue par la Scientologie. Pour obtenir ce graphe, il a simplement fallu crawl (avec une profondeur donnée) à partir de scientology.org. Aucun traitement supplémentaire ou nettoyage des résultats a été nécessaire.

[Web Version of the grap](Scientologie/index.html)

### *Caption*: 

* Node : Web site/entity
* Edge : Hyperlink beteen two entities
* Color/Size : node degree

![Graphe Scientologie](uploads/images/sciento.png)

### Analyse du graphe: 
* Le Web de la Scientologie **ressemble à un sorte intranet**, il n'y a aucun lien qui se dirige vers le Web *classique* tel que *Youtube*, etc.
* Les noeuds ont un **degré extrêmement grand** : généralement sur un échantillon de cette taille, l'entité avec le plus grand degré est Youtube. 
Ici, les entités au plus grand degré sont pointées par près de 90% des sites.
* Il y a une **densité très grande** (créant cette forme ronde)
* Il y a deux pôles: un religieux (scientology.org,...) et un culturel (Dianetics.org,...)
* Plus on s'éloigne du centre, plus les sites correspondent à des entités locales (Scientologi.se, Scientology-Detroit.org,...)
* Il y a très peu de noeuds français et ces noeuds ont un degré extrêmement faible

### Conclusions:
La Scientologie a très bien réfléchi son occupation du Web. Premièrement, l'existence du pôle culturel moins connoté religion représente une porte d'entrée vers la Scientologie. L'idée d'avoir des pages sans lien sortant de ce cluster Scientologie permet de conserver ses internautes. Les degrés très grands permettent un très bon référencement par l'algorithme de Google. Enfin, les déclinaisons locales ont des degrés très faibles car elles représentent des entités utiles pour des "croyants" confirmés et à l'utilisation plus quotidienne. Ces sites sont donc le bout du chemin pour un utilisateur. 

Le degré des noeuds français est un argument explicant la présence moindre de cette secte en France par rapport à d'autres pays. Ainsi, on constate que la stratégie d'occupation du territoire numérique n'a pas été encore appliqué sur le Web français.

## Technologies
* Python (crawler)
* Gephi
* Hyphe
