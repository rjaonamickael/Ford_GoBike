# Système de partage de vélos : Ford GoBike
## by Mickaël RATISARIJAONA


## Base de données

Cet ensemble de données comprend des informations sur les trajets individuels effectués dans un système de partage de vélos couvrant la grande région de la baie de San Francisco : [**Ford GoBike**](https://video.udacity-data.com/topher/2020/October/5f91cf38_201902-fordgobike-tripdata/201902-fordgobike-tripdata.csv)

## Résumé des résultats
Pour les variables numériques, année de naissance et durée d'utilisation des vélos (en seconde), j'ai du transformer la première en âge (puisque c'est l'information que l'on souhaitera analyser) et convertir les durées en minutes (puisque c'est plus intuitif concernant des trajets quotidiens en vélo. J'ai pu constater que la généralité des clients ont moins de 60 ans et leur trajet dure généralement à moins de 30 min. Au dela de cela, ce sont toutes des valeurs abérrantes.

Nous avons pu observer que c'est comportement change en fonction de deux variables : le type de forfait du client (Abonné ou non) ainsi que le type de vélo utilisé par ce dernier (Partagé ou non). Nous avons pu voir que les non abonnés ont un temps d'utilisation généralement plus élevé (variant de 0 à presque 40 minutes) que celui des abonnés (variant de 0 à moins de 25 minutes). Nous avons pu voir également l"âge des clients utilisant les vélos partagé se concentre dans les vingtaines. Et surtout, l'une des résultats intéressant que nous vions pu observer : seul les abonnés utilisent des vélos partagé.

Concernant les lieux géographique des stations de départ et d'arrivé, nous avons constater une forte colinéarité entre ces variables : coordonnées géographiques des stations de départ et d'arrivés. Ce qui fait donc que l'emplacement géographique des stations de départ et d'arrivée ne sont pas trop éloigné.


## Informations clés pour la présentation

Pour la présentation je me concetrerais que sur 4 variables : le type de forfait et de vélo, l'âge des clients ainsi que la durée d'utilisation des vélos. J'utilise des graphes montrant les distributions de ces différents variables (Histogramme, Boîte à Moustache et violon) afin que le changement de ces distribution soit très remarquable.
