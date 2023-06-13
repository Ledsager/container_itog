# Задание
1) Используя команду cat в терминале операционной системы Linux, создать два файла Домашние животные (заполнив файл собаками, кошками, хомяками) 
и Вьючные животными заполнив файл Лошадьми, верблюдами и ослы), а затем объединить их. Просмотреть содержимое созданного файла. Переименовать файл, дав ему новое имя (Друзья человека).
2) Создать директорию, переместить файл туда.
3) Подключить дополнительный репозиторий MySQL. Установить любой пакет из этого репозитория.
4) Установить и удалить deb-пакет с помощью dpkg.
5) Выложить историю команд в терминале ubuntu

```
  440  mkdir gbatestat
  441  cd gbatestat/
  442  cat "Домашние животные"
  443  cat > "Домашние животные"
  444  cat > "Вьючные животные"
  445  cat "Домашние животные" "Вьючные животные" > test
  446  cat test
  447  mv test "Друзья человека"
  448  mkdir new
  449  mv "Друзья человека" new/
  450  wget https://dev.mysql.com/get/mysql-apt-config_0.8.25-1_all.deb
  451  sudo dpkg -i mysql-apt-config_0.8.25-1_all.deb
  452  sudo apt update
  453  sudo apt install mysql-server mysql-client
  454  mysql
  455  sudo mysql
  456  sudo  mysql -u root -p
  457  wget https://www.webmin.com/download/deb/webmin-current.deb
  458  ls
  459  sudo dpkg -i webmin-current.deb
  460  ls
  461  sudo apt -f install
  462  sudo dpkg -r webmin
  463  history
  ```
  6) Нарисовать диаграмму, в которой есть класс родительский класс, домашние животные и вьючные животные, в составы которых в случае домашних
животных войдут классы: собаки, кошки, хомяки, а в класс вьючные животные войдут: Лошади, верблюды и ослы).

![class](https://github.com/Ledsager/container_homework3/blob/main/animals-class.png)




