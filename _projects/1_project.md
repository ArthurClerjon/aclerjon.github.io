---
layout: page
title: Les usages de l'énergie
description: Analyse du système énergétique français et leviers de décarbonation
img: assets/img/Sankey/Itese_Sankey_Gradient.png
importance: 1
category: Usages de l'énergie en France
related_publications: true
---


<div class="alert alert-warning text-center">
  <strong>Attention :</strong> Page en cours de construction.
</div>

<div style="text-align: center;">
  <h2>La France dépend encore majoritairement des énergies fossiles.</h2>
  <h3>Quels leviers pour décarboner ?</h3>
</div>

<div class="alert alert-secondary">
J'ai réalisé ce travail entre 2022 et 2023 au sein du CEA I-Tésé. Dans une dynamique de capitalisation et regroupement de mes production, je le présente sur cette page. Le document original est disponible <a href="https://www.cea.fr/energies/i-tese/Pages/Actualites/Focus-Thematiques/usages-energie-france.aspx" target="_blank">ici.</a>.
</div>


#### Résumé  
Nous avons construit une représentation graphique des flux entre la consommation d’énergie finale et les usages sous forme d’un diagramme de Sankey. Ce diagramme décrit les volumes en jeu, leur origine et leur contenu en CO₂, et sert de base pour analyser les leviers majeurs de décarbonation.

  <div class="text-center my-4">
    <img src="/assets/img/Sankey/Itese_Sankey_Gradient.png" alt="Diagramme de Sankey" style="max-width: 100%; height: auto;">
  </div>


<div class="box-green">
  <h5 class="text-center" style="font-weight: bold;">Messages principaux</h5>
  <p><strong>Les chiffres clefs :</strong></p>
  <ul>
    <li>En 2019, la France a consommé <strong>1840 TWh</strong> d’énergie finale.</li>
    <li><strong>65 %</strong> de cette consommation est d’origine fossile.</li>
    <li>Les usages les plus consommateurs en énergie et les plus dépendants des énergies fossiles sont :
      <ul>
        <li><strong>Transport routier</strong> :
          <ul>
            <li>488 TWh, dont 450 TWh fossile</li>
            <li>30 % des émissions de GES sur le territoire</li>
          </ul>
        </li>
        <li><strong>Chauffage résidentiel-tertiaire</strong> :
          <ul>
            <li>400 TWh, dont 218 TWh fossile</li>
            <li>15 % des émissions de GES sur le territoire</li>
          </ul>
        </li>
      </ul>
    </li>
  </ul>

  <p><strong>Les défis à venir :</strong></p>
  <ul>
    <li>L’électrification massive des usages est un levier indispensable pour réduire fortement la consommation d’énergie fossile.</li>
    <li>Cette électrification :
      <ul>
        <li>Implique de fortes consommations additionnelles</li>
        <li>Nécessite de nouvelles capacités de production d’électricité bas-carbone</li>
      </ul>
    </li>
    <li>La disponibilité d’électricité bas carbone étant limitée au moins à court terme :
      <ul>
        <li>Il faudra privilégier les solutions à <strong>forte efficacité énergétique</strong>
          <ul>
            <li>Exemples : pompes à chaleur, véhicules électriques</li>
          </ul>
        </li>
      </ul>
    </li>
    <li>Les autres solutions complémentaires :
      <ul>
        <li>Biomasse</li>
        <li>Valorisation de la chaleur fatale</li>
        <li>Ces solutions <strong>ne sont pas disponibles en quantité suffisante</strong> pour remplacer totalement les fossiles</li>
      </ul>
    </li>
    <li>Certaines matières premières minérales seront en tension avec cette électrification</li>
  </ul>

  <p><strong>Des efforts de <em>sobriété</em></strong>, c’est-à-dire une <strong>réduction de la demande en énergie</strong>, sont également <strong>indispensables</strong> pour atteindre les objectifs de la SNBC.</p>
</div>

### Introduction
L’objet de ce document est de présenter dans sa globalité le système énergétique français, de l’utilisation des ressources primaires aux usages finaux. Nous rappelons ici les principaux ordres de grandeur de consommation d’énergie, par sources et usages, afin de donner aux lecteurs une intuition des enjeux qu’implique la fin du recours aux énergies fossiles.
Le système énergétique national étant éminemment complexe, nous ne rentrerons pas dans le détail de l'ensemble des solutions de décarbonation. Nous avons plutôt choisi de montrer, à travers des exemples simples, l’effet que pourrait avoir le développement de différentes technologies sur la consommation d’énergie. Cette approche nous permet de présenter les grands enjeux de la transition énergétique et de prendre la mesure du chemin à parcourir, que ce soit du point de vue des technologies ou de l’évolution des modes de vie.
Cet article n’a pas vocation à décrire une marche à suivre pour décarboner l’économie. Nous avons au contraire souhaité donner des éléments de contexte pour que le lecteur puisse construire sa propre analyse.

Les données énergétiques utilisées pour la réalisation de ce graphique proviennent de l’agrégation de rapports du (SDES) pour l’année 2019, avant la crise sanitaire. Le cadre méthodologique est identique à celui choisi par ces rapports, à l'exception du transport international (aérien et maritime) qui a été ajouté. Les données d'émissions de CO2 proviennent quant à elles du <a href="https://bilans-ges.ademe.fr/" target="_blank">centre de ressources Base Carbone de l’ADEME</a>.

---

## Sommaire 

<div id="sommaire"></div>

