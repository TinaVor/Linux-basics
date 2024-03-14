**ПРИЛОЖЕНИЕ         Основные команды Linux** 

Общие команды Linux  ![](Aspose.Words.d7aeafcc-0795-45c8-a7de-ddece0e81a3a.001.png)![](Aspose.Words.d7aeafcc-0795-45c8-a7de-ddece0e81a3a.002.png)

- uname -a  Отобразить версию ядра Linux; 
- lsb\_release -a  Отобразить на экране информации о версии операционной системы; 

||# man hier |||Отобразить описания иерархии файловой системы; ||||
| :- | - | :- | :- | - | :- | :- | :- |
|# clear |||Осуществить очищение экрана терминала; |||||
|# wall Hello |||Осуществить отправление на терминалы других |||||
||||пользователей сообщение «Hello»; |||||
|# date |||Отобразить текущую дату и время; |||||
<table><tr><th colspan="2" rowspan="2"></th><th colspan="6"># cal -3 </th><th colspan="1"></th><th colspan="1"></th><th colspan="5">Отобразить в удобной форме предыдущий, текущи</th><th colspan="1" valign="top">й</th></tr>
<tr><td colspan="1"></td><td colspan="1"></td><td colspan="7">и последующий месяц; </td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="6" valign="top"># uptime </td><td colspan="1"></td><td colspan="7">Отобразить текущее время и работу системы без перезагрузки и выключения; </td></tr>
<tr><td colspan="1"></td><td colspan="4"># hostname </td><td colspan="1"></td><td colspan="1"></td><td colspan="6">Отобразить сетевое имя компьютера; </td><td colspan="1"></td></tr>
</table>
- whois linux.org  Отобразить информацию о доменом имени linux.org; 

