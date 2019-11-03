# kube-app-golang
This app includes two services for the demo purpose

$helm install --name starkapp1 --namespace tenant1 --set ingress.host=starkapp.spartan-360.com starkapp
$helm install --name starkapp2 --namespace tenant2 --set ingress.host=starkapp2.spartan-360.com starkapp
