Effacement sécurisé des données
###############################

Effacer des données n'est pas aussi facile qu'il n'y parait.

- Il est possible d'effacer des données sur un disque dur mécanique
  (avec un bras) avec ``nautilus wipe`` par exemple.
- Il est **impossible** d'effacer **completement** une mémoire flash: un petit
  bout de la mémoire est alloué aléatoirement a chaque démarrage du disque,
  qui empèche l'effacement de cette zone: après un effacement on ne peut pas
  être certain que les données sont effectivement supprimées.

Utiliser une clé USB
====================

La solution la plus sure est donc d'utiliser une clé USB chiffrée (avec LUKS
par exemple).

Suppression de fichiers dans Tails
==================================

Deux choses à montrer sur tails:

1. Secure Wipe dans nautilus ou dans Tails, pour supprimer des fichiers
2. Effacer l'espace disque disponible, ce qui permet de remplir l'espace disque
   restant avec des 0.
