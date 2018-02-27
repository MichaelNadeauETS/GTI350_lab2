# GTI350_lab2

## TODO
- ~~1 doigt sur le fond: translation de la caméra~~ : Done
- ~~1 doigt sur une forme: translation de la forme~~ : Done
- ~~1 doigt sur la sélection actuelle: translation de toutes les formes sélectionnées~~ : Done
- Rajouter un bouton "Effacer" permettant d'effacer des formes complètes. Attention: quand
vous supprimez une forme, assurez-vous de l'enlever du ArrayList selectedShapes,
sinon ça pourrait rester en mémoire : Elsa
- Rajouter un bouton "Encadrer" qui fait un zoom pour centrer la scène. Pour programmer
cette fonction, faites quelque chose
comme gw.frame(shapeContainer.getBoundingRectangle(),true),
où gw est l'instance de GraphicsWrapper : JB
- Rajouter un bouton "Créer" permettant de créer des nouveaux polygones. Conseil: au lieu
de créer le nouveau polygone à partir des positions brutes des doigts (qui peuvent vous
arriver dans n'importe quel ordre),
utilisez Point2DUtil.computeConvexHull() pour calculer un enveloppe
convexe des doigts, et utilisez cet enveloppe convexe pour créer le nouveau polygone : Khoi

## Git strategy
Always make a clean project before any commit and/or push

## Setup guide

## Import project
file/new/import project 

## Update gradle
src : http://devdeeds.com/update-gradle-plugin-android-studio/
steps : file/projects structure/

## Emulator system image : API27

## Build issues and fix
- "Failed to finalize session : INSTALL_FAILED_INVALID_APK: Split lib_slice_5_apk was defined multiple times" 
- Session 'app': Error Installing APKs

Fix : Build/Clean project; Build/Make Module

## SDK dir
fichier local.properties doit être modifié pour chacun d'entre nous, exemple :
sdk.dir=/Users/am56700/Library/Android/sdk
