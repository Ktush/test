# Способ установки

- cp certificates_controller.rb /var/www/top52/app/controllers

- rsync -a certificates /var/www/top52/app/views

- cp routes.rb /var/www/top52/config

- cp _application.html.slim /var/www/top52/engines/face/app/views/layouts/face

- rsync -a cert_create /var/www/top52/public

- Запустить