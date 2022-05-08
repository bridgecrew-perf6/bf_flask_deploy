# usrSide


cd flask/ && docker build -t flask:bf .

cd ..

cd nginx/ && docker build -t nginx:bf .

cd ..

docker compose up -d

docker ps