<table><tr><th colspan="2"># pppconfig </th><th colspan="1"></th><th colspan="2"></th><th colspan="2">Осуществить создание и настройка Dial-Up </th><th colspan="1"></th></tr>
<tr><td colspan="4"></td><td colspan="1"></td><td colspan="1"></td><td colspan="2">соединения для выхода в Интернет по модему; </td><td colspan="1"></td></tr>
<tr><td colspan="4" valign="top"># pppoeconf </td><td colspan="1"></td><td colspan="1"></td><td colspan="3">Осуществить создание и настройка выхода в Интернет через ADSL-модем; </td></tr>
<tr><td colspan="2"># !! </td><td colspan="1"></td><td colspan="2"></td><td colspan="2">Осуществить повторение последней выполненной </td><td colspan="1"></td></tr>
<tr><td colspan="4"></td><td colspan="1"></td><td colspan="1"></td><td colspan="2">команды; </td><td colspan="1"></td></tr>
<tr><td colspan="4"># history | tail -50 </td><td colspan="1"></td><td colspan="1"></td><td colspan="3">Отобразить последние 50 набранных команд; </td></tr>
<tr><td colspan="2"># exit </td><td colspan="1"></td><td colspan="2"></td><td colspan="2">Осуществить завершение сеанса текущего </td><td colspan="1"></td></tr>
<tr><td colspan="4"></td><td colspan="1"></td><td colspan="1"></td><td colspan="2">пользователя; </td><td colspan="1"></td></tr>
<tr><td colspan="4" valign="top"># passwd </td><td colspan="1"></td><td colspan="1"></td><td colspan="3">Осуществить изменение пароля текущего пользователя; </td></tr>
<tr><td colspan="1"></td><td colspan="3"># shutdown -h now </td><td colspan="1"></td><td colspan="1"></td><td colspan="2">Осуществить выход из Linux; </td><td colspan="1"></td></tr>
<tr><td colspan="4"># poweroff </td><td colspan="1"></td><td colspan="1"></td><td colspan="3">Осуществить выход из Linux; </td></tr>
<tr><td colspan="1"></td><td colspan="3"># reboot </td><td colspan="1"></td><td colspan="1"></td><td colspan="2">Осуществить перезагрузку системы; </td><td colspan="1"></td></tr>
<tr><td colspan="4"># last reboot </td><td colspan="1"></td><td colspan="1"></td><td colspan="3">Отобразить статистику перезагрузок; </td></tr>
<tr><td colspan="1"></td><td colspan="3"># host site.ru </td><td colspan="1"></td><td colspan="1"></td><td colspan="2">Отобразить IP-адрес введенного сайта; </td><td colspan="1"></td></tr>
<tr><td colspan="4" valign="bottom">Работы с файлами и директориями </td><td colspan="1"></td><td colspan="1"></td><td colspan="3"></td></tr>
<tr><td colspan="1"></td><td colspan="3"># pwd </td><td colspan="1"></td><td colspan="1"></td><td colspan="2">Отобразить текущий путь; </td><td colspan="1"></td></tr>
<tr><td colspan="4"># ls </td><td colspan="1"></td><td colspan="1"></td><td colspan="3">Отобразить список файлов и каталогов по порядку; </td></tr>
<tr><td colspan="2"># ls -laX </td><td colspan="1"></td><td colspan="2"></td><td colspan="2">Отобразить форматированный список всех файлов </td><td colspan="1" valign="top">и</td></tr>
<tr><td colspan="4"></td><td colspan="1"></td><td colspan="1"></td><td colspan="2">директорий, включая скрытые; </td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="4"># cd </td><td colspan="1"></td><td colspan="1"></td><td colspan="3">Осуществить переход в домашнюю директорию; </td></tr>
<tr><td colspan="1"></td><td colspan="3"># cd /home </td><td colspan="1"></td><td colspan="1"></td><td colspan="2">Осуществить переход в директорию /home; </td><td colspan="1"></td></tr>
<tr><td colspan="4"># touch /home/file </td><td colspan="1"></td><td colspan="1"></td><td colspan="3">Осуществить создание пустого файла /home/file; </td></tr>
<tr><td colspan="1"></td><td colspan="3"># cat /home/file </td><td colspan="1"></td><td colspan="1"></td><td colspan="2">Отобразить содержимое файла /home/file; </td><td colspan="1"></td></tr>
<tr><td colspan="4" valign="top"># tail /var/log/file </td><td colspan="1"></td><td colspan="1"></td><td colspan="3">Отобразить окончание файла (последние строки данного файла, которые поместятся на экран). Удобно при работе с логами и большими файлами; </td></tr>
<tr><td colspan="1"></td><td colspan="3"># nano /home/file </td><td colspan="1"></td><td colspan="1"></td><td colspan="2">Осуществить редактирование файла /home/file; </td><td colspan="1"></td></tr>
<tr><td colspan="4"># gedit /home/file </td><td colspan="1"></td><td colspan="1"></td><td colspan="3">Осуществить редактирование файла /home/file; </td></tr>
<tr><td colspan="1" rowspan="2"></td><td colspan="3"># echo «the End»| sudo tee -a </td><td colspan="1" rowspan="2"></td><td colspan="1" rowspan="2"></td><td colspan="2">Осуществить добавление к концу файла «the End» в</td><td colspan="1" rowspan="2"></td></tr>
<tr><td colspan="3">/home/file </td><td colspan="2">файл /home/file; </td></tr>
<tr><td colspan="4"># cp /home/work/primer.txt /home/primer.txt </td><td colspan="1"></td><td colspan="1"></td><td colspan="3">Осуществить копирование /home/work/primer.tx в home/primer.txt; </td></tr>
<tr><td colspan="1" rowspan="2"></td><td colspan="3"># ln -s /home/work/primer.txt </td><td colspan="1" rowspan="2"></td><td colspan="1" rowspan="2"></td><td colspan="2">Осуществить создание символической ссылки </td><td colspan="1" rowspan="2"></td></tr>
<tr><td colspan="3">/home/primer </td><td colspan="2">/home/primer к файлу /home/work/primer.txt; </td></tr>
<tr><td colspan="4"># mkdir /home/work/ dir </td><td colspan="1"></td><td colspan="1"></td><td colspan="3">Осуществить создание директории с именем dir; </td></tr>
<tr><td colspan="1"></td><td colspan="3"># rmdir /home/work/ dir </td><td colspan="1"></td><td colspan="1"></td><td colspan="2">Осуществить удаление директории с именем dir; </td><td colspan="1"></td></tr>
</table>
- rm -rf /home/work/ dir  Осуществить удаление директории с вложенными фалами; 

<table><tr><th colspan="1"></th><th colspan="2"># cp -la /dir1 /dir2 </th><th colspan="1"></th><th colspan="1"></th><th colspan="2">Осуществить копирование директорий; </th><th colspan="1"></th></tr>
<tr><td colspan="3"># mv /dir1 /dir2 </td><td colspan="1"></td><td colspan="1"></td><td colspan="3">Осуществить переименование директории; </td></tr>
<tr><td colspan="2"># du -sh /home/work/ </td><td colspan="1"></td><td colspan="3">Отобразить на экран размер заданной директории. </td></tr>
<tr><td colspan="3" rowspan="2"></td><td colspan="1" rowspan="2"></td><td colspan="1" rowspan="2" valign="top"></td><td colspan="2">Можно использовать для определения размера </td><td colspan="1" rowspan="2" valign="top"></td></tr>
<tr><td colspan="2">файлов; </td></tr>
<tr><td colspan="3"># locate primer </td><td colspan="1"></td><td colspan="1"></td><td colspan="3">Осуществить поиск всех файлов с именем primer; </td></tr>
<tr><td colspan="2"># [sudo] chmod 0777 /home/ </td><td colspan="1"></td><td colspan="3">Осуществить изменение прав доступа к директории</td></tr>
<tr><td colspan="3" rowspan="2"></td><td colspan="1" rowspan="2"></td><td colspan="1" rowspan="2" valign="top"></td><td colspan="2">только для /home. 0777 – разрешение на </td><td colspan="1" rowspan="2" valign="top"></td></tr>
<tr><td colspan="2">чтение/запись/исполнение для всех групп; </td></tr>
</table>
- [sudo] chmod -R 0777 /home/  Осуществить рекурсивное изменение прав доступа к директории /home. 777 – разрешение на чтение/запись/исполнение для всех групп. Все вложенные директории и файлы будут иметь права 0777; 

