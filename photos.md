# Pourquoi la photo de mon profil et celle de l'accueil ne sont pas toujours conservées ?

_date de mise à jour de l'article: 2023-01-29_

L'app enki nous permet de personnaliser un peu son interface, afin de la rendre plus chaleureuse: il est possible de modifier la photo de profil et la photo de l'accueil. Cependant, ces modifications ne sont enregistrées que sur le smartphone utilisé, et non sur les serveurs enki, ce qui a pour effet de ne pas être propagé sur un autre smartphone avec le même compte enki ou lorsqu'on supprime les données de l'app enki puis que l'on se reconnecte (cf. [Pourquoi supprimer le cache et/ou les données de l'app enki ?](#pourquoi-supprimer-le-cache-etou-les-donn%C3%A9es-de-lapp-enki-)):
- ainsi si l'on se connecte avec le même compte enki sur un autre smartphone, les photos ne seront pas affichées, et il sera nécessaire d'en ajouter de nouvelles
- à la suite de la suppession des données de l'app enki, ce sera la même chose: photos non affichées, nécessité de les ajouter de nouveau

Dans le détails, avec un accès root sous android, le fichier shared_prefs/Hawk2.xml contient ces 2 photos: en le supprimant puis en relançant l'app enki, les photos ne sont plus affichées; en ajoutant de nouveau ces 2 photos, le fichier est modifié aux sections suivantes:
- [id]-USER_BACKGROUND_PICTURE: correspond à la photo de l'accueil
- [id]-USER_PROFILE_PICTURE: correspond à la photo du profil
