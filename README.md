helm repo add argo https://argoproj.github.io/argo-helm
helm repo update
## Pull and unpack
helm pull vm/victoria-logs-cluster --version <version_number> --untar