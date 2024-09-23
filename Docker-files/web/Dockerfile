FROM nginx
LABEL "project"="vprofile"
LABEL "Author"="Ceto"

RUN rm -rf /etc/nginx/conf.d/default.conf
COPY nginvproapp.conf /etc/nginx/conf.d/vproapp.conf

EXPOSE 8080