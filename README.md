![picto](/doc/img/geocompiegnois_2020_reduit_v2.png)

* Statut
  - [ ] à rédiger
  - [x] en cours de rédaction
  - [ ] relecture
  - [ ] finaliser
  - [ ] révision

# Schéma des standards locaux des réseaux

Urbanisation des modèles de données des différents réseaux de compétence locale.

# Contexte

Les collectivités sont soumises à diverses réglementations concernant les réseaux (DICT, prises de compétence, entretiens, ...) et peuvent être gérés en régie ou délégués à un ou plusieurs prestataires. Dans ce contexte, la première question qui est souvent abordée est, mais où passent mes réseaux ? La donnée devient donc un enjeu majeur pour les collectivités. Si elle n'existe pas en interne (ou uniquement sur des plans papiers plus ou moins à jour), elle est souvent disponible auprès d'un délégataire assigné à la gestion de mon réseau. La seconde question est comment accéder à cette information pour la gestion courante de mes services ? Les standards nationaux mis en place sur les réseaux doivent répondre à cette question puisqu'ils organisent et structures des formats d'échanges entre les acteurs. Malheureusement il n'existe pas de standards nationaux pour tous les types de réseaux et cela ne résoud pas la question d'une gestion cohérente et homogène des données à l'intérieur d'une collectivité pouvant provenir de x producteurs.

Le Service de l'Information Géographique de l'Agglomération de la Région de Compiègne, qui dispose d'un entrepôt de données géographiques, s'oriente vers une gestion commune des données de réseaux. Il s'agit pas d'intégrer tous les réseaux dans une même base de données mais bien de réfléchir à utiliser un modèle de données standard à tous types de réseaux. Un réseau fonctionnant de la même façon quelque soit son usage (un filaire conducteur, des ouvrages et des appareils), nous a conduit à l'opportunité de mettre en oeuvre un modèle fonctionnant sur un tronc commun avec des spécifications propres à chacun. Il n'était pas envisageable d'intégrer les standards tels quels à moins de gérer des fichiers par réseaux, multipliés par x délégataires du même réseau. Cette solution aurait eu l'avantage d'offrir une rapidité de mise en place, mais deviendrait vite cronophage.

Dans ce scénario, les standards nationaux redeviennent donc un temps d'échanges entre acteurs. La collectivité intègre les standards dans son modèle propre et renvoie les données dans le standard en question.

# Avertissement

Ce choix de la collectivité offre une plus grande latitude en terme de gestion de la donnée. Un affranhchissement des standards actuels et à venir, permettra une meilleure cohérence entre eux, une homogénéisation et une performance de gestion à moyen et long terme. En contre partie, ce modèle implique une plus grande rigueur en terme d'intégrations des données, d'adaptation du modèle en fonction des spécificités du réseau traité. Il est à noter également que ce choix s'est adapté à une vision d'accès à l'information des réseaux. Une gestion en régie impliquant la gestion des données ne sera peut-être pas compatible avec cette vision en fonction des outils déjà développés faisant appel à un autre modèle de données.

# Voir aussi

Les modèles standards nationaux des différents type de réseaux sont réalisés par la COVADIS. Vous pouvez vous y référer pour prendre connaissance des spécifications de chacun.

* [Standard RAEPA](http://www.geoinformations.developpement-durable.gouv.fr/geostandard-reseaux-d-adduction-d-eau-potable-et-d-a3478.html) (Réseaux d’adduction d’eau potable et d’assainissement)
