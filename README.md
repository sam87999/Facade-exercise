# Facade-exercise
#Énoncé
On veut simuler un système de lecture de musique.

Une application doit :

allumer les haut-parleurs
lancer le lecteur
charger une playlist
régler le volume

#Sans façade, le client devrait appeler chaque système séparément.

Travail demandé :
1. Créer les classes suivantes :

SpeakerSystem
MusicPlayer
PlaylistManager
VolumeController


2. Créer une classe Façade appelée MusicFacade avec :

start_music()
stop_music()


3. La façade doit coordonner les sous-systèmes pour démarrer et arrêter la musique.

4. Écrire un petit test montrant que le client utilise seulement la façade.


## Résultat du programme

![Résultat](Capture%20d’écran%202026-02-08%20153502.png)
