## Replicaset with 10 pod

Commands:


`kubectl apply -f .\myreplicaset.yaml` => create replicaset from myreplicaset.yaml

`kubectl describe replicaset myreplicaset` => show with details the replicaset created

`kubectl get replicasets` => show without detailed the replicasets created

`kubectl scale replicaset myreplicaset --replicas 20
` => Scale for more or less pods
