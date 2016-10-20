---
comments: true
excerpt: |
    Lundi matin, une fausse manipulation chez Orange a entraîné le
    blocage de nombreux sites, comme Google.fr et Wikipedia, ainsi que
    la redirection des personnes tentant d'y accéder vers une [page du
    ministère de l'intérieur][mainrouge] dénonçant l'apologie du
    terrorisme. Beaucoup d'internautes ont sans doute été très surpris
    par l'apparition de ce message. Mais, au-delà de la fausse
    manipulation chez Orange, de quoi s'agit-il?
layout: post
tags:
- CensureDuNet
- CEtat
- CNIL
title: "L'incident chez Orange qui révèle le traitement de données personnelles par le ministère de l'intérieur"
---


Lundi matin, une fausse manipulation chez Orange a entraîné le blocage de nombreux sites, comme Google.fr et Wikipedia, ainsi que la redirection des personnes tentant d'y accéder vers une [page du ministère de l'intérieur][mainrouge] dénonçant l'apologie du terrorisme. Beaucoup d'internautes ont sans doute été très surpris par l'apparition de ce message. Mais, au-delà de la fausse manipulation chez Orange, de quoi s'agit-il? 

[mainrouge]: https://twitter.com/yannux/status/787929698307280896

Depuis l'adoption de la loi Cazeneuve en 2014, l'administration a désormais le pouvoir de dresser une liste de sites destinés à être bloqués afin de lutter contre l'apologie du terrorisme. Cette liste, élaborée en secret et sans aucun contrôle judiciaire, est ensuite transmise aux opérateurs, lesquels sont chargés de mettre en place la censure sur leurs réseaux (dans la plus grande confidentialité)[^dns]. 

[^dns]: Pour les explications techniques de cette censure par DNS, voir notamment <http://www.bortzmeyer.org/google-detourne-par-orange.html>. «Par blocage, filtrage ou prévention de l'accès à des contenus sur Internet, on entendra en général des mesures techniques visant à restreindre l'accès à des informations ou ressources le plus souvent hébergées dans une autre juridiction. Ces actions son en général menées par le fournisseur d'accès à Internet grêce à des produits logiciels ou matériels qui bloquent des contenus ciblés et les empêchent d'être reçus ou affichés sur les dispositifs des clients des fournisseurs d'accès à Internet. Un certain nombre de techniques peuvent être employées, par exemple le blocage du DNS (Système de noms de domaine -Domain Name System) ou de l'URL (Uniform Resource Locator). La suppression ou le retrait de contenus en ligne, en revanche, couvrent de manière générale des demandes ou mesures concernant l'opérateur du site web (ou « hébergeur ») afin que celui-ci retire ou supprime les contenus en ligne ou pages web litigieux. Les fournisseurs d'accès à Internet et les hébergeurs peuvent tous deux être considérés comme des « intermédiaires d'Internet ». » Source : Extrait d'une étude du 1er juin 2016 sur le blocage, le filtrage et le retrait des contenus illégaux qui a été réalisée à partir des législations de 47 États membres du Conseil de l’Europe. Préparée par l'Institut suisse de droit comparé, elle met sur le même plan la France, la Russie et la Turquie.  <https://rm.coe.int/CoERMPublicCommonSearchServices/DisplayDCTMContent?documentId=0900001680657b4d> (p. 3)

Mais, en plus de ce dispositif de blocage, déjà fort critiquable, le gouvernement a également décidé d'imposer aux opérateurs la redirection des visites interceptées vers une page du ministère de l'Intérieur. De ce fait, le gouvernement a créé de sa propre initiative (la loi ne l'ayant pas prévu) un système permettant techniquement au ministère de l'intérieur de savoir qui voudrait visiter tel site bloqué.

Nous avions [fortement critiqué][recours] cette obligation de redirection lors d'une procédure devant le Conseil d'État. Par une [décision du 15 février 2016][ce], ce dernier a rejeté nos arguments, considérant que cette obligation de redirection, bien que permettant au ministère de recevoir des données identifiant les visiteurs interceptés, n'implique pas que le ministère fasse un traitement des données interceptées et n'est donc pas en soit susceptible de constituer une atteinte à la vie privée.

[recours]: https://exegetes.eu.org/recours/filtragecazeneuve/CEtat/
[ce]: https://exegetes.eu.org/recours/filtragecazeneuve/CEtat/2016-02-15-decisionCE-blocage-deref.pdf


Or, qu'observe-t-on aujourd'hui?

Suite à l'évènement de lundi et à la réaction publique qui a suivi, le ministère de l'intérieur a été contraint de [reconnaitre][aveux] qu'il « dispose d'un prestataire pour le suivi statistique des consultations [...] de cette page de blocage »  (et de la page « recours » y étant liée) et que ce prestataire conserve les « adresses IP collectées lors des consultations redirigées » (à l'exception de celles collectées durant l'incident de lundi et qui ont été, elles seules, supprimées). Cette collecte de données est précisément ce que nous dénonçions comme étant l'unique raison d'être de l'obligation de redirection, mais que le Conseil d'État a feint de ne pouvoir anticiper.

[aveux]: https://twitter.com/Place_Beauvau/status/788442407385858056

Or, d'une part, le traitement de données personnelles ici reconnu par le ministère n'a pas été autorisé validement. Pour ce faire, son autorisation aurait au moins dû être précédée par un examen préalable de la CNIL (tel que cette dernière le rappelait dans son avis concernant l'obligation de redirection[^cnil]), ce qui n'a pas été le cas. D'autre part --- et c'est l'essentiel --- un tel traitement, même s'il respectait les formalités légales, resterait illicite en ce qu'il constituerait une atteinte à la vie privée et à la liberté d'information disproportionnée par rapport à l'objectif initialement prévu par le législateur.

[^cnil]: Dans sa délibération n° 2015-001, la CNIL « rappelle que si des traitements de données à caractère personnel spécifiques étaient alimentés par ces données [, recueillies via la page de blocage], ils devraient être soumis à l'examen préalable de la commission ».

Nous avons déjà saisi la CNIL d'une [plainte](https://exegetes.eu.org/recours/filtragecazeneuve/Cnil/) à ce sujet. La récente déclaration du Ministère de l'Intérieur nous ouvre probablement une autre voie contentieuse… À suivre !