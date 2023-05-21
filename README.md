**Create a docker image:** `docker build -t <name> .` 
**OR** `docker build -t <username>/<name>` (recommended)

**Push image to docker hub:** `docker push <name>`

**To create kubernetes pod, run config file:** `kubectl apply -f <name>`

**List all pods:** `kubectl get pods`

**Delete deployment:** `k delete deployment <deployment-name>` 

`kubectl get service ingress-nginx-controller --namespace=ingress-nginx`

To set hostname go to 
> C:/Windows/System32/drivers/etc/hosts

and set 
`127.0.0.1 posts.com
::1 posts.com`