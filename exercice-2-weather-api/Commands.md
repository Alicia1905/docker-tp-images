## Commandes pour l'xercice 2

# 1
docker build -t asli20/weather-api:1.0.0 .


# 2
docker run -p 3000:3000 asli20/weather-api:1.0.0

# 3
docker login

# 4
docker push asli20/weather-api:1.0.0

# 5
docker tag asli20/weather-api:1.0.0 asli20/weather-api:latest

# 6
docker push asli20/weather-api:latest