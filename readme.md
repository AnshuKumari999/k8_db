1. kubectl create -f mysql-secret.yaml
2. kubectl create -f mysqldatabase.yaml
3. kubectl create -f mysqlservice.yaml
4. kubectl get deployment
5. kubectl get pods
6. kubectl exec --stdin --tty <pod_name> -- /bin/bash
7. mysql -p
8. show databases;