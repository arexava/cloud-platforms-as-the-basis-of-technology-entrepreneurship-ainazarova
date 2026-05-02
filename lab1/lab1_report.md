**University:** ITMO University  
**Faculty:** [FTMI]  
**Course:** Облачные платформы как основа технологического предпринимательства  
**Year:** 2025/2026  
**Group:** U4125  
**Author:** Nazarova Arina Ilinichna  
**Lab:** Lab1  
**Date of create:** 02.05.2026  
**Date of finished:** 02.05.2026 

## Отчет по лабораторной работе "Обзор Google Cloud и исследование основных сервисов"  
**Цель работы**  
Ознакомиться с основными возможностями и преимуществами облачной платформы Google Cloud.  

**Ход работы:**   
1. Зашла в Google Cloud и во вкладке IAM создала service account с ролью storage admin:  
<img width="645" height="58" alt="Снимок экрана 2026-05-03 в 00 25 39" src="https://github.com/user-attachments/assets/7f95eda6-3872-461a-9420-044a20cc7d11" />

3. Создала виртуальную машину с заданными условиями лабы параметрами:  
<img width="676" height="242" alt="Снимок экрана 2026-05-03 в 00 32 27" src="https://github.com/user-attachments/assets/c031af82-7d5d-4c4d-ba19-6024211ad3bc" />

В качестве сервисного аккаунта выбрала свой, созданный шагом ранее:  
<img width="493" height="205" alt="Снимок экрана 2026-05-03 в 00 38 17" src="https://github.com/user-attachments/assets/596bb422-71b6-48ea-bd61-478f994ec4e9" />

4. Возникла проблема - после создания машина не запускалась, решилось переподключением настроек (поменять spot на standard и обратно). После прожатия "SSH" открылся терминал:
<img width="769" height="348" alt="Снимок экрана 2026-05-03 в 00 46 51" src="https://github.com/user-attachments/assets/3c3ca545-5112-4e44-ad1b-0e55610e41a4" />

5. Нашла бакет с помощью утилиты gcloud и скопировала файлы. Проверила результат работы с помощью команды ls -lah, все отобразилось:  
<img width="591" height="370" alt="Снимок экрана 2026-05-03 в 00 49 19" src="https://github.com/user-attachments/assets/92db9691-e7a5-4d4b-9895-eeb96bcd64d9" />

6. Снова зашла в IAM, удалила роль в своем сервис акке:  
<img width="739" height="276" alt="Снимок экрана 2026-05-03 в 00 52 09" src="https://github.com/user-attachments/assets/ee6ba39a-e44f-48ec-b6df-c84717ddc6e8" />

7. Заменила роль на compute viewer:  
<img width="681" height="52" alt="Снимок экрана 2026-05-03 в 00 56 19" src="https://github.com/user-attachments/assets/46e28864-c943-4c8f-ae88-724c0186f986" />