<table><tr><th colspan="1" rowspan="2"></th><th colspan="1"># [sudo] chown work:test </th><th colspan="1" rowspan="2"></th><th colspan="1" rowspan="2"></th><th colspan="1">Осуществить изменение владельца и группы тольк</th><th colspan="1" rowspan="2" valign="top">о </th></tr>
<tr><td colspan="1">/home/primer.txt </td><td colspan="1">для файла /home/primer.txt; </td></tr>
<tr><td colspan="2"># [sudo] chown -R work /home/ Работа с архивами </td><td colspan="1"></td><td colspan="1"></td><td colspan="2" valign="top">Осуществить изменение владельца для всего содержимого директории /home; </td></tr>
</table>

- tar cf primer.tar /home/primer.txt  Осуществить создание tar-архива с именем primer.tar ![](Aspose.Words.d7aeafcc-0795-45c8-a7de-ddece0e81a3a.003.png)содержащий /home/primer.txt; 
- tar czf primer.tar.gz  Осуществить создание tar-архива с сжатием Gzip по /home/primer.txt  имени primer.tar.gz; 

<table><tr><th colspan="1" rowspan="2"></th><th colspan="1"># tar cjf primer.tar.bz2 </th><th colspan="1" rowspan="2"></th><th colspan="1" rowspan="2"></th><th colspan="1">Осуществить  создание tar-архива с сжатием Bzip2 </th><th colspan="1" rowspan="2"></th></tr>
<tr><td colspan="1">/home/primer.txt </td><td colspan="1">по имени primer.tar.bz; </td></tr>
<tr><td colspan="2" valign="top"># tar xf primer.tar </td><td colspan="1"></td><td colspan="1"></td><td colspan="2">Осуществить распаковку архива primer.tar в текущую папку; </td></tr>
<tr><td colspan="1"></td><td colspan="1"># tar xzf primer.tar.gz </td><td colspan="1"></td><td colspan="1"></td><td colspan="1">Осуществить распаковку tar-архива с Gzip; </td><td colspan="1"></td></tr>
<tr><td colspan="2"># tar xjf primer.tar.bz </td><td colspan="1"></td><td colspan="1"></td><td colspan="2">Осуществить распаковку tar-архива с Bzip2; </td></tr>
</table>

Установка программ (RPM-дистрибутивы) ![](Aspose.Words.d7aeafcc-0795-45c8-a7de-ddece0e81a3a.004.png)![](Aspose.Words.d7aeafcc-0795-45c8-a7de-ddece0e81a3a.005.png)

- rpm -qa  Отобразить список установленных пакетов RPM в системе; 
- [sudo] rpm -i pkgname.rpm  Осуществить установку RPM пакета pkgname.rpm; 

||# [sudo] rpm -e pkgname |||Осуществить удаление RPM пакета pkgname; ||
| :- | - | :- | :- | - | :- |
|# [sudo] dpkg -i \*.rpm |||Осуществить установку всех пакетов в директории; |||

Установка программ (DEB-дистрибутивы) ![](Aspose.Words.d7aeafcc-0795-45c8-a7de-ddece0e81a3a.006.png)![](Aspose.Words.d7aeafcc-0795-45c8-a7de-ddece0e81a3a.007.png)

- dpkg -l |more  Отрбразить список установленных пакетов DEB в системе; 
- apt-cache search pack  Осуществить поиск в индексах наличее доступного пакета и выводит на экран краткую информацию о пакете pack (очень полезная команда для поиска и установки программ из консоли); ![](Aspose.Words.d7aeafcc-0795-45c8-a7de-ddece0e81a3a.008.png)![](Aspose.Words.d7aeafcc-0795-45c8-a7de-ddece0e81a3a.009.png)
- apt-cache showpkg pack  Отрбразить полную информация о пакете pack; 
- [sudo] apt-get update  Осуществить обновление списка доступных пакетов из Internet; 

