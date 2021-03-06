+++
title = "Big Data Overview"
+++

<!-- Slide 1 -->
<!--: .wrap .text-landing ..aligncenter -->
<!--: .text-Virgil -->
Alexandre Linte / Gaëtan Allain
<br><br>
# **Big Data Overview** <a href=https://20100701.github.io/bigdata>{{% fontawesome github %}}</a><br>
2021 - 2022<br>

---
<!-- Slide ABOUT -->
<!--: .wrap -->
<!--: .text-Virgil -->
{{< div class="content-left" >}}

#### Avant-propos
<small>
*Ce contenu a pour objectif de faire découvrir les concepts de ce que l'on appelle le "Big Data". Certains aspects sont simplifiés dans le but de rester compréhensible par un public voulant appréhender ce sujet sans en devenir des experts.*
</small>
<br><br><br>
#### Objectif
<small>
Ce contenu doit permettre aux étudiants d'appréhender les concepts du Big Data ainsi que les solutions techniques misent en œuvre.<br>
Il sert donc de support pour un module d'enseignement du Big Data aussi bien pour les parties théoriques que pratiques. Il limite au maximum le temps passé sur la phase de déploiement des environnements afin de laissé le plus de temps possible à la compréhension du Big Data et aux échanges entre étudiants et formateurs.
</small>
{{< /div >}}

<figure class="content-right">
  <img alt="Screenshot" src="https://images.unsplash.com/photo-1519452635265-7b1fbfd1e4e0?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=934&q=80">
</figure>

---
<!-- Slide 3 -->
<!--: .wrap -->
# Big Data, qu'est-ce que c'est ?

## Une problématique
C'est l'un des plus grands défis des années 2010-2030 pour le monde de l'IT mais aussi et surtout pour l'ensemble de la société (citoyens, états, entreprises, ...). Ce défi est aussi bien technique que sociétale.

En effet, avec la capacité à récolter et effectuer de traitement sur des quantités de donnée de plus en plus importante, les questions autour de la propriété de ces données et de leur utilisation se posent aujourd'hui. L'Europe a par exemple déjà légiféré sur le sujet en votant le <A href="https://fr.wikipedia.org/wiki/Règlement_général_sur_la_protection_des_données">Règlement Général sur la Protection des Données</a> (aka RGPD), le texte est disponible <a href="https://eur-lex.europa.eu/legal-content/FR/TXT/?uri=CELEX:32016R0679">ici</a>.

## Le principe des 3 V
Nous n'avons pas attendu l'avènement du terme "Big Data" pour récolter et effectuer du traitement sur des données. Ce qui change avec le "Big Data" ce sont essentiellement trois caractéristiques liées aux capacités de traitement et à la récolte de donnée : <br>
-  **le volume** : le nombre de donnée créé ne cesse de croitre<br>
-  **la vélocité** : la fréquence à laquelle les données sont créées/récoltées/partagées est de plus en plus élevée<br>
-  **la variété** : les données sont de diverses formes (brutes, non-structurées, structurées, semi-structurées)<br>

---
<!-- Slide 4 -->
<!--: .wrap -->
# Quelques chiffres 
Pour entrapercevoir le monde du Big Data voici quelques chiffres :<br>
<small>Note : il y a 525 600 minutes dans une année</small>

<!--: .flexblock gallery -->
- {{< gallery title="2018 2019" href="https://528484-1683244-raikfcquaxqncofqfm.stackpathdns.com/wp-content/uploads/2019/04/internet-minute-comparison.jpg.webp" src="https://528484-1683244-raikfcquaxqncofqfm.stackpathdns.com/wp-content/uploads/2019/04/internet-minute-comparison.jpg.webp" >}}{{< /gallery >}}
- {{< gallery title="2020 2021" href="https://www.idboox.com/wp-content/uploads/2021/07/Internet-1-minute-2021.jpg" src="https://www.idboox.com/wp-content/uploads/2021/07/Internet-1-minute-2021.jpg" >}}{{< /gallery >}}


---
<!-- Slide 5 -->
<!--: .wrap -->
## Un écosystème
Avec les années, l'écosystème du Big Data est devenu de plus en plus important et il est maintenant associé à celui de l'intelligence artificielle, comme présenté ci-dessous.

