# myApp

Application d'exemple Ionic

## Prise de notes

###	Découverte de l’environnement Ionic 1h
Installer NPM puis ionic en tant que client

Ionic et le framework « passerelle » : Cordova ou Capacitor
    Dans le projet démarré, on utilise Cordova
    
Ionic véhicule les valeurs suivantes
*	Utiliser les framework web récent (Angular)
*	Offrir une passerelle simplifié avec Cordova
*	Proposer un framework graphique

Ionic et les webView https://ionicframework.com/docs/building/webview
* 	https://developer.apple.com/documentation/webkit/wkwebview
*	https://developer.chrome.com/multidevice/webview/overview

###	Création d’une première application 1h
Initialiser une application ‘ionic start myApp’

Démarrer l’application en mode web (‘ionic serve’)

###	Ionic et les outils 1h
Démarrer l’application depuis IntelliJ (import OK [vu comme une appli Angular], script npm : ‘start’)

Propager le code sous Git

###	Démarrer l’application en mode mobile sur Android 1h
Démarrer un virtual device

Préparer l’application ‘ionic cordova prepare android’

Installer le « native run » ‘npm i -g native-run’

Déclarer les variables d’environnements vers les outils du SDK

Démarrer sur l’application mobile ‘ionic cordova run android -l’
    Cela peut être long à se propager sur le mobile

Utiliser les outils natifs de IntelliJ

###	Démarrer l’application en mode mobile sur iOS 1h

###	Savoir débugger une application 1h

###	Développer en Ionic 1h
Créer de nouvelles pages ‘ionic g page InfiniteSquare’
Créer de nouveaux composants ‘ionic generate’

###	Autres
Migrer de Ionic 1 vers Ionic 4 https://ionicframework.com/docs/building/migration#migrating-from-ionic-1-0-to-ionic-4-0-overview
o	Nécessite de migrer de AngularJS (1.x) vers Angular (7+) 