<div class="row mb-4">
  <div class="col-md-12">
    <h5>1 – Le point sur l'utilisation des ressources énergétiques en France</h5>
    <ul>
      <li>
        <strong><a href="#section-1a">📎 1.a – Présentation du diagramme principal</a></strong><br>
        <img src="/assets/img/Sankey/Itese_Visual_1.png" alt="Diagramme principal" class="img-thumbnail" style="max-width: 100px; margin-top: 0.3rem;">
      </li>
      <li>
        <strong><a href="#section-1b">📎 1.b – Un système qui repose majoritairement sur les fossiles</a></strong><br>
        <img src="/assets/img/Sankey/Itese_Visual_2.png" alt="Diagramme fossiles" class="img-thumbnail" style="max-width: 100px; margin-top: 0.3rem;">
      </li>
      <li>
        <strong><a href="#section-1c">📎 1.c – Une répartition inégale des énergies fossiles entre les secteurs</a></strong><br>
        <img src="/assets/img/Sankey/Itese_Visual_3.png" alt="Diagramme secteurs" class="img-thumbnail" style="max-width: 100px; margin-top: 0.3rem;">
      </li>
    </ul>

    <h5 class="mt-4">2 – Quelles alternatives pour décarboner ?</h5>
    <ul>
      <li>
        <strong><a href="#section-2a">📎 2.a – Le fort potentiel des pompes à chaleur</a></strong><br>
        <img src="/assets/img/Sankey/Itese_Visual_5a.png" alt="PAC" class="img-thumbnail" style="max-width: 100px; margin-top: 0.3rem;">
      </li>
      <li>
        <strong><a href="#section-2b">📎 2.b – Le potentiel des véhicules électriques</a></strong><br>
        <img src="/assets/img/Sankey/Itese_Visual_6.png" alt="VE" class="img-thumbnail" style="max-width: 100px; margin-top: 0.3rem;">
      </li>
      <li>
        <strong><a href="#section-2c">📎 2.c – Effet global des scénarios technologiques</a></strong><br>
        <img src="/assets/img/Sankey/Itese_Visual_7a.png" alt="Scénarios globaux" class="img-thumbnail" style="max-width: 100px; margin-top: 0.3rem;">
      </li>
      <li>
        <strong><a href="#section-2d">📎 2.d – Quels leviers supplémentaires pour décarboner ?</a></strong><br>
        <img src="/assets/img/Sankey/Itese_Equation.png" alt="Équation Kaya" class="img-thumbnail" style="max-width: 100px; margin-top: 0.3rem;">
      </li>
    </ul>
  </div>
</div>



---

<!-- Section 1.a -->
<div id="section-1a" style="background-color: #eef4f7; border-left: 4px solid #0d3b66; padding: 1rem; margin-top: 2rem;">
  <h3>
    1.a – Présentation du diagramme principal
    <a href="#sommaire" title="Retour au sommaire" style="font-size: 0.8rem; margin-left: 1rem;">🔝</a>
  </h3>
</div>


<p>
  En France métropolitaine, environ 65 % de l’énergie finale consommée est d’origine fossile (pétrole, gaz, charbon). 
  C’est ce qu’illustre le 
  <a href="https://www.statistiques.developpement-durable.gouv.fr/edition-numerique/bilan-energetique-2019/pdf/document.pdf" target="_blank">Bilan énergétique de la France</a>, 
  une publication annuelle du Service des Données et Études Statistiques (SDES). Ces rapports font notamment l’état de la consommation des ressources énergétiques primaires en France, 
  comme le pétrole brut, le gaz ou les ressources fissiles ; ainsi que de leur transformation en énergie dite finale, disponible à la consommation.
</p>

<p>
  Afin d’illustrer les étapes principales de la chaîne d’approvisionnement énergétique et définir un vocabulaire commun, nous avons schématisé sur le graphique ci-dessous 
  le processus permettant d’aboutir à une énergie finale, disponible à la consommation.
</p>

<div class="text-center my-4">
  <img src="/assets/img/Sankey/Itese_Visual_1.png" alt="Schéma d'approvisionnement énergétique" style="max-width: 100%; height: auto;">
</div>

<p>
  De gauche à droite, tout commence par l’extraction de ressources énergétiques primaires, comme le pétrole brut, l’énergie hydraulique ou encore la biomasse. 
  Celles-ci sont ensuite converties et transformées avant d’être disponibles à la consommation comme énergie finale (ou vecteur énergétique final). 
  L’énergie finale, sous la forme d’électricité, de combustible ou de chaleur, sera ensuite consommée pour différents usages, comme ceux de l’industrie ou le transport (rond de droite).
  Le flux entre ressources primaires et énergies finales est régulièrement présenté sous la forme d’un diagramme de Sankey, comme celui ci-dessous<sup><a href="#note-1a-1">1</a></sup>.
</p>

<p class="text-center" style="font-weight: bold;">FLUX ÉNERGÉTIQUES ENTRE RESSOURCES PRIMAIRES ET ÉNERGIES FINALES EN FRANCE – 2019</p>

<div class="text-center my-4">
  <img src="/assets/img/Sankey/sankey-SDES.png" alt="Diagramme de Sankey SDES" style="max-width: 100%; height: auto;">
</div>

<p>
  Cette représentation permet de visualiser la répartition des sources d’énergie finale utilisées en France (partie de droite), ainsi que l’ensemble des pertes du système énergétique 
  associées à la conversion des ressources primaires (partie haute). 
  On y lit notamment qu’en 2019, le système énergétique français a consommé 258 Mtep<sup><a href="#note-1a-2">2</a></sup> d’énergie primaire, 
  pour une énergie finale disponible à la consommation de 153 Mtep. 
  Cette différence s’explique principalement par les pertes lors de la conversion des énergies primaires en énergie électrique<sup><a href="#note-1a-3">3</a></sup>. 
  Le reste de cette différence est imputé aux exportations d’électricité et de pétrole pour le transport international.
</p>

<p>
  Ce graphique ne montre cependant pas quels sont les usages faits de chacun de ces vecteurs énergétiques. 
  Le pétrole est-il principalement utilisé pour le transport, les besoins de l’industrie, le chauffage ? 
  Dans une dynamique de décarbonation, il est nécessaire de comprendre quels sont les potentiels reports des sources fossiles vers des sources ‘bas-carbone’, 
  et dans quelles mesures ces solutions peuvent être déployées.
</p>

<p>
  Afin de mettre en évidence le potentiel de réduction du recours aux énergies fossiles, et à titre pédagogique, 
  nous avons prolongé ce diagramme pour faire le lien entre les sources d’énergie finale et les usages. 
  Le graphique ci-dessous montre la répartition par usages des 1750 TWh d’énergie finale annuellement consommée sur le territoire<sup><a href="#note-1a-4">4</a></sup>.
</p>

<div class="text-center my-4">
  <img src="/assets/img/Sankey/Itese_Sankey_Gradient.png" alt="Diagramme Sankey par usage" style="max-width: 100%; height: auto;">
</div>

<p>
  Les données utilisées pour produire ce graphique proviennent d’une agrégation de données publiques, notamment du SDES et de l’Agence Internationale de l’Énergie (AIE) pour l’année 2019, 
  avant la crise sanitaire liée à la COVID. 
  En plus des volumes des énergies en jeu, représentés par l’épaisseur des flux, un code couleur en niveaux de gris quantifie le contenu CO₂ équivalent de l’ensemble des vecteurs énergétiques finaux.
