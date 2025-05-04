FROM php:8.1-cli

WORKDIR /var/www/html

COPY . .

CMD ["php", "-S", "0.0.0.0:10000"]
