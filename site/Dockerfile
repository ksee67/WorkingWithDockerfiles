FROM nginx

COPY index.html /usr/share/nginx/html/ 
COPY about.html /usr/share/nginx/html/
COPY contact.html /usr/share/nginx/html/
COPY frog.html /usr/share/nginx/html/

# слушаем порт 80
EXPOSE 80

CMD ["nginx", "-g", "daemon off;"]
