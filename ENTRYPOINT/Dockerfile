FROM redhat/ubi9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
RUN echo "Hello World from ENTRYPOINT" > /usr/share/nginx/html/index.html
EXPOSE 80
CMD [ "google.com" ]
ENTRYPOINT [ "ping" ]