<table><tr><th colspan="1" rowspan="2"></th><th colspan="6"># [sudo] apt-get upgrade </th><th colspan="1"></th><th colspan="1"></th><th colspan="8">Осуществить обновление доступной версии </th><th colspan="1"></th></tr>
<tr><td colspan="1"></td><td colspan="1"></td><td colspan="10">установленных пакетов в системе; </td><td colspan="1"></td></tr>
<tr><td colspan="8"># [sudo] apt-get install pkgname </td><td colspan="1"></td><td colspan="9">Осуществить установку DEB пакета pkgname; </td></tr>
<tr><td colspan="1"></td><td colspan="6"># [sudo] apt-get remove pkgname </td><td colspan="1"></td><td colspan="1"></td><td colspan="8">Осуществить удаление DEB пакета pkgname; </td><td colspan="1"></td></tr>
<tr><td colspan="8"># [sudo] dpkg -i *.deb Мониторинг работы и просмотр логов </td><td colspan="1"></td><td colspan="9" valign="top">Осуществить  установку всех пакетов в директории; </td></tr>
<tr><td colspan="4" rowspan="2"></td><td colspan="6"># top </td><td colspan="1"></td><td colspan="1"></td><td colspan="7">Отобразить информацию в реальном времени о </td><td colspan="1"></td></tr>
<tr><td colspan="1"></td><td colspan="1"></td><td colspan="9">загруженных процессах, потребление ОЗУ; </td><td colspan="1"></td></tr>
</table>
- dmesg  Отобразить log-файл загрузки ОС и нахождения новых устройств; 

<table><tr><th colspan="1" rowspan="3"></th><th colspan="5"># mpstat 1 </th><th colspan="1"></th><th colspan="4">Отобразить расширенную статистику потребления </th></tr>
<tr><td colspan="1" rowspan="2"></td><td colspan="1" rowspan="2" valign="top"></td><td colspan="5">ресурсов системы в процентах (для некоторых </td><td colspan="1" rowspan="2" valign="top">t)</td></tr>
<tr><td colspan="5">дистрибутивов необходима установка пакета syssta</td></tr>
<tr><td colspan="4" valign="top"># vmstat 2 </td><td colspan="1"></td><td colspan="5">Отобразить расширенную статистику по использованию виртуальной памяти; </td></tr>
<tr><td colspan="4" rowspan="2"></td><td colspan="6"># iostat 2 </td><td colspan="1"></td><td colspan="1"></td><td colspan="5">Отобразить расширенную статистику прерываний </td><td colspan="1" valign="top">п</td></tr>
<tr><td colspan="1"></td><td colspan="1"></td><td colspan="7">устройствам; </td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="8" valign="bottom">Информация об устройствах </td><td colspan="1"></td><td colspan="7"></td></tr>
<tr><td colspan="1" rowspan="2"></td><td colspan="6"># lsdev </td><td colspan="1"></td><td colspan="1"></td><td colspan="6">Отобразить информацию об уже установленных </td><td colspan="1"></td></tr>
<tr><td colspan="1"></td><td colspan="1"></td><td colspan="9">устройствах; </td><td colspan="1"></td></tr>
<tr><td colspan="8"># cat /proc/cpuinfo </td><td colspan="1"></td><td colspan="7">Отобразить полную информацию о модели </td></tr>
</table>

процессора (частота, поддерживаемые инструкции и т.д.); 

