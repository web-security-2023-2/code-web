* Running LNMP container
$ docker run -p "8000:80" -v ./Project:/var/www/html \
	-v ./nginx/default.conf:/etc/nginx/conf.d/default.conf \
	--name lnmp
