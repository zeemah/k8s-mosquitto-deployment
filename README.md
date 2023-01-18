# k8s-mosquitto-deployment

### To run the config files use:
    ""kubectl apply -f <filename.yaml>""

### To check if the pod was created use:
    ""kubectl get pod""

### To enter into the pod

    ""kubectl exec -it <podname> -- /bin/sh""

### To delete pod

    ""kubectl delete -f <filename.yaml>""