<table><tr><th colspan="2" rowspan="4"></th><th colspan="8"># cat /proc/meminfo </th><th colspan="1"></th><th colspan="8">Отобразить расширенную информацию о </th></tr>
<tr><td colspan="1" rowspan="3"></td><td colspan="9">занимаемой оперативной памяти (MemTotal, </td></tr>
<tr><td colspan="1" rowspan="2" valign="top"></td><td colspan="9">MemFree, Buffers, Cached, SwapCached,HighTotal, </td><td colspan="1" rowspan="2" valign="top"></td></tr>
<tr><td colspan="9">HighFree, LowTotal и т. д.); </td></tr>
<tr><td colspan="8"># grep SwapTotal /proc/meminfo </td><td colspan="1"></td><td colspan="9">Отобразить размер раздела выделенного под swap; </td></tr>
<tr><td colspan="1"></td><td colspan="6"># watch -n1 'cat /proc/interrupts' </td><td colspan="1"></td><td colspan="1"></td><td colspan="8">Отобразить информацию о прерываниях; </td><td colspan="1"></td></tr>
<tr><td colspan="7" valign="top"># free -m </td><td colspan="1"></td><td colspan="1"></td><td colspan="9">Отобразить информацию о используемой и свободной ОЗУ и Swap-файле (-m указывает, что отображать нужно в Мб); </td></tr>
<tr><td colspan="1"></td><td colspan="6"># lshal </td><td colspan="1"></td><td colspan="1"></td><td colspan="8">Отобразить список всех устройств и их параметров</td><td colspan="1">; </td></tr>
<tr><td colspan="7" valign="top"># cat /proc/devices </td><td colspan="1"></td><td colspan="1"></td><td colspan="9">Отобразить все устройства в системе (названия взяты из директории /proc/devices); </td></tr>
<tr><td colspan="1"></td><td colspan="6"># lspci -tv </td><td colspan="1"></td><td colspan="1"></td><td colspan="8">Отобразить обнаруженные PCI-устройства; </td><td colspan="1"></td></tr>
<tr><td colspan="7"># lsusb -tv </td><td colspan="1"></td><td colspan="1"></td><td colspan="9">Отобразить обнаруженные USB-устройства; </td></tr>
<tr><td colspan="5"># [sudo] dmidecode </td><td colspan="1"></td><td colspan="2"></td><td colspan="8">Отобразить информацию о версии BIOS </td><td colspan="1"></td></tr>
<tr><td colspan="7"></td><td colspan="1"></td><td colspan="1"></td><td colspan="8">компьютера; </td><td colspan="1"></td></tr>
<tr><td colspan="7" valign="top"># gtf 1024 768 75 </td><td colspan="1"></td><td colspan="1"></td><td colspan="9" valign="top">Отобразить строку ModeLine для Вашего монитора на параметрах экрана 1024x768x75Hz; </td></tr>
<tr><td colspan="7" valign="bottom">Жесткие диски и файловая система </td><td colspan="1"></td><td colspan="1"></td><td colspan="9"></td></tr>
<tr><td colspan="5"># fdisk -l </td><td colspan="1"></td><td colspan="2"></td><td colspan="8">Отобразить информацию о всех подключенных </td><td colspan="1"></td></tr>
<tr><td colspan="7"></td><td colspan="1"></td><td colspan="1"></td><td colspan="8">жестких и сменных дисках; </td><td colspan="1"></td></tr>
<tr><td colspan="7" valign="top"># [sudo] hdparm -I /dev/sda </td><td colspan="1"></td><td colspan="1"></td><td colspan="9">Отобразить  полную информацию о IDE/ATA жестких дисках; </td></tr>
<tr><td colspan="5"># smartctl -a /dev/sda1 </td><td colspan="1"></td><td colspan="9">Отобразить SMART-информацию о разделе </td></tr>
<tr><td colspan="7" rowspan="2"></td><td colspan="1" rowspan="2"></td><td colspan="1" rowspan="2" valign="top"></td><td colspan="8">жесткого диска /dev/sda1 (необходима установка </td><td colspan="1" rowspan="2" valign="top"></td></tr>
<tr><td colspan="8">пакета smartmontools); </td></tr>
<tr><td colspan="7" valign="top"># [sudo] blkid </td><td colspan="1"></td><td colspan="1"></td><td colspan="9">Отобразить UUID всех доступных накопителей информации в системе; </td></tr>
<tr><td colspan="1"></td><td colspan="6"># [sudo] hdparm -tT /dev/sda </td><td colspan="1"></td><td colspan="1"></td><td colspan="8">Отобразить производительность жесткого диска; </td><td colspan="1"></td></tr>
<tr><td colspan="7" valign="top"># mount | column -t </td><td colspan="1"></td><td colspan="1"></td><td colspan="9">Отобразить полную информацию о примонтированных устройсвах; </td></tr>
<tr><td colspan="5"># cat /proc/partitions </td><td colspan="1"></td><td colspan="2"></td><td colspan="8">Отобразить только примонтированные разделы </td><td colspan="1"></td></tr>
<tr><td colspan="7"></td><td colspan="1"></td><td colspan="1"></td><td colspan="8">жесткого диска; </td><td colspan="1"></td></tr>
<tr><td colspan="7"># df </td><td colspan="1"></td><td colspan="1"></td><td colspan="9">Отобразить свободное место на разделах; </td></tr>
<tr><td colspan="5"># [sudo] mount /dev/sda1 /mnt </td><td colspan="1"></td><td colspan="2"></td><td colspan="8">Осуществить монтирование раздел /dev/sda1 к точк</td><td colspan="1" valign="top">е </td></tr>
<tr><td colspan="7"></td><td colspan="1"></td><td colspan="1"></td><td colspan="8">монтирования /mnt; </td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="7"># [sudo] mount -t auto /dev/cdrom /mnt/cdrom </td><td colspan="1"></td><td colspan="1"></td><td colspan="9">Осуществить монтирование большинство CD- ROM`ов; </td></tr>
<tr><td colspan="1" rowspan="2"></td><td colspan="6"># [sudo] mount /dev/hdc -t iso9660</td><td colspan="1" rowspan="2"></td><td colspan="1" rowspan="2"></td><td colspan="8">Осуществить монтирование IDE CD-ROM; </td></tr>
<tr><td colspan="6">-r /cdrom </td><td colspan="9"></td></tr>
</table>
- [sudo] mount /dev/scd0 -t iso9660 Осуществить монтирование SCSI CD-ROM; -r /cdrom 

