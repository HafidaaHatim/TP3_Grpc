## => Première Partie :
Reprendre les mêmes exemple de la démonstration vidéo pour implémenter les 4 modèles :
- Unary Model
- Server Sreaming Model
- Client Streaming Model
- BiDirectional Streaming Model
Pour le cas d'une conversion de monnaie


### 1.Test the Unary Model using BloomRPC:
<img width="960" alt="convertBloomRpc" src="https://github.com/HafidaaHatim/TP-N-4-Mise-en-oeuvre-d-un-micro-service/assets/130146750/21953dbb-471c-4fb5-8c9e-d9d2d5ac3e1d">
  Test With client using blockingStub (mode synchrone):
<img width="375" alt="Capture" src="https://github.com/HafidaaHatim/TP-N-4-Mise-en-oeuvre-d-un-micro-service/assets/130146750/2c0df4a9-271a-44ec-8c5b-317afac79794">
 ### 2.Test the Streaming Model using BloomRPC(count to 21):
<img width="953" alt="getStram" src="https://github.com/HafidaaHatim/TP-N-4-Mise-en-oeuvre-d-un-micro-service/assets/130146750/180eb7e5-46a2-417b-b2bc-e86bf35ee39f">
### 3.The client number 3 got an item every second (Server Streaming) :
<img width="560" alt="Client3" src="https://github.com/HafidaaHatim/TP-N-4-Mise-en-oeuvre-d-un-micro-service/assets/130146750/2900595d-1b8e-4d16-8617-50213a500796">
### 4.Perform stream:
<img width="648" alt="Client4" src="https://github.com/HafidaaHatim/TP-N-4-Mise-en-oeuvre-d-un-micro-service/assets/130146750/f319f9c9-9988-479d-8800-9a8d88346ca6">

## => Deuxième partie
 1. Créer un serveur Chat GRPC
 2. Tester le serveur Chat avec un client GRPC comme BloomRPC
 4. Créer un client GRPC Java
 5. Créer un client GRPC Python

## => Troisième partie
 1. Créer un serveur JEU GRPC :
     - Au démarrage le serveur choisit un nombre aléatoire entre 1 et 1000. 
     - Ensuite les clients GRPC doivent deviner en compétition le nombre secret.
     - le serveur répond à chaque fois avec les éventualités suivantes :
        . Votre nombre est plus grand
        . Votre nombre est plus petit
        . BRAVO vous avez gagné et envoyer le gagnant aux clients
        . Jeu terminé, le gagnant est ""Numéro du gagnant"
