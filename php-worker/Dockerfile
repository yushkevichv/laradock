#
#--------------------------------------------------------------------------
# Image Setup
#--------------------------------------------------------------------------
#
# To take a look at the'php-worker' base Image, visit its DockerHub page
#    https://hub.docker.com/r/nielsvdoorn/laravel-supervisor/
#

FROM nielsvdoorn/laravel-supervisor

MAINTAINER Mahmoud Zalt <mahmoud@zalt.me>

#
#--------------------------------------------------------------------------
# Optional Supervisord Configuration
#--------------------------------------------------------------------------
#
# Modify the ./supervisor.conf file to match your App's requirements.
# Make sure you rebuild your container with every change.
#
COPY supervisord.conf /etc/supervisord.conf

#
#--------------------------------------------------------------------------
# Optional Software's Installation
#--------------------------------------------------------------------------
#
# If you need to modify this image, feel free to do it right here.
#
	# -- Your awesome modifications go here -- #


#
#--------------------------------------------------------------------------
# Final Touch
#--------------------------------------------------------------------------
#

WORKDIR /etc/supervisor/conf.d/
