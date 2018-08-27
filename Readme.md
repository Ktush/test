# Способ установки

- cp certificates_controller.rb /var/www/top52/app/controllers

- rsync -a certificates /var/www/top52/app/views

- cp routes.rb /var/www/top52/config

- rsync -a cert_create /var/www/top52/public

- Запустить