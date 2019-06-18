## Auteur :

# Contexte :
Dans le cadre de mes études a l'EEMI (Licence Chef de Projet Digital) j'ai l'occasion de partager avec vous un dictatiel sur l'élaboration d'une documentation serveur. Nous reprendrons donc les notions basiques en rapport avec l'infrastructure IT(7(8) Couches réseaux).

**A noter que pour simplifier la compréhension de tous, nous prendrons un serveur inexistant pour exemple tout en respectant les standards de nommage ISO**

# Sommaire :

1. Introduction
2. Quesqu'un Serveur ?
3. Les notions clef
* Le réseau local 
* Le réseau externe
* Le serveur
* Les terminaux & API
4. Les Facteurs clefs
* Le réseaux local
* Le serveur
5. Les problématiques
* Le réseau externe
* Les terminaux & API
6. FAQ
7. Outils recommandés
8. Standard
9. Conclusion
10. Bibliographie

# 1 Introduction
Le serveur comme tout code informatique nécessite un entretien ainsi qu'une documentation afin de ne pas compromettre la transmission de savoir. Cela peut être problématique pour la croissance/maintien/survie d'une entreprise, c'est pourquoi il est nécessaire d'avoir une documentation complète afin d'être dans la possibilité d'améliorer l'infrastructure dans le cadre d'une politique SI.
# 2 Le Saint Grâle : Le serveur
Définition : Le serveur est un code informatique permettant la communication entre un client, serveur, WOT. Il respecte un protocole de communication.

Le schéma des 7 couches réseaux :

Avis : Le schéma et la notion de 7 couches réseaux n'est plus trop d'actualité en effet nous voyons de plus en plus une 8 ème voir parfois une 9 ème couche dans les infrastructure complète notamment celles des GAFAM.

Préconisation : Le serveur est l'élément clef dans toutes les infrastructures IT. C'est pourquoi il est important de le protéger.

Hypothèse : nous connaissons les caractéristiques clefs d'un serveur :
1. Les ports 
2. Le maintien des services
3. Les performances

Nous devons donc élaborer une documentation qui met en avant ces aspects la tout en les gardant accessible uniquement à l'utilisateur autorisés.

Nous devons donc élaborer une documentation qui met en avant ces aspects la tout en les gardant accessible uniquement à l'utilisateur autorisé.

## 3.1 Le réseau local 
Définition : Le réseaux local est représenté par les dispositifs matériel permettant la connexion entre le serveur et Internet. 

C'est avec le port une des premières portes d'entrée sur le serveur. En effet en observant un réseau local, il est facilement possible d'observer les requêtes du serveur.

C'est pourquoi il est également essentiel de documenter cet notion afin d'avoir les informations nécessaires en cas de crise majeur mais également cela donne la possibilité a l'équipe infra de faire évoluer le réseau local existant. (je pense notamment à la mise en place d'une DMZ)
## 3.2 Le réseau externe
Définition : Le réseaux externe est caractérisé par les connexions entrantes sur le serveur.

Il est essentiel de caractériser ce que vous représentez comme réseaux externe en effet, il est important de définir le périmètre d'accès à votre serveur. En effet les connexion externes peuvent être restreinte via les adresse MAC des machines.

## 3.3 Le serveur

## 3.4 Les terminaux & API
Définition
## 4.1 Facteurs clef 1
## 4.2 Facteurs clef 2
## 5.1 Problématique 1
## 5.2 Problématique 2
# 6 FAQ
# 7 Outils recommandés
# 8 Standard
# 9 Conclusion
# 10 Bibliographie
