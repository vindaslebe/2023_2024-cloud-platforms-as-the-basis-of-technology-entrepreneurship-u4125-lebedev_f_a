University: [ITMO University](https://itmo.ru/ru/)
Faculty: [FICT](https://fict.itmo.ru)
Course: [Cloud platforms as the basis of technology entrepreneurship](https://itmo-ict-faculty.github.io/cloud-platforms-as-the-basis-of-technology-entrepreneurship/) 
Year: 2023/2024
Group: U4125
Author: Lebedev Fedor Alekseevich
Lab: Lab1
Date of create: 25.04.2024
Date of finished: 
Был создан service account с ролью storage admin
![image](https://github.com/vindaslebe/2023_2024-cloud-platforms-as-the-basis-of-technology-entrepreneurship-u4125-lebedev_f_a/assets/165409365/9f7056e1-175d-4a9c-b4e1-11d9ba407568)
Была создана виртуальная машина с machine type e2-micro в режиме spot. Был выбран свой созданный ранее service account.
![image](https://github.com/vindaslebe/2023_2024-cloud-platforms-as-the-basis-of-technology-entrepreneurship-u4125-lebedev_f_a/assets/165409365/4456ada4-23ef-4b99-9818-2e0edf3b08a4)
С помощью утилиты gsutils был найден бакет lab1-bucket-itmo и были скопированы 3 файла в локальную папку на виртуальную машину.
![image](https://github.com/vindaslebe/2023_2024-cloud-platforms-as-the-basis-of-technology-entrepreneurship-u4125-lebedev_f_a/assets/165409365/c31fa69a-fd97-475c-85a6-3b8a8e630484)
Были изменены права доступа моего service account с Storage Admin на Compute Viewer
![image](https://github.com/vindaslebe/2023_2024-cloud-platforms-as-the-basis-of-technology-entrepreneurship-u4125-lebedev_f_a/assets/165409365/1045b728-02c5-4947-807b-e7f9c9762763)
Возникла ошибка при повторной попытке копирования файлов на виртуальную машину. Она связана с ограничением доступа. Роль Compute Viewer предоставляет только права на чтение ресурсов Compute Engine, но не предоставляет доступ к данным, хранящимся на этих ресурсах, в то время как роль Storage Admin предоставляет полный контроль над бакетами и объектами.
![image](https://github.com/vindaslebe/2023_2024-cloud-platforms-as-the-basis-of-technology-entrepreneurship-u4125-lebedev_f_a/assets/165409365/d66f23f1-52af-4707-b70f-2b9c0cf7ce35)
