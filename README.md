# K8S
### -  Cria o configmap
    kubectl apply -f k8s/configmap-family.yaml

### - Comando para entrar no bash do pod
    kubectl exec -it pode-name -- bash

### - Comando para ver logs do pod 
    kubectl logs pod-name