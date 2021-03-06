# SNMP-Monitoring-App

###### Un outil pour superviser, surveiller le réseau et alerter en cas d'anomalie 

Le SNMP (Simple Network Management Protocol) est un protocole de surveillance populaire qui a commencé avec des éléments de réseau mais s'est depuis étendu pour être utilisé dans n'importe quel matériel ou logiciel.
Pour représenter graphiquement les données de performance ou envoyer des alarmes, tous les systèmes de surveillance le prennent en charge immédiatement.
Ce protocole utilise un espace de noms hiérarchique qui contient des identifiants d'objet (OID), qui sont représentés sous la forme d'une liste de nombres (généralement 1.3.6.13.6.1...).
Chaque OID identifie une variable qui peut être lue et/ou écrite à l'aide du protocole et représente une grandeur réelle (par exemple dans un équipement réseau la vitesse négociée par un port ou si ce port est connecté).
Les OID standardisés sont mappés à des noms significatifs à l'aide d'une MIB (Management information base) qui décrit chaque OID.

## Surveiller les equipements avec SNMP

Les réseaux d'entreprise sont hétérogènes. En plus des applications à plusieurs niveaux, une partie critique de l'infrastructure se compose de périphériques réseau et d'autres applications spécifiques au fournisseur. Cependant, ces appareils ont normalement un agent (interface) SNMP (Simple Network Management Protocol), ce qui facilite la surveillance SNMP.

SNSM est un outil de surveillance SNMP qui prend en charge la surveillance des périphériques SNMP. Il peut surveiller les agents compatibles SNMP V1, V2c et V3 dans une application compatible SNMP. 

## Outil de surveillance SNMP

Le gestionnaire d'applications prend en charge la surveillance SNMP et permet aux administrateurs de surveiller des applications et des périphériques supplémentaires. Un utilisateur doit uniquement charger un fichier MIB et sélectionner les OID SNMP qui doivent être surveillés. Des tableaux de bord et des vues graphiques par défaut sont créés. Vous pouvez également activer les rapports SNMP pour les OID sélectionnés.

 Il est livré avec une belle interface utilisateur HMTL5 :
* Tableau de bord qui montre un aperçu des derniers messages
* Affiche les messages envoyés par un hôte spécifique
* Affiche les messages par gravité
* Affiche les messages spécifiques reçus
* Mise à jour en direct des pièges reçus

et plus.

Vous pouvez définir le niveau de gravité pour chaque message reçu (définir des seuils afin d'être averti lorsqu'un problème survient), ignorer des types de messages spécifiques, créer des périodes de maintenance pour les hôtes, définissez des heures de silence par utilisateur et plus encore. Les alarmes et notifications instantanées vous aident à prendre des mesures corrective


Les notifications sont définies par utilisateur/gravité, par défaut pris en charge sont :
* Notification par e-mail
* Notification SMS

## screenshots

Vous trouverez ci-dessous quelques exemples de captures d'écran de l'interface utilisateur :

• Interface d’authentification
L’utilisateur saisit ses informations dans les champs indiqués dans la figure suivante.

![image](https://user-images.githubusercontent.com/81916000/139585935-805764a0-dbf9-4cfb-b2da-6483ee7d1efc.png)

• La barre des menus :
Après l’authentification le superviseur pourra choisir parmi ces Menus soit pour consulter
l’état général, l’historique des pannes, choisir un équipement pour consulter ces informations
depuis le menu groupes des équipements qui classe les équipements selon leur type (routeur,
serveur, commutateur), statistiques et la cartographie.

![image](https://user-images.githubusercontent.com/81916000/141693297-9a23335a-a456-4f41-b60e-4098162d1d13.png)

• Menu Administrateur :
Représente le menu à partir duquel l’administrateur peut ajouter des équipements , gérer
les comptes de superviseurs et recevoir les notifications.

![image](https://user-images.githubusercontent.com/81916000/139592503-d2a00930-fdf8-41dd-9492-b66d821a4f15.png)

• Page d’ajouter un équipement :
Lorsque l’administrateur désire ajouter un nouvel équipement à superviser, il sélectionne
l’ajout d’un équipement parmi les choix présentés dans la figure précédente, et saisi les
informations correspondantes, parmi ces informations figurent les éléments nécessaires au
protocole SNMP tel que : l’adresse IP, la communauté, la version SNMP.

![image](https://user-images.githubusercontent.com/81916000/141709304-bc2f6c46-a7af-4a29-a53c-1eee4a8e8eae.png)

• Page statistiques (Tableau de bord)  :
Permet de donner aux superviseurs le droit de consultation les informations du trafic
entrant/sortant et d’autres informations en mode graphique.

![image](https://user-images.githubusercontent.com/81916000/141701492-efcd62fd-219b-4bdb-b99e-9e4dacab7b08.png)

Page historiques des pannes :
Cette page montre les pannes, nous pouvons remarquer trois types de pannes, elles sont
affichées avec l’heure de leur déclenchement. L’administrateur à le droit d’archiver ces pannes.

![image](https://user-images.githubusercontent.com/81916000/141705177-ed8609a1-953f-4166-83d6-32629312330e.png)

 Page équipement :
Quand le superviseur clique sur un IP depuis les IP existants dans la table affiché dans la
figure précédente cette page s’affiche, depuis cette page les superviseurs peuvent Consulter
quelques informations réseau nécessaires et de stockage sur chaque équipement supervisé.

![image](https://user-images.githubusercontent.com/81916000/141709068-064c5f0d-3165-4507-bcc9-8dd534ef48ad.png)


La capacité SNMP du gestionnaire d'applications comprend :

    -Collecte de données à partir de n'importe quelle ressource SNMP
    -Rapports et configuration des seuils sur toutes les données d'objet SNMP (OID) collectées
    -Prise en charge des objets table SNMP et scalaires SNMP
    -Envoyer des interruptions SNMP
    -Traiter les interruptions SNMP




