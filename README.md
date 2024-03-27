1. Déploiement de nginx en resolproxy à partir de l'image
   docker run -d -p 8080:80 -v /var/run/docker.sock:/tmp/docker.sock -t jwilder/nginx-proxy 
2. Utilisez docker compose pour déployer 4 services nginx et un loadbalancer.
