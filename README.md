# k8s-mosquitto-deployment

### To run the config files use:
    ""kubectl apply -f <filename.yaml>""

### To check if the pod was created use:
    ""kubectl get pod""

### To enter into the pod

    ""kubectl exec -it <podname> -- /bin/sh""

### To delete pod

    ""kubectl delete -f <filename.yaml>""

Note: Create the ConfigMap and Secrets first as they are referenced in the mosquitto cluster, else the cluster will fail to create. 