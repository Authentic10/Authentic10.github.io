---
title: "Fatal Encounters"
description: "Fatal Encounters documente les décès non policiers qui se produisent lorsque la police est présente ou qui sont précipités par l'action ou la présence de la police."
---
<div style="text-align:justify;">L'objectif de ce post est d'explorer le jeu de données <a href="https://fatalencounters.org/" target="_blank">Fatal Encounters</a>. Tout d'abord, nous avons défini un ensemble de questions. Ensuite, nous avons créé des graphiques pour répondre à ces questions et enfin, nous avons commenté ces graphes.</div><br/>
<div style="text-align:justify;">Fatal Encounters documente les décès non policiers qui se produisent lorsque la police est présente ou qui sont précipités par l'action ou la présence de la police. Il documente tous les enregistrements disponibles pour les 50 États des États-Unis, jusqu'en 2000.</div><br/>
<div style="text-align:justify;"> Le plan de ce post se présente comme suit : </div>

- Partie 1 : <a href="#exploration"> Exploration</a>
     1. <a href="#race">Visualisation sur les races</a>
     2. <a href="#state">Visualisation sur les États</a>
     3. <a href="#other">Autres visualisations</a>
- Partie 2 : <a href="#summary"> Résumé</a>


<h2 id="exploration">Partie 1 : Exploration</h2>

<h3 id="race">1. Visualisation sur les races</h3>

- Question 1 : Quelle est la répartition des décès ?

![repartition_by_race](/graph-1.png)

- Question 2 : Quelle est l'évolution des décès ?

![evolution_by_race](/graph-2.png)

- Question 3 : Quelle est la cause la plus fréquente de décès ?

![comparaison_men_women](/graph-3.png)

<br/>
<div style="text-align:justify;">Avec le graphique d'évolution produit, nous pouvons voir l'évolution par race mais nous pouvons conclure que les décès ont fortement augmenté autour des années 2014 et 2015 mais diminuent depuis 2018 de manière générale. Le dernier graphique montre que les personnes sont plus tuées par balle.</div>


<h3 id="state">2. Visualisation sur les États </h3>


- Question 4: Quel État compte le plus grand nombre de décès ? ?


![deaths_by_states](/graph-4.png)

<br/>
<div style="text-align:justify;">Le graphique ci-dessus montre que la Californie et le Texas sont les États où l'on enregistre le plus de décès. Ce n'est pas surprenant car ils ont respectivement les populations les plus importantes. C'est la même chose pour la Floride et d'autres états également, donc d'après les données, nous pouvons dire qu'il y a une corrélation entre la population et le nombre de décès. Vérifions cette hypothèse à l'aide du graphique suivant.</div>

- Question 5 : Y a-t-il une corrélation entre la population et le nombre de décès ?

![correlation_population_deaths](/graph-5.png)

<br/>
<div style="text-align:justify;">Le graphique montre qu'il existe une forte corrélation entre la population et le nombre de décès. Cela confirme notre hypothèse.</div>


<h3 id="other">3. Autres visualisations</h3>


- Question 6 : Quelle est la distribution des âges ?


![distribution_ages](/graph-6.png)

<br/>
<div style="text-align:justify;">Ce graphique montre que les personnes qui meurent le plus se situent dans la tranche d'âge de 20 à 50 ans.</div>

<h2 id="summary">Partie 2 : Résumé</h2>
<br/>
<div style="text-align:justify;"> En résumé, nous avons exploré le jeu de données Fatal Encounters en créant des graphiques pour répondre à des questions que nous avions définies. Nous avons constaté qu'il y a plus de personnes blanches enregistrées et cela est sûrement dû au fait qu'il y a plus de personnes blanches que d'autres races. Nous avons également constaté qu'il y a une corrélation entre la population et le nombre de décès et que les gens meurent en général par balle. L'évolution des décès est en baisse depuis 2018.</div>
