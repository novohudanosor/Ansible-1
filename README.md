# Ansible-1
* mkdir Ansible
* Из директории Ansible запускаем Vagrantfile - vagrant up  - по VPN поднимаем хост
* inventory файл ./staging/staging/hosts - данные для файла hosts получаем после команды vagrant ssh-config (vagrant ssh-config.png)
* ./templates/nginx.conf.j2   - модуль, который будет копировать этот шаблон на хост
* ansible-playbook nginx.yml  
* vagrant ssh
* curl  http://10.0.2.15:8080 - проверка работы. curl nginx.png
