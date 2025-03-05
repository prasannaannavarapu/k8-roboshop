FROM mysql:5.7
# ENV MYSQL_ROOT_PASSWORD=RoboShop@1 \  #Adding this in to ConfigMap
#     MYSQL_DATABASE=cities \
#     MYSQL_USER=shipping \
#     MYSQL_PASSWORD=RoboShop@1
COPY scripts/*  /docker-entrypoint-initdb.d/
