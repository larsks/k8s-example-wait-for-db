# so-example-75268222

This repository shows how to use an `initContainer` in an application pod to wait until a database is available. It accompanies my answer to <https://stackoverflow.com/q/75268222/147356>.

# To deploy this example

Run (from the directory containing `kustomization.yaml`):

```
kubectl apply -k .
```

Or if you would like to see the generated manifests without deploying them, you can run:

```
kubectl apply -k . -o yaml --dry-run=client
```
