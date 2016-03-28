![Université de Lorraine](/images/udl.jpg)

#*Historique de la Fraude au Président*  
**Un rapport de Sécurité des Réseaux présenté par**  
*Benjamin Joly et Déborah Servili*  
**pour l'obtention de leur M2 Informatique**

*Académie de Nancy-Metz*  
*Université de Lorraine*  
*Unité de Formation et Recherche Mathématique, Informatique et Mécanique*  
*Département Informatique*  
*Spécialité SSSR – Formation SSI*  
*Année 2015-2016*

##Sommaire

###[Introduction](https://github.com/BenjaminJoly/Historique-Fraude-Au-President/blob/master/Historique%20de%20la%20Fraude%20au%20President.md#introduction-1)
###[I. La fraude au président : Qu'est-ce ?](https://github.com/BenjaminJoly/Historique-Fraude-Au-President/blob/master/Historique%20de%20la%20Fraude%20au%20President.md#i-la-fraude-au-pr%C3%A9sident--quest-ce--1)
###[II. Prévenir l'escroquerie : Pistes de Réflexion](https://github.com/BenjaminJoly/Historique-Fraude-Au-President/blob/master/Historique%20de%20la%20Fraude%20au%20President.md#ii-pr%C3%A9venir-lescroquerie--pistes-de-r%C3%A9flexion-1)
###[Conclusion](https://github.com/BenjaminJoly/Historique-Fraude-Au-President/blob/master/Historique%20de%20la%20Fraude%20au%20President.md#conclusion-1)
======

##Introduction

Dans le cadre de notre Master 2 en Sécurité des Systèmes d'Information, nous avons réalisé une étude sur l'une des attaque du domaine du *social engineering* : La fraude au président. Cette attaque touchant en grande majorité de pays francophone rapporte des millions à certains, et de la même façon fait perdre d'autre millions à d'autres. Mais souvent, les conséquences peuvent être pires que de simples euros perdus ... 

Comment un type d'attaque qui a plus de 10 ans a-t-il pu fleurrir autant ? Comment cela fonctionne, et comment une simple usurpation d'identitée peu faire si peur au peu de nombre de personnes sensibilisés au sujet ? Comment pourrions nous prévenir ce phénomène plutôt que de chercher a le guérir ? Tant de question que nous sommes légitimement en droit de nous poser. 

Dans un premier temps, nous allons nous concentrer sur le phénomène : Qu'est-il, quel est son but ? Après avoir répondu à ces questions, nous allons parler d'exemple et de chiffre, pour montrer que le problème est relativement grave, puissant, inévitable et qui ne doit pas être sous estimé, comme il l'est de nos jours. Et enfin, pour apporter un peu d'optimisme a tout ce noir tableau, nous donnerons des solutions possibles, des pistes de réflexions que nous avons eu pour essayer d'endiguer ce problème.

##I. La fraude au président : Qu'est-ce ? 

L’attaque de type « fraude au président » ne date pas d’hier. Le premier cas a en effet eu lieu le 25 juillet 2005, au lendemain des attentats de Londres. A Paris, la directrice d’une Banque Postale est contactée par une personne se présentant comme le PDG de la Poste. Cette dernière lui explique qu’un agent secret va prendre contact avec elle et solliciter son aide dans le cadre d’une opération visant à arrêter des terroristes planifiant de nouveaux attentats. Bien entendu, l’opération doit être tenue secrète, personne ne doit être au courant, la jeune femme a même l’interdiction d’évoquer le sujet avec son PDG quelques soient les circonstances. Le fameux agent lui demande d’acheter un nouveau téléphone portable, privé, afin de pouvoir la contacter à n’importe quelle heure du jour ou de la nuit. Enfin, il lui explique sa tâche : Elle doit emporter une grande somme d’argent, un peu moins d’un demi-million d’euros, en espèces, dans une mallette qu’elle emmène alors dans un café parisien. Après un temps d’attente, elle descend dans les toilettes de l’établissement, attendant le prochain signal de son interlocuteur. Lorsque celui-ci frappe à la porte et lui donne le mot de passe, elle n’a qu’à lui faire glisser la mallette par l’entrebâillement de la porte. Elle n’a pas autorisation de regarder le visage de l’agent qui doit marquer les billets afin de pouvoir les tracer par la suite avant de les lui rendre. L’employée de la Banque Postale s’exécute sans discuter, et tout le plan se déroule sans encombre, à une exception près… Elle ne reverra jamais ni la mallette, ni les espèces.

