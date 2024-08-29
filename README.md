# loadbalancer-nginx-flask2server
Load Balancer Using NGINX with two flask webserver


# How to compile docker-compose
docker-compose up --force-recreate --build -d

# How to use after compile docker-compose finish
1. Access using browser https://you-ip-address:8080 (http://localhost:8080/)
2. You can test shutdown your app1 or app2 to validate or you can refresh the page , then the page will show you app1 and app2 alternately.
