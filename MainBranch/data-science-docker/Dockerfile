# DockerFile
# Ce Dockerfile crée une image avec Python, installe les dépendances, copie ton code et exécute main.py.

# Python Image
FROM python:3.10 

# Crée un dossier pour ton app 
WORKDIR /app

# Copie les fichiers 
COPY requirements.txt ./
RUN pip install --no--cachedir -r requirements.txt

COPY . . 

# Lance le script main.py avec l'image 
CMD ["python","main.py"]

