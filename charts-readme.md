# Building repo

## Enable GitHub Pages with source from main branch
Now get an github.io link https://davescreen.github.io/helm-gitops-example/index.yaml

## Create index.yaml 
helm repo index . --url https://davescreen.github.io/helm-gitops-example


# Using the repo
## Add repo
helm repo add helm-gitops-example https://davescreen.github.io/helm-gitops-example

## Search for my-chart
helm search repo my-chart

## install with
helm install my-chart helm-gitops-example/my-chart