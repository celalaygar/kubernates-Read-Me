# kubernates-Read-Me

#### List pods 
kubectl get pods

#### List pods instant changing status
kubectl get pods -w

#### POD Scale replicas
kubectl scale deployment POD_NAME --replicas=0    or 1

#### POD Editing resources 
kubectl edit deploy POD_NAME

#### POD logs (stdout)
kubectl logs POD_NAME -f                                 
