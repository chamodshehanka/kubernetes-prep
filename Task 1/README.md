Create a namespace

```
kubectl create ns chamod
```

Pull the image from the Repository and create a Container on the Cluster
```
kubectl run pxe-demo --image nj93/pxe-demo --port 8080 -n chamod -o yaml > pxe-demo.yaml
```