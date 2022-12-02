# ToDoApp
ToDoApp est une application de gestion de projet collaboratif. Elle permet de créer des projets et de consulter le statut des tâches qui y sont rattachées. Elle possède:
1) Un système de session utilisateur et de gestion de compte
2) La possibilité de créer ses projets, en être administrateur et créer des tâches reliées à ce dernier
3) La possibilité d'affecter d'autres utilisateurs à ses projets et aux tâches existantes
# Pré-requis
1) Créer une base de donnée dans PhpMyAdmin se nommant projetmcd
2) Importer la base de donnée qui se trouve dans DB (le fichier projetmcd.sql)
3) Dans PhpMyAdmin, crée un utilisateur avec tous les privilèges avec un nom 'projet2' et un mot de passe 'projet2' également
4) Sinon créer une base de donnée avec un autre nom et un autre utlisateur. Il faudra à ce moment-là changer en fonction, les propriétés $dsn, $username et $password dans la classe src/Core/Model
