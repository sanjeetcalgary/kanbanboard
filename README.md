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

<img width="505" alt="image" src="https://github.com/sanjeetcalgary/kanbanboard/assets/103237142/37d05e8a-b007-4c44-8f52-f479e298b308">

<img width="588" alt="image" src="https://github.com/sanjeetcalgary/kanbanboard/assets/103237142/f4345ce3-588e-4196-948d-83f7ce854f89">

<img width="689" alt="image" src="https://github.com/sanjeetcalgary/kanbanboard/assets/103237142/b390ff0e-a32c-4a24-866f-ad715e8b3298">

<img width="714" alt="image" src="https://github.com/sanjeetcalgary/kanbanboard/assets/103237142/b8c75594-20ac-4863-9fb1-13c0c3d6a7c0">

<img width="712" alt="image" src="https://github.com/sanjeetcalgary/kanbanboard/assets/103237142/d6463a4a-d005-4719-9f91-31767a9477bd">


## Now we will create app helm
-------------------------------------

<img width="719" alt="image" src="https://github.com/sanjeetcalgary/kanbanboard/assets/103237142/d6ca0b21-91e2-4854-a55f-ee2f8779a437">

<img width="536" alt="image" src="https://github.com/sanjeetcalgary/kanbanboard/assets/103237142/1a516d25-f5b2-480f-975c-17dc1cb4de44">

<img width="548" alt="image" src="https://github.com/sanjeetcalgary/kanbanboard/assets/103237142/edb85896-6a8a-4943-9413-b745e78a07a9">

<img width="462" alt="image" src="https://github.com/sanjeetcalgary/kanbanboard/assets/103237142/bb7eee6a-7bdb-475a-8fe7-dc1c2aac6aec">

<img width="715" alt="image" src="https://github.com/sanjeetcalgary/kanbanboard/assets/103237142/b1d0a018-2f54-498c-8dd5-0963a60f6760">

<img width="955" alt="image" src="https://github.com/sanjeetcalgary/kanbanboard/assets/103237142/61f728d7-43e2-4718-be84-54c600ec0cc2">



