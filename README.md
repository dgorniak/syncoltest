## Hello World

```bash
if sh -c "$(curl -fosSL "https://example.com/$POTATO")"; then
	echo yes
fi
```

```console
$ kubectl get namespaces
NAME      STATUS   AGE
default   Active   6m
$ kubectl create namespace potato
namespace/potato created
```
