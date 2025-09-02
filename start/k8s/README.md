```shell
    kubectl --kubeconfig <путь до kubeconfig.yaml от бота> apply -f app.yaml 
```

```shell
    kubectl  --kubeconfig <путь до kubeconfig.yaml от бота> \
        port-forward service/bomberman 8000:8000
```

```shell
    kubectl --kubeconfig <путь до kubeconfig.yaml от бота> get po
```

```shell
    kubectl --kubeconfig <путь до kubeconfig.yaml от бота> \
        logs <имя пода>
```
