# kubernates-Read-Me

### List pods 
##### kubectl get pods

### List pods instant changing status
##### kubectl get pods -w

### POD Scale replicas
##### kubectl scale deployment POD_NAME --replicas=0    or 1

### POD Editing resources 
##### kubectl edit deploy POD_NAME

### POD logs (stdout)
##### kubectl logs POD_NAME CONTAINER_NAME -f                                 

### POD Deploy Information
##### kubectl get deployment -o wide                                

### Namespace listing
##### kubectl get ns

### usage grep commend 
##### kubectl get ns | grep cecece

### deploying detail
##### kubectl get pods -n NAME_SPACE_NAME -o wide
##### kubectl get pods -n dev_dev -o wide


### usage svc
##### kubectl get svc -n NAME_SPACE_NAME
