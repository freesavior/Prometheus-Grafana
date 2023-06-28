# Installation de Prometheus, Grafana sur Minikube avec le driver Hyperkit

Ce guide vous explique comment installer Prometheus, Grafana sur kubernetes(minikube) avec le driver Hyperkit sur votre machine Macbook

# Prérequis
Assurez-vous d'avoir Docker installé sur votre machine.
Assurez-vous d'avoir les outils kubectl et helm installés sur votre machine.

# Étapes d'installation minikube
brew install minikube

# Démarrez Minikube avec le driver Hyperkit et la mémoire de 4Go ou 8Go ça depend de vos besoins
minikube start --driver=hyperkit --memory=4096

# Vérifiez que le cluster Kubernetes Minikube est en cours d'exécution
kubectl cluster-info