<!--: .flexblock gallery -->
- {{< gallery title="landscape" href="http://46eybw2v1nh52oe80d3bi91u-wpengine.netdna-ssl.com/wp-content/uploads/2021/12/Data-and-AI-Landscape-2021-v3-small.jpg" src="http://46eybw2v1nh52oe80d3bi91u-wpengine.netdna-ssl.com/wp-content/uploads/2021/12/Data-and-AI-Landscape-2021-v3-small.jpg" >}}{{< /gallery >}}

---
<!-- Slide 6 -->
<!--: .wrap -->
## Une tendance qui s'accélère
La croissance du Big Data n'est pas prête de s'arrêter et plusieurs facteurs vont l'aider en cela :<br>
- l'IPv6 : le déploiement de l'IPv6 dans les réseaux opérateurs et d'entreprises va permettre de connecter 667 millions de milliards d'appareils à Internet sur chaque millimètre carré de la surface terrestre.<br>
- le nombre d'internaute : en 2018, 3,8 milliards d'humain utilisent Internet, 4,1 milliards en 2021.<br>
- ainsi que le débits des réseaux, le coût du stockage et les domaines utilisant des objets connectés (ex : le médical, la domotique, les télécommunications, la finance, l'agriculture, ...)

<!--: .flexblock gallery -->
- {{< gallery title="Accès Internet" href="https://cdn.statcdn.com/Infographic/images/normal/9775.jpeg" src="https://cdn.statcdn.com/Infographic/images/normal/9775.jpeg" >}}{{< /gallery >}}
- {{< gallery title="croissance IoT" href="https://www.researchgate.net/publication/332392350/figure/fig2/AS:747069593620480@1555126679190/IoT-growth-chart-by-years.png" src="https://www.researchgate.net/publication/332392350/figure/fig2/AS:747069593620480@1555126679190/IoT-growth-chart-by-years.png" >}}{{< /gallery >}}

---
<!-- Slide 7 -->
<!--: .wrap -->
### Exemples d'acteur du Big Data
Dans les principaux acteurs du Big Data, il y a des acteurs du monde de l'IT mais aussi des sociétés dont le cœur de métier est tout autre.
Parmi les leaders du domaine, il y a Google, Apple, Facebook, Yahoo!, Amazon , Microsoft mais aussi Netflix, Tesla, Uber, AirBnB ... 

### Exemples de cas d'usage
Il y a beaucoup d'exemple de cas d'usage Big Data, ceux qui sont listés ci-dessous ont été choisis car ils ne sont pas liés à des entreprises du monde de l'IT. Ils montrent que dès qu'une entreprise détient un grand nombre de donnée, elle peut en tirer un profit grâce au Big Data, quel que soit son secteur d'activité.<br>
<small>
<br>**Suivi épidémiologique** : Grâce à l'Open Data il est possible de suivre l'évolution de la pandémie de covid-19. (<a href=https://covidtracker.fr>site</a>)
<br>**Sauvons les Livebox** : Orange a mis en place en 2016 un scénario Big Data lui permettant de limiter le nombre de Livebox foudroyée. (<a href=https://datascience.wp.imt.fr/2016/04/11/livebox-foudroyee-en-spark>article</a>)
<br>**Vue client 360°** : T-Mobile a mis en place grâce au Big Data une vue client 360° afin de limiter la perte de client. (<a href=https://datafloq.com/read/t-mobile-usa-cuts-downs-churn-rate-with-big-data/512>article</a>)
<br>**Publicité ciblée** : Starbuck a mis en place un système de publicité ciblée grâce aux traitements effectués sur les données de ses clients. (<a href=https://www.forbes.com/sites/bernardmarr/2018/05/28/starbucks-using-big-data-analytics-and-artificial-intelligence-to-boost-performance/#4b0acd0165cd>article</a>)
<br>**Personnalisation des recommandations** : Spotify utilise le Big Data pour proposer à ses clients les morceaux de musique les plus pertinents en fonction de leur goût. (<a href=https://labs.spotify.com/2016/08/07/commodity-music-ml-services/>article</a>)
<br>**Sur de bons rails** : Union Pacific gère les actes de maintenance préventive à l'aide du Big Data et des objets connectés, ce qui a réduit le risque de "déraillement" de ces trains et augmenté la disponibilité des voies. (<a href=https://datafloq.com/read/union-pacific-railroad-turned-industrial-internet-/365>article</a>)
<br>**Le même jus d'orange** : Coca Cola mixe des données satellite, de la météo, des récoltes d'orange et beaucoup d'autres pour s'assurer que le goût de leur jus d'orange sera toujours le même quelque soit la période de l'année. (<a href=https://www.forbes.com/sites/bernardmarr/2017/09/18/the-amazing-ways-coca-cola-uses-artificial-intelligence-ai-and-big-data-to-drive-success/#58b6a1d078d2>article</a>)
<br>**Assistant agricole** : John Deere permet aux agriculteurs mesurer différentes activités afin de les aider à prendre les décisions. (<a href=https://www.terre-net.fr/materiel-agricole/tracteur-quad/article/a-quoi-servent-les-solutions-connectees-john-deere-concretement-207-146778.html>article</a>)
</small>

---
<!-- Slide 8 -->
<!--: .wrap -->
# Big data, une ( r )évolution technique
L'essor du Big Data a entrainé une ( r )évolution dans la façon dont les datacenters étaient gérés. Les infrastructures techniques sur lesquelles fonctionnent les solutions de Big Data comportent de très nombreuses machines physiques le déploiement et la gestion de toutes ces machines est un vrai défi.

La **standardisation** et l'**automatisation** sont deux des aspects les plus importants lorsqu'il s'agit d'opérer, de construire ou de faire évoluer rapidement une solution de Big Data afin de limiter les erreurs humaines et de réduire les coûts.

Pour faciliter la mise en œuvre de ces infrastructures Big Data, toutes les **machines sont identiques**, cela permet de **rationnaliser leur gestion** (ex : remplacement en cas de panne). Du fait de leur nombre, ces machines sont choisis pour limiter la consommation d'énergie (alimentation électrique, climatisation, ...) car la ce poste de dépense est le plus important dans un datacenter.

---
<!-- Slide 9 -->
<!--: .wrap -->
# Clusters qui passent à l'échelle (hyperscale)
La notion de cluster est connue dans le monde informatique depuis de très nombreuses années. Il existe pléthore de solution technique qui fonctionne avec des clusters, souvent constituées de 2 à quelques dizaines de machine. 

Mais dans l'univers du Big Data, les clusters peuvent atteindre plusieurs milliers de machine, c'est pour cela que la mention "qui passent à l'échelle" est importante. De par leur taille les clusters Big Data doivent couvrir l'ensemble des exigences suivantes :<br>
- **Évolutivité (Scalability)** : capacité à pouvoir croître<br> 
- **Élasticité (Elasticity)** : capacité à être redimensionné sans arrêt de service<br>
- **Cohérence (Constitency)** : capacité à ne pas perdre/altérer les données/traitements<br>
- **Résilience (Resilient)** : capacité à pouvoir perdre un ou plusieurs éléments sans impact<br>
- **Disponibilité (Availibility)** : capacité à avoir un taux de disponibilité proche de 100%<br>
- **Distribution (Distributive)** : capacité à pouvoir être déployé dans plusieurs racks/zones/sites distants<br>

---
<!-- Slide 10 -->
<!--: .wrap -->
# Le réseau
Un cluster Big Data a besoin de s'appuyer sur un réseau afin de pouvoir **récolter** les données et les **échanger** entre les différents nœuds du cluster. Les clusters Big Data manipulent de **très grande quantité de donnée**, il est donc facile de concevoir que la capacité du réseau à pouvoir transporter rapidement ces données est un enjeu majeur.
Pour répondre à ce besoin l'architecture des réseaux au sein des datacenters évolue pour passer d'un modèle "3 tiers" à un modèle "Spine-leaf".

---
<!-- Slide 11 -->
<!--: .wrap -->
|||v
## Architecture "3 tiers"
Comme son nom l'indique ce modèle est composé de **3 étages de composant réseau** (switch). Cette architecture n'est pas adaptée aux exigences du Big Data. En effet, si les serveurs représentent les différents nœuds du cluster, le transfert de donnée entre ces nœuds va **transiter jusqu'au "Core switch"**. De plus, un seul chemin réseau est actif pour atteindre une destination (les liens sont en mode **actif/passif**). Du fait du volume de donnée manipulé par un cluster Big Data, cette architecture augmente le risque de congestion du réseau ce qui nuira à la performance du cluster Big Data. 

|||

![architecture 3 tiers](https://20100701.github.io/bigdata/static/images/3tiers.png)

---
<!-- Slide 12 -->
<!--: .wrap -->
|||v
## Architecture "Spine-leaf"
Cette architecture est composée de **2 étages de composant réseau** (switch). En plus de la diminution du nombre de composant, l'intérêt de ce modèle est qu'il permet d'utiliser l'ensemble des liens réseaux en même temps (**actif/actif**).
Le résultat est qu'il y a plusieurs chemins réseaux possible (**+ de débit**) entre 2 nœuds et ils sont plus courts (**- de latence**).
Il est à noter un autre avantage, il est très facile d'augmenter le nombre de switch. En effet, avec cette topologie l'ajout de switch augmente le nombre de chemin réseau possible est donc diminue le risque de congestion.

|||

![spine leaf architecture](https://20100701.github.io/bigdata/static/images/spine_leaf_network.png)

---
<!-- Slide 13 -->
<!--: .wrap bg=bg-black bg=left bgimage=https://cdn.pixabay.com/photo/2018/05/07/22/32/microphone-3381837_960_720.jpg -->
# QUESTION ?

---
<!-- Slide 14 -->
<!--: .wrap -->
![hadoop](https://upload.wikimedia.org/wikipedia/commons/thumb/0/0e/Hadoop_logo.svg/640px-Hadoop_logo.svg.png)

---
<!-- Slide 15 -->
<!--: .wrap -->

# Apache Hadoop, c'est quoi ?
Il existe un grand nombre de solution de Big Data, nous avons choisi de commencer par étudier la solution <a href=https://hadoop.apache.org>Hadoop</a> car c'est l'une des solutions les plus utilisées (quelques exemples d'utilisation d'Hadoop <a href=https://cwiki.apache.org/confluence/display/HADOOP2/PoweredBy>ici</a>).

### ![logo Hadoop](https://hadoop.apache.org/elephant.png) La solution Hadoop <a href=https://hadoop.apache.org/docs/current>{{% fontawesome book-open %}}</a>
Apache Hadoop est une solution écrite en Java qui a pour but de faciliter les traitements distribués sur de grande quantité de donnée. Elle est composée de plusieurs modules (common, hdfs, yarn, mapreduce, ...).Pour cela elle s'appuie sur une architecture en cluster qui passent à l'échelle (hyperscale).

Mais Hadoop n'est pas composé d'un cluster mais en fait de deux clusters qui fonctionnent en parallèle :<br>
- Hadoop Distributed File System (**HDFS**) : pour gérer les ressources de stockage (disk) et les données déposées dans le système de fichier.<br>
- Yet Another Ressource Negociator (**YARN**) : pour gérer les ressources de calcul (cpu + ram) et les traitements qui s'exécutent sur le cluster.<br>

### Deux clusters indépendants
Pourquoi dit-on qu'**HDFS et YARN fonctionnent indépendamment l'un de l'autre** ?
Parce qu'il est possible d'utiliser uniquement HDFS, par exemple, il est possible de stocker des données sur HDFS pour des besoins d'archivage, sans jamais avoir besoin d'effectuer des traitements YARN sur ces données. Inversement, les traitements exécutés sur YARN peuvent ne pas avoir besoin d'utiliser des données stockées sur HDFS comme les calculs mathématiques (ex : le calcul des décimales de PI).

---
<!-- Slide 16 -->
<!--: .wrap -->
|||v
# Écosystème Hadoop
Hadoop fait parti d'un écosystème Big Data ou il existe énormément de solution technique. L'illustration ci-dessous propose la vision de Mercy (Ponnupandy) Beckham de cet écosystème.

|||

![écosystème Hadoop](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2016/10/HADOOP-ECOSYSTEM-Edureka.png)

---
<!-- Slide 17 -->
<!--: .wrap -->

# HDFS en quelques mots
<A href="https://hadoop.apache.org/docs/r1.2.1/hdfs_design.html">HDFS</A> est un système de fichiers distribué, extensible et portable développé par Hadoop à partir du <A href="https://fr.wikipedia.org/wiki/Google_File_System">GoogleFS</A>.  
Écrit en Java, il a été conçu pour stocker de très gros volumes de données sur un grand nombre de machines équipées de disques durs banalisés. Il permet l'abstraction de l'architecture physique de stockage, afin de manipuler un système de fichiers distribué comme s'il s'agissait d'un disque dur unique.

### Les composants HDFS
Une architecture système de fichier HDFS repose sur deux types de composants majeurs : le **namenode** et le **datanode**.

#### Namenode
Ce composant gère l'espace de noms, l'arborescence du système de fichiers et les métadonnées des fichiers et des répertoires. Il centralise la localisation des blocs de données répartis dans le cluster. 

#### Datanode
Ce composant stocke et restitue les blocs de données. Lors du processus de lecture d'un fichier, le NameNode est interrogé pour localiser l'ensemble des blocs de données. Pour chacun d'entre-eux, le NameNode renvoie l'adresse du DataNode le plus accessible, c'est-à-dire le DataNode qui dispose de la plus grande bande passante. Les DataNodes communiquent de manière périodique au NameNode la liste des blocs de données qu'ils hébergent. Si certains de ces blocs ne sont pas assez répliqués dans le cluster, l'écriture de ces blocs s'effectue en cascade par copie sur d'autres.

---
<!-- Slide 18 -->
<!--: .wrap -->
## HDFS : opération d'écriture

![hdfs-WRITE](https://20100701.github.io/bigdata/static/images/hdfs-WRITE.png)

<br><small>*Note : une fois l'opération d'écriture effectuée, le Namenode mets à jour les metadata après avoir interroger les différents Datanodes. Ce mécanisme se déroule régulièrement ce qui permet au Namenode de garantir la cohérence des données stockées dans le système de fichier HDFS et leurs emplacements.*</small>

---
<!-- Slide 19 -->
<!--: .wrap -->
## HDFS : opération de lecture 

![hdfs-READ](https://20100701.github.io/bigdata/static/images/hdfs-READ.png)

---
<!-- Slide 20 -->
<!--: .wrap -->
# Yarn en quelques mots
<A href="https://hadoop.apache.org/docs/current/hadoop-yarn/hadoop-yarn-site/YARN.html">YARN</A> (ou MRV2) est un gestionnaire de ressources. Son rôle est d’attribuer des ressources d'un cluster (CPU & mémoire) sous forme de conteneurs à une application demandeuse.*Note : une application demandeuse est un traitement qui s'exécute sur le cluster.*

### Les composants

|||v
#### ResourceManager
Ce composant gère l’ensemble des ressources du cluster, c’est lui qui a autorité pour attribuer les ressources aux applications demandeuses.
Il embarque un ordonnanceur qui priorise l’attribution des ressources aux différentes applications en accord avec certains paramètres définis au niveau du cluster (queue, limite, …).

#### NodeManager
Ce composant est présent sur chaque machine du cluster (comme le Datanode du HDFS), il surveille les ressources disponibles sur le nœud et remonte un état de ce dernier périodiquement au ResourceManager. Il est également en charge du lancement et de l’exécution des conteneurs. Il en existe deux types : ApplicationMaster et Container.

|||
#### ApplicationMaster
Lorsque une application est lancée sur la cluster, le RessourceManager commence par demander l’instanciation d’un conteneur maître, l'Application Master qui va être en charge de : 
* réserver les ressources nécessaires à l’exécution de l’application auprès du ResourceManager
* suivre l’état de chaque conteneur de l’application
* gérer les échecs et relances de certains conteneurs
* fournir l’état global de l‘application au ResourceManager

#### Container
Il exécute une partie du traitement de l’application, il remonte son état auprès de son ApplicationMaster.

---
<!-- Slide 21 -->
<!--: .wrap -->
# YARN : interactions
![yarn](https://20100701.github.io/bigdata/static/images/yarn.png)

---
<!-- Slide 22 -->
<!--: .wrap -->
# Synthèse Hadoop
Ci-dessous un exemple de ce que pourrait être un cluster Hadoop minimal composé d'un Master et de trois Nodes.

![hadoop_synthese](https://20100701.github.io/bigdata/static/images/hadoop_synthese.png)

---
<!-- Slide 23 -->
<!--: .wrap bg=bg-white bg=aligncenter bgimage=https://images.unsplash.com/photo-1583791031153-d55e79f7f115?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=1867&q=80 -->
# Thank you for your attention

