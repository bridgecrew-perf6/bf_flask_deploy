# bf


python 3.8
aws ec2 ubuntu 20.04


install docker by https://www.digitalocean.com/community/tutorials/how-to-install-and-use-docker-on-ubuntu-20-04

install docker-compose by https://dejavuhyo.github.io/posts/install-docker-compose/


----------------------------------------------


cd flask/ && docker build -t flask:bf .

cd ..

cd nginx/ && docker build -t nginx:bf .

cd ..

docker-compose up -d

docker ps




---------------------------------------------

add [inbound] 80 port as 'http' [security groups]

 than, connect ec2 instans's [public IPv4 DNS]