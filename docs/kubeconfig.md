Move k3s.yaml from master node to current machine

```shell
mv /etc/rancher/k3s/k3s.yaml ~/.kube/config
```

```shell
rsync -avz <remote_host>:<path_from_remote_file> <path_to_local_file>
```

Change clusters/cluster/server: <ip> in `~/.kube/config`

