# simplilearn-phpinfo

docker container run --detach --entrypoint php  --name php-latest --publish 80:8080 --rm --workdir /src index.docker.io/ramjmeka/caltech-phpinfo:latest -f index.php -S 0.0.0.0:8080
