# foo-sample-controller

Set image env
```
export IMG=aa332266/sample-controller:kubebuilder
```

Build image
```
make docker-build
```

Push to docker hub
```
nmake docker-push
```

Deploy in cluster
```
make deploy
```