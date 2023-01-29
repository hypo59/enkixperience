# Pourquoi supprimer le cache et/ou les données de l'app enki ?

date de mise à jour de l'article: 2023-01-29

[Le cache](#le-cache)  
[Les données](#les-donn%C3%A9es)
- [android](#android)
- [ios](#ios)

https://github.com/hypo59/enkixperience/edit/supprimer-cache-et-donn%C3%A9es/content.md#ios
https://github.com/hypo59/enkixperience/edit/supprimer-cache-et-donn%C3%A9es/content.md#android
https://github.com/hypo59/enkixperience/edit/supprimer-cache-et-donn%C3%A9es/content.md#les-donn%C3%A9es
https://github.com/hypo59/enkixperience/edit/supprimer-cache-et-donn%C3%A9es/content.md#le-cache

## Le cache

Lors de l'utilisation d'une application sur un smartphone, des données sont stockées sur le smartphone dans des dossiers et des fichiers localisés dans un endroit précis de l'arborescence du système de fichiers du smartphone. Pour permettre une réactivité plus grande de l'application, certaines de ces données sont stockés dans un endroit spécifique appelé "cache". L'app enki n'échappe évidemment pas à la règle.

Supprimer/vider le cache permet de nettoyer une ou plusieurs données possiblement corrompues pouvant empêcher le bon fonctionnement de l'app, sans incidence toutefois sur son accès: en règle générale, une fois le cache supprimé/vidé, l'app enki est toujours disponible sans qu'il n'y ait besoin de se reconnecter en saisissant identifiant et mot de passe, et la manipulation des objets reste disponible.

Cette opération n'est toutefois possible que sous android, iOS ne le permettant pas. Pour la réaliser, les étapes à suivre diffèrent selon la ou les surcouches android implémentées par le vendeur et/ou l'opérateur du smartphone et selon la version android installée sur le smartphone, mais en principe il suffit de réaliser les points suivant:
- faire un long clic sur l'icône de l'app jusqu'à apparition d'un menu
- dans le menu, sélectionner le sous-menu dont le texte est proche de "informations de l'app", "i", etc.
- une fois la page d'informations de l'app affichée, rechercher un sous-menu ayant pour texte proche "stockage", "données" ou "cache", puis y entrer
- une fois la page affichée, cliquer sur le bouton de suppression/vidage du cache

Une fois le cache supprimé/vidé, il sera régénéré automatiquement par l'app enki lors de sa prochaine utilisation, de manière totalement transparente.

Exemples
- avec un Samsung Galaxy S9 sous android 12 (Noble ROM 2.8): clic long > "i" > Stockage > Vider le cache 
- avec un Xiaomi Redmi Note 10 Pro sous android 12 (stock): clic long > Informations sur l'application > Effacer les données > Vider le cache

## Les données

De la même manière que pour le cache, il peut arriver que les données générales de l'app enki soient partiellement corrompues, pouvant empêcher son accès ou pouvant provoquer des incohérences d'utilisation à travers ces différentes pages. En ce cas, une suppression des données peut permettre de résoudre le problème.

Egalement, si l'on possède plusieurs comptes enki (gestion de bungalo, maison secondaire, superficie omportante, etc.) et que l'on navgue régulièrement d'un compte  à l'autre, il peut être préférable de supprimer les données du précédent compte entre chaque changment de compte.

Enfin, si pour une raison particuloère l'on souhaite créee un compte enki avec un pays différent de celui du compte actuellement utilisé, il est nécessaire d'en passer par la suppression des données afin que le choix du pays s'affiche dès l'ouverture de l'applicarion. Le choix du pays permet de bénéficier d'un choix différents d'objets: pour la France, tous les objets enki sont disponibles; en revanche, pour les autres pays, ce choix est très restreint, certainement parce que tous les objets n'y osnt pas commercilaisés. 

Mais que provoque la suppression des données de l'app enki ? Est-ce que je perds mon compte ? Mes objets ? Mes scénarios ?

Soyez rassuré(e): bien évidemment non ;) ! La suppression des données de l'app eki permet seulement de supprimer toute trace de votre activité sur le smartphone utilisé, et non sur les serveurs enki qui portent l'entièreté de vos appairages, scénarios, etc.. Dit autrement, si vous vous connectez à l'app enki avec le même identifiant sur plusieurs smartphones, puis que sur l'un d'eux vous supprimez les données de l'app enki, rien ne se sera reporté sur les autres smartphones. Encore dit d'une manière différente, si vous vous connectez à l'app enki depuis un smartphone supplémentaire, celui-ci récupère bien les informations de votre compte en provenance des serveurs enki, et ces informations sont strictement identques que celles présentées sur l'apap enki de votr autre smartphone: les données sont bien issues du même compte enki, en provenance des seruers enki.

Lorsque l'on supprime les données de l'app enki, il s'agit bien de supprimer l'activité d'utilisation de lapp enki sur le smartphone en question, et non de demander à la platefomre enk ide supprimer purement et simplement le compte et tout ce qu'il contient.

La suppression des données de l'app enki est disponbile pour ios et android, et se réalise de la manière suivante:

### android

Les étapes à suivre diffèrent selon la ou les surcouches android implémentées par le vendeur et/ou l'opérateur du smartphone et selon la version android installée sur le smartphone, mais en principe il suffit de réaliser les points suivant:
- faire un long clic sur l'icône de l'app jusqu'à apparition d'un menu
- dans le menu, sélectionner le sous-menu dont le texte est proche de "informations de l'app", "i", etc.
- une fois la page d'informations de l'app affichée, rechercher un sous-menu ayant pour texte proche "stockage", "données" ou "cache", puis y entrer
- une fois la page affichée, cliquer sur le bouton de suppression/vidage des données

Exemple
- avec un Samsung Galaxy S9 sous android 12 (noble rom 2.8): clic long > "i" > Stockage > Supprimer les données 
- avec un Xiaomi Redmi Note 10 Pro sous android 12 (stock): clic long > Informations sur l'application > Effacer les données > Effacer toutes les données

### ios

Il est nécessaire de supprimer puis réinstaller l'app enki, ios ne proposant pas d'alternative moins lourde. 
