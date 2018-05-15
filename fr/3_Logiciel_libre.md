[« Page précédente : Normes ouvertes](2_Normes_ouvertes.md) | [Table des matières](../README.md#table-des-mati%C3%A8res) | [Page suivante : Code source libre »](4_Code_source_libre.md)

## Logiciels libres

- [Terminologie](#terminology)
- [Historique](#history)
- [Propriété intellectuelle](#intellectual property)
- [Utilisation des logiciels libres](#using-open-source-software)
- [Avantages](#benefits)
- [Risques et inconvénients](#risks-and-drawbacks)
- [Pratiques exemplaires pour l'utilisation des logiciels libres](#best-practices-for-using-oss)
- [Publication des logiciels libres](#releasing-open-source-software)
- [Logiciels libres préférés](#preferred-open-source-software)
- [Exemples](#examples)

### Terminologie

Le code source est la version d'un logiciel interprétable par un humain. Le code est rédigé par des développeurs, et il peut être lu et modifié par d'autres. On peut compiler le code pour en faire un fichier exécutable ou binaire, qui n'est pas lisible.

Les logiciels libres et les logiciels à source ouverte sont des logiciels dont le code source est distribué et peut être utilisé, copié, étudié et redistribué sans restriction.

Le terme « logiciel libre » a d'abord été proposé par Richard Stallman et défendu par la Free Software Foundation (FSF). Le logiciel libre est défini par [quatre libertés essentielles](https://www.gnu.org/philosophy/free-sw.fr.html) : La liberté d'exécuter le programme, la liberté d'étudier son fonctionnement, la liberté de le modifier et la liberté de le redistribuer. L'accès au code source est une condition préalable de ces libertés; il ne constitue pas le but ultime en soi.

Le terme « logiciel à source ouverte » est utilisé par l'Open Source Initiative (OSI). Ils sont l'autorité pour certifier si une licence de logiciel est une licence source ouverte. La [définition du logiciel à source ouverte](https://opensource.org/docs/osd) s'appuie sur dix critères.

En anglais, le terme « free » peut signifier que quelque chose est disponible sans frais (gratuit) ou qu'il donne certaines libertés (libre). Beaucoup de renseignements disponibles en ligne présentent la liberté d'expression, la bière gratuite et même les chatons gratuits comme des métaphores des logiciels libres et gratuits.

Les logiciels libreset les logiciels à source ouverte sont presque équivalents, mais ils correspondent à deux visions différentes, et aucun ne veut être inclus dans l'autre. Des auteurs utilisent les termes « logiciel libre et ouvert » (LLO) ou « logiciel libre et en source ouverte » (FLOSS, pour « free/libre open source software »). Aux fins du présent livre blanc, nous avons choisi d'utiliser le terme « logiciel libre » (LL) pour englober les termes « logiciel libre » et « logiciels à source ouverte ».

### Historique

Le LL remonte aux débuts de l'informatique. Un grand nombre des réussites du gouvernement ouvert seraient impossibles sans un code source libre et la générosité des communautés d'internautes. Nous devrions rendre la pareille.

Les licences d'utilisation de logiciels (libres ou exclusives) tirent leur origine d'une source commune : le système d'exploitation Unix. ([source](https://opensource.com/article/17/9/open-source-licensing)) L'histoire est décrite en détail dans le document [Origins and History of Unix](http://www.faqs.org/docs/artu/ch02s01.html). Unix, premier système d'exploitation général, a été mis au point par AT&T Bell Laboratories à la fin des années 1960 et au début des années 1970. À cette époque, le département de la Justice des États-Unis avait émis un décret de consentement interdisant à AT&T de se livrer à des activités commerciales à l'extérieur de son champ d'activité principal, le service téléphonique. En raison du décret de consentement, AT&T ne pouvait pas exploiter Unix en tant que produit commercial, ce qui a poussé Bell Laboratories à céder Unix sous forme de code source selon des modalités autorisant sa modification ou sa redistribution. Cette situation a permis une utilisation généralisée d'Unix par les informaticiens et favorisé sa grande popularité dans les années 1970 et 1980.

Après l'abrogation du décret de consentement par le département de la Justice des États-Unis en 1983, AT&T a commercialisé Unix en tant que produit exclusif et adopté des conditions de licence plus restrictives. Pendant ce temps, il y a eu l'avènement des micro-ordinateurs (ou ordinateurs personnels) dans les années 1980, ce qui a conduit à une normalisation des logiciels. Cette normalisation a ensuite incité les entreprises à distribuer leurs logiciels sous forme binaire seulement parce que les utilisateurs avaient moins besoin d'examiner ou de corriger le code source. La licence exclusive est donc devenue le modèle dominant pour l'octroi de licences de logiciels.

À la suite de ce changement, Richard Stallman et le projet GNU ont commencé la conception d'un système d'exploitation offrant une alternative libre à UNIX. À la même période environ, la Free Software Foundation (FSF) a été créée pour promouvoir l'utilisation de LL. Le système d'exploitation avait à la fois besoin du noyau et des outils nécessaires à l'installation, à l'exécution et au développement de programmes. Le projet GNU a mis au point les outils, mais il manquait un noyau fonctionnel. C'est à ce moment que Linus Torvalds, un adolescent finlandais, a développé le premier noyau Linux dans le cadre d'un projet scolaire.

L'ensemble du noyau Linux et des outils GNU, communément appelé « Linux », a été publié dans le cadre de la [licence publique générale GNU](https://www.gnu.org/licenses/gpl-3.0.fr.html) (GPL), un modèle de licence créé par le projet GNU. La licence GPL a accordé aux bénéficiaires des droits illimités de redistribution du logiciel à condition que le code source ne puisse pas être tenu secret. Avec la popularité croissante de Linux, de ses milliers de contributeurs et de ses milliards d'utilisateurs, l'industrie a appris à suivre et à adopter les modalités de la licence GPL. Vers la fin des années 1990, la licence GPL et le paradigme des licences libres ont gagné en popularité et reçu un accueil largement favorable à l'échelle de l'industrie.

### Propriété intellectuelle

#### Licences

Aujourd'hui, la licence GPL en est à sa troisième version (GNU GPLv3) et elle n'est qu'un des nombreux types de licences libres. L'Open Source Initiative (OSI) a approuvé plus de 80 licences libres. Ces licences appartiennent habituellement à l'une de deux catégories suivantes : les licences permissives et les licences réciproques.

Même parmi les licences que la Free Software Foundation (FSF) et l'OSI approuvent parce qu'elles possèdent les caractéristiques de base du LL, les modalités et les obligations varient grandement. On observe toutefois plusieurs catégories de clauses courantes :

- les avis généraux sur l'exonération de garantie ou la non-responsabilité;
- les obligations de notification, qui exigent généralement d'aviser les utilisateurs en aval de la licence de LL qui s'applique à l'oeuvre;
- les obligations relatives au code source, qui exigent généralement la fourniture du code source du logiciel au moment de la distribution;
- les obligations relatives à l'octroi de licence réciproque, qui nécessitent généralement la publication de toute modification ou amélioration en vertu de la même licence.

On retrouve les deux premiers types de clauses, soit les avis et les obligations de notification, dans presque toutes les licences de LL. En fait, la [licence BSD à deux clauses](https://opensource.org/licenses/BSD-2-Clause), courte et populaire, contient à peine plus que ces deux obligations. D'autres licences plus vastes, comme la licence GPL, contiennent des clauses qui énoncent ces quatre obligations.

##### Avis

La plupart des licences de LL comprennent un avis d'exonération de garantie le plus exhaustif possible afin de veiller à ce qu'aucune garantie ne s'applique. Par exemple, la clause suivante de la [deuxième version de la licence publique Mozilla](https://www.mozilla.org/en-US/MPL/2.0/) (MPLv2) propose une version typique de cette modalité de la licence :
> En vertu de la présente licence, les logiciels visés sont fournis « en l'état », sans aucune garantie explicite, implicite ou légale, ce qui comprend notamment toute garantie concernant l'absence de défectuosité, la qualité marchande, l'adaptation à un usage particulier ou l'absence de contrefaçon du logiciel visé. Vous assumez en totalité le risque lié à la qualité et au rendement du logiciel visé. Si le logiciel visé se révèle défectueux à quelque égard que ce soit, vous (et non un contributeur) devez assumer les coûts d'entretien, de réparation ou de correction nécessaires. Le présent avis de non-responsabilité constitue une part essentielle de la licence. La licence n'autorise aucune utilisation du logiciel visé, sauf en vertu du présent avis.

Comme on l'a montré, en plus de préciser que la licence est « sans aucune garantie », ces clauses prennent le plus souvent soin d'exclure toute garantie de « qualité marchande » ou d'« adaptation à un usage particulier ». Cela permet de clarifier et de veiller à ce que ces deux garanties ne s'appliquent pas, car certaines lois pourraient autrement les imposer en tant que conditions implicites d'un contrat ou d'une licence. Par exemple, lors de la vente de logiciels en Ontario, la [Loi sur la vente d'objets](https://www.ontario.ca/fr/lois/loi/90s01) impose des garanties implicites quant à la qualité marchande (article 13) et, dans certains cas, des garanties relatives à l'adaptation à un usage particulier (article 15). Toutefois, compte tenu des exclusions explicites dans les licences de LL typiques, ces garanties ne s'appliquent pas.

De nombreuses licences énoncent explicitement les garanties d'absence de contrefaçon (p. ex., la licence MPLv2, comme on l'a indiqué ci-dessus). Cet avis vise à exclure la doctrine américaine d'une garantie implicite d'absence de contrefaçon de l'[article 2-312 de l'Uniform Commercial Code](https://www.law.cornell.edu/ucc/2/2-312), qui garantit autrement que le logiciel ne viole pas le droit d'auteur d'un tiers. Par exemple, si un développeur de logiciel téléchargeait un élément de code dans un projet de LL et que cet élément provenait à l'origine d'un logiciel exclusif protégé par droit d'auteur, quiconque téléchargerait ou utiliserait le LL enfreindrait techniquement le droit d'auteur. En cas de poursuite pour une telle violation, la garantie d'absence de contrefaçon ferait en sorte que l'utilisateur n'aurait aucun recours contre les distributeurs ou les développeurs; l'utilisateur doit faire preuve de vigilance. Au Canada, même s'il n'existe pas de doctrine précise sur la garantie d'absence de contrefaçon, cette clause de licence présente un avis concernant les garanties de titre semblables (surtout lorsqu'elle est prise en compte conjointement avec un avis général sur le fait que la licence vient « sans aucune garantie » à l'article 13 de la [Loi sur la vente d'objets] [https://www.ontario.ca/fr/lois/loi/90s01]). En plus des avis sur les garanties, presque toutes les licences comportent un avis de non-responsabilité. Par exemple, la licence MPLv2 indique ce qui suit :
> Un contributeur, ou toute personne qui distribue le logiciel visé dans la mesure permise ci-dessus, ne peut en aucun cas et sous aucune théorie juridique, qu'elle découle d'un délit civil (y compris la négligence), être tenu responsable envers vous de tout dommage direct, indirect, particulier, accessoire ou consécutif de quelque nature, ce qui comprend notamment les dommages découlant de la perte de bénéfices, de la défection de clients, d'un arrêt de travail, d'une défaillance informatique, ou de toute autre perte ou tout autre dommage commercial, même si cette partie aurait dû être informée de la possibilité de tels dommages. Cette limitation de responsabilité ne s'applique pas à la responsabilité en cas de décès ou de préjudice corporel résultant de la négligence d'une telle partie dans la mesure où la loi en vigueur l'interdit. Certaines administrations ne permettent pas l'exclusion ou la limitation des dommages accessoires ou consécutifs; il est donc possible que cette exclusion ou limitation ne s'applique pas à vous.

Encore une fois, cet avertissement vise de façon générale à couvrir tous les motifs de responsabilité et tous les types de dommages possibles. Il en résulte que toute personne qui utilise un LL le fait à ses propres risques.

Étant donné que le contributeur (le gouvernement du Canada dans le cas présent) n'assume aucune responsabilité et n'offre aucune forme de garantie pour les contributions faites ou les produits obtenus, il doit également renoncer à toute forme de propriété réelle ou perçue liée au code ou au produit généré.

Ces avis sont courants dans la presque totalité des licences de LL, mais les concédants peuvent les modifier. Dans certains cas, une licence de LL permet au concédant de formuler d'autres avis. Par exemple, la licence MPLv2 permet au concédant de « prévoir d'autres avis d'exonération de garantie ou limitations de la responsabilité propres à une administration donnée ». Dans d'autres cas, un concédant peut faire le contraire et choisir d'offrir une garantie ou d'accepter une responsabilité, en supprimant l'effet de l'avis d'exonération de garantie. Par exemple, selon la licence MPLv2 « [v]ous pouvez choisir d'offrir et de facturer des frais pour la garantie, le soutien, l'indemnisation ou les obligations relatives à la responsabilité pour au moins un destinataire du logiciel visé ».

##### Obligations de notification

Comme les avis, une clause relative aux obligations de notification est la norme dans presque toutes les licences de LL. Il s'agit d'une obligation de reproduire le texte de la licence (directement ou par un hyperlien) chaque fois que l'oeuvre autorisée est reproduite. Les obligations de notification exigent aussi d'habitude que les oeuvres distribuées conservent les autres avis qui les accompagnent (p. ex., déclarations relatives au droit d'auteur, autres avis d'exonération de garantie ou de non-responsabilité, ou avis sur les brevets). Habituellement, les obligations de notification s'appliquent au moins à la distribution du code source, mais elles s'appliquent souvent aussi à la redistribution du code exécutable, selon la licence. À titre d'exemple, l'obligation de notification typique de la licence MPLv2 prévoit ce qui suit :
> Vous ne pouvez pas supprimer ou modifier la teneur des avis de la licence (y compris l'avis de droit d'auteur, l'avis sur le brevet, les avis d'exonération de garantie ou les limitations de la responsabilité) contenue dans le code source du logiciel visé, sauf dans la mesure requise pour corriger des inexactitudes factuelles connues.

##### Licences réciproques

Une caractéristique distinctive et courante des LL a tendance à répartir les licences en deux catégories, soit celles ayant une obligation réciproque (aussi appelée « gauche d'auteur », « partage à l'identique » ou
« héréditaire ») et celles qui n'en ont pas. Les licences de la catégorie réciproque stipulent que les modifications apportées au logiciel doivent également être visées par la même licence. Par conséquent, si une personne apporte un changement à un logiciel réciproque ou si elle inclut un code visé par une licence réciproque dans son propre logiciel, cette personne ne peut pas distribuer la nouvelle oeuvre en tant que logiciel exclusif; elle doit seulement redistribuer le nouveau code avec la même licence de LL. La licence GPL, qui est la licence de gauche d'auteur la plus populaire, explique cette stipulation comme suit :
> Pour protéger vos droits, nous devons empêcher les autres de vous les refuser ou de vous demander de les céder. Vous avez donc une certaine responsabilité si vous distribuez des copies du logiciel, ou si vous le modifiez, à savoir la responsabilité de respecter la liberté des autres.
> Par exemple, si vous distribuez des copies d'un tel programme, à titre gracieux ou contre rémunération, vous devez transmettre aux bénéficiaires les mêmes libertés que vous avez reçues. Vous devez veiller à ce qu'ils reçoivent eux aussi le code source ou qu'ils puissent l'obtenir.

Seules certaines licences de LL contiennent cette stipulation, alors que d'autres licences populaires, comme la licence MIT, la licence BSD et la licence Apache, ne l'ont pas. Les licences sans cette stipulation sont généralement appelées « licences permissives ». Dans ces cas, l'auteur des modifications n'est pas tenu d'assujettir ses modifications à la même licence, ni même à toute autre licence de LL. En général, l'auteur des modifications peut même utiliser et redistribuer le logiciel modifié en tant qu'application logicielle exclusive. La figure ci-dessous illustre les deux différents types de permis de LL.

(Image?)

Cependant, différentes licences réciproques établissent des degrés variables de mise en application de cette obligation réciproque de distribution en vertu d'une même licence, ce qui vient brouiller la distinction entre ces types de licences. Il s'agit peut-être de l'aspect le plus déroutant des licences de LL et il mérite une attention particulière. Pour déterminer si une certaine activité comporte une obligation réciproque, il faut tenir compte (1) du type de distribution et (2) de l'ampleur de l'intégration avec le code original.

En ce qui concerne le type de distribution, les obligations réciproques ne s'appliquent qu'à certaines activités relatives à la « distribution ». En l'absence d'une telle distribution, les licences permettent presque toujours à une personne d'utiliser et de modifier un logiciel visé par une licence réciproque sans jamais publier son code. Par exemple, une entreprise peut modifier et personnaliser un logiciel en vertu d'une licence réciproque à des fins internes, et elle n'a pas besoin de partager ce logiciel ou le code source du logiciel. Toutefois, une « distribution » déclenche une obligation réciproque de distribution en vertu de la licence originale. Il existe deux types de déclencheurs courants dans les licences de LL :

- **Distribution du code source ou exécutable** : La distribution du logiciel, soit par Internet ou sur un support physique comme un disque compact, qu'il s'agisse de code source ou de code exécutable, est le déclencheur le plus courant d'une obligation réciproque. Par exemple, il s'agit du déclencheur prévu dans la licence GPL, très populaire.
- **Accès sur un réseau informatique** : Élément présent dans la [licence publique générale GNU Affero](https://www.gnu.org/licenses/agpl-3.0.fr.html), l'accès à un réseau informatique est un déclencheur beaucoup plus important large qui impose une obligation réciproque chaque fois que d'autres personnes accèdent au logiciel sous licence par l'entremise d'un réseau informatique. Ce déclencheur vise à englober les entreprises de services Web qui exploitent leurs plateformes à l'aide de LL; ces entreprises doivent mettre leur code source à la disposition des autres.

Même si le logiciel est distribué, les obligations réciproques ne s'étendent qu'à certaines modifications (selon la licence) :

- **oeuvres dérivées** : Comme le prévoit la licence GPL, ce type de clause réciproque stipule que l'obligation s'applique à toutes les « oeuvres dérivées » (l'équivalent américain d'une « adaptation » en vertu de la loi canadienne sur le droit d'auteur, probablement d'une portée semblable). La limite exacte de ce qui constitue une « oeuvre dérivée » est chaudement débattue; cependant, il est clair qu'une simple « collection » d'oeuvres ne déclenche pas d'obligations réciproques.
- **Collections** fait référence à la distribution collective de nombreux programmes informatiques (p. ex., sur le même disque compact) qui, toutefois, n'interagissent pas étroitement entre eux.
- **oeuvres dérivées avec autorisation de liaison** : L'exemple le plus frappant de ce type de clause est celui que l'on trouve dans la [licence publique générale GNU amoindrie (https://www.gnu.org/licenses/lgpl-3.0.fr.html) (LGPL). Cette licence ressemble à la licence GPL, mais elle autorise explicitement une personne à lier son code de manière statique ou dynamique à une bibliothèque de programmes visés par une licence LGPL, sans déclencher d'obligation réciproque (en développement logiciel, le terme « liaison » comprend un couplage souple dans le cadre duquel un élément logiciel communique avec un d'autres logiciels et utilise leurs fonctions).
- **Fichiers modifiés seulement** : Propre à la licence publique Mozilla (MPL), ce type de clause n'impose que des obligations réciproques sur les fichiers modifiés. Si une oeuvre dérivée contient des fichiers qui sont des versions modifiées de l'oeuvre originale, ainsi que de nouveaux fichiers, seuls les fichiers originaux directement modifiés sont visés par l'obligation réciproque.

Les différences entre les diverses licences de l'ensemble populaire GNU illustrent comment le type de distribution et l'étendue de l'intégration interagissent pour déterminer dans quelles circonstances une obligation réciproque s'applique, comme le montre le tableau suivant.

|            | **oeuvre dérivée de l'original** | **oeuvre dérivée avec liens vers l'original seulement** | **Collection, y compris l'original non modifié** |
| ---------- | ---------- | ---------- | ---------- |
| **Distribution du code source ou du code d'objet** | GPLv3 : **Oui**<br/>LGPLv3 : **Oui**<br/>AGPLv3 : **Oui** | GPLv3 : **Oui**<br/>LGPLv3 : **Non**<br/>AGPLv3 : **Oui** | GPLv3 : **Non**<br/>LGPLv3 : **Non**<br/>AGPLv3 : **Non** |
| **Fourniture d'un accès sur un réseau informatique** | GPLv3 : **Non**<br/>LGPLv3 : **Non**<br/>AGPLv3 : **Oui** | GPLv3 : **Non**<br/>LGPLv3 : **Non**<br/>AGPLv3 : **Oui** | GPLv3 : **Non**<br/>LGPLv3 : **Non**<br/>AGPLv3 : **Non** |

##### Obligations relatives au code source

Les licences réciproques comprennent habituellement une « obligation relative au code source » qui exige que toute oeuvre distribuée par une personne comprenne le code source ou, à tout le moins, un lien vers ce code. Ainsi, le logiciel demeure dans un format que les utilisateurs en aval peuvent continuer de modifier. Sans une telle exigence, quelqu'un pourrait apporter des changements au logiciel en vertu d'une licence réciproque, mais seulement redistribuer le code exécutable. Cela ne permettrait plus à d'autres d'apporter d'autres changements ou de les réintégrer dans le projet initial.

Bien qu'une obligation relative au code source aille habituellement de pair avec une licence réciproque, il convient de prendre note que, dans certains cas, cette obligation peut seulement être rattachée au code original. Cet élément devient particulièrement important lorsqu'on utilise des bibliothèques de logiciels. Par exemple, les fournisseurs de logiciels exclusifs peuvent établir des liens vers des bibliothèques de LL qui sont visées par une licence publique GNU amoindrie, ainsi que les utiliser. Tant que le logiciel exclusif ne fait qu'établir des liens menant à ces bibliothèques, l'obligation réciproque ne s'applique pas. Le fournisseur n'est pas tenu de divulguer son propre code source. Toutefois, l'obligation relative au code source s'applique toujours aux bibliothèques elles-mêmes. Le fournisseur a l'obligation de redistribuer ou de fournir autrement le code source original de la bibliothèque avec le produit exclusif.

Dans certains cas, il n'est pas possible pour une personne de fournir directement le code source avec le code exécutable. Si l'on distribue un logiciel sur un disque compact ou un DVD, il peut être difficile d'inclure les deux, surtout si l'on tient compte du fait que le code source peut être beaucoup plus volumineux que le code exécutable. Pour cette raison, les licences sont habituellement souples quant à la façon dont il faut fournir le code source. Par exemple, la licence GPLv3 permet à une personne de fournir, au lieu du code source lui-même, une offre écrite de distribution du code source sur un disque compact distinct ou par l'entremise d'un serveur réseau. En cas de distribution du code exécutable par l'entremise d'Internet, une personne peut simplement fournir des instructions sur la façon de télécharger le code source à partir d'un autre serveur branché à Internet.

#### Droit d'auteur

La licence et le droit d'auteur sont deux choses distinctes. Dans certains cas, la licence peut accorder des droits supplémentaires au titulaire du droit d'auteur. Les oeuvres réalisées par des employés du gouvernement du Canada pendant les heures de travail sont visées par un droit d'auteur qui appartient à l'État ou au gouvernement du Canada.

### Utilisation d'un logiciel libre

Dans le contexte de l'utilisation d'un logiciel libre pour lequel personne ne distribue le logiciel, les organisations s'en servent habituellement à cinq fins : services Web et de fichiers, suite bureautique, application logicielle spécialisée, logiciel personnalisé à des fins internes et logiciel personnalisé qui sera utilisé par d'autres services de la même organisation.

Le [Guide de l'open source] de Smile (http://www.open-source-guide.com/fr) énumère actuellement plus de 350 solutions « professionnelles » de LL avec examens et évaluations.

#### Logiciel côté serveur

Surtout par l'entremise d'Internet, les LL sont depuis longtemps une pierre angulaire du logiciel serveur. Les LL de serveur Web comme Apache et Nginx exploitent plus de 65 % des sites actifs dans Internet selon l'[enquête sur les serveurs Web de février 2017 de Netcraft](https://news.netcraft.com/archives/2017/02/27/february-2017-web-server-survey.html). Les serveurs libres de bases de données MySQL et MariaDB sont très populaires, et le LL Tomcat occupe la majorité du marché des serveurs d'applications Java ([source](https://blog.jelastic.com/2016/04/14/software-stacks-market-share-first-quarter-of-2016/).

Les organisations du secteur public déploient des LL pour les serveurs aussi rapidement que les organisations du secteur privé. Par exemple, le site Web principal du gouvernement du Canada à [Canada.ca](https://www.canada.gc.ca) utilise le serveur Web libre Apache. Le Conseil national de recherches du Canada (CNRC) utilise Apache, MySQL et l'outil d'authentification OpenLDAP pour les publications électroniques. En fait, dans l'ensemble, les logiciels côté serveur demeurent la principale utilisation des LL au sein des organisations du secteur public. (Exemples plus récents...)

#### Suite bureautique

Comparativement à l'utilisation des LL côté serveur, l'utilisation institutionnelle et opérationnelle des logiciels de bureau libres est un phénomène relativement nouveau. Toutefois, un document de recherche publié en 2008 intitulé « [The Migration of Public Administrations Towards Open Source Desktop Software] » (https://www.igi-global.com/chapter/migration-public-administrations-towards-open/10088) montre que ce domaine des LL a suscité un intérêt accru ces dernières années, surtout dans le secteur public. Par exemple, les administrateurs publics de la ville de Paris ont décidé de transférer 17 000 ordinateurs de bureau exécutant Microsoft Office et Microsoft Internet Explorer vers OpenOffice.org et Mozilla Firefox. Selon un [article publié sur le site Web de l'Interoperability Solutions for Public Administrations de l'Union européenne](https://joinup.ec.europa.eu/news/french-gendarmerie-open-sou), la Gendarmerie nationale française a commencé par utiliser OpenOffice sur la totalité de ses 90 000 ordinateurs personnels. En 2006, elle a installé le navigateur Web Mozilla Firefox et le client de courriel Mozilla Thunderbird sur tous ses ordinateurs personnels, puis d'autres outils de bureau libres, y compris le logiciel de manipulation d'images Gimp et l'application multimédia VLC. En 2008, elle a mis en oeuvre Ubuntu Linux sur 5000 postes de travail; aujourd'hui, elle possède 72 000 postes de travail exécutant Ubuntu Linux. Bien que LibreOffice et Firefox soient parmi les applications de bureautique libres les plus courantes, un large éventail d'applications sont disponibles.

#### Logiciels spécialisés

De nombreux services publics et applications libres desservent un secteur d'activité particulier ou d'autres intérêts. Dans le cas des logiciels hautement spécialisés, il n'existe peut-être même pas de solutions de rechange à une application libre particulière si aucun marché suffisamment important n'a été développé pour attirer des fournisseurs de produits exclusifs. Dans bien des cas, les chercheurs universitaires publient directement leurs initiatives de recherche spécialisées sous la forme de bibliothèques et d'applications de LL.

À titre d'exemple, dans le domaine spécialisé de la géomatique, [MapServer](http://mapserver.org/) est un LL couramment utilisé pour afficher des cartes spatiales dynamiques par l'entremise d'Internet. MapServer a été mis au point à l'Université du Minnesota. Publié en vertu de la licence de LL, il est maintenant administré par l'Open Source Geospatial Foundation (OSGeo), et il est utilisé et appuyé par une communauté mondiale de développeurs.

#### Modification interne

Toutes les licences de LL accordent aux utilisateurs de vastes droits pour modifier le logiciel. Étant donné que seule la distribution peut déclencher des obligations réciproques, il est possible de modifier les logiciels à des fins internes sans déclencher d'autres obligations juridiques. Le contexte juridique de la modification d'un LL et de son utilisation interne est le même que celui de son utilisation interne sans modification.

Cependant, bien qu'il n'y ait pas de différence juridique entre ces deux scénarios, certaines organisations et entreprises pourraient toujours souhaiter établir une politique différente pour le traitement des logiciels modifiés, comme les « Lignes directrices sur les LL du CNRC » (disponibles à partir de GCpédia). Le suivi et le traitement des logiciels modifiés avec une plus grande prudence peuvent aider à veiller à ce qu'une organisation ou une entreprise ne distribue pas le logiciel par erreur ultérieurement (ce qui pourrait alors avoir d'autres conséquences juridiques).

#### Distribution interne

Le scénario d'« utilisation sans distribution » (c.‑à‑d. le contexte qui ne déclenche pas d'obligations en matière de licence réciproque) a une portée relativement vaste. En général, la distribution interne au sein d'une entreprise ou d'une organisation ne constitue pas un « transfert » ou une « distribution » de nature juridique, et elle ne comprend pas d'obligations en matière licence réciproque. Par exemple, la licence GPL considère la distribution comme étant « tout type de propagation qui permet à d'autres parties de faire ou de recevoir des copies ». Une société n'est qu'une seule partie juridique et elle peut faire des LL, les modifier et les distribuer à ses employés sans déclencher d'autres obligations.

Étant donné que les ministères distincts fonctionnent de façon semi-autonome, on peut appuyer que les différents ministères constituent des « parties » différentes. Toutefois, cette interprétation est peu probable. Une telle interprétation serait incompatible avec l'interprétation juridique générale selon laquelle le gouvernement fédéral ou un gouvernement provincial constitue une seule entité juridique. Un document de recherche de 2005 intitulé « [Legal Issues for the Use of Free and Open Source Software in Government] » (http://www.austlii.edu.au/au/journals/MelbULawRw/2005/13.html) démontre qu'Eben Moglen, avocat général de la Free Software Foundation (FSF), qui encourage habituellement une interprétation forte et étendue de la distribution, considère que les « organismes du gouvernement fédéral peuvent partager des LL sans ‘‘distribution'' ».

Toutefois, la distribution entre des entités juridiques différentes du gouvernement fédéral et d'un gouvernement provincial, ou entre gouvernements provinciaux, constitue presque certainement une « distribution ».

### Avantages

L'une des principales caractéristiques des LL est que n'importe qui peut les distribuer librement. Par conséquent, la plupart des LL peuvent être téléchargées par l'entremise d'Internet sans frais, mais il y a certainement encore des dépenses d'entretien et de gestion. Pour les entreprises qui choisissent d'utiliser des LL, l'absence de droits de licence initiaux constitue un facteur crucial et attrayant pour prendre cette décision. En effet, cette décision peut réduire les dépenses de fonctionnement. Pour le secteur public, le coût est également important. En outre, d'autres avantages publics peuvent inciter le secteur public à utiliser des LL.

Les organisations modernes optent pour les LL pour mettre au point leurs logiciels. Parmi les avantages documentés par rapport aux logiciels mis au point par une poignée de développeurs, il y a la qualité des solutions générées par la diversité des idées et des communautés qui se forment autour d'un défi commun. L'exposition de la problématique à d'autres organisations intéressées apporte également un capital humain supplémentaire pour relever les défis. Par exemple, le système d'exploitation libre Linux est le plus grand projet de développement au monde; des milliers de personnes contribuent à chaque publication. De nombreuses entreprises concurrentes contribuent à Linux et à d'autres LL, ce qui leur permet de tirer parti du travail d'une communauté mondiale de développeurs de LL et de faire passer les développeurs d'un travail de faible valeur à un travail de grande valeur.

L'utilisation des LL permet de personnaliser les produits, fait progresser l'interopérabilité entre les outils grâce à l'utilisation de [normes libres](2_Open_Standards.md) et améliore la qualité globale du produit final. Voici d'autres avantages :

#### Évitement de l'asservissement à un fournisseur

Lorsqu'une application logicielle exclusive est intégrée aux processus ou aux produits d'une organisation ou d'une entreprise, cette organisation devient dépendante de ce fournisseur de logiciels, ou « asservie », pour les nouvelles fonctionnalités, les corrections de bogues et, dans bien des cas, le soutien du produit. Si un fournisseur n'est pas disposé à mettre en oeuvre une nouvelle fonction, il faudra peut-être opter pour une solution de rechange, souvent à un coût considérable. Lorsqu'un fournisseur tarde à fournir des correctifs de bogue ou du soutien, cela peut avoir une incidence négative sur vos propres échéances et peut aussi poser un risque pour la sécurité.

Les LL comportent un avantage en ce sens qu'il crée un marché ouvert pour les fournisseurs de tous les types de soutien. Toute entreprise de soutien ayant des compétences suffisantes en développement de logiciels peut ajouter de nouvelles fonctions et corriger des bogues dans le logiciel. Les utilisateurs de LL peuvent aussi passer à un fournisseur de soutien différent chaque fois qu'une entreprise existante ne répond plus à leurs besoins ou ne respectent plus leurs échéances.

La souplesse de l'utilisation des LL oblige le gouvernement du Canada (GC) à répondre aux besoins des utilisateurs en modifiant ou en créant de nouveaux LL. Les LL sont particulièrement adaptées au prototypage et à l'expérimentation rapides. Le processus de mise à l'essai génère des coûts minimes, et le processus favorise le recensement et l'élimination des défauts non reconnus par l'équipe de développement originale.

#### Soutien de l'économie et des communautés locales

Selon la dynamique de l'industrie du logiciel à un endroit donné, l'utilisation des LL pourrait mieux appuyer les entreprises locales de la région. Étant donné que les LL sont disponibles, distribuables et modifiables, un plus grand nombre de petites entreprises offrant des « services de soutien » peuvent offrir des services commerciaux. Au lieu d'un seul fournisseur qui offre la garantie et le soutien technique, toute entreprise locale de la technologie de l'information (TI) compétente peut fournir ces services. Au lieu d'un seul fournisseur qui est le seul à pouvoir personnaliser les logiciels, une entreprise locale de consultation ou de développement de logiciels peut fournir des versions spécialisées du logiciel. Cette dynamique peut contribuer directement à la croissance économique canadienne.

Le code source accessible au public permet un examen continu et général par les pairs. Qu'il s'agisse simplement de publier le code terminé ou d'ouvrir le processus de développement, la pratique consistant à étendre le processus d'examen et de mise à l'essai à un public plus large au-delà de l'équipe de développement assure une fiabilité et une sécurité accrues des logiciels. Le fait de se développer dans un environnement libre permet aussi à d'autres opinions d'éclairer l'orientation d'un produit afin de maximiser son utilité pour la communauté qu'il dessert.

Le code créé par une administration publique appartient au public. En mettant au point des LL, nous favorisons le développement d'un espace commun plus vaste dans lequel les villes, les états, les entreprises et les individus peuvent mener des activités. Cela crée une véritable valeur économique en réduisant le fardeau du dédoublement des travaux similaires et en permettant au secteur privé de créer de nouvelles entreprises fondées sur le code développé par le gouvernement du Canada ou de s'en inspirer. Les LL sont reconnus mondialement comme un important catalyseur de l'innovation.

#### Coût

Le coût total de propriété de toute application logicielle comprend trois grandes catégories de dépenses : (1) les coûts initiaux d'octroi de licence et de mise en oeuvre; (2) les coûts permanents d'entretien et de soutien; et (3) les coûts de mise à niveau ou de transition des logiciels.

Lorsqu'on utilise des LL, le coût de licence initial est nul (à l'exception des coûts internes d'évaluation du logiciel et d'octroi de licence). Une licence LL est toujours « libre » et accordée au monde entier, en ce sens qu'elle permet à tout le monde d'utiliser le logiciel sans frais exigibles. De plus, en raison du fait que les licences de LL donnent à chacun le droit de redistribuer le logiciel, presque tous les LL peuvent être téléchargés gratuitement par l'entremise d'Internet.

De plus, les coûts d'entretien permanent des LL sont souvent moins élevés. En ce qui concerne les logiciels exclusifs, le fournisseur et ses partenaires d'affaires sont souvent les seules entreprises capables d'offrir le soutien nécessaire (soit parce que la licence du logiciel accorde au fournisseur un contrat de soutien exclusif ou que le fournisseur est le seul à détenir l'expertise spécialisée ou la capacité d'examen ou d'utilisation du code source). Cela peut nuire à un appel d'offres concurrentiel et, dans certains cas, entraîner un mauvais soutien sans solution de rechange. En revanche, les LL permettent à quiconque d'installer, de réparer et d'appuyer autrement le logiciel. Cela favorise un appel d'offres plus concurrentiel pour les services de soutien entre les entreprises. En ce qui concerne les mises à niveau des logiciels, certains fournisseurs exclusifs exigent que les titulaires de licence achètent une nouvelle licence ou paient des frais de mise à niveau pour les nouvelles versions d'un logiciel. En revanche, pour les LL, aucune nouvelle licence n'est nécessaire pour commencer à utiliser la nouvelle version d'un logiciel.

La souplesse des LL permet de réagir rapidement à l'évolution des missions et des marchés, ainsi que de répondre rapidement aux besoins des utilisateurs connus et imprévus. Le fait d'être extensible dans les deux sens entraîne une réduction des risques des répercussions financières à long terme (et des licences potentiellement redondantes). Le soutien et la mise à jour des LL, contrairement aux utilisations plus lourdes des logiciels exclusifs, offrent un avantage réel sur le plan des coûts lorsque de multiples copies de logiciels sont requises ou lorsque le nombre d'utilisateurs augmente. Le coût total de propriété est partagé avec une communauté, et non pas seulement par le gouvernement du Canada.

#### Sécurité

L'un des aspects les plus mal compris du modèle de développement des LL concerne les avantages qu'ils offrent en matière de sécurité. La sécurité des LL repose sur un code véritablement renforcé qui est mis à l'essai par un grand nombre d'examinateurs dans diverses circonstances. Linus Torvalds a simplement fait remarquer que « les belles paroles ne valent rien, mais montrez-moi plutôt le code. »

Lorsque vous utilisez des LL, le code source est publié ouvertement dans son intégralité. Il est donc difficile pour quiconque d'insérer subrepticement un code malveillant. Il permet également aux vérificateurs de la sécurité et aux chercheurs en sécurité d'inspecter le code pour y déceler des lacunes. Bien que la sécurité des logiciels soit une préoccupation pour toutes les entités, elle revêt une importance primordiale pour les gouvernements. Voilà pourquoi les organismes de défense et de sécurité nationale utilisent très souvent des LL. Le document de recherche de 2008 intitulé « [Open Source Technology and Policy] » (http://www.cambridge.org/gb/academic/subjects/computer-science/computing-and-society/open-source-technology-and-policy#reAzLTMdGB0YmGoC.97), donne l'exemple de l'utilisation étendue des LL au sein du département de la Défense des États-Unis et de la National Security Agency et explique les avantages pour la sécurité :
> L'un des principaux facteurs de l'attrait des logiciels libres dans les applications de sécurité (et de sécurité nationale) est leur capacité de vérification. Il est évidemment plus difficile de dissimuler des choses dans du code source libre. Par ailleurs, les gouvernements peuvent avoir des raisons de se méfier du contenu des codes exclusif. Dans le contexte américain, le principal fournisseur exclusif est une société des États-Unis; on peut donc s'attendre du gouvernement qu'il travaille sur les mécanismes de divulgation avec le fournisseur. Il s'agit toutefois d'un scénario moins probable pour les entités détenues à l'étranger. Par exemple, est-ce que Microsoft est susceptible de divulguer un code exclusif au gouvernement vénézuélien parce que ce gouvernement veut examiner les applications Microsoft pour y déceler des pièges ou des lacunes de sécurité?

Par conséquent, lorsqu'un LL est bien élaboré et bien inspecté par des tiers, la sécurité est généralement améliorée. Il existe aussi certains risques pour la sécurité, dont il est question ci-dessous.

##### Recours au durcissement plutôt qu'à l'obscurcissement

Le logiciel libre s'appuie sur de bonnes pratiques de sécurité plutôt que sur l'obscurcissement. On croit souvent à tort que le fait de cacher un code aide à prévenir les attaques réussies. Comme le recommande l'organisme de normalisation du National Institute of Standards and Technology (NIST) : « La sécurité d'un système ne devrait pas dépendre du secret de la mise en oeuvre ou de ses composantes. » Les pratiques de développement des LL reposent sur le durcissement (ou l'amélioration de la sécurité) du code en le mettant à la disposition des pairs pour qu'ils puissent le mettre à l'essai et tentent de le briser, puis en réglant les problèmes relevés.

Les LL ne sont pas toujours plus sûrs, mais, en théorie et en pratique, le modèle de sécurité des LL a démontré qu'ils favorisent une réaction plus rapide aux problèmes de sécurité et facilitent leur correction.

L'obscurcissement repose sur l'ignorance des agresseurs et cache les mauvaises pratiques de sécurité. Dans les cinq mois qui ont suivi la diffusion du code source de la version 6 d'InterBase, une porte dérobée à code fixe rigide qui existait depuis sept ans a été trouvée et réparée par la communauté des LL.

##### Vaste examen par les pairs

Si l'on suppose que l'objectif est de créer des logiciels sûrs, il est évident que la façon la plus facile de trouver des défauts dans un projet est de rendre tout le code du projet complètement transparent. Cette approche peut sembler contre-intuitive, si le but ultime correspond à d'autres choses que l'intégrité de la technologie.

En publiant ouvertement le code d'un projet et en le rendant facilement accessible par l'entremise d'Internet, la communauté des pairs examinateurs s'étend à l'échelle mondiale. La communauté trouvera rapidement des lacunes, et l'équipe de projet pourra prendre des mesures pour les corriger. Cette méthode permet aussi de recueillir les commentaires exceptionnellement étendus et approfondis des promoteurs qui ont besoin que le code soit aussi sûr que possible pour leur propre usage et celui de la communauté. Les propriétaires du projet et la communauté profitent du partage des lacunes et des solutions.

Étant donné que le modèle de sécurité des LL est fondé sur les pratiques exemplaires reconnues par l'industrie et que le code actuel est largement disponible, les projets sont grandement examinés, scrutés minutieusement, améliorés concrètement et durcis rapidement.

Seul un examen ouvert par des pairs peut rendre possibles de bonnes pratiques de sécurité. Voilà la base d'une approche fondée sur des données probantes dans n'importe quel domaine d'études. La technologie n'est pas différente et elle ne devrait pas être traitée comme si les fournisseurs étaient les seuls à détenir la vérité.

Si vous voulez en apprendre davantage sur la sécurité des LL, vous pouvez consulter le document « [UK CESG OSS – Exploring the Risk (PDF)] » (https://www.ncsc.gov.uk/content/files/guidance_files/GPG%2038%20-%20Open%20Source%20Software%20%20-%20issue%201.1%20-%20Oct%2015%20-%20NCSC%20web.pdf) et [la foire aux questions sur les LL du département de la Défense des États-Unis](http://dodcio.defense.gov/Open-Source-Software-FAQ/#OSS_and_Security.2FSoftware_Assurance.2FSystem_Assurance.2FSupply_Chain_Risk_Management).

#### Gains de productivité

L'ouverture des projets de LL et la disponibilité du code source permettent aux professionnels de la technologie de l'information (TI) d'être plus efficaces à bien des égards, par exemple :

- évaluer ou éprouver rapidement une plateforme avec le moins de coûts et de retards administratifs possibles (p. ex., validation de principe);
- interagir facilement avec la communauté (développeurs, utilisateurs) pour poser des questions, suggérer des améliorations et signaler les bogues;
- trouver rapidement de l'information pertinente par de nombreux canaux ouverts (p. ex., documentation, wiki, forum, système de suivi des bogues) et l'améliorer au besoin;
- influencer la feuille de route du projet.

#### Compétences en matière de technologie de l'information (TI)

Un nombre croissant de professionnels de la TI ont des antécédents ou de l'expérience dans le domaine des services opérationnels pour de nombreuses raisons :

- Les LL sont largement utilisés par les entreprises, du développement à la production, ce qui générant une forte demande de compétences.
- Les contributions aux projets de LL permettent de faire partie d'un « réseau de confiance » public et de produire un curriculum vitæ précieux.
- Certains préfèrent travailler avec les LL parce que cela améliore leur satisfaction au travail (voir l'avantage suivant).

Par conséquent, il devient de plus en plus nécessaire de s'ouvrir aux LL pour attirer des personnes talentueuses et des compétences novatrices en matière de TI.

##### Satisfaction au travail

Les LL peuvent aussi accroître la satisfaction des employés qui appuient de telles solutions :

- plus de possibilités d'apprentissage, car ils ont accès à toute la mécanique;
- le sentiment positif qu'ils prennent part à quelque chose de plus important qu'eux-mêmes grâce aux contributions aux LL (corrections de code source, rapports de bogues, mises à jour de la documentation, etc.);
- l'amélioration des compétences en matière de collaboration au fur et à mesure qu'ils s'engagent auprès d'autres développeurs du projet de LL (et qu'ils apprennent des personnes plus expérimentées).

#### Réduction de la responsabilité

Les licences de LL ne créent pas d'obligations sur la simple utilisation de logiciels et elles ne réduisent pas les risques juridiques accrus associés à l'utilisation de solutions exclusives. Le fait de ne pas accepter d'obligations pour la simple utilisation du logiciel fait partie de la définition de logiciel libre de la FSF et de la définition de logiciel à source ouverte de l'Open Source Initiative (OSI). S'il existe une obligation découlant de l'utilisation du logiciel, celui-ci ne peut pas être considéré comme étant un LL.

### Risques et inconvénients

Bien entendu, une entreprise ou un organisme gouvernemental doit trouver un équilibre entre ces avantages et plusieurs inconvénients, comme une mauvaise connaissance des LL par l'utilisateur.

#### Moins de connaissances des utilisateurs

La connaissance que possède l'utilisateur des LL est souvent beaucoup plus faible que celle sur les logiciels exclusifs. Les logiciels exclusifs sont bien implantés dans les écoles (du moins au Canada), et de nombreuses personnes apprennent à utiliser des ordinateurs au moyen de logiciels exclusifs, en raison de leur préinstallation par des fournisseurs de matériel. Voilà pourquoi les LL peuvent exiger plus de formation et de soutien.

#### Sécurité

Étant donné que tout le code source des LL est publié ouvertement, n'importe qui – y compris les « pirates aux mauvaises intentions » – peut examiner le code pour y déceler des failles de sécurité. En particulier, les attaquants malveillants peuvent observer où les LL partagent la même conception, la même base de codes ou la même architecture que le logiciel qui peut avoir des vulnérabilités connues en matière de sécurité. ([source][https://www.igi-global.com/book/handbook-research-open-source-software/494])

Bien sûr, il faut tenir compte de ce désavantage par rapport aux avantages de sécurité mentionnés précédemment. Dans bien des cas, les pirates malveillants peuvent toujours avoir accès au code source des logiciels exclusifs lorsque les ententes de non-divulgation, les procédures éthiques de l'entreprise ou les mécanismes de sécurité des fournisseurs font défaut. Ou ils peuvent démonter le système binaire exclusif et l'analyser pour cerner les défauts potentiels. Attendu que la sécurité des logiciels exclusifs dépend d'une tentative de maintien d'un déséquilibre d'information entre les « bienveillants » (analystes de la sécurité informatique) et les « malveillants » (pirates informatiques mal intentionnés), la sécurité des LL dépend d'un processus concurrentiel ouvert pour trouver et combler les failles de sécurité. Les modèles reposent sur des stratégies différentes, et chaque modèle comporte des risques particuliers qu'une organisation doit évaluer et prendre en considération.

#### Perte de contrôle sur la gestion des logiciels

La facilité et l'option sans frais du téléchargement des LL à partir d'Internet, et de leur installation instantanée, peuvent créer une proposition attrayante pour les employés qui souhaitent contourner les processus d'approvisionnement. Par conséquent, le personnel de la technologie de l'information (TI) peut perdre de vue les logiciels qui fonctionnent sur les postes de travail des employés, ce qui rend plus difficile la gestion de la sécurité des systèmes.

Il en va de même pour les codes sources modifiés ou mélangés sans surveillance adéquate, y compris par l'entremise d'un entrepreneur externe, des risques juridiques peuvent survenir en matière de propriété intellectuelle (droit d'auteur et licence). Il est important de veiller au respect de la Loi sur le droit d'auteur et à ce que ces activités soient intégrées et planifiées dans le cycle de développement de logiciels.

#### Expertise interne

Ceux qui envisagent d'utiliser et de mettre au point des sources libres « internes » doivent veiller à  ce qu'ils aient le bon niveau d'expertise pour la gérer efficacement. Le personnel est habituellement formé à l'utilisation de logiciels exclusifs, de sorte que l'introduction de nouvelles solutions libre peut nécessiter un recyclage.

#### Disponibilité des fournisseurs

Les grands intégrateurs de systèmes peuvent être réticents à proposer des solutions libres qui peuvent générer moins de revenus et ne pas être alignés sur leurs produits ou leurs compétences.

#### Taux de changement

Certains projets de logiciel libre évoluent rapidement avec de courts cycles de publication, ce qui peut exiger plus de travail pour déployer les mises à jour aux utilisateurs. D'un autre côté, certains projets peuvent avoir un taux de changement très lent en raison d'un manque de participation de la communauté (utilisateurs, fournisseurs, etc.). C'est pourquoi il est important d'évaluer soigneusement le niveau d'activité d'une communauté donnée si nous envisageons de nous y fier d'une certaine façon.

### Pratiques exemplaires pour l'utilisation d'un logiciel libre

#### Évaluation et acquisition de logiciels

##### Évaluation des caractéristiques des logiciels

En général, les mêmes facteurs qui s'appliquent à l'évaluation de l'ensemble de caractéristiques et de la maturité du LL s'appliquent également aux LL. Les facteurs suivants méritent d'être pris en considération lors de l'évaluation des LL :

- **communauté** Une forte communauté d'utilisateurs participant à un projet permet aux gens de répondre aux questions, de tester les logiciels, de signaler les bogues, de suggérer des améliorations et de susciter un intérêt général pour les logiciels.
- **Activité de publication** Une forte communauté de développeurs ayant des antécédents de publication et une participation continue tend à démontrer que les correctifs et les améliorations aux logiciels se poursuivront à l'avenir.
- **Longévité** La longévité, mesurée en fonction de l'âge du produit et du nombre de versions publiées, indique la stabilité et les chances de survie d'un projet.
- **Licence** Le logiciel est disponible pour une réutilisation en vertu d'une licence de LL, et le code se trouve dans un dépôt de codes communs. La licence d'un projet peut avoir une incidence sur le niveau de risque juridique que vous devez assumer (voir [Gestion des risques juridiques] [#legal-risk-management]).
- **Disponibilité du soutien** Les considérations de soutien comprennent le soutien aux utilisateurs (c.-à-d. la disponibilité de l'aide pour l'installation et l'utilisation) et la maintenance (c.-à-d. la résolution des problèmes dans le logiciel). Le soutien des LL peut être fourni par la communauté ou les entreprises de services de soutien rémunérés.
- **Documentation** La documentation de l'utilisateur fournit des renseignements importants pour aider les utilisateurs à installer le logiciel et à utiliser ses fonctions.  La documentation technique fournit les exigences et les instructions pour l'installation, le développement, le déploiement et la configuration du logiciel.
- **Sécurité** Bien que le code des LL soit vérifiable, cela ne signifie pas nécessairement qu'il est sécurisé. La qualité du code et le temps de réponse habituel pour corriger les lacunes de sécurité aident à indiquer le niveau de sécurité du logiciel.
- **Fonctionnalité** Les besoins particuliers en matière de fonctionnalité dépendent de l'analyse de rentabilisation du logiciel, et ils doivent être évalués au cas par cas.
- **Intégration** Lorsqu'un logiciel interagit avec d'autres logiciels, ou avec des formats de données particuliers, la compatibilité et la capacité d'intégrer le logiciel et les données ensemble devient une considération primordiale.

Le site Web [OpenHub](https://www.openhub.net/) fournit de nombreuses mesures utiles pour aider à l'évaluation des LL. Par exemple, il énumère les vulnérabilités en matière de sécurité du projet, le nombre de collaborateurs et la fréquence des mises à jour des logiciels.

##### Comparaison des logiciels libres et exclusifs

Lorsqu'il s'agit de prendre des décisions en matière d'acquisition de logiciels, il est pratique courante d'évaluer les LL sur un pied d'égalité avec les logiciels exclusifs (exemples...). À partir d'une liste des exigences opérationnelles, un organisme gouvernemental ou une entreprise peut évaluer dans quelle mesure l'ensemble de fonctions d'un LL correspond aux exigences et calculer le coût global par fonction pendant la durée de vie utile du logiciel.

Ce type d'évaluation constitue un point de départ utile. Cependant, plusieurs personnes interrogées ont fait état d'expériences difficiles dans l'établissement de comparaisons « de pommes à pommes » entre les LL et les logiciels exclusifs. Bien qu'une évaluation du coût total de la propriété soit possible pour les deux, il est difficile de tenir compte de facteurs comme les avantages pour le public (p. ex., l'efficacité économique globale, le soutien aux entreprises locales, etc.).

En plus de cette difficulté, les processus établis d'acquisition de logiciels et d'appel d'offres de services sont parfois adaptés aux solutions exclusives. Les processus ne sont pas toujours assez souples pour évaluer et traiter adéquatement les solutions libres. Par exemple, un processus d'approvisionnement peut d'abord comprendre un appel d'offres pour le contrat de licence initial. Dans ce cas-ci, les entreprises fondées sur des LL ne sont pas susceptibles de soumissionner, car elles n'ont pas de licences à vendre. Lorsque la prochaine étape d'un processus d'approvisionnement consisterait à lancer un appel d'offres pour des services de soutien, les entreprises de soutien basées sur les LL pourraient déjà être écartées. Les fournisseurs de logiciels exclusifs interdisent souvent à quiconque d'assurer l'entretien ou le soutien de leur produit, ce qui empêche les entreprises fondées sur des LL de participer à l'ensemble du processus. ([source][http://www.cbc.ca/news/technology/an-open-door-for-open-source-1.810739])

Par conséquent, bien qu'une comparaison directe entre toutes les solutions possibles – libres et exclusives – soit une pratique utile, il peut également être nécessaire pour les entreprises et les organisations de revoir les procédures et processus existants afin de veiller à ce qu'ils tiennent compte adéquatement des deux catégories de logiciels.

#### Formation et soutien

Selon le contexte, il est prudent d'affecter des ressources appropriées à la formation et à l'aide aux LL. Même si cela n'est peut-être pas nécessaire lorsqu'il s'agit simplement d'installer un nouveau LL sur un serveur (où seul le personnel compétent est susceptible d'interagir avec lui), cet élément est particulièrement important quand il est question des logiciels de bureautique libres. Souvent, les utilisateurs sont plus habitués aux logiciels exclusifs, populaires depuis longtemps, et ils connaissent peut-être peu les LL. Les organisations qui ont opté pour les applications de bureau libres ont tiré plusieurs leçons utiles et pratiques exemplaires de leur décision. ([source] [https://www.igi-global.com/chapter/migration-public-administrations-towards-open/10088])

##### Analyse et préparation

- Étudier et planifier les coûts et les analyses de rentabilisation de la migration
- Réaliser des études pilotes.

##### Migration

- Modérer le rythme de la migration, en évitant une approche de « big bang » (p. ex., favoriser d'abord l'adoption volontaire pour avoir des utilisateurs expérimentés qui peuvent ensuite aider leurs collègues).
- Prévoir une période de transition durant laquelle les utilisateurs ont accès aux logiciels existants et à l'alternative libre.
- Obtenir le soutien de la haute direction.
- Susciter une attitude positive chez les utilisateurs.

##### Formation

- Offre une formation adéquate et se concentrer sur les fonctionnalités générales quotidiennes des logiciels.

##### Soutien

- Donner accès à plusieurs types de soutien, comme les foires aux questions (FAQ) et les guides, l'accès au soutien par téléphone et par courriel, et l'accès à une personne-ressource.

##### Conversion des formats

- Faire un effort significatif afin de veiller à ce que les formats de fichiers et de données des logiciels exclusifs du titulaire puissent être facilement importés et exportés par la solution libre.
- Ne pas oublier que la conversion des documents, par exemple entre Microsoft Office et LibreOffice, est une tâche qui peut exiger beaucoup de ressources humaines pour tous les documents complexes, surtout lorsqu'ils comprennent un formatage précis ou des macros de Microsoft Office.

##### Fonctionnalité

- Les fonctionnalités générales sont souvent équivalentes dans les LL analogues, mais les ensembles de fonctions ne correspondent pas toujours parfaitement, ce qui peut engendrer des problèmes précis pour les utilisateurs.

#### Gestion des risques juridiques

Dans l'ensemble, il est peu probable qu'une licence de LL influe fortement sur la décision d'utiliser ou non des LL. Comme on l'a mentionné précédemment, une simple utilisation de LL déclenche peu d'obligations relatives aux licences. Plus important encore, les obligations réciproques en matière de licence ne s'appliquent pas. Dans ce contexte, seulement trois caractéristiques des licences de LL ont tendance à être très différentes des licences exclusives, et il faut s'y attarder : (1) l'absence de garantie; 2) l'avis de non-responsabilité et d'absence d'indemnisation; et (3) l'absence de clause de compétence législative ou de clause attributive de compétence.

##### Absence de garantie

Une garantie est une assurance donnée par un fournisseur qu'un produit fonctionnera comme promis et sans défaut. Une garantie peut aussi comporter l'assurance qu'un produit est exempt de contraintes juridiques, comme une propriété intellectuelle non autorisée qui peut appartenir à des tiers (c.-à-d. une garantie d'absence de contrefaçon). Selon les modalités de la garantie, lorsqu'un produit ne respecte pas les garanties, le client peut demander que le fournisseur répare le produit, le rembourse ou lui verse une compensation monétaire.

Compte tenu de l'absence typique de garantie dans une licence de LL, il devient plus impératif pour une entreprise ou une organisation gouvernementale d'obtenir des contrats de soutien externe. Une entreprise de services de soutien de LL qui connaît bien les logiciels peut aider à résoudre les problèmes et, surtout, à corriger directement les bogues qui surviennent.

Certaines entreprises de services de soutien contribuent également à atténuer les risques qui peuvent survenir en raison de l'absence d'une garantie d'absence de contrefaçon. Par exemple, Red Hat offre à ses clients le [Red Hat Open Source Assurance Program](https://www.redhat.com/fr/about/open-source-assurance) et Canonical propose l'[Ubuntu Advantage Assurance](https://www.ubuntu.com/legal/ubuntu-advantage/assurance). Ces deux programmes offrent des services de remplacement de toute partie de leurs distributions Linux respectives (Red Hat et Ubuntu) qui porterait atteinte aux droits de propriété intellectuelle d'autres parties. De plus, ces programmes offrent également d'indemniser les clients contre toute poursuite intentée à la suite de telles violations de la propriété intellectuelle.

##### Avis de non-responsabilité et d'absence d'indemnisation

Lorsqu'une licence ou un contrat ne contient pas d'avis, le titulaire de permis peut habituellement tenir le concédant civilement responsable des pertes subies en raison de toute négligence dans la conception, la mise en oeuvre ou la mise à l'essai du logiciel. En outre, quand un concédant accepte de verser une indemnisation au titulaire de la licence, si une autre partie (souvent un client du titulaire de la licence) intente une poursuite en dommages-intérêts et que la cause des dommages peut être associée au logiciel du titulaire de licence original, c'est le titulaire de la licence qui soit en définitive payer les dommages.

Toutefois, compte tenu de l'avis de non-responsabilité et d'absence d'indemnisation dans une licence de LL, les organisations et les entreprises ne peuvent pas transférer au fournisseur leurs risques en matière de responsabilité civile. L'avis de non-responsabilité signifie qu'il est généralement impossible d'obtenir une indemnisation auprès du fournisseur pour les dommages causés par des problèmes liés au logiciel. L'absence d'indemnisation signifie que si d'autres parties subissent des pertes en raison de problèmes liés à l'utilisation du logiciel, vous risquez d'être tenu responsable et vous ne pouvez pas transférer ce risque au fournisseur du logiciel original.

Dans l'ensemble, les clauses d'indemnisation des licences de logiciel exclusif fonctionnent de la même façon que l'assurance, c'est-à-dire qu'elles couvrent les pertes en cas de poursuite intentée par des tiers. Par conséquent, en ce qui concerne les LL, les entreprises et les organisations peuvent envisager l'assurance comme solution de rechange à une clause d'indemnisation. Au lieu que ce soit le fournisseur de logiciels qui contracte une assurance en responsabilité juridique, un assureur fait la même chose.

##### Aucun choix de droit ou d'instance

Il existe une autre différence que les utilisateurs de LL ne devraient pas oublier : les licences de LL comprennent rarement de clause de compétence législative ou de clause attributive de compétence. Les licences exclusives peuvent préciser que les tribunaux doivent interpréter la licence et résoudre les différends en vertu des lois d'un pays ou d'une juridiction en particulier (clause de compétence législative) et que les poursuites doivent être entendues par les tribunaux d'une juridiction en particulier (clause attributive de compétence). Lorsque ces règles ne sont pas précisées dans les licences de LL, les tribunaux appliquent des règles standard sur les conflits de lois pour déterminer la loi appropriée et la compétence pertinente dans un contexte particulier. Cette situation accentue l'incertitude quant à d'éventuelles poursuites nécessaires dans un pays étranger ou en vertu de lois inconnues, ce qui entraînerait des frais juridiques plus élevés.

#### Participation communautaire

Les LL s'appuient sur la collaboration et la participation de la communauté, et ils en dépendent. Il est généralement sensé de tenter de « redonner » à la communauté de qui vous tirer des avantages. Cette réciprocité contribue non seulement à maintenir en vie un projet de LL, mais elle vous aide aussi à établir des liens et de bonnes relations avec les autres membres de la communauté. Cela peut vous aider à obtenir l'aide de la communauté ou à présenter des demandes de caractéristiques. Cette question fait l'objet d'un examen dans un document de recherche de 2005 intitulé « [The Role of Social Capital in Open Source Software Communities] » (https://pdfs.semanticscholar.org/c22c/99099f93e569f4a7e9450f73594d32a8ee4.pdf).

Même sans fournir de code, il y a de nombreuses autres façons de contribuer à un projet de LL. Par exemple, un utilisateur peut envisager une ou plusieurs des activités suivantes :

- **Soumettre des suggestions de logiciels** : Fournir des rapports de bogues et suggérer toute nouvelle fonctionnalité susceptible d'améliorer le logiciel.
- **Améliorer la documentation** : Aider à rédiger de nouveaux guides d'utilisation, à corriger et à améliorer la documentation existante, ou à soumettre des oeuvres d'art telles que des icônes, des arrière-plans et des logos.
- **Aider les autres** : Participer à des forums d'aide et à des listes d'envoi de produits de soutien.
- **Faire des contributions financières** : Surtout si un utilisateur profite du logiciel, celui-ci peut en partager une partie avec la communauté sous forme de dons au projet.
- **Contribuer à l'infrastructure** : Fournir du matériel, offrir du temps sur un serveur ou même aider à maintenir le contenu du portail Web du projet.
- **Promouvoir le logiciel** : Faire profiter les autres des avantages d'un logiciel et rédiger des critiques.

#### Interopérabilité et harmonisation des licences

L'interopérabilité des licences pose rarement des problèmes pour une simple utilisation de LL, à condition qu'il n'y ait pas de distribution du logiciel. Comme on l'a déjà mentionné, en général, les seules obligations en matière de licence que l'on doit accepter et respecter en cas de simple utilisation sont des avis d'exonération de garantie et de non-responsabilité. Même lorsque des logiciels provenant de sources multiples sont modifiés et combinés en vertu de licences multiples, ces avis ne sont jamais susceptibles d'entrer en conflit. Les avis n'imposent qu'une obligation passive, c'est-à-dire qu'ils ne vous obligent pas à prendre une mesure particulière ou à renoncer à une mesure précise. Le titulaire d'une licence n'a qu'à accepter le risque juridique imposé.

Bien que l'interopérabilité des licences ne soit pas une préoccupation pour l'utilisation des LL, le format et l'interopérabilité des données peuvent avoir une incidence sur les décisions d'utiliser ou non les LL. Pour évaluer l'interopérabilité des données, il est important de faire une analyse au cas par cas. Les logiciels exclusifs peuvent toujours mettre en oeuvre des « normes libres » largement interopérables pour les données. De la même façon, les LL peuvent, dans certains cas, utiliser des normes spécialisées non publiées et non libres pour le stockage des données.

Toutefois, les tendances culturelles et la dynamique du modèle opérationnel des LL tendent à pousser les projets de LL vers l'utilisation de l'interopérabilité et des [normes libres](2_Open_Standards.md) pour la lecture, la rédaction et le stockage des données. En effet, même lorsque les LL ne mettent pas en oeuvre une norme libre pour l'échange de données, la disponibilité du code source offre toujours une « mise en oeuvre libre » à tout le moins. Le code source est un exemple que n'importe qui d'autre peut mettre en oeuvre la même fonctionnalité pour lire et écrire le format de données sous-jacent.

## Publication de code source libre

Voir le [code source libre](4_Code_source_libre).

## Logiciels libres préférés

Les critères d'évaluation des LL sont définis ci-dessus dans la section [Évaluation et acquisition des logiciels](#software-evaluation-and-procurement). Les LL préférés doivent également appuyer l'utilisation des [normes libres](2_Open_Standards.md).

Pour tirer le maximum d'avantages économiques et en matière de qualité, il faut utiliser les LL de façon concertée et coordonnée. Le Conseil d'examen de l'architecture intégrée (CEAI) du Secrétariat du Conseil du Trésor (SCT) tiendra à jour une liste des LL préférés en fonction de l'évaluation des solutions par les ministères présents. Cette liste ne doit pas freiner l'innovation ou la mise à l'essai de nouvelles solutions, ce qui peut faciliter l'évolution de la liste. D'un autre côté, elle définit les LL à privilégier et, avec le temps, cernera les LL à abandonner. Elle participe ainsi à la convergence graduelle de l'utilisation des LL et favorise une culture de collaboration entre les ministères et organismes, mais aussi avec les communautés des LL. À ce titre, elle doit être intégrée aux plans stratégiques de gestion de l'information (GI) et de technologie de l'information (TI) des ministères et organismes et prise en compte lors des nouveaux développements, achats, mises à niveau ou migrations.

### Exemples

#### États-Unis

- [Digital Services Playbook](https://playbook.cio.gov/) - Un contrat qui s'assure que les solutions libres sont évaluées lorsque des choix technologiques sont faits et que l'on envisage des solutions de LL à chaque couche de la pile.
- [Politique sur les logiciels libres 18F](https://github.com/18F/open-source-policy/blob/master/policy.md) - Utilisation de LL dans les projets et contribution en retour à la communauté des LL.
- [Foire aux questions sur les LL du département de la Défense](http://dodcio.defense.gov/Open-Source-Softwaree-FAQ/) - Ressources éducatives pour les employés et les entrepreneurs du gouvernement afin de comprendre les politiques et les questions juridiques relatives à l'utilisation des LL au sein du département de la Défense.
- [Mémoire du département de la Défense sur les directives concernant les LL](http://dodcio.defense.gov/Portals/0/Documents/OSSFAQ/2009OSS.pdf) - Il y a eu de mauvaises compréhensions et interprétations des lois, des politiques et des règlements existants qui concernent les logiciels et qui s'appliquent aux LL, qui ont entravé l'utilisation et le développement efficaces des LL au sein du département de la Défense.

#### Royaume-Uni

- [Technology Code of Practice](https://www.gov.uk/government/publications/technology-code-of-practice/technology-code-of-practice) - Ouvrir les choses en accordant la même importance aux LL lorsque vous choisissez la technologie - en tenant compte du coût total de la propriété du service, y compris les coûts de sortie et de transition.

#### France

- La France a une liste de LL recommandée sur son site [Socle interministériel des logiciels libres](http://references.modernisation.gouv.fr/socle-logiciels-libres). Ce site est mis à jour chaque année depuis 2012 et il couvre les LL pour les postes de travail, les serveurs, les bases de données et les environnements de développement.

#### Australie

- [Australian Government Open Source Software Policy](http://www.finance.gov.au/sites/default/files/australian-government-open-source-software-policy-2013.pdf) - Les processus d'approvisionnement doivent tenir compte activement et équitablement de tous les types de logiciels disponibles. Les organismes participeront activement aux activités des communautés de LL et y contribueront au besoin.

#### Canada

Parmi les exemples d'utilisation continue de LL par le gouvernement du Canada (GC), il y a l'infrastructure liée à la météorologie à Environnement Canada, les outils 2.0 du GC mis en oeuvre par le Secrétariat du Conseil du Trésor (SCT) (c.-à-d. GCpédia and GCconnex), le [Portail du gouvernement ouvert](ouvert.canada.ca), et plusieurs autres ministères qui contribuent ouvertement au projet libre de Boîte à outils de l'expérience Web sur GitHub ([source] [http://www.ssc-spc.gc.ca/pages/itir-triti/itir-triti-afac-271115-pres1-fra.html]). Ces éléments sont courants, mais peu de mesure sont prises pour les mettre à jour les politiques, la gouvernance, le financement et les processus du GC afin de veiller à ce que les outils libres soient utilisés au bon endroit et au bon moment. De plus, il est nécessaire de veiller à ce que les LL soient appuyés de façon durable et à ce qu'il y ait une politique et une orientation appropriées pour les employés.

Le présent livre blanc vise à évaluer l'utilisation actuelle des programmes, des activités et des outils de LL par le GC. Il vise également à cerner les lacunes actuelles afin de tracer la voie à suivre pour créer un environnement ouvert plus complet.

- [Ressources naturelles Canada – Free and Open Source Software Licensing Primer](http://ftp.maps.canada.ca/pub/nrcan_rncan/publications/ess_sst/295/295663/cgdi_ip_33_e.pdf)
