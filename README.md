# sf__wordpress_experimental
Добрый день!

Для запуска контейнеров нужно сделать следующее:

git clone https://github.com/UnderT0p/sf__wordpress_experimental - склонировать себе репозиторий

cd sf__wordpress_experimental - перейти в него

********************************************************************************
Установить Docker and Docker Compose, если не установлены, одним из скриптов:

bash install_dc_deb.sh - для debian

bash install_dc_ubu.sh - для ubuntu

bash install_dc_cent.sh - для centos
********************************************************************************

bash  wp_up.sh  - запустить скрипт, который развернет два контейнера

localhost:8000 - ввести в браузер и убедиться что работает.
