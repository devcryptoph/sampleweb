# sampleweb
Sample nginx web server istio service mesh on rancher

### Deploy
`kubectl -n demo apply -f https://raw.githubusercontent.com/devcryptoph/sampleweb/master/sampleweb.yaml`

`kubectl -n demo apply -f https://raw.githubusercontent.com/devcryptoph/sampleweb/master/sampleweb-gateway.yaml`

### Remve
`kubectl -n demo delete -f https://raw.githubusercontent.com/devcryptoph/sampleweb/master/sampleweb.yaml`

`kubectl -n demo delete -f https://raw.githubusercontent.com/devcryptoph/sampleweb/master/sampleweb-gateway.yaml`
