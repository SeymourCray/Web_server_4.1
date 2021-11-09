# Установка и запуск веб-сервера в Linux

Цель работы:
Освоить основные навыки установки и первоначальной настройки веб-сервера в ОС Linux.

Задания для выполнения:

1. Используя apt-get установить Apache2 на виртуальную машину
![image](https://user-images.githubusercontent.com/70951761/140971105-3ecf6637-2c9b-4291-b116-39b07f3ef419.png)
![image](https://user-images.githubusercontent.com/70951761/140971166-73f5cbdf-4906-4af1-acda-34085ef39361.png)

2. С браузера хост-машины по IP-адресу виртуальной машины увидеть приветствие
![image](https://user-images.githubusercontent.com/70951761/140971212-3bb49910-a25c-4c54-ad79-52f5ff7dd34c.png)
![image](https://user-images.githubusercontent.com/70951761/140971243-72b4fd36-a2ef-4cd6-9b06-b3a824c0de68.png)

3. В настройках сервера изменить  порт на :8080
![image](https://user-images.githubusercontent.com/70951761/140971283-8eefbf47-785f-4643-a5b9-9de1d1986976.png)
![image](https://user-images.githubusercontent.com/70951761/140971301-2da28f5c-2c68-42d8-88f8-6426e711fbf4.png)
![image](https://user-images.githubusercontent.com/70951761/140971355-b17f21f0-222d-4919-999a-2da6f35272bd.png)

4. Снова выполнить п 2, но с указанием порта
![image](https://user-images.githubusercontent.com/70951761/140971418-2743cb58-0c34-48aa-9a92-3176017e0cdd.png)

5. Изменить порт обратно и проверить как работает заглушка
![image](https://user-images.githubusercontent.com/70951761/140971503-1e1f9cf1-ee3c-47ae-b57f-1c5a4058d3f3.png)
![image](https://user-images.githubusercontent.com/70951761/140971526-b4339d3e-4dc3-4b20-86c3-35cebf669ae2.png)
![image](https://user-images.githubusercontent.com/70951761/140971545-1c433e12-0302-43f8-b0fd-216a777c0548.png)

6. В hosts хост-машины создать три домена: a1.com, b2.com, c3.com и связываем с IP виртуальной машины с Apache
![image](https://user-images.githubusercontent.com/70951761/140971590-048e4270-2ce5-41b5-a4c1-e4d604d3c0c3.png)

7. Для каждого домена проверить всё ли правильно, с помощью ping

![image](https://user-images.githubusercontent.com/70951761/140971638-6875d3c8-bc74-420d-a48e-0a97c8e75583.png)
![image](https://user-images.githubusercontent.com/70951761/140971612-3cc1674c-8463-4b01-9452-7f1003466ca8.png)

8. Зайти на все три домена, написав их вместо IP виртуальной машины
![image](https://user-images.githubusercontent.com/70951761/140971653-4c23f7b3-b0b0-49a4-aceb-9ef2b5176d77.png)
![image](https://user-images.githubusercontent.com/70951761/140971668-954af68d-cd33-49a5-9afb-3f7f2f6373f9.png)
![image](https://user-images.githubusercontent.com/70951761/140971682-30f72b9d-1e0b-42fd-842e-becf39b493ce.png)

9. Создать директории /var/www/a1.com, /var/www/b2.com, /var/www/c3.com
![image](https://user-images.githubusercontent.com/70951761/140971715-83f197dc-79cc-48eb-b2c2-ab54322c97bb.png)

10. В каждой из них создать пустой index.html

11. В каждом из них написать различное содержимое


![image](https://user-images.githubusercontent.com/70951761/140971785-43ea0b9b-9345-444d-bda5-8e9f3394e1ee.png)
![image](https://user-images.githubusercontent.com/70951761/140971803-f7f74267-93f4-45cf-8f1f-e492291908ff.png)

12. Сделать так, чтобы из браузеров хост-машины открывались сайты из директории, а не общая заглушка
![image](https://user-images.githubusercontent.com/70951761/140971907-a7c53e49-041c-48e5-b6b0-7259dce84548.png)
![image](https://user-images.githubusercontent.com/70951761/140971934-6942fec1-4228-4ca1-b72c-221a70fe4676.png)
![image](https://user-images.githubusercontent.com/70951761/140972012-0710e99c-4c77-4d9e-b11f-a891be47dd14.png)
![image](https://user-images.githubusercontent.com/70951761/140972044-0070dd70-74c2-43ef-b17e-bdaa6bfbe317.png)



Аналогично делаем с b2 и c3, затем получаем:


![image](https://user-images.githubusercontent.com/70951761/140972098-95ab5343-cafe-43d4-9d9b-94b8f8c69abf.png)
![image](https://user-images.githubusercontent.com/70951761/140972113-85990ec4-6fcc-46d6-810a-3b88d13aad52.png)
![image](https://user-images.githubusercontent.com/70951761/140972132-040ffecf-89ce-4569-b712-8e703e71bf2e.png)
