## Replicaset with 10 pod

Commands:


`kubectl apply -f .\mydeployment.yaml` => create deployment from mydeployment.yaml

`kubectl get deployment` => show list deployments created

`kubectl get replicasets` => show without detailed the replicasets created

`kubectl scale replicaset myreplicaset --replicas 20
` => Scale for more or less pods
