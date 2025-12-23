# DevOpsLab_04
Создали клон предыдущей виртуальной машины

<img width="1003" height="608" alt="image" src="https://github.com/user-attachments/assets/83254cbf-1b12-4848-83b3-bf41dbd636b7" />

Настройка общей сети и проброс портов

<img width="1920" height="1017" alt="image" src="https://github.com/user-attachments/assets/347a4b7c-dced-4eac-a3ae-24da672e5f36" />

<img width="1340" height="758" alt="image" src="https://github.com/user-attachments/assets/bc32c402-f7f6-41a3-8e3e-35890dd63577" />

Настройка сети внутри виртуальной машины – переключение с DHCP на статику (optional)

<img width="958" height="1017" alt="image" src="https://github.com/user-attachments/assets/b02cfae3-3d6a-49e8-bba0-1ea9c000d504" />
<img width="957" height="1016" alt="image" src="https://github.com/user-attachments/assets/801291dd-36e3-41aa-82ef-0a52faa0edff" />

Проверка применения настроек.
На виртуальной машине клоне лучше видно, что появился ip адрес с дополнительной фразой:
valid_lft forever preferred_lft forever

<img width="960" height="1017" alt="image" src="https://github.com/user-attachments/assets/53b8c8ff-9ec3-46b0-b062-13a7831d7087" />
<img width="959" height="1017" alt="image" src="https://github.com/user-attachments/assets/76ead2ba-511a-48f9-9bec-197c623cc1cd" />

На виртуальной машине клоне создали пользователя, выдали ему пароль

<img width="633" height="191" alt="image" src="https://github.com/user-attachments/assets/e1b9b964-1d58-4b67-8800-ae69a1e10de1" />

Изменили файл /etc/sudoers добавив в него пользователя runner

<img width="955" height="1016" alt="image" src="https://github.com/user-attachments/assets/7a753e49-32f8-47ca-ab59-54e776c7c294" />

Оформили подключение по ключу из первой машины к клону

<img width="880" height="729" alt="image" src="https://github.com/user-attachments/assets/0f503739-df21-400c-a643-44228e93445f" />

Установили sudo apt install ansible и проверили версию

<img width="813" height="316" alt="image" src="https://github.com/user-attachments/assets/2b848c5b-70be-41f8-ae61-978d791e710b" />

Оформили заготовки под плейбук и инвентарь

<img width="633" height="117" alt="image" src="https://github.com/user-attachments/assets/caeae387-35ec-4f90-bc75-f4ad9421628f" />
<img width="600" height="159" alt="image" src="https://github.com/user-attachments/assets/376542ed-79f5-4dcb-8825-ca75818aec1e" />