<table><tr><th colspan="2"># [sudo] mount -t smbfs -o </th><th colspan="1"></th><th colspan="4">Осуществить монтирование сетевых ресурсов </th><th colspan="1"></th></tr>
<tr><td colspan="1" rowspan="2" valign="top"></td><td colspan="2">username=vasja,password=pupkin </td><td colspan="1" rowspan="2" valign="top"></td><td colspan="1" rowspan="2"></td><td colspan="4">(SMB); </td><td colspan="1"></td></tr>
<tr><td colspan="2">//pup/Video </td><td colspan="1"></td></tr>
<tr><td colspan="3"># [sudo] mount -t iso9660 -o loop /home/file.iso /home/iso </td><td colspan="1"></td><td colspan="6" valign="top">Осуществить монтирование ISO-образов; </td></tr>
<tr><td colspan="1" rowspan="3"></td><td colspan="3"># [sudo] mount /dev/sdb1 -t vfat -</td><td colspan="1" rowspan="2" valign="top">o </td><td colspan="4">Осуществить монтирование раздел с файловой </td></tr>
<tr><td colspan="3">rw /mnt </td><td colspan="1" valign="top"></td><td colspan="4">системой FAT 16/32 (к примеру USB-накопитель) к</td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="4">точки монтирования /mnt с возможностью записи; </td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="5"><p># [sudo] umount /mnt </p><p>Настройка сети </p></td><td colspan="1"></td><td colspan="5" valign="top">Осуществить демонтирование раздел от точки монтирования /mnt; </td></tr>
<tr><td colspan="1"></td><td colspan="3"># ifconfig </td><td colspan="1"></td><td colspan="1"></td><td colspan="4">Отобразить параметры всех сетевых интерфейсов; </td><td colspan="1"></td></tr>
<tr><td colspan="5"># ifconfig eth0 </td><td colspan="1"></td><td colspan="5">Отобразить параметры сетевого интерфейса eth0; </td></tr>
<tr><td colspan="2"># [sudo] ethtool eth0 </td><td colspan="1"></td><td colspan="7">Отобразить состояние сетевого интерфейса. Коман</td></tr>
<tr><td colspan="4" rowspan="3"></td><td colspan="1" rowspan="3"></td><td colspan="6">ethtool применяется только для проводных </td></tr>
<tr><td colspan="3" rowspan="2" valign="top"></td><td colspan="5">подключений, не работает с беспроводными </td><td colspan="1" rowspan="2" valign="top"></td></tr>
<tr><td colspan="5">интерфейсами; </td></tr>
<tr><td colspan="4" valign="top"># [sudo] ethtool -s eth0 speed 100 duplex full autoneg off </td><td colspan="1"></td><td colspan="3"></td><td colspan="6">Осуществить принудительное задание скорости сетевому интерфейсу 100Mbit и режим Full duplex и отключить автоматическое определение; </td></tr>
<tr><td colspan="1" rowspan="2"></td><td colspan="3"># ifconfig eth0 192.168.50.254 </td><td colspan="1" rowspan="2"></td><td colspan="3" rowspan="2"></td><td colspan="5">Осуществить задание основного IP-адреса сетевом</td><td colspan="1" rowspan="2" valign="top">у </td></tr>
<tr><td colspan="3">netmask 255.255.255.0 </td><td colspan="5">интерфейсу eth0; </td></tr>
<tr><td colspan="4"># ip addr add 192.168.50.254/24 dev eth0 </td><td colspan="1"></td><td colspan="3"></td><td colspan="6">Осуществить задание основного IP-адреса сетевому интерфейсу eth0; </td></tr>
<tr><td colspan="1" rowspan="2"></td><td colspan="3"># ifconfig eth0:0 192.168.51.254 </td><td colspan="2" rowspan="2"></td><td colspan="2" rowspan="2"></td><td colspan="5">Осуществить задание дополнительного IP-адреса </td><td colspan="1" rowspan="2"></td></tr>
<tr><td colspan="3">netmask 255.255.255.0 </td><td colspan="5">сетевому интерфейсу eth0; </td></tr>
<tr><td colspan="4"># ip addr add 192.168.51.254/24 dev eth0 label eth0:1 </td><td colspan="1"></td><td colspan="3"></td><td colspan="6">Осуществить задание дополнительного IP адреса сетевому интерфейсу eth0; </td></tr>
<tr><td colspan="1"></td><td colspan="3"># [sudo] ifconfig eth0 up </td><td colspan="1"></td><td colspan="3"></td><td colspan="5">Осуществить запуск сетевого интерфейса eth0; </td><td colspan="1"></td></tr>
<tr><td colspan="4"># [sudo] ifconfig eth0 down </td><td colspan="1"></td><td colspan="3"></td><td colspan="6">Осуществить отключение сетевого интерфейса eth0; </td></tr>
<tr><td colspan="1" rowspan="2"></td><td colspan="3"># ifconfig eth0 hw ether </td><td colspan="1" rowspan="2"></td><td colspan="3" rowspan="2"></td><td colspan="5">Осуществить смену MAC адреса; </td></tr>
<tr><td colspan="3">00:01:02:03:04:05 </td><td colspan="6"></td></tr>
<tr><td colspan="4"># [sudo] /etc/init.d/dhcpd restart </td><td colspan="1"></td><td colspan="3"></td><td colspan="6">Осуществить перезагрузка DHCP клиента; </td></tr>
<tr><td colspan="2"># ping 192.168.0.2 </td><td colspan="1"></td><td colspan="2"></td><td colspan="6">Осуществить проверку сетевого соединения. </td><td colspan="1"></td></tr>
<tr><td colspan="4"></td><td colspan="1"></td><td colspan="3"></td><td colspan="5">Проверяется доступность IP адрес 192.168.0.2; </td><td colspan="1"></td></tr>
<tr><td colspan="4"># route -n </td><td colspan="1"></td><td colspan="3"></td><td colspan="6">Отобразить на экране таблицу маршрутизации; </td></tr>
<tr><td colspan="1"></td><td colspan="3"># netstat -rn </td><td colspan="1"></td><td colspan="3"></td><td colspan="5">Отобразить на экране таблицу маршрутизации; </td><td colspan="1"></td></tr>
<tr><td colspan="4"># netstat -an | grep LISTEN </td><td colspan="1"></td><td colspan="3"></td><td colspan="6">Отобразить список всех открытых портов; </td></tr>
<tr><td colspan="2"># lsof -i </td><td colspan="1"></td><td colspan="2"></td><td colspan="6">Отобразить список всех открытых портов в сеть </td><td colspan="1"></td></tr>
<tr><td colspan="4"></td><td colspan="1"></td><td colspan="3"></td><td colspan="5">Internet; </td><td colspan="1"></td></tr>
<tr><td colspan="4"># [sudo] netstat -tup </td><td colspan="1"></td><td colspan="3"></td><td colspan="6">Отобразить активные соединения с интернетом; </td></tr>
<tr><td colspan="1"></td><td colspan="3"># socklist </td><td colspan="1"></td><td colspan="3"></td><td colspan="5">Отобразить  все открытые сокеты; </td><td colspan="1"></td></tr>
</table>
- [sudo] netstat -anp --udp --tcp |  Отобразить список приложений, которые открывают grep LISTEN  порты; 

