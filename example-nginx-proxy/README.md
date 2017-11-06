# Help

Recompose docker-compose up after first docker-compose up

check :
docker-compose exec nginx-gen docker-gen /etc/docker-gen/templates/nginx.tmpl

regenerate :
docker-compose exec nginx-gen docker-gen /etc/docker-gen/templates/nginx.tmpl /etc/nginx/conf.d/default.conf