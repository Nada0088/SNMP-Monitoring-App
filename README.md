# SNMP-Monitoring-App

###### Un outil pour superviser, surveiller le réseau et alerter en cas d'anomalie 

Le SNMP (Simple Network Management Protocol) est un protocole de surveillance populaire qui a commencé avec des éléments de réseau mais s'est depuis étendu pour être utilisé dans n'importe quel matériel ou logiciel.
Pour représenter graphiquement les données de performance ou envoyer des alarmes, tous les systèmes de surveillance le prennent en charge immédiatement.
Ce protocole utilise un espace de noms hiérarchique qui contient des identifiants d'objet (OID), qui sont représentés sous la forme d'une liste de nombres (généralement 1.3.6.13.6.1...).
Chaque OID identifie une variable qui peut être lue et/ou écrite à l'aide du protocole et représente une grandeur réelle (par exemple dans un équipement réseau la vitesse négociée par un port ou si ce port est connecté).
Les OID standardisés sont mappés à des noms significatifs à l'aide d'une MIB (Management information base) qui décrit chaque OID.

Ce projet porte sur la conception et la realisation d'un systeme de monitoring et alerting du reseau. Il est livré avec une belle interface utilisateur HMTL5 :
* Tableau de bord qui montre un aperçu des derniers messages
* Affiche les messages envoyés par un hôte spécifique
* Affiche les messages par gravité
* Affiche les messages spécifiques reçus
* Mise à jour en direct des pièges reçus

et plus.

Vous pouvez définir le niveau de gravité pour chaque message reçu, ignorer des types de messages spécifiques, créer des périodes de maintenance
pour les hôtes, définissez des heures de silence par utilisateur et plus encore.


Les notifications sont définies par utilisateur/gravité, par défaut pris en charge sont :
* Notification par e-mail
* Notification SMS

## screenshots

Some sample UI screenshots can be found below:
![Screen1](/css/screenshots/Screen1.png?raw=true "Screen1")
![Screen2](/css/screenshots/Screen2.png?raw=true "Screen2")
![Screen3](/css/screenshots/Screen3.png?raw=true "Screen3")
![Screen4](/css/screenshots/Screen4.png?raw=true "Screen4")


## setup




