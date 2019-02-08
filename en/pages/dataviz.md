# Graph visualization

## Academic context
I created these graphs for **Franck Ghitalla**'s network science course. In these graphs, each edge is a hyperlink and a node is a web entity. To create these graphs, I just needed to realize few simple crawls.

Thanks to this kind of graph, we can visualize and analyze strategies for occupation of web territory. We can also consider social organizations thanks to the web content production.

I studied the strategy of occupation of several groups : far right, Scientology and Jehovah's Witnesses. I choosed to show only the graphe about Scientology because I consider it as the most clean and atypical.

## Graph on Scientology's strategy of web occupation
Sur le graphe ci-dessous, on peut visualiser une occupation du territoire numérique très bien conçue par la Scientologie. Pour obtenir ce graphe, il a simplement fallu crawl (avec une profondeur donnée) à partir de scientology.org. Aucun traitement supplémentaire ou nettoyage des résultats a été nécessaire.

[Web Version of the graph](Scientologie/index.html)

### *Caption*: 

* Node : Web site/entity
* Edge : Hyperlink beteen two entities
* Color/Size : node degree

![Graphe Scientologie](uploads/images/sciento.png)

### Graph analysis: 
* Le Web de la Scientologie **ressemble à un sorte intranet**, il n'y a aucun lien qui se dirige vers le Web *classique* tel que *Youtube*, etc.
* Les noeuds ont un **degré extrêmement grand** : généralement sur un échantillon de cette taille, l'entité avec le plus grand degré est Youtube. 
Ici, les entités au plus grand degré sont pointées par près de 90% des sites.
* Il y a une **densité très grande** (créant cette forme ronde)
* Il y a deux pôles: un religieux (scientology.org,...) et un culturel (Dianetics.org,...)
* Plus on s'éloigne du centre, plus les sites correspondent à des entités locales (Scientologi.se, Scientology-Detroit.org,...)
* Il y a très peu de noeuds français et ces noeuds ont un degré extrêmement faible

### Conclusions:
Scientology deployed a very cleaver Web occupation. Firstly, we notice the existence of a cultural pole which could be a important entry point to the religious part of Scientology. The idea of not having outbound links in this cluster allows to keep the users in the Scientology Web. The big degrees grants a vey good ranking by Google algorithms. Finally, the local entities have low degrees because they present an interest for "believers" who have a daily use of these websites. They are like the end of the road in the Scientology Web. 

The low degree of french nodes is a strong argument to explain the small presence of Scientology in France (compared to other countries). Therefore, we notice that Scientology haven't succeed in deploying their strategy of Web occupation in France yet.

## Technologies
* Python (crawler)
* Gephi
* Hyphe
