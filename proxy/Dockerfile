# Image de base : nginx version 1.12
FROM nginx:1.12
# copier default.conf dans : /etc/nginx/conf.d/default.conf
COPY default.conf /etc/nginx/conf.d/
# Fichier HTML pour réponses BACKEND-NOT-FOUND : à copier dans /var/www/html/backend-not-found.html
COPY backend-not-found.html /var/www/html/
# Configuration du proxy : copier proxy.conf dans /etc/nginx/includes/
COPY proxy.conf /etc/nginx/includes/
# Exposer le port 80
EXPOSE 80
