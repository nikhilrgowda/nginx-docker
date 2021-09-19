FROM nginx:latest
RUN rm /etc/nginx/conf.d/*.conf;
RUN mkdir -p -v /mydir
COPY ./*.html /mydir
COPY ./conf.d/server1.conf /etc/nginx/conf.d
EXPOSE 9001