</p>

<p>
  Nous allons dans la suite de ce document analyser pas-à-pas ce diagramme pour apporter des éléments de réponses aux questions suivantes :
</p>

<ul>
  <li>Comment l’énergie finale est-elle répartie entre les différents secteurs de l’économie ?</li>
  <li>Quels sont les secteurs les plus consommateurs en énergie et émetteurs de gaz à effet de serre (GES) ?</li>
  <li>Quels sont les potentiels reports de ressources fossiles vers des sources bas-carbone ?</li>
  <li>Quels sont les secteurs à décarboner en priorité ?</li>
</ul>

<p>
  Pour cela, nous distinguerons les vecteurs énergétiques dits ‘bas carbone’ et ‘haut carbone’ :
</p>
<ul>
  <li>
    On qualifie de ‘haut carbone’ l’énergie finale issue des combustibles fossiles, comme le charbon, le gaz et le pétrole. 
    À titre indicatif, ces vecteurs énergétiques ont un contenu carbone entre 200 et 400 gCO₂/kWh.
  </li>
  <li>
    Par opposition, les vecteurs ‘bas-carbone’ ont un contenu CO₂ plus faible, entre 50 et 130 gCO₂/kWh. 
    C’est le cas de l’électricité en France – grâce au parc électro-nucléaire, à l’hydroélectricité et aux énergies renouvelables – 
    de la chaleur commercialisée et de l’énergie issue des déchets et de la biomasse.
  </li>
</ul>

<div class="text-center my-4">
  <h5 style="font-weight: bold;">Diagramme interactif – Flux d’énergie finale par usage</h5>
  <iframe 
    src="https://plotly.com/~ArthurClerjon/15.embed" 
    width="100%" 
    height="600" 
    frameborder="0" 
    scrolling="no"
    style="max-width: 900px; border: none;">
  </iframe>
</div>


<hr>
<p><strong>Notes</strong></p>
<ol style="font-size: 0.9rem;">
  <li id="note-1a-1">Dans ce diagramme de Sankey, les soutes internationales désignent la consommation énergétique (carburants) du transport aérien et maritime international.</li>
  <li id="note-1a-2">Le Mtep (Millions de tonnes équivalent pétrole) est une unité qui permet de quantifier l’énergie, au même titre que le TWh. 1 Mtep = 11,6 TWh.</li>
  <li id="note-1a-3">Les pertes des centrales électriques proviennent principalement des centrales nucléaires. La fission du combustible nucléaire dégage une forte quantité de chaleur, dont seulement 30 à 40 % est convertie en électricité.</li>
  <li id="note-1a-4">Sur ce diagramme a été ajoutée la consommation de pétrole imputée au transport aérien et maritime international. Celui-ci s’élève à environ 90 TWh, soit une énergie finale totale consommée de 1840 TWh en 2019.</li>
</ol>


---

<div style="background-color: #eef4f7; border-left: 4px solid #0d3b66; padding: 1rem; margin-top: 2rem;">
  <h3>1.b - Un système qui repose majoritairement sur les fossiles</h3>
</div>


La répartition de l’énergie finale par source (électricité, pétrole, gaz, etc...) – représentée par la partie gauche du diagramme de Sankey – est agrégée sous un autre format sur le visuel ci-dessous.

<div class="text-center my-4">
  <img src="/assets/img/Sankey/Itese_Visual_2.png" alt="" style="max-width: 100%; height: auto;">
</div>

Ce graphique montre que près de 65% de l’énergie finale consommée est d’origine fossile – pétrole, gaz naturel et charbon. Le reste de la consommation finale est répartie entre : 
- L’électricité, bas carbone en France. 
- Les énergies renouvelables thermiques (ENRt) et déchets, à savoir les énergies produites directement sous forme de chaleur et non pas d’électricité, notamment le chauffage au bois, les  pompes à chaleur, le solaire thermique et les centrales thermiques à base de combustible ‘renouvelable’.
- La chaleur commercialisée.


Près de 65% de l'énergie finale consommée en France est d'origine fossile.

---

<div style="background-color: #eef4f7; border-left: 4px solid #0d3b66; padding: 1rem; margin-top: 2rem;">
  <h3>1.c - Une répartition inégale des énergies fossiles entre les secteurs</h3>
</div>



Demandons-nous maintenant quels sont les postes de consommation de cette énergie finale ? Quels sont les secteurs aujourd’hui les plus demandeurs en énergie fossile ? C’est ce que révèle l’analyse de la partie droite de notre diagramme de Sankey, qui montre la répartition de l’approvisionnement énergétique des différents secteurs de l’économie, organisée comme suit :
- Industrie
- Transport national et international imputé au territoire
- Usages des secteurs résidentiel et tertiaire (chauffage, eau chaude sanitaire (ECS), autres usages et imputés nulle part ailleurs)
- Agriculture et  pêche
- Usages non-énergétiques des fossiles en tant que matière première.

Ces données sont agrégées dans le visuel ci-dessous (partie de droite du Sankey) représentant pour chaque secteur sa consommation totale d’énergie en fonction des vecteurs énergétiques finaux.

<div class="box-accent box-right">
  <p><strong>Charbon énergétique et charbon métallurgique, quelles différences ?</strong></p>
  <p>
    Il faut distinguer le charbon dit thermique (14 TWh en 2019) du <strong>charbon métallurgique</strong>, utilisé dans les hauts fourneaux pour la production d’acier. Ce dernier, après transformation en coke par pyrolyse, est utilisé comme source de carbone pour transformer de l’oxyde de fer en acier.
  </p>
  <p>
    La consommation de charbon métallurgique en France représente annuellement environ 50 TWh. N’étant pas utilisé pour la production d’énergie, mais nécessitant tout de même des étapes de transformation avant usage, sa consommation n’apparaît dans aucun secteur sur les graphiques présentés ici.
  </p>
  <p>
    Plus de détails sur la transformation du charbon en France sont disponibles
    <a href="https://www.statistiques.developpement-durable.gouv.fr/sites/default/files/2021-12/repere-energies-charbon-septembre2021.pdf" target="_blank">
      dans cette publication du SDES
    </a>.
  </p>
</div>

<div class="text-center my-4">
  <img src="/assets/img/Sankey/Itese_Visual_3.png" alt="" style="max-width: 100%; height: auto;">
