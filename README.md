# learn

git clone https://github.com/bitnami/tutorials

sudo service docker start

cd phpfpm-k8s/
docker build . -t  lewadik/phpfpm-app:0.1.0
vim app-code/docker-compose.yml
docker login
docker push lewadik/phpfpm-app:0.1.0

unzip myarch.zip
helm install phpfpm . --set mariadb.mariadbRootPassword=mini,mariadb.mariadbUser=mini,mariadb.mariadbPassword=mini,mariadb.mariadbDatabase=mini
