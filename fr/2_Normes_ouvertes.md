[<- Page précédente : Introduction](1_Introduction.md) | [Table des matières](../README.md#table-des-mati%C3%A8res) | [Page suivante : Logiciels libres (open source) - Utilisation ->](3_Logiciel_libre_Utilisation.md)

## Normes ouvertes

- [Interopérabilité](#interopérabilité)
- [Avantages](#avantages)
- [Risques et inconvénients](#risques-et-inconvénients)
- [Pratiques exemplaires pour l'adoption de normes ouvertes](#pratiques-exemplaires-pour-l-adoption-de-normes-ouvertes)
- [Normes ouvertes privilégiées](#normes-ouvertes-privilégiées)
- [Guide numérique du gouvernement du Canada](#guide-numérique-du-gouvernement-du-canada)

Les normes ouvertes sont un ensemble de règles conçues pour faire un travail spécifique dans la technologie. Les normes ouvertes désignent les formats de fichier, les protocoles et les interfaces d'application qui peuvent être mis en oeuvre par toute personne (dans le cadre de logiciels libres et de logiciels exclusifs) puisque les spécifications sont disponibles gratuitement et que leur élaboration et leur normalisation sont ouvertes et transparentes. Ce travail de normalisation est effectué par des organismes spécialisés qui sont habituellement soit des organismes gouvernementaux ou des organismes créés par des professionnels d'un secteur industriel donné. Le Groupe de travail IETF, l'Organisation internationale de normalisation (ISO) et l'Organisation pour l'avancement des normes sur l'information structurée (OASIS) en sont des exemples.

La définition exacte des normes ouvertes peut varier d'une administration à l'autre, mais il y a un haut niveau de convergence dans le [Référentiel Général d'interopérabilité] de la France  (http://references.modernisation.gouv.fr/interoperabilite) (RGI), le [Cadre commun d'interopérabilité du gouvernement du Québec](https://www.tresor.gouv.qc.ca/fileadmin/PDF/ressources_informationnelles/architecture_entreprise_gouvernementale/AEG_3.1-CCIGQinteroperabilite.pdf) (CCIGQ), le [Cadre d'interopérabilité européen](https://ec.europa.eu/isa2/eif_en) (CIE) et les [Principes de normes ouvertes](https://www.gov.uk/government/publications/open-standards-principles/open-standards-principles#open-standard-definition) du Bureau du Cabinet britannique.

Inspirés par les quatre documents stratégiques, les critères suivants définissent les normes ouvertes :

- le processus d'élaboration de la norme est ouvert et transparent pour toutes les parties intéressées et ne peut pas être contrôlé par une seule personne ou entité ayant des intérêts particuliers;
- une plateforme indépendante, neutre et utilisable pour de multiples mises en oeuvre;
- les spécifications et le matériel de soutien sont disponibles gratuitement, sous réserve de restrictions limitées;
- les normes sont appuyées par la collectivité et elles font preuve d'indépendance ou d'une procédure régulière approuvée par un consensus approximatif entre les participants.

### Interopérabilité

La capacité des organisations à interagir en vue d'atteindre des objectifs mutuellement bénéfiques, et compte la mise en commun de renseignements et de connaissances entre ces organisations, à travers les processus opérationnels qu'elles appuient, au moyen de l'échange de données entre leurs systèmes des TIC. L'interopérabilité est une capacité que possède un produit ou un système, dont les interfaces sont intégralement connues, à fonctionner avec d'autres produits ou systèmes existants ou futurs et ce sans restriction d'accès ou de mise en oeuvre.

Cette définition est aussi un rappel du lien vital entre l'interopérabilité et les normes ouvertes. Les interfaces précisées font l'objet de processus de normalisation afin que l'émergence et le maintien de références courantes et documentées soit assurés.

Le fond de la question n'est pas seulement technique; il repose aussi sur un ensemble de préoccupations à différents niveaux. Le [CIE](https://ec.europa.eu/isa2/eif_en) les définit comme suit :

- **La gouvernance de l'interopérabilité** s'entend des décisions relatives aux cadres d'interopérabilité, aux dispositions institutionnelles, aux structures organisationnelles, aux rôles et responsabilités, aux politiques, aux accords et à d'autres aspects du maintien et du suivi de l'interopérabilité aux niveaux national et européen.
- **L'interopérabilité juridique** veille à ce que les organisations opérant sous différents cadres juridiques, politiques et stratégies puissent travailler ensemble.
- **L'interopérabilité organisationnelle** désigne la façon dont les administrations publiques harmonisent leurs processus opérationnels, leurs responsabilités et leurs attentes pour atteindre des objectifs communs et mutuellement bénéfiques.
- **L'interopérabilité sémantique** veille à ce que le format et le sens précis des données et de l'information échangées soient préservés et compris tout au long des échanges entre les parties, autrement dit « ce qui est envoyé est ce qui est compris ». Dans le [CIE](https://ec.europa.eu/isa2/eif_en), l'interopérabilité sémantique couvre les aspects sémantiques et syntaxiques.
- **L'interopérabilité technique** couvre les applications et les infrastructures reliant les systèmes et les services. Les aspects de l'interopérabilité technique comprennent les spécifications des interfaces, les services d'interconnexion, les services d'intégration de données, la présentation et l'échange de données et les protocoles de communication sécurisés.

#### Interopérabilité interne

L'interopérabilité interne est beaucoup plus axée sur la dimension technique. Il faut porter une attention particulière à sa définition pour veiller à ce qu'elle reflète fidèlement les attentes associées au terme, particulièrement en termes d'indépendance - le terme souveraineté est parfois utilisé - et de neutralité.

Les anciens systèmes constituent un obstacle majeur à l'interopérabilité. Historiquement, les applications et les systèmes d'information des administrations publiques ont été développés de façon ascendante, en essayant de résoudre des problèmes locaux et spécifiques au domaine. Il en est résulté une GI/TI fragmentée qui est difficile à interopérer. En raison de la taille de l'administration publique et de la fragmentation des solutions de GI/TI, la pléthore de systèmes existants crée un obstacle supplémentaire à l'interopérabilité dans la couche technique.

L'interopérabilité technique devrait être assurée, dans la mesure du possible, par l'utilisation de normes ouvertes.

### Avantages

#### Interopérabilité

Pour toute organisation, en particulier pour les administrations publiques, les besoins d'interopérabilité se situent à deux niveaux distincts mais qui se chevauchent, soit l'interopérabilité interne avec ses propres technologies de l'information et de la communication (TIC) et celle avec les TIC des acteurs externes (autres administrations, le public, les entreprises, les associations), directement ou indirectement, par la disponibilité de données ouvertes.

##### Indépendance et substituabilité

D'un point de vue interne, l'interopérabilité est étroitement liée à la question de l'architecture d'entreprise, en ce sens qu'elle permet de découpler ses diverses composantes tout en restant intégrée. Ainsi, le [Cadre commun d'interopérabilité du gouvernement du Québec](http://www.tresor.gouv.qc.ca/ressources-informationnelles/architecture-dentreprise-gouvernementale/standards-et-normes/cadre-commun-dinteroperabilite/) (CCIGQ) est lié au Cadre de référence de l'architecture intégrée du gouvernement; et la version 2 du document français [Référentiel général d'interopérabilité](http://references.modernisation.gouv.fr/interoperabilite) renvoie au [Cadre commun d'urbanisation du système d'information de l'État](http://references.modernisation.gouv.fr/sites/default/files/Cadre%20Commun%20d%27Urbanisation%20du%20SI%20de%20l%27Etat%20v1.0_0.pdf).

Dans le contexte de l'architecture d'entreprise entièrement sous votre contrôle, une option consiste à s'assurer que les composants ont des modèles d'intégration clairs, directement via les produits ou en utilisant une famille de produits généralement proposés par un seul fournisseur. Cette approche peut avoir des avantages fonctionnels (généralement en termes d'intégration harmonieuse entre les produits), mais elle a l'inconvénient de lier la technologie de l'information interne à un système externe ou à un fournisseur particulier. Cette connexion peut devenir à la fois un handicap technique (en écartant l'adoption potentielle de nouvelles solutions plus pertinentes) et un handicap économique (en réduisant les possibilités de négociation et en augmentant les coûts de changement). Dans un scénario idéal d'interopérabilité, cependant, les composantes de base peuvent être substituées; chacune peut être modifiée plus facilement et indépendamment. Cette approche renforce la liberté de choix et rend l'architecture intégrée plus souple, parce que chaque élément de base peut être remplacé par un autre qui a la même fonctionnalité sans avoir d'impact sur le reste des systèmes.

##### Adhérences applicatives - Enfermement

À l'interne, l'interopérabilité peut être vue en fonction de deux dimensions : La dimension horizontale (entre deux applications distinctes) qui, de par nature, est la dimension en jeu lorsque deux systèmes différents interagissent; et la dimension verticale, qui concerne les composantes d'une seule application. C'est généralement le cas entre l'application elle-même et les composantes de l'infrastructure sous-jacente (p. ex., une application peut nécessiter une base de données particulière qui, elle-même, ne fonctionne que sur un système d'exploitation particulier, sans qu'aucune fonctionnalité n'entre en jeu). C'est là que l'adhérences applicatives entre en ligne de compte, ce qui dépasse la portée de l'interopérabilité même si un certain nombre de principes fondamentaux sont les mêmes.

##### Infonuagique

L'informatique en nuage consiste à fournir des services d'infrastructure et des services d'applications sur demande. Cela est possible grâce à un niveau élevé de virtualisation des composantes matérielles au moyen de logiciels d'infrastructure de service. L'informatique en nuage est basée sur une architecture logicielle qui gère simultanément l'élasticité des ressources (processeurs, mémoire d'accès aléatoire, stockage et réseaux) et la capacité des applications d'utiliser ces ressources par le biais d'interfaces de libre-services.

Alors que les primitives fondamentales sous-jacentes de l'infrastructure et des architectures d'application restent relativement cohérentes entre les déploiements en nuage et les déploiements d'infrastructure traditionnels, la principale différence réside dans l'accessibilité et la programmabilité de l'infrastructure. L'infonuagique permet, par le biais d'API et d'intégrations d'orchestration, de déployer et de gérer des applications à l'aide de code. L'utilisation de l'orchestration programmatique améliore la capacité d'établir des normes par le biais d'implémentations de référence et d'architectures pré-approuvées.

Une différence notable entre l'infonuagique et l'infrastructure traditionnelle est la disponibilité de services de plus haut niveau dans l'infonuagique.  Ces services, tout en offrant des avantages substantiels pour l'écosystème, ne sont souvent pas transférables à d'autres fournisseurs.  L'utilisation de ces services peut avoir de fortes implications sur l'interopérabilité car ils peuvent créer une sorte de verrouillage.  Ces services sont souvent intégrés directement dans la couche application, ce qui permet un couplage plus étroit entre l'application et le fournisseur.  Lorsqu'on choisit les services d'un fournisseur d'infonuagique, il est important de se poser la question suivante : "Ce service est-il disponible auprès d'un autre fournisseur et quels sont les défis de la commutation ?  L'exploitation des pratiques d'Infrastructure-as-Code (IaC) et DevOps peut aider à atténuer certains des risques de verrouillage, car elles fournissent une interface pour faire évoluer les détails d'un déploiement.

Toute externalisation d'infrastructures ou d'applications vers un service d'infonuagique public doit tenir compte de la capacité de l'organisation privée ou tierce à appliquer des normes qui permettent de changer de fournisseur ou de rétablir un certain nombre de services, si nécessaire. Dans ce contexte, l'absence d'un cadre d'interopérabilité et de normes ouvertes acceptées par le fournisseur constitue un risque important pour la durabilité de la solution.

En ce qui concerne le déploiement d'un nuage privé, l'interopérabilité favorise la concurrence entre les fournisseurs en ce qui concerne le matériel et les logiciels, ainsi que la capacité de développer davantage l'infrastructure au fil du temps. En effet, l'utilisation de normes, par l'entremise des interfaces de programmation (API) par exemple, accroît l'indépendance par rapport aux différents moteurs propres aux composants matériels, et elle rend ces services d'infrastructure indépendants du logiciel déployé.

La mise en œuvre d'une approche infonuagique en premier est une occasion unique de normaliser ces processus et de s'entendre sur un cadre commun. L'utilisation d'un cadre d'interopérabilité et de normes ouvertes facilite et rend moins coûteuse l'impartition d'une partie de l'infrastructure à un organisme tiers, ou la migration vers Services partagés Canada, dans une solution hybride.

#### Logiciel libre

Le [Logiciel libre](3_Logiciel_libre_Utilisation.md) (LL) est un moyen de développer et de distribuer des logiciels. Le code est souvent écrit en collaboration, et il peut être téléchargé, utilisé et modifié par n'importe qui.

Le LL utilise habituellement ou contribue à définir les normes ouvertes et les spécifications accessibles au public. Les logiciel libre sont, de par leur nature, des spécifications accessibles au public, et la disponibilité de leur code source favorise un débat ouvert et démocratique sur leurs spécifications, ce qui les rend à la fois plus robustes et interopérables. Du point de vue de la conception, l'interopérabilité et les logiciels libres sont clairement distincts, tout comme les logiciels libres et les normes ouvertes. Toutefois, du point de vue culturel et historique, il existe des liens solides entre ces concepts. Cela peut s'expliquer par la "collectivité des valeurs" - en raison de leur nature ouverte, les modèles économiques de logiciels libres sont fondés moins sur des stratégies de verrouillage de l'utilisateur et plus sur l'interopérabilité au profit de l'utilisateur. L'utilisation de normes ouvertes est nécessaire pour assurer l'interopérabilité entre les produits ou les systèmes.

### Risques et inconvénients

#### Standards Proliferation

Les normes sont créées pour répondre à des besoins spécifiques et la prolifération des normes concurrentes peut augmenter le temps nécessaire pour sélectionner le bon de réduire les problèmes dans la gestion à long terme des données, des informations et des applications. La co-création de normes peut prendre du temps et l'émergence de nouvelles normes s'il n'est pas possible de parvenir à un accord entre les parties prenantes peut augmenter le risque de passer à une autre norme, le marché élargi pouvant prendre une direction différente.

### Pratiques exemplaires pour l'adoption de normes ouvertes

#### Définir les principes de sélection des normes ouvertes

- Principes utilisés pour évaluer des normes ouvertes spécifiques et exiger leur utilisation, le cas échéant
- Veiller à ce que les normes sélectionnées permettent l'interopérabilité des logiciels via des protocoles ouverts et l'échange de données entre les logiciels et les dépôts de données

#### Identifier les normes ouvertes à utiliser au GC

- Cadre d'interopérabilité qui répertorie les normes ouvertes obligatoires et recommandées
- Alignement et collaboration possible avec [Open Standards Board du Royaume-Uni](https://www.gov.uk/government/groups/open-standards-board) sur la sélection de normes ouvertes pour le gouvernement

#### Formation et soutien

La formation et le soutien à la migration vers l'adoption de normes ouvertes sont similaires aux [Pratiques exemplaires en matière de formation et de soutien à l'utilisation des logiciels libres](3_Logiciel_libre_Utilisation.md#formation-et-soutien).

#### Conversion des formats

- Faire un effort significatif afin de veiller à ce que les formats de fichiers et de données fermés peuvent être convertis en normes ouvertes
- Ne pas oublier que la conversion des documents, par exemple entre Microsoft Office et LibreOffice, est une tâche qui peut exiger beaucoup de ressources humaines pour tous les documents complexes, surtout lorsqu'ils comprennent un formatage précis ou des macros.

### Normes ouvertes privilégiées

La [Norme sur l'interopérabilité du Web du GC](https://www.tbs-sct.gc.ca/pol/doc-fra.aspx?id=25875) rend les normes ouvertes suivantes obligatoires pour les sites Web du GC.

- **Langue de balisage** : [HTML5](https://www.w3.org/TR/html5/)
- **Codage du caractère** : [UTF-8](https://tools.ietf.org/html/rfc3629)
- **Données HTML et vocabulaire de données** : [RDFa Lite](https://www.w3.org/TR/rdfa-lite/), [Schema.org](http://schema.org/)
- **Fil Web** : [Format de syndication Atom](https://tools.ietf.org/html/rfc4287)

La [Norme sur l'accessibilité des sites Web du GC](https://www.tbs-sct.gc.ca/pol/doc-fra.aspx?id=23601) rend la norme ouverte suivante obligatoire pour les sites Web du GC.

- [Règles sur l'accessibilité des contenus Web (WCAG) 2.0](https://www.w3.org/TR/WCAG20/)

#### Autres normes ouvertes au GC

Bibliothèque et Archives Canada (BAC) [Lignes directrices sur les formats de fichier à utiliser pour transférer des ressources documentaires](http://www.bac-lac.gc.ca/fra/services/gestion-ressources-documentaires-gouvernement/lignes-directrices/Pages/lignes-directrices-formats-fichier-transferers-ressources-documentaires.aspx) énumèrent les formats recommandés pour les textes, présentations, courriels, images fixes, audio, vidéo, géospatial, la conception assistée par ordinateur (CAO) et les jeux de données. Le rapport de Patrimoine Canadien sur les [Éléments d'un cadre d'interopérabilité technique](https://wiki.gccollab.ca/%C3%89l%C3%A9ments_pour_un_cadre_d%27interop%C3%A9rabilit%C3%A9_technique_pour_Patrimoine_Canadien), le [Cadre commun d'interopérabilité du gouvernement du Québec](http://www.tresor.gouv.qc.ca/fileadmin/PDF/ressources_informationnelles/architecture_entreprise_gouvernementale/AEG_3.1-CCIGQinteroperabilite.pdf) du Québec et le [Référentiel Général d'interopérabilité](http://references.modernisation.gouv.fr/sites/default/files/Referentiel_General_Interoperabilite_V2.pdf) de la France identifient plusieurs des mêmes normes ouvertes recommandées.

[Les principes des données ouvertes du GC](https://ouvert.canada.ca/fr/principes-de-donnees-ouvertes) indique que "l'utilisation de formats communs" est l'un des principes des données ouvertes, de sorte que les jeux de données diffusés par le GC soient dans des formats de fichier librement accessibles le plus souvent possible.

Services publics et Approvisionnement Canada (SPAC) a mis à l'essai le [Standard de données sur la commande publique ouverte](http://standard.open-contracting.org/latest/fr/) afin de démontrer l'utilisation de la norme en établissant des liens entre les phases du processus d'approvisionnement à l'aide des données provenant des approvisionnements effectués par SPAC au nom des ministères et organismes gouvernementaux. ([source](https://achatsetventes.gc.ca/donnees-sur-l-approvisionnement/projet-pilote-norme-relative-aux-donnees-sur-la-passation-de-marches-ouverts)).

#### Normes ouvertes pour le gouvernement du Royaume Uni

Le [Conseil des normes ouvertes du Royaume-Uni](https://www.gov.uk/government/groups/open-standards-board) sélectionne un ensemble de normes ouvertes pour être utilisé dans la technologie gouvernementale. L'objectif est de les appliquer uniformément à l'ensemble des organismes gouvernementaux, afin d'améliorer les services aux utilisateurs. Les normes ouvertes sont sélectionnées après une période d'examen par les pairs et de commentaires du public par l'entremise du [Centre des normes](https://github.com/alphagov/open-standards). Ce qui suit sont les [Normes ouvertes pour le gouvernement](https://www.gov.uk/government/publications/open-standards-for-government) approuvées.

- **Consulter les documents gouvernementaux** : [HTML5](https://w3.org/TR/html5/) [Format/archivage de documents portables (PDF/A) 1](https://www.iso.org/standard/38920.html) [Format/archivage de documents portables (PDF/A) 2](https://www.iso.org/standard/50655.html)
- **Partage ou collaboration en lien avec des documents gouvernementaux** : [Format de document ouvert (FDO)](https://www.iso.org/standard/66363.html)
- **Profil d'encodage de caractères multiplateforme** : [Unicode 6.2](http://www.unicode.org/versions/Unicode6.2.0/), [UTF-8](https://tools.ietf.org/html/rfc3629)
- **Données contractuelles ouvertes** : [Standard de données sur la commande publique ouverte](http://standard.open-contracting.org/latest/fr/)
- **Codes de pays** : [ISO 3166-1:2013](https://www.iso.org/fr/standard/63545.html)
- **Codes de langues** : [ISO 639-1:2002](https://www.iso.org/fr/standard/22109.html)
- **Données sur le développement international** : [IATI](http://iatistandard.org/202/)
- **Publication des postes vacants** : [JobPosting - Schema.org](http://schema.org/JobPosting)
- **Échange de points de localisation** : [Système européen de référence terrestre (ETRS) 89](http://etrs89.ensg.ign.fr/), [Système géodésique mondial (WGS) 84)](https://www.nga.mil/ProductsServices/GeodesyandGeophysics/Pages/WorldGeodeticSystem.aspx)
- **Identificateurs persistants et résolubles** : [Protocole de transfert hypertexte (HTTP) 1.1](https://tools.ietf.org/html/rfc2616), [Identificateur uniforme des ressources (URI)](https://tools.ietf.org/html/rfc3986)
- **Échange de coordonnées** : [vCard](https://tools.ietf.org/html/rfc6350)
- **Échange d'événements du calendrier** : [iCalendar](https://tools.ietf.org/html/rfc5545)

### Guide numérique du gouvernement du Canada

- [Utiliser des normes et des solutions ouvertes](https://canada-ca.github.io/digital-playbook-guide-numerique/views-vues/standards-normes/fr/4-utiliser-normes-solutions-ouvertes.html)