</div>


Ce graphique indique clairement que le transport et les usages du résidentiel-tertiaire sont les deux secteurs les plus intensifs en énergie, représentant à eux deux la majeure partie de la consommation des fossiles. Pour compléter ce graphique, rappelons que le transport représente environ 30 % des émissions de GES sur le territoire, tandis que le chauffage résidentiel et tertiaire en représente environ 15 %.

Ces deux postes de consommation vont faire l’objet d’une analyse détaillée dans la suite du texte. Nous montrerons notamment quel peut être l’effet de certaines mesures de décarbonation, comme le développement des véhicules électriques ou des  pompes à chaleur.

Le transport et les usages du résidentiel-tertiaire sont les deux secteurs les plus intensifs en énergie, représentant à eux deux la majeure partie de la consommation des énergies fossiles.

---

<h2 style="font-size: 1.6rem; font-weight: bold; color: #0d3b66; margin-bottom: 0.5rem;">
  2. Quelles alternatives pour décarboner ?
</h2>
<hr style="width: 80px; border: 3px solid #117a8b; margin-left: auto; margin-bottom: 2rem;">


<!-- Section 2.a -->
<div id="section-2a" style="background-color: #eef4f7; border-left: 4px solid #0d3b66; padding: 1rem; margin-top: 2rem;">
  <h3>
    2.a – Le fort potentiel des pompes à chaleur
    <a href="#sommaire" title="Retour au sommaire" style="font-size: 0.8rem; margin-left: 1rem;">🔝</a>
  </h3>
</div>

<p style="font-style: italic; font-size: 1.05rem; text-align: justify;">
  La baisse de consommation des énergies fossiles passera – en partie – par le report vers les vecteurs 
  <em>‘bas-carbone’</em>. C’est aujourd’hui le cas de 
  <a href="https://www.rte-france.com/eco2mix/les-donnees-de-la-production-par-filiere" target="_blank" style="color: #0d3b66; text-decoration: underline;">l’électricité en France</a>,
  et pour des quantités plus faibles des biocarburants (tant qu’ils sont produits de manière durable) et de la récupération de chaleur fatale.
</p>

<p style="font-style: italic; font-size: 1.05rem; text-align: justify;">
  Pour illustrer le potentiel de ce report, nous avons choisi les exemples du transport routier et du besoin de chauffage du résidentiel et tertiaire.
  Rappelons avant tout que ces deux secteurs sont responsables de respectivement <strong>30 %</strong> et <strong>15 %</strong> des émissions de GES sur le territoire.
</p>

<hr style="width: 60px; border: none; border-top: 2px solid #ccc; margin: 1rem auto;">

<p>
  Le secteur du bâtiment est aujourd’hui susceptible de réduire fortement sa consommation d’énergie, notamment par des gains d’efficacité énergétique réalisés à la fois en rénovant les bâtiments les moins bien isolés 
  (<a href="https://www.ademe.fr/particuliers-eco-citoyens/habitation/renover/connaitre-classe-energetique">Classes Énergétiques F, G</a>) ; 
  et en remplaçant les chaudières au gaz et au fioul par des 
  <a href="https://www.ademe.fr/particuliers-eco-citoyens/habitation/se-chauffer/chauffage-economique/pompes-chaleur">pompes à chaleur (PAC)</a>.
</p>

<p>
  En effet, les pompes à chaleur, lorsque leur installation est possible, produisent en moyenne 3 unités de chaleur pour une unité d’énergie électrique consommée, comme l’illustre le schéma de principe ci-dessous.
</p>

<div class="text-center my-4">
  <img src="/assets/img/Sankey/Itese_Visual_4.png" alt="" style="max-width: 100%; height: auto;">
</div>

<p>
  Dans un <a href="https://www.statistiques.developpement-durable.gouv.fr/renovation-energetique-du-parc-immobilier-en-france"><strong>rapport du SDES</strong></a> faisant état de l’efficacité des différentes mesures de rénovation du parc immobilier français réalisées de 2016 à 2019, celui-ci indique que <strong>la rénovation, d’une part de la toiture, des murs et du plancher</strong>, d’autre part <strong>le remplacement des moyens de chauffage et de l’Eau Chaude Sanitaire (ECS)</strong> sont les actions les plus efficaces pour réduire la consommation énergétique. En 2019, <strong>ces deux leviers représentaient respectivement 57 % et 39 %</strong> des économies d’énergie générales.
</p>

<p>
  Afin de comprendre dans quelle mesure <strong>le développement massif des pompes à chaleur</strong> sur le territoire pourrait affecter la production de chauffage, plaçons-nous dans le scénario suivant :  
  <strong>« Demain, 50 % des chaudières à gaz et au fioul seront remplacées par des pompes à chaleur avec un coefficient de performance (COP) de 3 »</strong>.  
  <em>Attention, il s’agit là d’un choix arbitraire, le curseur pourrait être poussé dans un sens comme dans l’autre. C’est un scénario caricatural à des échéances courtes<sup><a href="#note-2a-1">1</a></sup> mais qui permet de souligner le potentiel et les limites d’une telle solution technologique.</em>
</p>

<div class="text-center my-4">
  <img src="/assets/img/Sankey/Itese_Visual_5a.png" alt="" style="max-width: 100%; height: auto;">
</div>

<p>
  On lit sur la barre de gauche la répartition par source du besoin de chauffage en 2019 (400 TWh), à droite la répartition de ce même besoin dans le scénario d’électrification <strong>‘50% PAC’</strong> décrit précédemment. Voici les principaux messages de ce graphique :
</p>

<ul>
  <li>On observe une baisse de 50% des énergies fossiles pour atteindre 110 TWh.</li>
  <li>Les pompes à chaleur produisant plus d’énergie thermique que d’électricité consommée<sup><a href="#note-2a-2">2</a></sup>, la consommation totale d'énergie baisse de 70 TWh.</li>
</ul>

