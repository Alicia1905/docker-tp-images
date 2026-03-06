## Commandes pour l'xercice 1 Flask

# 1
docker build -t flask-app:1.0.0 .

# 2
docker tag hello-flask:1.0.0 hello-flask:latest

# 3
docker run -p 5000:5000 flask-app:1.0.0

# 4
docker ps (dans un autre terminal)

# 5
docker stop f852eda3ff57



