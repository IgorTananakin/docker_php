## Развернуть php на докере
1) после того как склонировал указать локальный порт если нужно
2) выполнить docker-compose up -d   поднять контейнер   
- если ошибка поднять ubuntu сначала docker run nginx
3) зайти в контейнер если нужно 
- docker exec -it dockernginx-web-1 bash  
4) выключить контейнер 
- docker-compose down
5) перезапустить nginx    
- docker exec app_nginx nginx -s reload