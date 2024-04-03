mon application s'appel application MetaDefance c'est une application pour le suivies de tous les condamnées

dans mon application il doit avoir 4 acteurs qui doivent interagir avec l'application
 1 Acteurs c'est l'administrateurs qui doit enregistrer les utilisateurs de la plates forms


2eme utilisateurs c'est le grefié qui se connect sur la plateforme avec son nom et son identifiant ensuite sa le ramene sur le formulaire d'enregistrement du détenue.

3eme utilisateurs c'est le commendemant qui poura se connecter avec son identifiant et poura lanser un alerte de notification push pour la liberation du détenues.

4eme utilisateurs c'est les comissariats qui vont recevoirs les alerte de la liberations des detenues et voir la trassabilité de ses détenues..





-Administrateur général (ADMIN_GENERAL) : Il a des privilèges spécifiques par rapport aux autres administrateurs et est responsable de la gestion globale du système.
-Administrateurs (ADMIN) : Ils gèrent les autres utilisateurs et ont accès à toutes les fonctionnalités du système.
-Greffiers (GREFIE) : Ils sont responsables de l'enregistrement des détenus.
-Commandement (COMMANDEMENT) : Ils ont la capacité de lancer des alertes de libération pour les détenus.
-Commissariats (COMMISSARIAT) : Ils reçoivent des alertes de libération et peuvent~ voir la traçabilité des détenus.


1. *Administrateur général (ADMIN_GENERAL)* :
   - Ce type d'utilisateur a le rôle d'administrateur général dans le système. Il est responsable de la gestion globale du système et possède des privilèges spécifiques par rapport aux autres administrateurs.
   - L'administrateur général peut créer et gérer d'autres administrateurs, ainsi que superviser les activités dans l'ensemble du système.
   - Il est l'entité la plus élevée dans la hiérarchie des utilisateurs et a un accès complet à toutes les fonctionnalités du système.

2. *Administrateur Greffier (ADMIN_GREFIE)* :
   - Les administrateurs Greffiers ont le rôle de gérer les utilisateurs de type Greffier dans le système.
   - Ils peuvent créer, modifier et supprimer des comptes de Greffiers, ainsi que gérer les informations associées à ces comptes.
   - Les administrateurs Greffiers ont également la responsabilité de superviser les activités des Greffiers dans le système.

3. *Administrateur Commandement (ADMIN_COMMANDEMENT)* :
   - Les administrateurs Commandements ont le rôle de gérer les utilisateurs de type Commandement dans le système.
   - Ils peuvent créer, modifier et supprimer des comptes de Commandements, ainsi que gérer les informations associées à ces comptes.
   - Les administrateurs Commandements ont également la responsabilité de superviser les activités des Commandements dans le système.

4. *Greffier (GREFIE)* :
   - Les Greffiers sont chargés de l'enregistrement des détenus dans le système.
   - Ils ont la responsabilité de créer et de gérer les dossiers des détenus, en saisissant des informations telles que le nom, le prénom, le crime, la peine, etc.
   - Les Greffiers ne peuvent modifier que les informations qu'ils ont créées ainsi que celles créées par les utilisateurs de type Greffier qui sont sous leur responsabilité.

5. *Commandement (COMMANDEMENT)* :
   - Les Commandements ont la responsabilité de lancer des alertes de libération pour les détenus.
   - Ils peuvent envoyer des notifications push pour informer les Commissariats de la libération imminente des détenus.
   - Les Commandements ne peuvent modifier que les informations qu'ils ont créées ainsi que celles créées par les utilisateurs de type Commandement qui sont sous leur responsabilité.

6. *Commissariat (COMMISSARIAT)* :
   - Les Commissariats reçoivent des alertes de libération des détenus envoyées par le Commandement.
   - Ils peuvent également consulter la traçabilité des détenus dans le système pour suivre leur historique.
   - Les Commissariats ont un accès limité et ne peuvent pas modifier les informations dans le système.

Chaque type d'utilisateur a des responsabilités spécifiques et des autorisations correspondantes dans le système, ce qui garantit une gestion efficace des activités liées aux détenus.







Fonctionnalités  :
### Intervenants de l'Application

1. *ADMIN_GENERAL*
   - Gestion complète du système.
   - Création, modification et suppression de tous les types d'utilisateurs.
   - Accès total à toutes les fonctionnalités de l'application.
   
2. *ADMIN_GREFIE*
   - Gestion des utilisateurs de type Greffier.
   - Création, modification et suppression des comptes de Greffiers.
   - Supervision des activités des Greffiers.
   
3. *ADMIN_COMMANDEMENT*
   - Gestion des utilisateurs de type Commandement.
   - Création, modification et suppression des comptes de Commandements.
   - Supervision des activités des Commandements.
   
4. *ADMIN_COMMISSARIAT*
   - Gestion des utilisateurs de type Commissariat.
   - Création, modification et suppression des comptes de Commissariats.
   - Supervision des activités des Commissariats.
   
5. *GREFIE*
   - Enregistrement des détenus.
   - Saisie des informations sur les détenus dans le système.
   
6. *COMMANDEMENT*
   - Lancement des alertes de libération pour les détenus.
   - Envoi de notifications aux Commissariats pour les libérations imminentes.
   
7. *COMMISSARIAT*
   - Réception des alertes de libération des détenus.
   - Consultation de la traçabilité des détenus dans le système.

---

Cette présentation détaille les intervenants de l'application ainsi que les fonctionnalités spécifiques auxquelles ils ont accès dans le système de gestion des détenus.