# Flyway ~ Commandes / Options


###migrate :
  Permet de migrer les fichiers sql.

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
  Check le contenu des fichiers sql avant la migration.

```console
$ flyway [options] validate
```
options : http://flywaydb.org/documentation/commandline/validate.html

###baseline
  Initialise une base existante pour la versioner.

```console
$ flyway [options] baseline
```
options : http://flywaydb.org/documentation/commandline/baseline.html

###repair
  Répare la base de donnée en cas de conflit, supprime les migrations qui en sont la cause.

```console
$ flyway [options] repair
```
options : http://flywaydb.org/documentation/commandline/repair.html
