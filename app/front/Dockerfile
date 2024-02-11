FROM nginx:latest

WORKDIR /app

COPY entrypoint.sh /app/

RUN chmod +x ./entrypoint.sh

COPY index.html /usr/share/nginx/html/

ENTRYPOINT ["./entrypoint.sh"]
