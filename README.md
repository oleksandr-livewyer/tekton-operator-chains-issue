# tekton-operator-chains-issue

https://github.com/tektoncd/operator

Instructions:

helm install tekton-operator -n tekton-operator --create-namespace  post-install/tekton-operator/ --set installCRDs=true

helm install tekton-operator -n tekton-operator --create-namespace  pre-install/tekton-operator/ --set installCRDs=true