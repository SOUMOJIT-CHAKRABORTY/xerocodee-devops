# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

  ### docker compose up
  
  ### minikube start

  ### kubectl create namespace argcd

  ### kubectl apply -f rails-app_deployment.yml

  ### kubectl apply -f dynamodb-statefulset.yaml

  ### kubectl apply -f argocd-application.yml

  ### kubectl port-forward svc/argocd-server -n argocd 8080:443 [this will start the argocd gui on port localhost:8080]
  

* ...
