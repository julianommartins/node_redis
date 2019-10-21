# node_redis
Example node with redis

1- Install docker
2- Get redis image
docker pull redis

3- Run redis image
docker run --name redis13 -p 6379:6379 -d redis redis-server --appendonly no

4- Install dependencies
npm -i

5- Run
