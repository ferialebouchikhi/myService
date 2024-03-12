1) Démarrage de Minikube
2) Modification du fichier infrastructure.yaml: fichier contenant les informations de configuration de la gateway, du proxy et du service
3) kubectl apply -f front-back-app.yaml
4) Ce fichier permet l'utilisation de l'application
5) minikube service front-end --url --> utiliser l'url qui s'affiche
6) L'execution affiche "Hello (from the front end) World !(from the back end)"