<table><tr><th colspan="1"></th><th colspan="1"># [sudo] iptables -L -n -v </th><th colspan="1"></th><th colspan="1"></th><th colspan="1">Отобразить статус firewall (статус iptables); </th><th colspan="1"></th></tr>
<tr><td colspan="2"># [sudo] iptables -P INPUT ACCEPT </td><td colspan="1"></td><td colspan="1"></td><td colspan="2" valign="top">Осуществить открытие доступа ко всем портам; </td></tr>
<tr><td colspan="1" rowspan="2"></td><td colspan="1"># [sudo] iptables -P FORWARD </td><td colspan="1" rowspan="2"></td><td colspan="1" rowspan="2"></td><td colspan="1">Осуществить открытие доступа ко всем портам; </td></tr>
<tr><td colspan="1">ACCEPT </td><td colspan="2"></td></tr>
<tr><td colspan="2"># [sudo] iptables -P OUTPUT ACCEPT </td><td colspan="1"></td><td colspan="1"></td><td colspan="2" valign="top">Осуществить открытие доступа ко всем портам; </td></tr>
<tr><td colspan="1"></td><td colspan="1"># [sudo] iptables -X </td><td colspan="1"></td><td colspan="1"></td><td colspan="1">Осуществить удаление всей цепочки; </td><td colspan="1"></td></tr>
</table>
- [sudo] iptables -t nat -A  Осуществить включение NAT на интерфейсе eth0; POSTROUTING -o eth0 -j 

  MASQUERADE 

