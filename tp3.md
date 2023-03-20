1. Installation de Kind et Kubectl


2a. kubectl run my-pod-nginx --image=nginx

résultat :
pod/my-pod-nginx created


2b. (sudo) kubectl port-forward my-pod-nginx 80:8080

résultat :
Forwarding from 127.0.0.1:80 -> 8080
Forwarding from [::1]:80 -> 8080


3a. Creer les fichiers mySqlConf.yml et phpMyAdminConf.yml
Utiliser : kubectl apply -f mySqlConf.yml et kubectl apply -f phpMyAdminConf.yml

3b/c. Creer le fichier mySqlPod.yml
Utiliser : kubectl apply -f mySqlConf.yml et kubectl apply -f phpMyAdminConf.yml

3d.