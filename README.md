# rasa-kubernetes-deployment

# Prerequisites

Helm 3 (>= 3.5 )
Kubernetes 1.14+

# Download Chart 

Now create an empty values.yml file and copy it from rasa official helm repositry into values.yaml file and set you own unique configurations

#Helm deploy cmd

helm upgrade --namespace tenant-7654b5-pilot --reuse-values values.yml rasa/rasa
