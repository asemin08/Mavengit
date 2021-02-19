    mvn versions:display-dependency-updates 

(Liste toutes les dépendances ayant une version plus récente)

Permet de lister les dépendence ayant une  nouvelle versions

    mvn versions:display-plugin-updates

Permet de lister les plugins ayant une  nouvelle versions

    mvn versions:update-child-modules 

(changer d’abord la version du pom parent. En appelant ensuite ce goal sur le pom parent, il mettra à jour les versions dans enfants. pratique pour faire changements de versions)

        mvn versions:set 

– Comme update-child-modules mais permettant de spécifier la nouvelle version en ligne de commande (-DnewVersion=VALUE) au lieu de changer le pom parent.


