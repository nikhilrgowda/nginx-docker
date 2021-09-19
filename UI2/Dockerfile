FROM nginx:latest
RUN rm /etc/nginx/conf.d/*.conf;
RUN mkdir /mydir
COPY ./*.html /mydir
COPY ./conf.d/server2.conf /etc/nginx/conf.d
EXPOSE 9002