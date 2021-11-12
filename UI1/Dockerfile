FROM nginx:latest
RUN rm /etc/nginx/conf.d/*.conf;
RUN mkdir /proxyit1
RUN mkdir /proxyit1/ui1
COPY ./html /proxyit1/ui1
COPY ./conf.d/server1.conf /etc/nginx/conf.d
EXPOSE 9001