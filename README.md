# Mini projet de fin de formation Kubernetes - déploiement Wordpress

### Pré-requis :
* Un cluster Kubernetes
* Une StorageClass configurée sur le cluster

Pour déployer le projet :

`kubectl apply -k ./`

Le site déployé est accessible à l'adresse IP du master node, sur le port 30008