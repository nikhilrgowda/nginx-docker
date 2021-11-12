FROM nginx:latest
RUN rm /etc/nginx/conf.d/*.conf;
RUN mkdir /proxyit2
RUN mkdir /proxyit2/ui2
COPY ./html /proxyit2/ui2
COPY ./conf.d/server2.conf /etc/nginx/conf.d
EXPOSE 9002