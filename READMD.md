**Create a docker image:** `docker build -t <name> .` 
**OR** `docker build -t <username>/<name>` (recommended)

**Push image to docker hub:** `docker push <name>`

**To create kubernetes pod, run config file:** `kubectl apply -f <name>`

**List all pods:** `kubectl get pods`

**Delete deployment:** `k delete deployment <deployment-name>`