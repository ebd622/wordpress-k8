# wordpress-k8
Kubernetes challenge - Wordpress App.
This is the solution for the Wordpress App chalenge provided by https://kodekloud.com/

### The architecture specified in the challenge
<img src="images/architecture.png" width="60%">

### Solution
#### 1. Deploy PV for wordpress
```bash
kubectl create -f pv-wordpress.yaml
```

#### 2. Deploy PV for mysql
```bash
kubectl create -f ...
```

#### 3. Deploy PV for wordpress
```bash
kubectl create -f ...
```

#### 4. Deploy PVC for mysql
```bash
kubectl create -f ...
```

#### 5. Create a secret
```bash
kubectl create secret generic mysql-pass --from-literal=password=admin --from-literal=host=wordpress-mysql
```