L’auteur de ce coup de culot se nomme Gilbert Chikli, c’est lui qui du début à la fin a manipulé la jeune femme jusque dans les toilettes de ce café. Sa compagne de l’époque, Shirley Vacaint, le secondait, étant celle qui a récupéré l’argent. Leur idée était de profiter du climat post attentat afin de monter leur arnaque. Bien sûr, c’était un énorme coup de poker, un énorme coup de bluff, mais il a porté ses fruits et le couple s’est échappé avec près de 350 000€. Si la jeune femme a décidé de s’arrêter après ce coup de poker, Chilki, lui a continué l’arnaque, piégeant plus d’une trentaine d’entreprises entre juillet 2005 et fin 2006, pour un gain de 7,9 millions d’euros. Parmi ses victimes, la Banque Postale bien sûr, mais aussi le Crédit Lyonnais, les Pages Jaunes, les Galeries Lafayettes, ou encore la société Accenture. 

Et si aujourd’hui l’homme affirme avoir arrêté ses escroqueries, ce n’est pas pour autant que l’arnaque au président n’existe plus. En effet, malgré un creux depuis 2006, ces attaques sont de retour depuis 2010, et toujours en hausse.  De plus, si à l’origine elles ne concernaient que des entreprises françaises, aujourd’hui le scope des cibles s’étend non seulement aux pays francophones, tels que le Luxembourg ou la Belgique, mais aussi désormais le Royaume Uni ou même les Etats-Unis. Et si la stratégie globale reste la même, de nombreux scénarios ont désormais vu le jour. 

En effet, à côté de l’histoire de lutte contre le terrorisme est arrivé le script d’une OPA secrète, où le PDG demande au service comptable de virer de l’argent sur un compte étranger, ou celui du changement de RIB où, se faisant passer pour un fournisseur de l’entreprise, l’escroc demande au comptable de procéder à un changement de coordonnées bancaires, flouant à la fois l’entreprise visée et son fournisseur. D’autres scénarios plus ou moins exotiques ou efficaces ont également vu le jour. Notamment une arnaque basée sur les virements SEPA, afin de tester leur bon fonctionnement. L’escroc propose alors d’effectuer un premier virement, qui sera restitué, puis un second, où l’argent disparait.  Ou encore le plus original sans doute, où l’escroc s’est fait passer pour le ministre français de la Défense, Jean-Yves Le Drian, et, contactant des présidents africains, leur demander de procéder au paiement de rançon de ressortissants français retenus en otage dans leur pays. Fort heureusement, ce scénario n’a jamais porté ses fruits, mais ce n’est pas le cas des autres. 

Les victimes sont de ces arnaques sont de plus en plus nombreuses, et aux victimes directement imputables à Chikli se rajoutent des grands groupes tels que KPMG ou Michelin, mais aussi des PME. Voici d’ailleurs ci-dessous un résumé des plus grands succès de cette escroquerie et de ses variantes.

![Tableau contenant des exemples de fraude au président](/images/TableauEntreprisesFaraudeAuPresident.PNG)

##II. Prévenir l'escroquerie : Pistes de Réflexion

###A. Agir sur les causes

Si nous voulons pouvoir agir sur les causes d'un problème, il est assez important de les comprendre. C'est une tâche relativement complexe, car comprendre tous les vecteurs nécessite un recul assez important : Pour comprendre un évènement sur une frise chronologique, il est important de regarder ce qui l'a provoqué, en reculant notre regard pour avoir une bonne vue d'ensemble. Cependant, nous pouvons nous questionner sur notre habilité, actuellement, à pouvoir nous reculer : Les évènements récents n'ont peut-être pas encore dévoilés toutes les causes qui les ont amenés...

Deux remarques peuvent se faire, des correlations assez simples, néanmoins il est de notre devoir de le relever : Dans un premier temps, il semble évident que beaucoup d'entreprises visées sont francophones. Par ailleurs beaucoup de ceux qui réalisent ces attaques viennent également d'un pays avec un passé francophone. Et dans un second temps, nous pouvons citer la hierarchie relativement floue qui compose ses entreprises. Nous n'avons pas trouvé de réelle cause supplémentaire, mais nous n'avons probablement pas tout le recul nécessaire.

Outre le fait que l'"instigateur" de cette attaque soit d'originne franco-israëlienne, réglant de façon quasi automatique ce fait que le lieu de départ de l'attaque est de l'Israël vers le France, cela n'explique pas pourquoi il semble si difficile d'exporter ce modèle. Ce fait est probablement une question de conditions et d'hasards malheureux qui ont fini par offrir le cadre si parfait dont raffole ces criminels. 

