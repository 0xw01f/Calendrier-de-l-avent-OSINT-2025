# 🎄 Calendrier de l'Avent OSINT 2025

> Une collection sélectionnée d'outils, de techniques et de ressources OSINT révélés chaque jour tout au long du mois de décembre 2025.

## 📖 Aperçu

Bienvenue dans le Calendrier de l'Avent OSINT 2025 ! Ce dépôt présente 24 outils, techniques et ressources de Renseignement en Sources Ouvertes (OSINT) soigneusement sélectionnés, dévoilés un par un du 1er au 24 décembre 2025.

Chaque jour apporte un nouvel éclairage sur le monde de l'OSINT, couvrant tout, de la reconnaissance et la collecte de données aux techniques d'analyse et de visualisation.

## 🎁 Révélations Quotidiennes

Cliquez sur chaque jour pour découvrir l'outil ou la technique :

- **[Jour 1](#jour-1)** - Searx - Moteur de méta-recherche axé sur la vie privée
- **[Jour 2](#jour-2)** - Web-check - Outil d'analyse de site web tout-en-un
- **[Jour 3](#jour-3)** - Sputnik - Extension de navigateur pour l'analyse rapide de sites
- **[Jour 4](#jour-4)** - Host.io - Découverte de relations entre domaines
- **[Jour 5](#jour-5)** - Web Archives - Extension d'archivage web multi-sources
- **[Jour 6](#jour-6)** - Donut Browser - Navigateur multi-profils avec anti-détection
- **[Jour 7](#jour-7)** - Pappers Immobilier - Plateforme de renseignement immobilier
- **[Jour 8](#jour-8)** - ImportYeti - Outil de renseignement sur la chaîne logistique
- **[Jour 9](#jour-9)** - Hunter.io - Découverte d'emails et analyse de modèles
- **[Jour 10](#jour-10)** - Source Code Intelligence - PublicWWW, Grep.app, Sourcegraph
- **[Jour 11](#jour-11)** - Google Dorking - Opérateurs de recherche avancés
- **[Jour 12](#jour-12)** - Ads Intelligence - Bibliothèques publicitaires des plateformes
- **[Jour 13](#jour-13)** - Maritime OSINT - Base de données navale Equasis
- **[Jour 14](#jour-14)** - Énumération de noms d'utilisateur - RhinoUserChecker
- **[Jour 15](#jour-15)** - Portails Open Data - Sources de données gouvernementales
- **[Jour 16](#jour-16)** - Surveillance d'Internet - IODA, OONI, Liveuamap
- **[Jour 17](#jour-17)** - Services de Cartographie Alternatifs - Alternatives régionales à Street View
- **[Jour 18](#jour-18)** - NASA FIRMS - Surveillance thermique par satellite pour l'analyse de conflits
- **[Jour 19](#jour-19)** - Earthkit - Plateforme d'investigation géographique OSINT
- **[Jour 20](#jour-20)** - Smappen - Cartographie isochrone pour l'analyse temporelle
- **[Jour 21](#jour-21)** - Search by Image - Recherche d'image inversée multi-moteurs
- **[Jour 22](#jour-22)** - Cartographie d'Infrastructure - OpenInfraMap, OpenRailwayMap, Wikimapia
- **[Jour 23](#jour-23)** - Tracking de Véhicules - ADS-B Exchange & Global Fishing Watch
- **[Jour 24](#jour-24)** - *À venir le 24 décembre*

---

## 📅 Contenu Détaillé

### Jour 1
**Outil/Technique :** Searx - Moteur de méta-recherche axé sur la vie privée

**Description :** Searx est un méta-moteur de recherche open source qui agrège les résultats de dizaines de moteurs (Google, Bing, Qwant, etc.) tout en protégeant votre vie privée. Contrairement aux moteurs traditionnels, Searx nettoie vos requêtes avant de les envoyer, garantissant des résultats complets sans exposer votre identité ou vos habitudes de recherche.

Pour les enquêtes OSINT, cela élimine le pistage, les bulles de filtrage et les résultats personnalisés qui peuvent biaiser votre analyse. Vous obtenez des résultats bruts et impartiaux provenant de multiples sources sans être profilé ou traqué.

**Fonctionnalités Clés :**
- 🔎 **Agrégation multi-sources** : Cherchez sur plusieurs moteurs simultanément pour des résultats exhaustifs
- 🛡️ **Zéro traçage** : Pas de profilage, pas d'historique de recherche, protection complète de la vie privée
- 🧭 **Résultats impartiaux** : Pas de personnalisation basée sur la localisation ou l'historique - données pures et brutes
- 🔧 **Personnalisable & auto-hébergé** : Open source et configurable selon vos besoins
- 🌍 **Indépendant de la localisation** : Les résultats ne sont pas influencés par votre position géographique

**Ressources :**
- Instances publiques : https://searx.space/
---

### Jour 2
**Outil/Technique :** Web-check - Outil d'analyse de site web tout-en-un

**Description :** Lors du lancement d'une reconnaissance sur un site web, on finit souvent par jongler avec 5 ou 6 onglets ouverts - un pour le Whois, un pour le DNS, un autre pour vérifier le certificat SSL, encore un autre pour la localisation du serveur... C'est chronophage, cela disperse l'attention et on finit par rater des choses.

Web-check est un "couteau suisse" pour l'analyse web. Entrez simplement une URL et il lance une batterie de tests générant un tableau de bord complet. C'est un outil indispensable pour gagner du temps lors de la reconnaissance web.

**Fonctionnalités Clés :**
- 📊 **Tout-en-un** : IP, Chaîne SSL, En-têtes, DNS, Cookies, tout sur une seule page
- ⚡ **Vitesse** : L'analyse prend quelques secondes contre 10 minutes manuellement
- 🔍 **Profondeur** : Détecte souvent des infos techniques oubliées (WAF, technologies serveur, privacy.txt)
- 🖼️ **Visuel** : Idéal pour prendre des captures d'écran rapides et générer des rapports complets
- 🔓 **Open source** : Aucune installation requise pour la version web, mais également disponible en auto-hébergement

**Ressources :**
- Version Web : https://web-check.xyz/
- Dépôt GitHub : https://github.com/Lissy93/web-check
- Note : Fournit une "vision à rayons X" d'un site web sans installer aucun outil

---

### Jour 3
**Outil/Technique :** Sputnik - Extension de navigateur pour l'analyse rapide de sites

**Description :** Sputnik est une extension Chrome/Firefox qui fournit des informations techniques instantanées sur les sites web sans jamais quitter votre navigateur. Lors d'enquêtes sur des sites suspects, devoir copier les URL et basculer vers des outils externes rompt votre flux de travail et fait perdre du temps. Sputnik élimine cette friction en apportant les pivots OSINT essentiels directement dans votre navigateur.

D'un simple clic, vous obtenez les adresses IP, les localisations des serveurs, les informations d'hébergement et des liens directs vers les plateformes d'analyse. Il est conçu pour les enquêteurs qui doivent qualifier des cibles en continu sans briser leur rythme.

**Fonctionnalités Clés :**
- 🖱️ **Accès instantané** : Un clic pour obtenir l'IP, la localisation du serveur et l'hébergeur
- 🔗 **Pivots rapides** : Liens directs vers VirusTotal, Censys, Shodan et autres plateformes OSINT
- 📄 **Analyse de page** : Extrait automatiquement les URL, emails et artefacts de la page actuelle
- 🐛 **Informations de sécurité** : Détecte les technologies utilisées et les CVE associées
- 🎯 **Intégration au menu contextuel** : Clic droit sur n'importe quelle IP, domaine, hash ou URL pour une recherche OSINT instantanée

**Ressources :**
- Dépôt GitHub : https://github.com/mitchmoser/sputnik
- Installation : Disponible pour les navigateurs Chrome/Chromium et Firefox (installer depuis les "Releases" GitHub)

---

### Jour 4
**Outil/Technique :** Host.io - Découverte de relations entre domaines

**Description :** Host.io est un moteur de recherche qui va au-delà des simples requêtes DNS pour cartographier les relations entre les domaines. Lors de l'enquête sur un domaine cible, le Whois est souvent anonymisé (RGPD) et le DNS ne révèle pas tout. Host.io vous aide à comprendre l'écosystème complet autour d'un domaine en analysant les backlinks, les relations de co-hébergement et les redirections.

Au lieu de regarder un site web isolé, vous pouvez découvrir des réseaux entiers de domaines interconnectés - parfait pour démasquer des réseaux de désinformation, des PBN (Private Blog Networks) ou des opérations de fraude organisée.

**Fonctionnalités Clés :**
- 🔗 **Analyse de backlinks** : Voyez quels sites pointent vers votre cible, révélant réseaux et connexions
- 📍 **Découverte de co-hébergement** : Listez tous les domaines hébergés sur la même IP ou le même serveur
- ➡️ **Suivi des redirections** : Suivez la piste pour voir où les utilisateurs sont réellement envoyés
- 🌐 **Cartographie de réseau** : Visualisez les connexions entre les domaines liés
- 🔍 **Renseignement relationnel** : Découvrez des relations cachées entre des sites apparemment sans lien

**Ressources :**
- Site Web : https://host.io/

Cas d'usage : Analyse de réseau, enquête sur la fraude, recherche de domaines

---

### Jour 5
**Outil/Technique :** Web Archives - Extension d'archivage web multi-sources

**Description :** Le principe fondamental de l'OSINT est "Internet n'oublie jamais" (ou presque). Une page 404, un tweet supprimé ou un article discrètement modifié est le quotidien des enquêteurs. Si tout le monde connaît la Wayback Machine (Internet Archive) comme référence, elle n'est pas infaillible. Parfois elle est en panne, parfois les pages sont exclues ou simplement pas crawlées au bon moment. L'extension Web Archives est un outil open source qui permet, d'un simple clic droit sur n'importe quelle page (même morte), d'interroger simultanément toutes les archives web ou une par une.

Cet outil de méta-archivage augmente considérablement vos chances de récupérer des preuves numériques disparues en cherchant sur plusieurs services d'archives au-delà de la seule Wayback Machine.

**Fonctionnalités Clés :**
- 🔄 **Requête multi-sources** : Accédez à Archive.is, Yandex Cache, Memento Time Travel et plus encore simultanément
- 🌍 **Couverture géographique** : Yandex Cache est particulièrement utile pour le contenu d'Europe de l'Est/Russie
- ⚡ **Accès rapide** : Menu contextuel (clic droit) pour des recherches d'archives instantanées
- 📚 **Couverture complète** : Inclut Megalodon, Ghostarchive, Perma.cc et d'autres archives spécialisées
- 🎯 **Redondance** : Si une archive a manqué la page, d'autres l'ont peut-être capturée

**Ressources :**
- Extension Navigateur : https://github.com/dessant/web-archives

---

### Jour 6
**Outil/Technique :** Donut Browser - Navigateur multi-profils avec anti-détection

**Description :** En enquête, surtout sur des dossiers sensibles, utiliser son navigateur personnel (Chrome/Edge connecté à son compte Google) est une erreur critique. Le risque est la "contamination croisée" : les sites cibles peuvent détecter votre empreinte numérique incluant votre IP, vos comptes personnels se mélangent avec vos "sockpuppets" (faux comptes), et les différentes enquêtes ne sont pas isolées entre elles. Il y a un risque réel de fuiter accidentellement votre vraie identité. Il faut cloisonner : chaque enquête ou identité doit vivre dans une bulle isolée.

Donut Browser est conçu spécifiquement pour gérer plusieurs profils isolés. Sa vraie force réside sous le capot : il est basé sur Camoufox, un moteur de navigateur "anti-détection" qui modifie dynamiquement l'empreinte du navigateur pour paraître naturel et aléatoire, contrairement à un simple VPN qui ne change souvent que l'IP.

**Fonctionnalités Clés :**
- 🛡️ **Vrai anonymat** : Déjoue les protections anti-bot (Cloudflare, etc.) bien mieux que le simple mode "Incognito"
- 🎭 **Gestion d'identité** : Basculez entre les profils sans contamination croisée (cookies, stockage local, comptes d'enquête)
- 🔒 **Protection** : Vos recherches ne fuitent pas vers votre identité réelle
- 🌐 **Support Proxy** : Configurez différents proxys par profil pour l'isolation IP (VPN recommandé)
- 🔧 **Aléatisation d'empreinte** : Modification dynamique de l'empreinte navigateur via le moteur Camoufox

**Ressources :**
- Donut Browser : https://donut.surf/
- Moteur Camoufox : https://camoufox.com/
- Note : Actuellement disponible sur Linux & Mac, version Windows à venir
- ⚠️ Important : Donut/Camoufox ne masquent PAS votre adresse IP par défaut - à utiliser avec un VPN ou un proxy

---

### Jour 7
**Outil/Technique :** Pappers Immobilier - Plateforme de renseignement immobilier

**Description :** Savoir à qui appartient un immeuble, un entrepôt ou un terrain vague a longtemps été fastidieux (demandes au cadastre, délais, complexité). Pappers (la référence de la data entreprise) a sorti un outil qui change la donne en croisant ses données avec le cadastre. Pappers Immobilier est une interface cartographique qui permet de visualiser la donnée directement sur le plan cadastral. Concrètement : vous naviguez sur la carte, vous cliquez sur une parcelle et la "magie" opère.

Cet outil transforme la due diligence immobilière d'un processus de plusieurs jours en une tâche de 3 minutes, offrant une vision à rayons X sur la propriété, les transactions financières et les structures d'entreprise.

**Fonctionnalités Clés :**
- 📍 **Vision rayons X** : Voyez immédiatement quels bâtiments ou entreprises sont domiciliés sur une parcelle
- 💰 **Transparence financière** : Accès aux prix de vente immobiliers (DVF), dates de transaction et montants engagés
- 🏢 **Identification des propriétaires** : Remontez aux entreprises propriétaires (SCI, Holdings) en un clic
- 🗺️ **Cartographie interactive** : Interface visuelle cadastrale pour une navigation intuitive
- 🔍 **Données complètes** : Extrêmement complet même en version gratuite (ne couvre pas encore 100% du territoire avec une précision égale)

**Ressources :**
- Carte Interactive : https://immobilier.pappers.fr/
- Base DVF seule : https://app.dvf.etalab.gouv.fr/
- Note : Probablement le meilleur outil en accès libre actuellement pour le renseignement immobilier français

---

### Jour 8
**Outil/Technique :** ImportYeti - Outil de renseignement sur la chaîne logistique

**Description :** Savoir qui est votre cible est une chose. Savoir avec qui elle travaille (et d'où viennent son argent ou sa marchandise) en est une autre. Souvent, les entreprises gardent leurs fournisseurs secrets. Mais il y a une faille : la douane. ImportYeti est une mine d'or qui agrège plus de 70 millions d'enregistrements douaniers (Bills of Lading) concernant les imports vers les États-Unis. Il permet de visualiser graphiquement les relations commerciales entre entreprises.

Cet outil puissant révèle les réseaux cachés de la chaîne d'approvisionnement derrière les marques et les organisations, le rendant inestimable pour la due diligence, l'intelligence économique et le travail d'enquête.

**Fonctionnalités Clés :**
- 📦 **Traçabilité** : Découvrez qui fabrique réellement les produits pour une marque (ex: Apple, Nike ou votre concurrent)
- 🔗 **Cartographie de réseau** : Visualisez tout le réseau de fournisseurs et sous-traitants
- 🕵️ **Due diligence** : Vérifiez si une entreprise travaille avec des entités controversées ou dans des zones à risque
- 📊 **70M+ enregistrements** : Accès à des données massives d'importation douanière américaine
- 💎 **Version gratuite généreuse** : Incroyablement puissant même en version gratuite

**Ressources :**
- Site Web : https://www.importyeti.com/
- Cas d'usage : Analyse de chaîne logistique, veille concurrentielle, recherche de fournisseurs
- Note : Probablement l'outil le plus puissant pour enquêter sur les flux physiques

---

### Jour 9
**Outil/Technique :** Hunter.io - Découverte d'emails et analyse de modèles

**Description :** Quand votre cible est une organisation (un nom de domaine), l'étape suivante est de comprendre qui est derrière. Qui sont les employés ? Quelle est la structure interne ? Et trouver de nouveaux pivots (les emails sont puissants...). Hunter.io est la référence pour cartographier les adresses emails d'un nom de domaine. Il scanne le web public pour identifier les adresses professionnelles associées à une entreprise.

Cet outil essentiel fait le pont entre l'analyse d'une "entité morale" et l'identification des "personnes physiques" qui la composent.

**Fonctionnalités Clés :**
- 🔑 **Détection de modèle** : Analyse les données pour déduire la logique de création d'email (ex: prenom.nom@entreprise.com ou p.nom@...). Une fois connue, vous pouvez reconstruire l'email de n'importe qui, même s'il n'apparaît nulle part.
- 👥 **Recensement des employés** : Liste les emails "visibles" sur le web, aidant à dessiner l'organigramme de l'entreprise (qui est à la compta, qui est à l'IT, etc.)
- 🔗 **Attribution de la source** : Montre où chaque email a été trouvé (page contact, PDF technique, blog) - excellent indice pour comprendre le rôle réel de la personne
- 📧 **Vérification d'email** : Validation intégrée pour vérifier si les emails découverts sont actifs
- 🎯 **Couverture du domaine** : Scan complet à travers les sources web publiques

**Ressources :**
- Site Web : https://hunter.io/
- Outils Alternatifs : Lusha (https://www.lusha.com/), Apollo (https://www.apollo.io/), Kaspr (https://www.kaspr.io/)
- Note : Indispensable pour passer de l'analyse d'entité à l'identification de personnes

---

### Jour 10
**Outil/Technique :** Source Code Intelligence - PublicWWW, Grep.app, Sourcegraph

**Description :** Google indexe ce qui est écrit sur la page. Un enquêteur doit regarder ce qui est écrit derrière. Le code source peut contenir des identifiants de tracking, des commentaires de développeurs ou des liens vers des environnements de test. Les moteurs de recherche traditionnels ne peuvent pas "dorker" le code source efficacement. Pour cette dimension de l'OSINT, vous avez besoin d'outils spécialisés qui fouillent dans le HTML, le JavaScript, le CSS et les dépôts Git.

Ce trio d'outils complémentaires vous permet de chercher dans le code source de millions de sites et de dépôts publics pour trouver des connexions, des configurations et des liens cachés entre les sites.

**Fonctionnalités Clés :**
- 🌐 **PublicWWW** : "Le Google du code source" - indexe le HTML, JS et CSS de millions de sites pour trouver ceux utilisant les mêmes bouts de code
- ⚡ **Grep.app** : Recherche de chaînes exactes à travers plus de 500 000 dépôts Git publics en une fraction de seconde
- 🧠 **Sourcegraph** : Outil de développeur pour la navigation dans le code, véritable mine d'or pour l'OSINT - très similaire à grep.app
- 🔍 **Identifiants de tracking** : Trouvez tous les sites utilisant le même ID Google Analytics (UA-xxxxx) ou d'autres codes de suivi
- 🔗 **Liaison de domaines** : Découvrez des relations entre sites via des signatures de code partagées dans les pieds de page ou en-têtes

**Ressources :**
- PublicWWW : https://publicwww.com/
- Grep.app : https://grep.app/
- Sourcegraph : https://sourcegraph.com/search

---

### Jour 11
**Outil/Technique :** Google Dorking - Opérateurs de recherche avancés

**Description :** La plupart des gens utilisent les moteurs de recherche comme un dictionnaire. Un enquêteur les utilise comme une base de données structurée. Le "Dorking" est l'art d'utiliser des opérateurs de recherche avancés pour filtrer le bruit et trouver l'aiguille dans la botte de foin d'Internet. Le meilleur outil OSINT est votre cerveau - connaître la bonne syntaxe fait toute la différence.

Ne vous limitez pas à Google. Pour une investigation précise, Brave Search, Yandex, Bing, Baidu et d'autres renvoient souvent des résultats complètement différents. DuckDuckGo est souvent meilleur pour respecter les recherches de chaînes exactes et les caractères spéciaux que Google ignore.

**Fonctionnalités Clés :**
- 🎯 **site:** - Force la recherche uniquement sur un domaine spécifique (ex: site:linkedin.com "nom cible")
- 📄 **filetype:** - Cherche uniquement des fichiers spécifiques (pdf, xlsx, docx, pptx) - puissant combiné avec site:
- 🔍 **"phrase exacte"** - Indispensable. Empêche les moteurs de trouver des synonymes ou des approximations
- ➖ **opérateur moins** - Supprime le bruit (ex: jaguar -voiture pour chercher uniquement l'animal)
- 🔄 **Pivot multi-moteurs** : Différents moteurs (Google, Yandex, Bing, DuckDuckGo) renvoient des résultats différents

**Ressources :**
- Google Advanced Search : https://www.google.com/advanced_search
- DuckDuckGo : https://duckduckgo.com/
- Yandex : https://yandex.com/
- Cheat Sheet Dorking : De nombreuses ressources disponibles en ligne
- Note : Pas besoin de logiciel coûteux - juste la bonne syntaxe

---

### Jour 12
**Outil/Technique :** Ads Intelligence - Bibliothèques publicitaires des plateformes

**Description :** Les grandes plateformes sont obligées de rendre leurs publicités accessibles publiquement. Pour un enquêteur, c'est une mine d'or pour analyser la stratégie, le ciblage et l'identité réelle d'une entité. Ces bases de données de transparence vous permettent de voir qui diffuse des pubs, ce qu'ils promeuvent et qui est vraiment derrière une page ou une campagne.

Couvrir tout le spectre nécessite l'accès à plusieurs bibliothèques publicitaires sur différentes plateformes - chacune révèle différents aspects des opérations de marketing numérique et d'influence.

**Fonctionnalités Clés :**
- 📊 **Google Ads Transparency** : Tout sur la publicité Search et YouTube
- 📱 **Meta Ad Library** : La référence pour Facebook et Instagram - idéal pour traquer qui gère vraiment une page ou les opérations de dropshipping
- 💼 **LinkedIn Ad Library** : Essentiel pour l'OSINT Corporate - analyse du ciblage B2B et des campagnes de recrutement agressives
- 🔍 **Microsoft Ad Library (Bing)** : Souvent oublié mais crucial pour trouver le "malvertising" (fausses pubs distribuant des malwares)
- 📹 **TikTok Creative Center** : Analyse des tendances virales, des pubs vidéo et des opérations d'influence ciblant les jeunes
- 🎮 **Reddit Ads Inspiration** : Observez les campagnes ciblant des communautés de niche (Tech, Crypto, Gaming)

**Ressources :**
- Google : https://adstransparency.google.com/
- Meta : https://www.facebook.com/ads/library/
- LinkedIn : https://www.linkedin.com/ad-library/
- Microsoft : https://adlibrary.ads.microsoft.com/
- TikTok : https://library.tiktok.com/
- Reddit : https://ads.reddit.com/inspiration/

---

### Jour 13
**Outil/Technique :** Maritime OSINT - Base de données navale Equasis

**Description :** Pour suivre les navires, tout le monde a le réflexe MarineTraffic ou VesselFinder. Ces outils sont excellents pour la visualisation temps réel. Mais quand vous voulez accéder à l'historique complet ou aux structures de propriété détaillées, vous heurtez souvent un mur payant. Equasis est l'outil de référence - une base de données d'intérêt public (initiative UE et France) axée sur la sécurité et la qualité des navires. Là où les autres vendent de la donnée commerciale, Equasis fournit de la donnée administrative.

Contrairement au tracking AIS qui peut être usurpé, Equasis fournit des détails techniques immuables et des registres d'inspection officiels qui prouvent la présence physique et l'histoire d'un navire.

**Fonctionnalités Clés :**
- 🔗 **Chaîne de propriété** : Retracez l'historique complet - à qui appartenait le navire il y a 5 ans ? Qui était le constructeur ?
- 🔧 **ADN Technique** : Détails immuables (numéro IMO, chantier naval, date de construction) pour reconnaître un navire même repeint ou renommé
- ⚠️ **Sanctions & Détentions** : Liste les inspections de sécurité (Port State Control) - les navires bannis des ports ou fréquemment détenus sont des drapeaux rouges immédiats
- 📍 **Preuve de présence** : Contrairement à l'AIS qui peut être falsifié, une inspection enregistrée dans Equasis prouve physiquement la présence du navire dans un port à une date donnée
- 🌊 **Données administratives gratuites** : Accès aux registres officiels sans paywalls commerciaux

**Ressources :**
- Equasis : https://www.equasis.org/
- Alternative Avion : https://www.planespotters.net/ (outil incroyable pour les avions)

---

### Jour 14
**Outil/Technique :** Énumération de noms d'utilisateur - RhinoUserChecker

**Description :** Réutiliser le même nom d'utilisateur sur plusieurs plateformes est l'erreur d'OpSec la plus courante. C'est le pivot le plus simple pour passer d'un compte anodin à une activité sensible. Si WhatsMyName.app est la référence web connue, elle atteint parfois ses limites en termes de faux positifs ou de couverture. Des outils comme RhinoUserChecker par l'équipe Oscar Zulu Osint offrent une approche "revisitée" souvent plus performante.

C'est l'outil pivot par excellence pour élargir votre surface d'attaque - découvrir les "autres vies" d'une cible en trouvant où elle a réutilisé ses pseudos sur Internet.

**Fonctionnalités Clés :**
- 🛡️ **Contournement de limite de taux** : Détecte les blocages potentiels et fournit des liens directs pour vérification manuelle si l'automatisation échoue
- 🎨 **UX Moderne** : Interface plus moderne et lisible que les outils OSINT austères typiques - facilite la visualisation rapide des résultats positifs
- 🔄 **Suite unifiée** : Pas limité aux noms d'utilisateur - c'est un hub centralisant d'autres outils d'investigation (métadonnées, geoint) pour un pivot fluide
- 🔍 **Réduction des faux positifs** : Meilleure gestion des cas particuliers et des spécificités des plateformes
- 🕵️ **Découverte multi-plateformes** : Un utilisateur peut être prudent sur LinkedIn mais réutiliser son pseudo historique sur un forum douteux ou un site de rencontre

**Ressources :**
- RhinoUserChecker : https://github.com/degun-osint/RhinoUserChecker
- Hub OSINT Is Not A Crime : https://osintisnotacrime.com/ (avec d'autres outils intéressants à tester)
- Alternative : WhatsMyName.app pour comparaison
- Note : Essentiel pour découvrir des identités alternatives et élargir le périmètre d'enquête

---

### Jour 15
**Outil/Technique :** Portails Open Data - Sources de données gouvernementales

**Description :** En OSINT, remonter à la source primaire est essentiel pour garantir la fiabilité de l'information. Plutôt que de dépendre d'agrégateurs tiers, il est possible d'exploiter directement les données brutes mises à disposition par les États. Ces portails sont particulièrement utiles pour les développeurs voulant automatiser des recherches via API.

Ces portails gouvernementaux officiels fournissent la "matière première" de l'enquête - des données légales, non altérées, souvent disponibles via des API gratuites pour le traitement de masse.

**Fonctionnalités Clés :**
- 🇫🇷 **France (data.gouv.fr)** : Base SIRENE (entreprises), DVF (valeurs foncières), Répertoire National des Associations
- 🇬🇧 **Royaume-Uni (data.gov.uk)** : Accès direct aux données du gouvernement UK, intégration Companies House, transparence des dépenses publiques
- 🇪🇺 **UE (data.europa.eu)** : Point d'entrée des données institutionnelles de l'UE, registre TED (marchés publics à travers l'Europe)
- 🇺🇸 **USA (data.gov)** : Jeux de données fédéraux massifs, contrats fédéraux, FARA (registre d'influence étrangère)
- 🇷🇺 **Russie (data.gov.ru)** : Données administratives russes, marchés publics, statistiques fédérales (peut nécessiter un VPN)

**Ressources :**
- France : https://www.data.gouv.fr/
- Royaume-Uni : https://www.data.gov.uk/
- Union Européenne : https://data.europa.eu/
- États-Unis : https://www.data.gov/
- Russie : https://data.gov.ru/
- Exemple d'Application : Taipower Poles (utilise l'Open Data de Taïwan pour géolocaliser les poteaux électriques) - https://0d.lv/toolbox/taipower 

---

### Jour 16
**Outil/Technique :** Surveillance d'Internet - IODA, OONI, Liveuamap

**Description :** En géopolitique, observer l'état du réseau internet est un indicateur précieux. Une chute du trafic ou un blocage (comme ceux orchestrés par Roskomnadzor en Russie) peut signaler une crise imminente. Cependant, interpréter ces signaux demande une grande prudence : une panne technique, une surcharge ou une coupure de courant peut ressembler à s'y méprendre à un blocage volontaire.

Pour formuler une hypothèse solide, il faut trianguler les sources. Le but n'est pas de conclure immédiatement, mais de créer une "hypothèse stratégique". Par exemple, si IODA montre une coupure brutale à l'heure exacte où Liveuamap signale des émeutes, la corrélation est forte, mais ne devient preuve qu'après vérification.

**Fonctionnalités Clés :**
- 📊 **IODA (Internet Outage Detection)** : Surveille le trafic mondial pour détecter si une région est déconnectée, mais pas pourquoi - détecte l'anomalie technique sans distinguer censure étatique de la panne d'infra
- 🔒 **OONI Explorer** : Utilise des sondes locales pour tester le blocage spécifique de sites ou d'applis (WhatsApp, Telegram) - révèle la censure ciblée
- 🗺️ **Liveuamap** : Agrégateur cartographique d'incidents (conflits, manifestations) basé sur l'OSINT - montre si l'anomalie réseau coïncide avec des événements au sol
- ⚠️ **Triangulation requise** : Croisez les trois sources pour distinguer les problèmes techniques de la censure délibérée
- 🔍 **Le contexte est clé** : Corrélez avec les médias locaux, l'imagerie satellite et d'autres sources avant de tirer des conclusions

**Ressources :**
- IODA : https://ioda.inetintel.cc.gatech.edu/
- OONI Explorer : https://explorer.ooni.org/
- Liveuamap : https://liveuamap.com/
- Note : Le silence numérique peut signaler une crise - mais vérifiez avant de conclure

---

### Jour 17
**Outil/Technique :** Services de Cartographie Alternatifs - Alternatives régionales à Street View

**Description :** Google Maps ne voit pas tout. Si Street View est omniprésent en Occident, il est lacunaire voire inutile dans de vastes zones du monde. Pour un enquêteur, utiliser les services de cartographie locaux n'est pas une option - c'est une nécessité pour obtenir des images récentes, des plans intérieurs ou simplement une couverture là où Google est absent.

Chaque géant technologique cartographie son propre territoire mieux que les concurrents étrangers. Adapter votre outil cartographique à la zone géographique que vous investiguez améliore drastiquement la qualité des données et la couverture.

**Fonctionnalités Clés :**
- 🇫🇷 **Panoramax (France)** : Le "Wikipédia de la Street View" soutenu par l'IGN/État - contributif avec des mises à jour récentes, sans traçage publicitaire
- 🇷🇺 **Yandex Maps & 2GIS (Russie/CEI/Turquie)** : Meilleure résolution que Google en Europe de l'Est ; 2GIS cartographie l'intérieur des bâtiments, les plans d'étage et l'emplacement exact des entrées
- 🇨🇳 **Baidu Maps (Chine)** : Essentiel là où Google est quasi vide - couverture exhaustive des mégalopoles chinoises avec Baidu Total View ; notez l'obfuscation des coordonnées GCJ-02
- 🇰🇷 **Naver Map & Kakao Map (Corée du Sud)** : La Corée restreint l'export de données cartographiques pour sécurité - Google y est dégradé ; Street View ultra-HD avec vues aériennes récentes et données précises sur les commerces
- 🗺️ **Adaptation géographique** : Chaque région nécessite son outil cartographique spécifique pour une couverture OSINT optimale

**Ressources :**
- Panoramax (France) : https://panoramax.fr/
- Mapillary : https://www.mapillary.com/app/
- Yandex Maps : https://yandex.com/maps/
- 2GIS : https://2gis.ru/
- Baidu Maps : https://map.baidu.com/
- Naver Map : https://map.naver.com/
- Kakao Map : https://map.kakao.com/
- Note : Intérêt opérationnel - adaptez votre outil à votre zone géographique d'enquête

---

### Jour 18
**Outil/Technique :** NASA FIRMS - Surveillance thermique par satellite pour l'analyse de conflits

**Description :** Les caméras optiques ne voient rien la nuit ou à travers la fumée. Les capteurs thermiques, si. NASA FIRMS est un outil conçu à l'origine pour surveiller les feux de forêt, mais il est devenu indispensable pour détecter les explosions, les tirs d'artillerie ou les activités industrielles en temps quasi réel.

Le principe est simple : Si vous voyez une anomalie thermique (chaleur intense) au milieu de la nuit dans un champ en Ukraine ou à Gaza, ce n'est probablement pas un barbecue (ou alors il a mal tourné). C'est potentiellement une frappe, un véhicule en feu, peut-être une usine.

**Fonctionnalités Clés :**
- 🛰️ **Détection thermique** : Le capteur VIIRS avec une résolution de 375 mètres détecte des sources de chaleur invisibles aux caméras optiques
- ⏱️ **Quasi temps réel** : Latence d'environ 3-4 heures - pas du vrai direct, mais proche
- 🔍 **Méthodologie de recoupement** : Essentiel pour confirmer les événements en corrélant plusieurs sources
  - **OpenInfraMap** : Vérifiez s'il y a une centrale ou une raffinerie sous le point rouge (source de chaleur normale ?)
  - **Réseaux Sociaux (X, Telegram)** : Cherchez le nom de la localité + "explosion" ou "bruit" - les locaux en parlent-ils ?
  - **Imagerie Satellite (Maxar, Planet, Sentinel)** : Confirmez visuellement l'impact, la fumée ou les bâtiments détruits
- ⚠️ **Prudence d'interprétation** : FIRMS est une alerte, jamais une preuve immédiate - les usines et raffineries apparaissent aussi en rouge
- 📍 **Limites de précision** : La résolution de 375m signifie que vous localisez une zone, pas un bâtiment précis
- 🌙 **Vision nocturne** : Fonctionne 24/7 quelles que soient la lumière ou les conditions météo (sauf couverture nuageuse dense)

**Ressources :**
- NASA FIRMS : https://firms.modaps.eosdis.nasa.gov/map/
- OpenInfraMap (pour recouper) : https://openinframap.org/
- Cas d'usage : Surveillance de conflits, suivi d'activité industrielle, détection de feux
- Note : Recoupez toujours avec d'autres sources avant de tirer des conclusions sur les anomalies thermiques

---

### Jour 19
**Outil/Technique :** Earthkit - Plateforme d'investigation géographique OSINT

**Description :** On jongle souvent entre la collecte de données, la visualisation cartographique et la vérification visuelle. Earthkit est une plateforme open source qui consolide ces étapes dans un flux de travail unifié pour l'investigation géographique.

Le flux traditionnel est fragmenté : D'abord, vous extrayez des données d'Overpass Turbo (le moteur de recherche technique d'OpenStreetMap) qui renvoie des listes brutes de 1000+ points. Ensuite, vous copiez-collez manuellement les coordonnées dans Google Maps pour vérifier chacune. Ce processus est fastidieux. Earthkit comble ce fossé en combinant collecte, filtrage et vérification visuelle dans une seule interface.

**Fonctionnalités Clés :**
- 🗺️ **Intégration Overpass Turbo** : Interrogez OpenStreetMap pour des objets (ex: "tous les cinémas à 300m d'un McDonald's" ou "toutes les bouches d'incendie à Paris")
- 🔍 **Tri visuel (Sift)** : Importez les données Overpass pour un tri visuel accéléré - chaque coordonnée charge la vue Satellite, Street View et la carte simultanément
- ⚡ **Interface unifiée** : Plus de copier-coller dans Google Maps ou de changement d'onglets - faites défiler les résultats et qualifiez l'info (Pertinent/Faux positif) en quelques secondes
- 🤖 **Requêtes assistées par IA** : Vous ne savez pas coder en Overpass QL ? Demandez à l'IA intégrée en langage naturel : "Trouve-moi les centrales électriques près d'une rivière" et elle écrit la requête
- 📊 **Le pont parfait** : Combine la collecte de données de masse (Overpass) avec l'analyse de précision (vérification visuelle)

**Ressources :**
- App Earthkit : https://earthkit.app/
- Code Source : https://github.com/JettChenT/earthkit
- Overpass Turbo : https://overpass-turbo.eu/
- Note : Plateforme open source qui fluidifie le workflow d'investigation géographique

---

### Jour 20
**Outil/Technique :** Smappen - Cartographie isochrone pour l'analyse temporelle

**Description :** En enquête, la distance "à vol d'oiseau" est souvent trompeuse. Savoir qu'un suspect est à "5 km" d'un lieu ne veut rien dire s'il y a une rivière sans pont ou des embouteillages monstres. Ce qui compte n'est pas la distance, c'est le temps d'accès.

Smappen est un outil cartographique conçu à l'origine pour le marketing (zones de chalandise) mais détourné par les enquêteurs pour générer des isochrones - des zones atteignables dans un temps donné selon différents modes de transport.

**Fonctionnalités Clés :**
- ✅ **Vérification de cohérence** : Une cible prétend avoir quitté son bureau à 18h00 et être arrivée chez elle à 18h15. Tracez la zone de conduite de 15 minutes depuis le bureau. Si le domicile est hors de cette zone "tache d'huile", l'histoire est techniquement impossible.
- 🎯 **Triangulation par intersection** : Très puissant pour localiser une résidence ou une planque. Si vous savez que la cible vit à 10 min à pied d'une gare précise ET à 15 min en voiture d'un certain club de sport, tracez les deux zones et trouvez leur intersection - réduisant la zone de recherche d'une ville entière à quelques pâtés de maisons.
- 📍 **Profilage géographique** : Définissez des zones de recherche prioritaires autour d'un point, en distinguant ce qui est accessible à pied, à vélo ou en voiture
- 🗺️ **Zones de mobilité réalistes** : Passez du rayon théorique (cercle parfait, souvent faux) aux zones de mobilité réalistes (formes complexes basées sur les routes réelles)
- ⏱️ **Analyse temporelle** : Prend en compte les contraintes réelles comme le trafic, le réseau routier et le mode de transport

**Ressources :**
- Smappen : https://www.smappen.com/
- Cas d'usage : Vérification de chronologie, triangulation de résidence, profilage géographique
- Note : Essentiel pour réduire drastiquement les zones de recherche en se basant sur des temps de trajet réalistes

---

### Jour 21
**Outil/Technique :** Search by Image - Recherche d'image inversée multi-moteurs

**Description :** Se limiter à Google pour la recherche d'image inversée est souvent insuffisant. Chaque moteur a ses forces - Yandex excelle pour les visages et le texte cyrillique, Bing performe bien sur les produits et le contenu occidental, Baidu domine pour l'imagerie chinoise. Mais tester manuellement chaque moteur est fastidieux et chronophage.

Search by Image est une extension de navigateur open source qui automatise les recherches d'images inversées multi-moteurs, éliminant le besoin d'uploader manuellement la même image sur plusieurs plateformes.

**Fonctionnalités Clés :**
- 🚀 **Recherche multi-moteurs simultanée** : Lancez les recherches sur tous les moteurs choisis en une fois (Google, Bing, Yandex, Baidu, TinEye, et plus)
- ⚡ **Opération en un clic** : Clic droit sur n'importe quelle image et recherche à travers plusieurs moteurs - fini d'ouvrir 5 onglets manuellement
- 🌐 **Diversité des moteurs** : Chaque moteur indexe différentes parties du web - maximisez la couverture en les interrogeant tous simultanément
- 🎯 **Recherches ciblées** : Option de chercher sur des moteurs spécifiques individuellement pour une investigation focalisée
- 🔓 **Open source** : Code transparent, maintenu par la communauté, gratuit

**Ressources :**
- Dépôt GitHub : https://github.com/dessant/search-by-image
- Extensions Navigateur : Disponible pour Chrome, Firefox, Edge et autres navigateurs basés sur Chromium
- Moteurs supportés : Google, Bing, Yandex, Baidu, TinEye et beaucoup d'autres
- Note : Outil essentiel pour des enquêtes exhaustives par image inversée

---

### Jour 22
**Outil/Technique :** Cartographie d'Infrastructure - OpenInfraMap, OpenRailwayMap, Wikimapia

**Description :** Les cartes grand public se concentrent sur les routes et les lieux commerciaux. Pour un analyste, évaluer les capacités logistiques ou industrielles d'une zone nécessite des données spécialisées. Les services de cartographie classiques ne montrent pas les réseaux électriques, les spécifications ferroviaires ou les détails des installations industrielles.

Ce trio de cartes spécialisées vous permet de visualiser les réseaux d'infrastructure technique invisibles sur Google Maps mais cruciaux pour la géolocalisation, l'analyse logistique et le renseignement industriel.

**Fonctionnalités Clés :**
- ⚡ **OpenInfraMap (Réseau Électrique)** : Visualise les lignes haute tension, les transformateurs et l'infrastructure télécom basée sur OpenStreetMap. Crucial pour la géolocalisation - filtrez par voltage pour correspondre aux types de pylônes visibles sur les photos, réduisant drastiquement les zones de recherche aux seules lignes correspondantes.
- 🚂 **OpenRailwayMap (Réseau Ferroviaire)** : Détaille l'infrastructure ferroviaire mondiale incluant vitesse maximale, type d'électrification, écartement des rails et voies de service. Essentiel pour l'analyse logistique - évaluez si une ligne peut supporter du fret lourd ou identifiez les routes d'approvisionnement industriel.
- 🏭 **Wikimapia (Identification de Sites)** : Carte collaborative où les utilisateurs annotent bâtiments et zones industrielles directement sur l'imagerie satellite. Identifie les installations non répertoriées - là où Google Maps montre une zone grise sans nom, Wikimapia indique souvent la fonction précise (ex: "Usine chimique", "Dépôt militaire", "Centre pénitentiaire") grâce aux connaissances locales.
- 🔍 **Couches de données spécialisées** : Superposez des couches techniques (énergie, transport, industrie) sur la géographie physique pour comprendre comment un territoire fonctionne réellement
- 🎯 **Précision de géolocalisation** : Utilisez les signatures d'infrastructure pour restreindre les zones de recherche lors de l'investigation sur photos ou vidéos

**Ressources :**
- OpenInfraMap : https://openinframap.org/
- OpenRailwayMap : https://www.openrailwaymap.org/
- Wikimapia : https://wikimapia.org/
- Note : Loin d'être exhaustif - superposez les couches de données techniques pour comprendre le fonctionnement réel du territoire

---

### Jour 23
**Outil/Technique :** Tracking de Véhicules - ADS-B Exchange & Global Fishing Watch

**Description :** La plupart des sites de tracking (MarineTraffic, FlightRadar24) restreignent l'accès aux données intéressantes (historique, militaire) derrière des paywalls coûteux ou de la censure. Voici un duo d'outils gratuits pour contourner ces limitations et accéder à la "vérité terrain" sans contrainte budgétaire.

Ces outils cassent le modèle "Freemium" en fournissant un accès aux données non censurées et aux historiques que les plateformes commerciales cachent derrière des abonnements, permettant aux enquêteurs de suivre les mouvements militaires et de détecter les activités maritimes suspectes.

**Fonctionnalités Clés :**
- ✈️ **ADS-B Exchange (Air)** : Le seul tracker aérien majeur qui refuse de filtrer les données à la demande des propriétaires. Contrairement à ses concurrents, il affiche les jets privés d'oligarques, la police et les avions militaires. Si ça émet, ça s'affiche. Cliquez sur le bouton "U" en haut de la carte pour ne montrer que le trafic "Militaire et Intéressant".
- 🚢 **Global Fishing Watch (Mer)** : Ne vous fiez pas à son nom - cet outil écologique ingère les signaux AIS de tous les navires (Tankers, Cargos, Pêche). Offre un historique gratuit sur plusieurs années là où les autres font payer tout ce qui dépasse 24 heures.
- 🔍 **Tracking non censuré** : Accès aux vols militaires, jets privés et mouvements de navires que les plateformes commerciales censurent
- 📊 **Données historiques gratuites** : Historique de suivi sur plusieurs années sans abonnement premium
- 🎯 **Détection de transbordement** : GFW détecte automatiquement les "Rencontres" - quand deux navires restent ensemble en mer, indiquant de potentiels transferts illicites (pétrole sous embargo, ravitaillement) que les trafiquants tentent de cacher
- 💰 **Budget zéro** : Fonctionnalités complètes sans licences d'entreprise coûteuses

**Ressources :**
- ADS-B Exchange : https://globe.adsbexchange.com/
- Global Fishing Watch : https://globalfishingwatch.org/map
- Cas d'usage : Suivi de vols militaires, renseignement maritime, détection d'activité illicite
- Note : Ces outils fournissent la "vérité terrain" (vrais mouvements militaires, rencontres suspectes en mer) avec capacité de remonter le temps, sans budget requis

---

### Jour 24
**Outil/Technique :** Le Pack de Démarrage (Formation & Communauté)

**Description :** Le meilleur outil, c'est vous.

Pendant 23 jours, nous avons vu des outils spécifiques avec quelques techniques. Mais l'OSINT est un muscle : il faut l'entraîner et savoir où chercher quand on est bloqué.

Je tiens encore à remercier Florian P et tous ceux qui m'ont aidé pour réaliser ce calendrier de l'avent :)

Pour ce 24 décembre, voici votre "Pack de Démarrage" : les ressources pour vous équiper, vous former et ne pas rester seul.

**Ressources Essentielles :**

📚 **1. L'Encyclopédie**
Si vous ne devez garder qu'un seul favori, c'est celui-ci. Probablement la collection la plus connue du milieu. Elle répertorie de nombreux outils classés par catégorie (Pseudo, Maps, Email, Transport...).
🔗 **The Ultimate OSINT Collection :** https://start.me/p/DPYPMz/the-ultimate-osint-collection

🎓 **2. La Formation**
Pour partir sur des bases saines, rien ne vaut un cours structuré. L'association OSINT FR a créé un parcours d'initiation gratuit et complet, idéal pour acquérir la méthodologie avant de se lancer.
🔗 **MOOC OSINT FR :** https://mooc.osintfr.com/course/view.php?id=4

🎮 **3. La Pratique**
Ne restez pas passifs. Ces plateformes de CTF (Capture The Flag) proposent des défis concrets (géolocalisation, imagerie, recherche de personnes). C'est le meilleur moyen d'apprendre par l'erreur.
- **GeoDetective** : https://geodetective.io/
- **Challenge OSINT FR** : https://ctf.challenge-osint.fr/
- **Osintopia** : https://challenges.osintopia.fr/
- **Bellingcat** : https://challenge.bellingcat.com/
- **OSINT4Fun** : https://fr.osint4fun.eu/challenges/

🤝 **4. La Communauté**
L'OSINT est une discipline solitaire qui se gagne en équipe. La communauté francophone est incroyablement active et bienveillante. Rejoignez ces serveurs pour poser des questions ou participer à des événements.
- **OSINT FR** : https://discord.com/invite/dWY9sWFKYD
- **Projet Fox** : https://discord.com/invite/projet-fox-775480337727225879
- **Oscar Zulu** : https://discord.com/invite/oscar-zulu
- **Hack'Olyte** : https://discord.com/invite/dbNcPStqb7

---

**Le mot de la fin :**
Merci d'avoir suivi ce calendrier. Maintenant, fermez les tutos, ouvrez les cartes, et commencez à enquêter.

**Joyeuses fêtes à tous ! 🎄🕵️‍♂️**
