# wordpress-k8
Kubernetes challenge - Wordpress App

### 1. Deploy PV for wordpress
```bash
kuberbetes create -f pv-wordpress.yaml
```

#### 2. Deploy PV for mysql
```bash
kuberbetes create -f ...
```

## 3. Deploy PV for wordpress
```bash
kuberbetes create -f ...
```

## 4. Deploy PVC for mysql
```bash
kuberbetes create -f ...
```

## 5. Create a secret
```bash
kuberbetescreate secret generic mysql-pass --from-literal=password=admin --from-literal=host=wordpress-mysql
```



