# Utilisation de l'image Python slim
FROM python:3.12.6-slim

# Définition du répertoire de travail
WORKDIR /app

# Exposer le port 8000
EXPOSE 8000

# Commande pour démarrer le serveur http
ENTRYPOINT ["python3", "-m", "http.server", "8000"]