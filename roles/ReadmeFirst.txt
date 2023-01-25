1)Подключиться к серверу A по ssh
2)Скачать репозиторий
3)В файле hosts.txt указать релевантные данные
4)Запустить bash скрипт BashScript.sh
5)Затрачееное время на вылолнение автоматизированной части выведется на экран после завершения скрипта в секундах
________________
||||||||||||||||
\/\/\/\/\/\/\/\/

ssh root@<ip_A>
mkdir testcase
cd testcase
git clone https://github.com/BulatRakhimov/Ansible.git
cd roles
chmod 777 BashScript.sh
./BashScript.sh
