# Create index.yaml with
helm repo index . --url https://davescreen.github.io/helm-gitops-example

# Enable GitHub Pages with source from main branch
# Now get an github.io link :
with accessible https://davescreen.github.io/helm-gitops-example/index.yaml


# Add repo
helm repo add helm-gitops-example https://davescreen.github.io/helm-gitops-example
# install with
helm install my-chart helm-gitops-example/my-chart