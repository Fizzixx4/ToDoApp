# ToDoApp
Application de gestion de projet collaboratif
Un application avec un système de session utilisateur qui permet de créer des projets et de consulter le statut des tâches qui y sont rattachées.
# Pré-requis
1) Créer une base de donnée dans PhpMyAdmin se nommant projetmcd
2) Importer la base de donnée qui se trouve dans DB (le fichier projetmcd.sql)
3) Dans PhpMyAdmin, crée un utilisateur avec tous les privilèges avec un nom 'projet2' et un mot de passe 'projet2' également.
Sinon créer une base de donnée avec un autre nom et un autre utlisateur. Il faudra à ce moment-là changer en fonction, les propriétés $dsn, $username et $password dans la classe src/Core/Model
