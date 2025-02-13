```
git clone https://github.com/sorianfr/kustomize-course.git
```

Download the Kustomize binary:
```
curl -LO https://github.com/kubernetes-sigs/kustomize/releases/download/kustomize/v5.5.0/kustomize_v5.5.0_linux_amd64.tar.gz
```

Extract the Binary
```
tar -xzf kustomize_v5.5.0_*_amd64.tar.gz
```

Move the binary to /usr/local/bin:
```
sudo mv kustomize /usr/local/bin/
```

Verify Installation
```
kustomize version
```



```
kubectl apply -k .
```

