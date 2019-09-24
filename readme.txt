https://demo.bigbluebutton.org/gl/neo-cuh-7yv

https://hub.docker.com/_/odoo

docker exec -ti -u postgres db bash

psql -l

psql -U odoo -l

chmod -R 777 /srv/odoo

docker run -v /srv/odoo/addons:/mnt/extra-addons -v /srv/odoo/config:/etc/odoo -p 8069:8069 --name odoo --link db:db -t odoo

http://localhost:8069/web/database/manager



git config --global user.email "sbogdanovsky@gmail.com"
git config --global user.name "Vyacheslav"
git config --global http.proxy http://student_iitk:student_iitk@172.17.106.1:3128                 
git clone https://github.com/sbogdanovsky/web
git push -u origin master


visual Studio Code
git config --global http.proxy http://student_iitk:student_iitk@172.17.106.1:3128
git config --global user.email "sbogdanovsky@gmail.com"
git config --global user.name "Vyacheslav"


New Step

su -
toor

systemctl start docker

mkdir serverlab
cd serverlab/

mkdir www
mkdir mysql
mkdir logs
mkdir hosts
mkdir images

cd images

mkdir php

cd php

echo '' > Dockerfile
cat /etc/resolv.conf 

export http_proxy=http://student_iitk:student_iitk@172.17.106.1:3128

urpmi docker-compose
nameserver 172.17.106.1 (В файле resolv.conf)

docker-compose up -d

Запуск докер контейнера с веб сервером 
//----------------------------------
su -
git config --global user.email "sbogdanovsky@gmail.com"
git config --global user.name "Vyacheslav"
git config --global http.proxy http://student_iitk:student_iitk@172.17.106.1:3128                 
git clone https://github.com/sbogdanovsky/labweb
echo "nameserver 172.17.106.1" >> /etc/resolv.conf
cd labweb/
systemctl start docker
export http_proxy=http://student_iitk:student_iitk@172.17.106.1:3128
urpmi docker-compose

//------------------------------
Отправка изменений на сервер 
git add *
git commit -m "Second Comm"
git push -u origin master.

