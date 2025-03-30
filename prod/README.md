# PROD

This is the starting place for deploying gitea in production with mysql. To test do:

1. `ansible-playbook up.yaml` and ``
2. To see adminer, With the pod name run `kubectl port-forward mysql-d97fc6ccf-22ntv 8080:8080`
3. Adminer is a sidecar to mysql so the host name is either `mysql` or `127.0.0.1`