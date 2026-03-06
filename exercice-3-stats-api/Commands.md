## Commandes pour l'exercice 3

# 1
docker build -t asli20/stats-api:1.0.0 .

# 2
docker run -p 5000:5000 asli20/stats-api:1.0.0

# 3
docker login

# 4
docker push asli20/stats-api:1.0.0

# 5
docker build -t asli20/stats-api:2.0.0 .

# 6
docker run -p 5000:5000 asli20/stats-api:2.0.0

# 7
docker push asli20/stats-api:2.0.0

# 8
docker tag asli20/stats-api:2.0.0 asli20/stats-api:latest

# 9
docker push asli20/stats-api:latest
