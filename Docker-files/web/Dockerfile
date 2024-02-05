FROM nginx
LABEL "project"="vprofile"
LABEL "author"="mitul"

RUN rm -rvf /etc/nginx/conf.d/default.conf
COPY nginvproapp.conf /etc/nginx/conf.d/vproapp.conf
