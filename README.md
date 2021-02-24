# ECS-CloudFormation
here is cloud formation stack for creating ECS Cluster .
what this while Cloud Formation is doing is listed down.

1= creats ECS cluster
2= creats Taskdefination
3= pulls images from ECR
4= creats VPC for cluster
5= creats LoadBalancer for this app
6= creats nginx container which will work as a reverse proxy for python app.
7= attaches cloudewatch logs group for service logs.
8= outputs Loadbalancer DNS to access nginx proxy which will proxy users request to python app .

thank you . please if you can contribute fork it and generate pull request .
