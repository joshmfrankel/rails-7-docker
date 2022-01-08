# README

The following commands follow along with the official Docker tutorial [found here](https://docs.docker.com/samples/rails/)

```
docker-compose run --no-deps web rails new . --force --database=postgresql
sudo chown -R $USER:$USER .
docker-compose build
docker-compose up
docker-compose run web rails db:create
```