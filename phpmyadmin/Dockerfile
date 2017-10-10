FROM phpmyadmin/phpmyadmin

MAINTAINER Bo-Yi Wu <appleboy.tw@gmail.com>

# Add volume for sessions to allow session persistence
VOLUME /sessions
VOLUME ./config.user.inc.php:/etc/phpmyadmin/config.user.inc.php

# We expose phpMyAdmin on port 80
EXPOSE 80
