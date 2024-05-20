# kanbanboard-Helm
-------------------------------------------------

1- Create postgres chart `helm create postgres`

2- Delete contents of values.yaml, inside template directory unnecessary manifests

3- create deployment, pv, pvc , configmap and service for postgres in ./template directory

```
Create values.yaml
Create deployment.yaml
Create pv and pvc yaml
Create service and config yaml
```

4- Update the Chart.yaml

`helm install -f kanban-postgres.yaml postgres ./postgres --dry-run --debug`

<img width="588" alt="image" src="https://github.com/sanjeetcalgary/kanbanboard/assets/103237142/f4345ce3-588e-4196-948d-83f7ce854f89">

<img width="689" alt="image" src="https://github.com/sanjeetcalgary/kanbanboard/assets/103237142/b390ff0e-a32c-4a24-866f-ad715e8b3298">