<p>
  Loin de s’affranchir des énergies fossiles, le développement des pompes à chaleur dans ce scénario ‘50% PAC’ permettrait toutefois d’en réduire l’usage. Pour se décarboner davantage (en dehors d'une électrification plus importante), il est aussi possible de récupérer la chaleur dite ‘fatale’, majoritairement produite lors de procédés industriels et qui serait perdue si elle n’était pas valorisée. 
  En France, <a href="https://librairie.ademe.fr/changement-climatique-et-energie/3276-le-potentiel-de-la-chaleur-fatale-en-france.html" target="_blank">l’ADEME</a> évalue le potentiel de chaleur fatale qui pourrait être récupérée à 109,5 TWh thermique (dont 53 TWh à plus de 100 °C)<sup><a href="#note-2a-3">3</a></sup>, sous réserve de développer des infrastructures adaptées, comme des <strong>réseaux de chaleur urbains</strong>.
</p>

<div class="text-center my-4">
  <img src="/assets/img/Sankey/Itese_Visual_5b.png" alt="" style="max-width: 100%; height: auto;">
</div>

<p>
  Ce graphique montre que le potentiel total de récupération de chaleur fatale est du même ordre de grandeur que la consommation de fossiles pour répondre au besoin de chauffage dans le cas du scénario <strong>‘50% PAC’</strong>. Attention cependant, cette chaleur fatale ne peut être valorisable qu’en développant des infrastructures de transport de chaleur entre les sites industriels et les sites où elle sera utilisée. Les réseaux de chaleur urbains fonctionnant pour la majorité en France à plus de 100 °C, la chaleur fatale produite à moins de 100 °C (plus de la moitié) ne pourra pas être valorisée directement.
</p>

<div class="box-accent" style="max-width: 800px; margin: 2rem auto;">
  <p>
    <strong>Dans le scénario d’électrification ‘50 % PAC’</strong>, on observe une baisse de <strong>50 %</strong> de la consommation des énergies fossiles.
    Les pompes à chaleur produisant plus d’énergie thermique que d’électricité consommée, la consommation énergétique totale baisse de <strong>70 TWh</strong>.
  </p>
  <p>
    La consommation de fossiles — gaz, pétrole, charbon — est alors d’un peu plus de <strong>100 TWh</strong>.
    C’est du même ordre de grandeur que le potentiel maximum de récupération de chaleur fatale en France.
    Même s’il ne s’agit là que d’un potentiel, la valorisation de la chaleur fatale permettrait de <strong>décarboner en partie la production de chaleur</strong>,
    si des réseaux de chaleur urbains sont disponibles pour la transporter.
  </p>
</div>

<hr>
<p><strong>Notes</strong></p>
<ol style="font-size: 0.9rem;">
  <li id="note-2a-1">Aucun horizon temporel n’est visé, cet exemple est simplement choisi à titre indicatif.</li>
  <li id="note-2a-2">Dans le cadre de la méthodologie comptable employée par le SDES et l’AIE, l’énergie thermique ‘gratuite’, prélevée dans l’environnement par les pompes à chaleur doit être imputée au secteur Énergies renouvelables thermiques et déchets. Dans le cas de l’analyse de sensibilité ‘50 % PAC’, nous avons délibérément choisi de ne pas le faire, afin de garder visible le gain d'efficacité énergétique sur le graphique.</li>
  <li id="note-2a-3">Le niveau de température de la chaleur fatale a une importance primordiale. À haute température (plusieurs centaines de degrés) elle pourra être facilement valorisée, dans des procédés industriels par exemple. À basse température (~80–90 °C), les usages pouvant valoriser la chaleur sont moindres. Derrière cette question de température se cache la notion d’exergie, c’est-à-dire l’énergie ‘utile’ qui peut être extraite du flux de chaleur fatale.</li>
</ol>

---
<div style="background-color: #eef4f7; border-left: 4px solid #0d3b66; padding: 1rem; margin-top: 2rem;">
  <h3>2.b - Décarboner le transport routier : quel potentiel pour les véhicules électriques ?</h3>
</div>

<p style="font-style: italic; font-size: 1.05rem; text-align: justify;">
  Pour illustrer le potentiel de report vers les vecteurs 'bas-carbone', nous avons traité dans le paragraphe précédent l'exemple du chauffage du résidentiel et du tertiaire. 
  Dans ce paragraphe, nous analysons le transport routier. En effet, nous avons vu précédemment, que le transport est le secteur le plus consommateur d’énergies fossiles en France. 
  Le transport routier (véhicules particuliers, utilitaires et poids lourds), est à lui seul responsable de près de 
  <a href="https://www.notre-environnement.gouv.fr/themes/climat/les-emissions-de-gaz-a-effet-de-serre-et-l-empreinte-carbone-ressources/article/les-emissions-de-gaz-a-effet-de-serre-du-secteur-des-transports#:~:text=En%202019%2c%20le%20transport%20est%2crepr%C3%A9sentait%2022%20%25%20du%20total%20national." 
     target="_blank" 
     style="font-style: italic;">
    30% des émissions de GES sur territoire
  </a>.
</p>

<hr style="width: 60px; border: none; border-top: 2px solid #ccc; margin: 1rem auto;">

<p>Le graphique ci-dessous indique la répartition des émissions de GES du transport national. Il est important de remarquer que, au sein du transport national, la partie routière est responsable de plus de 95% des émissions de GES.</p>

<figure>
  <img src="/assets/img/Sankey/repartition-transports.png" alt="" class="img-fluid">
  <figcaption class="figure-caption">
    Source : 
    <a href="https://www.statistiques.developpement-durable.gouv.fr/chiffres-cles-du-climat-france-europe-et-monde-edition-2024" target="_blank">
      Chiffres clés du climat France, Europe et Monde ÉDITION 2021
    </a>
  </figcaption>
</figure>

<p>Ce graphique montre également que les véhicules particuliers sont responsables de plus de 50% des émissions de GES du transport, suivis par les utilitaires (16%) et les poids lourds (23%).</p>

<div class="box-accent box-left">
  <p><strong>Le potentiel des Véhicules Électriques (VE)</strong></p>
  <p><strong>Le couple batterie - moteur électrique : un fort gain d'efficacité énergétique</strong></p>
  <p>
    Les moteurs électriques ont un rendement mécanique de 90 %, contre 40 % pour les moteurs thermiques<sup><a href="#note-2b-1">1</a></sup>. 
    En ajoutant à cela les diverses pertes de transmission, la consommation des auxiliaires et la possibilité de récupérer de l’énergie au freinage pour les véhicules électriques, 
    on observe un rendement dit du réservoir à la roue (tank-to-wheel) d’environ 20 % pour les véhicules thermiques, contre 70 % pour les véhicules électriques.
  </p>
</div>

<p>
  Pour apprécier l’effet que pourrait avoir une électrification massive du transport routier, faisons l’hypothèse – optimiste à court terme – 
  que la quasi-totalité des véhicules particuliers et utilitaires est remplacée par des véhicules électriques. 
  Nous supposons pour cela que la consommation de produits pétroliers pour le transport routier diminuerait de 70 %. 
  Attention, il s’agit une fois de plus d’un choix de scénario arbitraire, ne reflétant pas nécessairement une limite maximale ou un objectif à un horizon lointain. 
  Cet exercice de pensée a pour unique ambition de souligner l’effet du développement des VE.
</p>

<p>Les résultats de cette analyse sont présentés sur la figure ci-dessous.</p>

<div class="text-center my-4">
  <img src="/assets/img/Sankey/Itese_Visual_6.png" alt="" style="max-width: 100%; height: auto;">
</div>

<p>
  On y observe de fait une baisse de la consommation de carburant fossile de 70 % (-315 TWh), accompagnée d'une hausse de la demande en électricité de 90 TWh. 
  Le tout s’équilibre autour d’une consommation totale d’énergie qui serait presque divisée par deux.
</p>

<blockquote style="font-style: italic; font-size: 1.05rem; margin: 2rem 0;">
  Dans le cas où la quasi-totalité des véhicules particuliers et utilitaires sont remplacés par des véhicules électriques, 
  la consommation de produits pétroliers pour le transport routier diminuerait de 70 % 
  et la consommation énergétique totale diminuerait de 225 TWh.
</blockquote>

<hr>
<p><strong>Notes</strong></p>
<ol style="font-size: 0.9rem;">
  <li id="note-2b-1">Pour un moteur, le rendement désigne le rapport entre l’énergie utile (mécanique) et l’énergie totale consommée (électricité ou combustible ici). Pour un moteur électrique de rendement 90 %, cela signifie que 10 % de l’électricité consommée par le moteur électrique n’a pas été consacrée à sa propulsion.</li>
</ol>

---

<div style="background-color: #eef4f7; border-left: 4px solid #0d3b66; padding: 1rem; margin-top: 2rem;">
  <h3>2.c - Bilan : effet global de ces scénarios de développement technologique</h3>
</div>

Évaluons maintenant l’effet cumulé que pourrait avoir le déploiement de ces deux  technologies – pompes à chaleur et véhicules électriques – sur la consommation globale d’énergie finale (hors transport international et consommations à usages non-énergétiques). Les résultats sont présentés sur la figure ci-dessous. Rappelons toutefois qu’il ne s’agit là que de scénarios d’électrification choisis arbitrairement et non pas de potentiels maximum.

<div class="text-center my-4">
  <img src="/assets/img/Sankey/Itese_Visual_7a.png" alt="" style="max-width: 100%; height: auto;">
</div>  


Ce graphique montre que l'électrification massive des usages permettrait effectivement de réduire à la fois la consommation totale d'énergie et la part des énergies fossiles dans le mix  d’énergie finale. Toutefois, en dépit des hypothèses fortes d’électrification choisies, il resterait une dépendance aux fossiles de 530 TWh (hors usages non-énergétiques et transport international), soit plus de 40% de la consommation totale, contre 60% aujourd’hui.
A ces gains, nous pouvons ajouter le potentiel de deux sources d’énergie bas-carbone, celle issue de la récupération de chaleur fatale et celle provenant de la biomasse.  Nous avons vu que : 

- À condition de développer des infrastructures adaptées, une partie du potentiel de la chaleur fatale, évaluée par l’[ADEME](https://librairie.ademe.fr/changement-climatique-et-energie/3276-le-potentiel-de-la-chaleur-fatale-en-france.html) à **110 TWh**, pourrait être valorisée.

- En complément, un potentiel de **300 TWh** de combustible issu de la biomasse (résidus de déchets agricoles, bois-énergie, boues d’épuration et déchets) est estimé à l’horizon 2050 par divers rapports : [France Stratégie](https://www.strategie.gouv.fr), [WWF France](https://www.wwf.fr), et [The Shift Project](https://theshiftproject.org).

L'accès à l’ensemble de ce potentiel est bien entendu soumis à de fortes incertitudes. Au-delà des nombreuses hypothèses formulées pour évaluer un potentiel prospectif, la valorisation des 410 TWh (110 chaleur + 300 combustibles) nécessiterait le développement d'infrastructures lourdes comme des réseaux de chaleur. L’accès à la ressource biomasse pour la transformation en combustible, pourrait de son côté susciter des compétitions d’usages avec l'alimentation, le retour au sol ou son utilisation comme matériaux de construction.

---

<div style="background-color: #eef4f7; border-left: 4px solid #0d3b66; padding: 1rem; margin-top: 2rem;">
  <h3>2.d - Quels leviers supplémentaires pour décarboner la consommation d'énergie ?</h3>
</div>

<p>
  Mis bout à bout, nous avons vu que, malgré un déploiement massif des pompes à chaleur et des véhicules électriques, la valorisation de la chaleur fatale et une utilisation intensive de la biomasse, ces technologies ne permettraient pas à elles seules de s’affranchir des énergies fossiles. Quelles sont alors les alternatives restantes ?
</p>

<div class="box-accent box-right">
  <p><strong>Pour que l’électrification des usages demeure vertueuse</strong></p>
  <p>
    Le développement des pompes à chaleur et véhicules électriques présenté plus haut implique une électrification massive des usages,
    et de fait une croissance de la consommation d’électricité. Pour que ce report de source d’énergies soit réellement vertueux, il faut s’assurer que les deux conditions ci-dessous soient remplies :
  </p>
  <ol>
    <li>La production d’électricité doit tout d'abord rester décarbonée. C’est aujourd’hui le cas en France, mais ces solutions ne seraient pas vraies pour tous les autres pays européens.</li>
    <li>Pour assurer la hausse globale de la consommation d’électricité, la France devra augmenter ses capacités de production en développant des moyens bas-carbone – le nucléaire et les ENR – en évitant le recours au gaz et au charbon.</li>
  </ol>
</div>

<p>
  Dans un contexte d’approvisionnement contraint en énergie, les solutions à forte efficacité, comme les PAC et les VE, seront priorisées dans un premier temps. Pour d’autres usages, notamment dans l’industrie ou le transport aérien, des solutions de production de vecteurs énergétiques à partir d’électricité (Power-To-X), pourront – pour une petite partie – se substituer aux combustibles fossiles. C’est en particulier le cas des procédés à faible rendement, comme la production d’hydrogène par électrolyse de l’eau, ou la synthèse de carburants. À titre indicatif, la production de 100 TWh de carburant de synthèse consommerait, en ordre de grandeur 220 TWh d’électricité. C’est plus de la moitié de la production de l’ensemble du parc nucléaire français sur une année. Un développement à grande échelle de ces solutions demanderait donc de construire des moyens de production d’électricité additionnels.
</p>

<p>
  Dans un contexte futur contraint en ressources carbonées non-fossiles (biomasse, CO₂), il faudra cependant veiller à utiliser ces ressources pour des usages où les vecteurs carbonés (i.e. les combustibles) ne sont pas ou peu substituables, comme l’aviation ou l’industrie.
</p>

<p>
  À la vue de l’ensemble des contraintes évoquées – et sans compter les limitations qui pourraient apparaître sur l’accès aux matières premières, la disponibilité des sols, etc. – nous comprenons désormais que l’arrêt du recours aux énergies fossiles ne pourra se faire uniquement grâce au développement technologique. Ce ne sont en effet pas les seuls leviers d’action. Une baisse de la demande énergétique globale, via la modification des usages – c’est-à-dire un effort de sobriété – sera également nécessaire.
</p>

<div class="box-accent box-right">
  <p><strong>La temporalité de choix et d'actions</strong></p>
  <p>
    L’industrialisation et le déploiement de nouvelles technologies, telles que le développement massif des véhicules électriques ou la rénovation du parc immobilier, sont des transformations qui s’opèrent sur les temps longs<sup><a href="#note-2d-2">2</a></sup> – plusieurs décennies.
  </p>
  <p>
    En revanche, l'évolution des modes de vie peut être stimulée par des décisions politiques et individuelles prises à des échelles de temps beaucoup plus courtes (ex. report modal, réglementation du trafic aérien ou des véhicules polluants).
  </p>
  <p>
    Ainsi, à court terme et dans un contexte d’urgence climatique, les actions de sobriété présentent le meilleur potentiel de limitation de nos émissions, ce qui les rend d’autant plus nécessaires.
  </p>
</div>

<p>
  Les moyens technologiques ne sont pas les seuls leviers d’action qui permettront de réduire la consommation d’énergie fossile. 
  L'équation de Kaya<sup><a href="#note-2d-1">1</a></sup> présentée ci-dessous illustre, de manière simplifiée, comment se répartissent des émissions (quelles qu’elles soient, GES, CO₂, particules fines, etc.), en fonction de trois leviers :
</p>

<ul>
  <li><strong>Le choix d’une énergie bas-carbone</strong>, afin de réduire le contenu CO₂ du vecteur énergétique choisi. C’est notamment le cas de l’électrification en France.</li>
  <li><strong>L’efficacité énergétique</strong>, c'est-à-dire l’énergie consommée pour répondre à un besoin donné. C’est par exemple le cas des véhicules électriques, plus efficaces que les véhicules thermiques.</li>
  <li><strong>La sobriété</strong>, c'est-à-dire la réduction des besoins, quels qu’ils soient : besoin de déplacements, d’énergie pour le chauffage d’un foyer, de fabrication de biens de consommation. Par exemple, concernant la mobilité, la sobriété peut se traduire soit par une diminution de l’usage, mais également par un report modal vers des mobilités dites douces ou des transports en commun.</li>
</ul>

<div class="text-center my-4">
  <img src="/assets/img/Sankey/Itese_Equation.png" alt="" style="max-width: 100%; height: auto;">
</div>

<p>
  Après avoir joué sur le choix d’énergies bas-carbone et l'efficacité énergétique, le changement des modes de vie ainsi que les efforts de sobriété auront un rôle crucial – et potentiellement plus rapide – pour atteindre les objectifs climatiques et l’arrêt du recours aux combustibles fossiles. 
  C’est notamment ce qui a été souligné pour la toute première fois par le GIEC dans son dernier rapport (Sixth Assessment Report), indiquant que des efforts de sobriété combinés à l'efficacité énergétique pourraient réduire les émissions de CO₂ de 40 à 70 % dans certains secteurs de l’économie mondiale (voir figure SPM.7b).
</p>

<div class="box-accent">
  <p class="text-center"><strong>Importance d’une approche interdisciplinaire</strong></p>
  <p>
    La transition vers la neutralité carbone impose une forte réduction de la consommation d’énergie, grâce à plus d’efficacité énergétique et à un recours accru à des pratiques de sobriété.
    Ces dernières doivent être appliquées partout où elles sont possibles, en interrogeant les usages.
    Ainsi, les auteurs du dernier rapport du GIEC soulignent que les évolutions des usages sont indispensables pour atteindre la neutralité carbone.
  </p>
  <p>
    Un travail en interdisciplinarité tenant compte également des aspects sociaux et humains ainsi que de la problématique des ressources et de leurs flux est essentiel.
  </p>
</div>

<hr>
<p><strong>Notes</strong></p>
<ol style="font-size: 0.9rem;">
  <li id="note-2d-1">Equation de Kaya : Yoichi Kaya et Keiichi Yokobori, <em>Environment, energy, and economy : strategies for sustainability</em> : Tokyo conference on Global Environment, Energy and Economic Development (1993), United Nations Univ. Press, Tokyo, 1997, 381 p. (ISBN 92-808-0911-3).</li>
  <li id="note-2d-2">Au rythme actuel, le parc automobile se renouvelle en 20 ans, le parc immobilier en 50 ans.</li>
</ol>


<hr style="width: 80px; border: 3px solid #117a8b; margin-left: auto; margin-bottom: 2rem;">

### Remerciements

Ce travail est le fruit d’une réflexion et d’une compréhension qui s’est construite sur le long terme avec de nombreux experts du domaine. Pour cette raison, l‘auteur principal souhaite remercier l’ensemble des chercheurs du CEA avec qui il a pu collaborer et échanger pour produire ce document.

En particulier au sein de l’équipe du **CEA I-Tésé**, merci à Clotilde Chagny, Arthur Lynch, Louise Leray, Valérie Seguin, Guillaume Boissonnet et Bertrand Charmaison pour leur collaboration. Merci également à Philippe Azaïs et Fabien Perdu pour leurs précieux conseils. Pour terminer, l'équipe d'I-Tésé remercie chaleureusement **Gabrielle Merite** de nous avoir aidés à illustrer chacun des messages scientifiques que nous avons souhaité partager.

---

### Notes méthodologiques

Les données utilisées pour réaliser ces graphiques correspondent à une agrégation de plusieurs documents issus du SDES, pour les données 2019. Les valeurs correspondent aux données réelles en 2019, et ne sont pas corrigées des aléas climatiques (par opposition à climat constant donc).

Le champ de l’étude inclut la France métropolitaine ainsi que les DROM.

La structure générale des données provient du **Service des Données et Études Statistiques (SDES)** du gouvernement. Les données sont disponibles [ici (Excel)](https://www.statistiques.developpement-durable.gouv.fr/sites/default/files/2020-12/bilan-energetique-2019-donnees-xls.zip) et [là (PDF)](https://www.statistiques.developpement-durable.gouv.fr/sites/default/files/2020-12/bilan-energetique-2019.pdf). Ces données ont été comparées avec la répartition par source et par usage faite par l’**Agence Internationale de l’Énergie (AIE)** sur la base des données du SDES. Ces deux sources sont cohérentes. Nous avons choisi, dans le cadre du transport domestique, d’utiliser la répartition proposée par l’AIE. Pour les autres secteurs, les données utilisées sont celles du SDES.

Il est important de noter également que les consommations énergétiques finales de gaz et combustibles gaz sont données au **PCI** (Pouvoir Calorifique Inférieur) et non au PCS.

Le contenu CO₂ des vecteurs énergétiques finaux provient de la [Base Carbone - Bilan GES de l’ADEME](https://bilans-ges.ademe.fr/). Celui-ci est exprimé en kgCO₂ équivalent par MWh (au PCI pour les combustibles), c’est-à-dire qu’il s’agit des émissions équivalentes de GES, ramenées au pouvoir de réchauffement du CO₂, par unité d’énergie disponible, avant utilisation et conversion dans un moteur ou un moyen de chauffage.


---

### Ressources supplémentaires – références

> 📝 **Note** : les données peuvent présenter des écarts avec celles diffusées dans le cadre du bilan de l'énergie (au-delà de la correction des variations climatiques réalisée dans le bilan). Ces écarts proviennent d'une différence de méthodologie et de champ. Par exemple, les secteurs de la réparation/installation de machines industrielles, de la distribution d'eau et du traitement des eaux usées/déchets sont comptabilisés dans le tertiaire dans le bilan, mais pas ici.

- **Données relatives au transport** :  
  [https://www.statistiques.developpement-durable.gouv.fr/edition-numerique/chiffres-cles-du-climat/11-emissions-de-ges-des-transports](https://www.statistiques.developpement-durable.gouv.fr/edition-numerique/chiffres-cles-du-climat/11-emissions-de-ges-des-transports)

- **Données relatives à la consommation énergétique en France** :  
  [https://www.statistiques.developpement-durable.gouv.fr/edition-numerique/bilan-energetique-2019/pdf/document.pdf](https://www.statistiques.developpement-durable.gouv.fr/edition-numerique/bilan-energetique-2019/pdf/document.pdf)

- **Données relatives au secteur résidentiel** :  
  [https://www.statistiques.developpement-durable.gouv.fr/consommation-denergie-par-usage-du-residentiel](https://www.statistiques.developpement-durable.gouv.fr/consommation-denergie-par-usage-du-residentiel)

- **Données relatives au secteur tertiaire** :  
  [https://www.statistiques.developpement-durable.gouv.fr/consommation-denergie-par-usage-du-tertiaire](https://www.statistiques.developpement-durable.gouv.fr/consommation-denergie-par-usage-du-tertiaire)

- **Base Carbone ADEME (bilans GES)** :  
  [https://bilans-ges.ademe.fr/](https://bilans-ges.ademe.fr/)



### Définitions

- **Bas carbone** : Qualifie l’ensemble des vecteurs énergétiques à faible contenu CO₂, tels que l’électricité en France, les ENRt et déchets, ainsi que la chaleur commercialisée (voir haut carbone).

- **Chaleur fatale** : Énergie qui serait perdue si elle n’est pas valorisée au moment de sa production. C’est typiquement le cas de la chaleur générée lors de procédés industriels ou chimiques, lorsqu’elle n’est pas récupérée.

- **Chaleur commercialisée** : Chaleur vendue à des tiers via des réseaux de chaleur ou des installations de cogénération non connectées à ces réseaux. Les données sont nettes des pertes de distribution.

- **Énergie finale** : Énergie livrée au consommateur pour sa consommation directe (par exemple : essence à la pompe, électricité à domicile).

- **Énergie primaire** : Ressource énergétique brute non transformée, exploitée directement ou importée : pétrole brut, gaz naturel, charbon, biomasse, énergie solaire, hydraulique, éolienne, géothermie, nucléaire. Dans ce document, on parle plutôt de ressource énergétique primaire, car elle doit encore être transformée pour devenir disponible.

- **Énergies renouvelables thermiques et déchets** : Énergies produites sous forme de chaleur, incluant :
  - Combustion : bois-énergie, biocarburants, biogaz, déchets urbains ou industriels.
  - Production primaire de chaleur : géothermie, solaire thermique, pompes à chaleur.

- **Haut carbone** : Qualifie les vecteurs énergétiques issus de combustibles fossiles comme le charbon, le pétrole et le gaz.

- **Réseau de chaleur** : Système de distribution de chaleur produite de manière centralisée pour alimenter plusieurs utilisateurs. Il peut inclure des unités de production permettant d’utiliser massivement des énergies renouvelables ou de récupération.

- **Usages non énergétiques des fossiles** : Utilisation des ressources fossiles comme matières premières (et non comme combustibles) pour produire d'autres substances, par exemple : ammoniac, plastiques, solvants, etc.


### Abréviations


- **COP** : Coefficient de Performance  
- **ECS** : Eau Chaude Sanitaire  
- **ENR** : Énergie Renouvelable  
- **ENRt** : Énergie Renouvelable Thermique  
- **GES** : Gaz à Effet de Serre  
- **GIEC** : Groupe d'experts Intergouvernemental sur l’Évolution du Climat  
- **PAC** : Pompe à Chaleur  
- **PCI** : Pouvoir Calorifique Inférieur (par opposition au PCS, Pouvoir Calorifique Supérieur)  
- **SNBC** : Stratégie Nationale Bas Carbone  
- **VE** : Véhicule Électrique  