Si on repart au Moyen-Âge, nous avions une hiérarchie déjà omniprésente par l'idée de la monarchie. L'histoire particulière de Jean-Baptiste Drouet lors de la révolution française montre bien que Louis XVI et sa famille avaient failli passer, avant que ce dernier ne le reconnaisse sur un assignat de 50 livres. Par la suite, la période de terreur a probablement aidé à ce principe à poursuivre sa route, et pour finir, l'empire Napoléonien et les différentes colonies françaises se sont chargés de la transmission de ce principe, laissant des marques encore aujourd'hui. C'est donc notre culture qui est la plus probable responsable de cet état de fait : Nous sommes les plus sensibles à cette fraude. En résultat, de nos jours, les hiérarchies sont souvent tellement verticales qu'il nous est parfois possible de n'avoir jamais vu le dirigeant de notre lieu de travail. 

De plus, nous avons parlé d'hasard malheureux : Gilbert Chikli, premier instigateur supposé de cette arnaque a également profité de chaos laissé par les attentats de Londres lors de Juillet 2005. Le climat de peur installé par ces évènements a laissé pour ce franco-israëlien une excuse en or pour pouvoir réaliser la fraude au président qui a touché Laposte. Tous ces évènements ont créé un contexte socio-économico-culturel idéal pour cette attaque. 

Que faire contre ce fait ? Nous avons été ainsi éduqué, et si nous pouvons bien entendu agir chacun de notre côté, en apprenant par exemple à nos successeurs la nécessité d'une hiérarchie moins mystérieuse et donc moins verticale, nous parlerions ici de changer ce qui fait de nous ce que nous sommes. Nous pouvons néanmoins prévenir les attaques en la rendant célèbre et classique, pour rendre les gens un peu plus méfiant de ce qui peut leur arriver. Pour cela, un moyen semble venir naturellement aux yeux : La formation. Apprendre à résister à une pression forte, expliquer les manipulations... Mais aussi apprendre à communiquer avec toutes les personnes avec qui nous travaillons. 

Une autre solution envisageable pourrait être une contre offensive. Les arnaqueurs utilisent beaucoup, comme nous l'avons vus, la collecte d'information. Pourquoi ne pas retourner cette pratique contre eux, en leur donnant par exemple des informations qui sont fausses. Ce qu'on appelle un *honeypot*. Ainsi, remarquer l'attaque, s'ils possèdent cette fausse information que nul ne dois possèder et qu'elle est prise au sérieux, alors il s'agit bien là la preuve recherchée. 

Concernant les causes, il s'agit de ce que nous en avons conclu. Mais concernant les conséquences, comment devons-nous agir ?

###B. Agir sur les conséquences

Un incident de ce genre a souvent de graves conséquences. Autant sur l'entreprise qui se fait visée que sur les personnes qui se font toucher par ce véritable harcèlement. Dans le cas d'un tel virement suspiceux, d'une étrange transaction dans les comptes, il est important déjà de discuter avec les personnes dans l'entreprise. Souvent, ce sont les personnes externes à l'arnaque qui ont le plus de chance et de facilité à déceler ce genre de problème.

Si l'arnaque a déjà démarré, il semble également important de contacter au plus vite les autorités compétentes pour pouvoir geler au plus vite les virements s'il n'est pas trop tard. C'est en effet en agissant au plus vite que les conséquences seront les moins graves possibles. 

Enfin, il est aujourd'hui possible d'avoir une assurance pour ce genre de scénarios. Bien sûr, il ne s'agit là que d'un paliatif, et non d'une réelle solution. Mais la solution existant, il semblait réellement indispensable d'en parler ici. 

Voici les solutions auxquelles nous avons réfléchi. Au final, beaucoup d'entre elles ne sont que du bon sens, auquel nous ne pouvons pas toujours penser, mais qu'il est important de se rappeller. Et c'est pour cette raison que ce type de rapport a son importance dans la société. 

##Conclusion

Au final, nous avons défini ce que nous appellions fraude au président. Nous avons analysé et regardé de multiples exemples, de cas différents pour avoir une bonne idée des démarches qui avaient été réalisées. Egalement savoir ce qui avait été efficace et ce qui ne l'avait pas été pour nous donner une idée des meilleurs comportements à adopter dans les cas présents, que nous avons présenté dans la dernière partie. 

Mais nous n'avons en aucun cas pu tester nos différentes propositions, et cela aurait été impossible dans le cadre d'un simple projet scolaire comme celui-ci. Ce qui est donc présenté dans ce rapport n'est que le résultat de la réflexion de deux étudiants en dernière année de sécurité informatique. Néanmoins, la suite logique de ce rapport serait de réaliser les tests qui s'imposent pour vérifier que nos suppositions sont véridiques. Mais une telle étude serait coûteuse en temps...

Nous remercions bien entendu l'université de Lorraine, ainsi que nos deux professeurs Messieurs A. Dulaunoy et R. Vinot de nous avoir permis de réaliser une telle étude, ainsi que les diverses idées qui nous ont été données. 
