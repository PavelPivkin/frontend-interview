Frontend developer
========

Проект позволяет тестировать в докер-контейнере шаблоны twig.

--- 

Для работы с проектом 

1. Установите на свой компьютер [Docker](https://www.docker.com/community-edition) или [Docker Toolbox](https://docs.docker.com/toolbox/overview/)

2. Запустите docker. Для этого надо выполнить команду в этой папке
   
   ```bash
   docker-compose up 
   ```
  
3. Теперь проект доступен по адресу http://localhost:4001  
   > На Windows 7 используйте Docker Machine IP вместо localhost. 
     Например, http://192.168.99.100:4001/. 
     Чтобы узнать свой IP-адрес используйте команду `docker-machine ip`.

4. Редактируйте файлы, которые находятся в папке `designer`