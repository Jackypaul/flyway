###migrate :
  Permet de migrer les fichier sql.

```console
$ flyway [options] migrate
```
options : http://flywaydb.org/documentation/commandline/migrate.html

###clean :
  Supprime tout ce que contient la base de donnée.
  
```console
$ flyway [options] clean
```
options : http://flywaydb.org/documentation/commandline/clean.html

###info : 
  Donne l'état, les détails des migrations. 

```console
$ flyway [options] info
  
```
options : http://flywaydb.org/documentation/commandline/info.html

###validate
  Check le contenu des fichier sql avant la migration.

```console
$ flyway [options] validate
```
options : http://flywaydb.org/documentation/commandline/validate.html

###baseline
  Part d'une base existante pour la versioner.

```console
$ flyway [options] baseline
```
options : http://flywaydb.org/documentation/commandline/baseline.html

###repair
  Répare la base de donnée en cas de conflit, supprime les migration source de ce conflit.

```console
$ flyway [options] repair
```
options : http://flywaydb.org/documentation/commandline/repair.html
