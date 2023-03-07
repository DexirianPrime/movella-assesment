Steps taken :

Install all prerequesites (minikube, docker, git)

https://minikube.sigs.k8s.io/docs/start/

https://docs.docker.com/desktop/install/
windows-install/

https://desktop.github.com/


Setup Dockerfile (Use NGINX base image and copy HTML folder)

Setup k8s files (deployment, service and ingress rules)

Ressources used :

https://minikube.sigs.k8s.io/docs/start/

https://minikube.sigs.k8s.io/docs/tutorials/nginx_tcp_udp_ingress/

https://www.baeldung.com/docker-local-images-minikube

https://awkwardferny.medium.com/getting-started-with-kubernetes-ingress-nginx-on-minikube-d75e58f52b6c

https://kubernetes.io/docs/tasks/access-application-cluster/ingress-minikube/

Monitoring setup :

Expose minikube's api via  `kubectl proxy --port=8080`

Use kubectl log command to gather logs from pod, for each line check if line contains error, if yes output to logfile, wait 5min and repeat.