<table><tr><th colspan="2"># [sudo] iptables -t nat -A </th><th colspan="1" rowspan="2"></th><th colspan="4">Осуществить перенаправление порта 20022, которы</th><th colspan="1" rowspan="2"></th></tr>
<tr><td colspan="2">PREROUTING -p tcp -d </td><td colspan="4">использется для ssh; </td></tr>
<tr><td colspan="1" rowspan="2" valign="top"></td><td colspan="2">78\.31.70.238 --dport 20022 -j </td><td colspan="1" rowspan="2" valign="top"></td><td colspan="1" rowspan="2"></td><td colspan="1" rowspan="2"></td></tr>
<tr><td colspan="2">DNAT --to 192.168.16.44:22 </td></tr>
<tr><td colspan="3"><p># [sudo] iptables -t nat -A PREROUTING -p tcp -d </p><p>78\.31.70.238 --dport 993:995 -j </p></td><td colspan="1"></td><td colspan="5" valign="top">Осуществить  перенаправление диапазона портов 993-995; </td></tr>
</table>

DNAT --to 192.168.16.254:993-995 

||# iptables -L -t nat |||Осуществить проверку статуса NAT; ||
| :- | - | :- | :- | - | :- |
|Создание и запись ISO образов ||||||
||# cdrecord -scanbus |||Отобразить все доступные CD-ROM; ||
- dd if=/dev/hdc of=/tmp/mycd.iso  Осуществить создание ISO образов с диска CD- bs=2048 conv=notrunc  ROM; 

  Пользователи и группы  ![](Aspose.Words.d7aeafcc-0795-45c8-a7de-ddece0e81a3a.010.png)![](Aspose.Words.d7aeafcc-0795-45c8-a7de-ddece0e81a3a.011.png)

- id  Отобразить сводную информацию по текущему пользователю (логин, UID, GID, группы); 
- finger work  Отобразить информацию о пользователе work; 

<table><tr><th colspan="1" rowspan="2"></th><th colspan="2"># last </th><th colspan="1"></th><th colspan="1"></th><th colspan="3">Отобразить список последних зарегистрированных </th><th colspan="1"></th></tr>
<tr><td colspan="1"></td><td colspan="1"></td><td colspan="3">пользователей; </td><td colspan="1"></td></tr>
<tr><td colspan="4" valign="top"># who </td><td colspan="1"></td><td colspan="4">Отобразить имя текущего пользователя и время входа; </td></tr>
<tr><td colspan="1"></td><td colspan="2"># adduser work </td><td colspan="1"></td><td colspan="2"></td><td colspan="3">Осуществить добавление нового пользователя work</td><td colspan="1">;</td></tr>
<tr><td colspan="3"># groupadd test </td><td colspan="1"></td><td colspan="2"></td><td colspan="4">Осуществить добавление группы test; </td></tr>
<tr><td colspan="2"># usermod -a -G test work </td><td colspan="1"></td><td colspan="1"></td><td colspan="3">Осуществить добавление пользователя work в </td><td colspan="1"></td></tr>
<tr><td colspan="3"></td><td colspan="1"></td><td colspan="2"></td><td colspan="3">группу test; </td><td colspan="1"></td></tr>
<tr><td colspan="3" valign="top"># groupmod -A work test </td><td colspan="1"></td><td colspan="2"></td><td colspan="4">Осуществить добавление пользователя work в группу test; </td></tr>
<tr><td colspan="1"></td><td colspan="2"># userdel work </td><td colspan="1"></td><td colspan="2"></td><td colspan="3">Осуществить удаление пользователя work; </td><td colspan="1"></td></tr>
<tr><td colspan="3" valign="top"># groupdel test </td><td colspan="1"></td><td colspan="2"></td><td colspan="4" valign="top">Осуществить удаление группы test; </td></tr>
<tr><td colspan="3" valign="bottom">Печать на принтере </td><td colspan="1"></td><td colspan="2"></td><td colspan="4"></td></tr>
<tr><td colspan="2"># export PRINTER=lbp2900 </td><td colspan="1"></td><td colspan="1"></td><td colspan="3">Осуществить выбор принтера по-умолчанию. В </td><td colspan="1"></td></tr>
<tr><td colspan="3"></td><td colspan="1"></td><td colspan="2"></td><td colspan="3">примере выбран принтер Canon LBP-2900; </td><td colspan="1"></td></tr>
<tr><td colspan="3" valign="top"># lpr #2 name.txt </td><td colspan="1"></td><td colspan="2"></td><td colspan="4">Осуществить печать на принтере Canon LBP-2900 две копии файла name.txt; </td></tr>
<tr><td colspan="2"># lprm - </td><td colspan="1"></td><td colspan="1"></td><td colspan="3">Осуществить удаление всех задач с принтера по </td><td colspan="1"></td></tr>
<tr><td colspan="3"></td><td colspan="1"></td><td colspan="2"></td><td colspan="3">умолчанию. </td><td colspan="1"></td></tr>
<tr><td colspan="3"></td><td colspan="1"></td><td colspan="2"></td><td colspan="4"></td></tr>
</table>

