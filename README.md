# Didiyun EBS CSI Plugin

Unofficial plugin to use Didiyun EBS as a PVC in Kubernetes.

## Deploy

```
helm repo add csi-didiyun-ebs https://raw.githubusercontent.com/supremind/csi-didiyun-ebs/master/charts
helm repo update
helm upgrade --install csi-ebs csi-didiyun-ebs/csi-didiyun-ebs --namespace didiyun --create-namespace --version 0.1.0 -f ./examples/values.yaml
```

## Contributors
- [@kelviN](https://github.com/killwing)
- [@houz42](https://github.com/houz42)
