Смотрим  тип и версию ядра с помощью команды uname -r

На сайте http://kernel.ubuntu.com/~kernel-ppa/mainline/ находим последнюю версию ядра и скачиваем 4 файла с помощью команды wget
![Снимок экрана 2023-09-07 202806](https://github.com/DronZap/linux_admin/assets/145288949/823be95e-a4df-447b-a5b7-d535062e7251)

![дз1 3](https://github.com/DronZap/linux_admin/assets/145288949/489e2d7b-4390-415d-b562-653e55c100ca)

![дз1 4](https://github.com/DronZap/linux_admin/assets/145288949/2178f29c-a6eb-4a5a-bbb9-86f80b8b3506)
С помощью команды sudo dpkg -i *.deb устанавливаем скачанные файлы
![Снимок экрана 2023-09-07 203819](https://github.com/DronZap/linux_admin/assets/145288949/c96c04f9-c5ed-43fe-b1ec-fd29806769f4)
Перезагружаем систему и проверяем снова версию ядра

![Снимок экрана 2023-09-07 204355](https://github.com/DronZap/linux_admin/assets/145288949/f5d43f17-dbb1-4951-a57b-93cc2547efab)
