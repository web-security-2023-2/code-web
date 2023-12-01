On the command line

This is the quickest way

# Launch a 20.04 based image with PHP 8
docker run -p "80:80" -v ${PWD}/app:/app mattrayner/lamp:latest-2004-php8

# Launch a 20.04 based image with PHP 7
docker run -p "80:80" -v ${PWD}/app:/app mattrayner/lamp:latest-2004-php7

# Launch a 18.04 based image with PHP 8
docker run -p "80:80" -v ${PWD}/app:/app mattrayner/lamp:latest-1804-php8

# Launch a 18.04 based image with PHP 7
docker run -p "80:80" -v ${PWD}/app:/app mattrayner/lamp:latest-1804-php7

# Launch a 16.04 based image with PHP 7
docker run -p "80:80" -v ${PWD}/app:/app mattrayner/lamp:latest-1604

# Launch a 14.04 based image with PHP 5
docker run -p "80:80" -v ${PWD}/app:/app mattrayner/lamp:latest-1404
