---
title: 1.01 Choisir un hébergeur adapté
people: Catherine G.
scope: Hébergement
responsible:
  - Code(use·ur) → Développeu·se·r
  - Designeu(se·r)
  - Low-code → Freelance et développeur Front-End d'agences
  - No-code → Madame et Monsieur tout le monde
lifecycle: Installation
priority_implementation: Moyen 👍👍
environmental_impact: Moyen 🌱🌱
saved_resources:
  - Déchets électroniques
  - Consommation électrique
  - Émissions de gaz à effet de serre
path: /fiches/WP_1.01-choisir-un-hebergeur-adapte
toIndex: true
---

## Sujet

Bien choisir sa solution d'hébergement est essentielle pour plusieurs raisons :

- **Pour la sécurité de votre site** Plusieurs hébergeurs proposent des offres d'hébergements avec WordPress déjà installé ou installable en un clic et des mises à jour automatiques. Pour éviter les mauvaises surprises lors du déploiement de votre site ou suite à une mise à jour automatique, assurez-vous que l'installation est aux normes de sécurité (aucun dossier n'utilise l'identifiant administrateur par exemple), que vous avez bien accès aux fichiers source et à la base de données, que le thème sélectionné est bien compatible avec les versions des différents logiciels utilisés que ce soit WordPress ou phpMyAdmin pour la gestion de votre base de données MySQL, etc.

- **Pour la souveraineté des données hébergées qu'elles soient d'ordre commercial ou privé** Vérifiez toujours les conditions de vente ainsi que les conditions d'utilisation des services que vous utilisez et informez vos visiteurs si certaines de leurs données sont collectées.

- **Pour la conformité de votre site avec le règlement européen pour la protection des données personnelles (RGPD)** Nous vous invitons à vous référer au site de la [CNIL](https://www.cnil.fr/) pour plus d'informations. ⚠️ Ce n'est pas parce que votre site ne collecte pas directement de données personnelles qu'il est conforme au RGPD et ce n'est pas parce qu'un service tiers est conforme au RGPD qu'il ne collecte pas des données (non personnelles) sur vos utilisateurs !

- **Pour renforcer votre démarche d'écoconception**

## GreenIT vous conseille

Même s'il n'existe pas de label ou certification multi-critères permettant d'évaluer le caractère vertueux d'un service d'hébergement web, nous vous proposons ici quelques critères sur lesquels s'appuyer :

- les certifications [ISO 50001](https://www.iso.org/fr/publication/PUB100400.html) et/ou [ISO 140001](https://www.iso.org/fr/iso-14001-environmental-management.html) afin de garantir le respect de certaines bonnes pratiques en matière de management de l'énergie et l'environnement ;
- la présence de l'hébergeur sur la liste des entreprises référencées comme conformes :
  - au [Code de Conduite européen <abbr title="European Energy Efficiency Platform">E3P</abbr> sur les datacenters](https://web.archive.org/web/20240918212256/https://e3p.jrc.ec.europa.eu/node/575) (archive) ;
  - à un [<abbr title="Renewable Energy Factor">REF</abbr> de 100% sur The Green Web Foundation](https://www.thegreenwebfoundation.org/)  (l'énergie utilisée est 100% renouvelable) ;
- la politique d’achat responsable avec la présence de labels sur le matériel comme des serveurs équipés d’une alimentation électrique conforme à l’écolabel 80Plus (niveaux Platinum et Titanium) et/ou les serveurs estampillés Energy Star ;
- l'utilisation de serveurs fonctionnant en mode asynchrone (i.e. qui ne sont pas tenus de créer un processus ou un thread pour chaque requête) ;
- la politique de l'hebergeur en matière de gestion de l'eau et des déchets électriques et électroniques (DEEE) ;
- l'efficience énergétique du data center (les indicateurs sont rarement publiés, mais peuvent parfois être communiqués par mail, il n'en reste pas moins difficilement vérifiables) :
  - Power Usage Effectiveness (PUE) < 1.6 ;
  - Carbon Usage Effectiveness (CUE) < 0.3 ;
  - Water Usage Effectiveness (WUE) < 0.5 ;
- le respect de la dimension sociale ;
- la compensation carbone.

> Il est aussi fortement recommandé de vérifier [les prérequis nécessaires pour faire tourner WordPress](https://fr.wordpress.org/about/requirements/) et d'adapter l'architecture de votre solution d'hébergement aux besoins de votre site.
> Cela veut dire qu'il faut adapter la dimension de son hébergement à la dimension de son site internet. Si vous en avez les compétences, référez-vous aux Bonnes pratiques 140 à 145 du [livre "Ecoconception web / les 115 bonnes pratiques V4"](https://www.greenit.fr/2022/05/11/mise-a-jour-majeure-du-referentiel-ecoconception-web-les-115-bonnes-pratiques/).
> Par exemple : Un site qui ne pèsera pas plus de 1Go après 10 ans d'utilisation n'a pas besoin de 100Go d'espace disque. Les hébergeurs proposent des hébergements mutualisés, qui permettent de mettre plusieurs sites (les vôtres ou non) sur une même machine physique et donc, de réduire l'impact de votre site (ressources + énergie).

## Exemples

Nous ne pouvons faire une liste exhaustive des hébergeurs. Voici quelques exemples :

- **Scaleway**

  - Normes ISO : https://www.scaleway.com/fr/securite-et-resilience/
  - Politiques et efficience énergétique : https://www.scaleway.com/fr/leadership-environnemental/

- **Hosterra**

  - Normes ISO : Hosterra disposent de centres de données Scaleway
  - Politiques et efficience énergitique (en temps réel) : https://hosterra.eu/fr/company/dc/

- **Datacampus**

  - Politiques : https://datacampus.fr/entreprise-a-mission/

- **Neutral-it**

  - Politiques et ACV (analyse de cycle de vie) : https://neutral-it.com/

- **Infomaniak**
  - Normes ISO : https://www.infomaniak.com/fr/ecologie/certificats-recompenses
  - Politiques : https://www.infomaniak.com/fr/ecologie/engagements

- **OVH**

  - Normes ISO : https://www.ovhcloud.com/fr/enterprise/certification-conformity/
  - Politiques et efficience énergétique : https://www.ovhcloud.com/fr/what-data-center/

## Principe de validation

| Critères                                                                                                        | est                |
| --------------------------------------------------------------------------------------------------------------- | :----------------: |
| Le nombre d'hébergeurs utilisé sans avoir vérifié les différents critères d'une démarche réelle d'écoconception | &le;&nbsp;0        |
| Le nombre de serveurs non adaptés à votre besoin                                                                | &le;&nbsp;0        |
| Renewable Energy Factor (RFE)                                                                                   | ≥&nbsp;100&nbsp;%  |
| Power Usage Effectiveness (PUE)                                                                                 | &le;&nbsp;1.6      |
| Carbon Usage Effectiveness (CUE)                                                                                | &le;&nbsp;0.3      |
| Water Usage Effectiveness (WUE)                                                                                 | &le;&nbsp;0.5      |
