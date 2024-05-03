University: [ITMO University](https://itmo.ru/ru/)  
Faculty: [FICT](https://fict.itmo.ru)
Course: [Cloud platforms as the basis of technology entrepreneurship](https://itmo-ict-faculty.github.io/cloud-platforms-as-the-basis-of-technology-entrepreneurship/) 
Year: 2023/2024
Group: U4125
Author: Lebedev Fedor Alekseevich
Lab: Lab4
Date of create: 03.05.2024
Date of finished:  
Схема инфраструктуры  
![photo_2024-05-03_18-35-07](https://github.com/vindaslebe/2023_2024-cloud-platforms-as-the-basis-of-technology-entrepreneurship-u4125-lebedev_f_a/assets/165409365/6cdd43e8-f788-4662-b662-8dc67bea473e)  
Расчет экономической модели, разделенный на несколько этапов: Начальное, тестирование партнерами и продовое решение  
Начальное:  
Начальный этап не требует больших затрат, но тут мы сразу заложим бюджет на будущее на базу данных. А так данная конфигурация отлично послужит для запуска теста  
VM: 2 vCPU + 1 GB memory 10 GB standard persistent disk — 6.51$  
SQL Cloud: PostgreSQL 2 vCPU 16 GB memory — 0,25$ per hour
![photo_2024-05-03_19-41-49](https://github.com/vindaslebe/2023_2024-cloud-platforms-as-the-basis-of-technology-entrepreneurship-u4125-lebedev_f_a/assets/165409365/07cbbed1-6a26-4f74-b624-af67dd0bc1bc)
![photo_2024-05-03_19-42-07](https://github.com/vindaslebe/2023_2024-cloud-platforms-as-the-basis-of-technology-entrepreneurship-u4125-lebedev_f_a/assets/165409365/6ba3db17-84f3-4a38-8465-91a5de036870)  
Тестирование партнёрами:  
Увеличивается количество пользователей, следовательно увеличиваем затрачиваемые мощности  
VM: 2 vCPU + 2 GB memory 10 GB standard persistent disk — 12.63$  
SQL Cloud: PostgreSQL 2 vCPU 16 GB memory — 0,25$ per hour
![photo_2024-05-03_19-45-48](https://github.com/vindaslebe/2023_2024-cloud-platforms-as-the-basis-of-technology-entrepreneurship-u4125-lebedev_f_a/assets/165409365/515621c3-e83b-45eb-8bd5-b597785122f5)
![photo_2024-05-03_19-42-07](https://github.com/vindaslebe/2023_2024-cloud-platforms-as-the-basis-of-technology-entrepreneurship-u4125-lebedev_f_a/assets/165409365/6ba3db17-84f3-4a38-8465-91a5de036870)  
Продовое решение:  
Продовое решение уже несет в себе объяснение причины расширения. Требуется большее количество ресурсов, что становится приичной расширения  
VM: 2 vCPU + 4 GB memory 10 GB standard persistent disk — 24.86$  
SQL Cloud: PostgreSQL 2 vCPU 16 GB memory — 0,26$ per hour
![photo_2024-05-03_19-50-39](https://github.com/vindaslebe/2023_2024-cloud-platforms-as-the-basis-of-technology-entrepreneurship-u4125-lebedev_f_a/assets/165409365/03385222-e4c5-4aea-bc0c-d159165f1cac)
![photo_2024-05-03_19-50-50](https://github.com/vindaslebe/2023_2024-cloud-platforms-as-the-basis-of-technology-entrepreneurship-u4125-lebedev_f_a/assets/165409365/c2e1c012-360f-4f5a-baea-b16bdf1ecccb)  
Подводя итог, я считаю, данный план развития используемой конфигурации, является одним из самых оптимальных для запуска, тестирования и продового решения.
