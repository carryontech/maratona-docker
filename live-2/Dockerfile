FROM nginx:latest
RUN mkdir -p /var/www/html
COPY ./nginx.conf /etc/nginx/conf.d/default.conf
ADD ./calculadoraIMC /var/www/html/site/
EXPOSE 80
LABEL description="Calculadora IMC"
