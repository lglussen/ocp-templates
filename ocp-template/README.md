# OpenShift Templates

Using defaults.  Note the generated password.
```shell

oc process -f my-app-template.yaml -o yaml

```

Using parameters

```shell
oc process -f my-app-template.yaml  -p APP_NAME=foo -p MY_SHARED_SECRET=whatever  -o yaml
```
