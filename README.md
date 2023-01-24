# JMeter_HW_1

![](https://github.com/Ilya-Tsatsuro/JMeter_HW_1/blob/main/images/Apache%20JMeter.png?raw=true)

Сделать сценарий с перечисленными endpoint.

- Дать нагрузку на 50, 250, 500 потоков.
- Результаты прогонов выгрузить в CSV.
- Настройки Jmeter, файл .jmx выгрузить на GitHub.


## 1) http://162.55.220.72:5005/get_method  

### Request  
Method: GET  
Request parameters:
>name: Ilia  
>age: int  

Configuration:
![]()

## 2) http://162.55.220.72:5005/user_info_2

### Request  
Method: POST  
Request parameters:
>name: Ilia  
>age: 29  
>salary: 5000

Configuration:
![]()

## 3) http://162.55.220.72:5005/user_info_3

### Request  
Method: POST  
Request parameters:
>name: Ilia  
>age: 29  
>salary: 5000

Configuration:
![]()


## 4) http://162.55.220.72:5005/object_info_1

### Request  
Method: GET  
Request parameters:
>name: Ilia  
>age: 29  
>weight: 68

Result:
![]()

Configuration:
![]()


## 5) http://162.55.220.72:5005/object_info_2

Method: GET  
Request parameters:
>name: Ilia  
>age: 29  
>salary: 5000

Configuration:
![]()


## 6) http://162.55.220.72:5005/object_info_3
-
Method: GET  
Request parameters:
>name: Ilia  
>age: 29  
>salary: 5000

Configuration:
![]()


## 7) http://162.55.220.72:5005/object_info_4

Method: GET  
Request parameters:
>name: Ilia  
>age: 29  
>salary: 5000

Configuration:
![]()


------

Configuration:
![](https://github.com/Ilya-Tsatsuro/JMeter_HW_1/blob/main/images/JMeter_500_users.png?raw=true)

Result:
![](https://github.com/Ilya-Tsatsuro/JMeter_HW_1/blob/main/images/View%20results%20tree%20500%20users.png?raw=true)

Result:
![](https://github.com/Ilya-Tsatsuro/JMeter_HW_1/blob/main/images/Summary%20report%20500%20users.png?raw=true)

Result:
![](https://github.com/Ilya-Tsatsuro/JMeter_HW_1/blob/main/images/View%20results%20in%20Table%20500%20users.png?raw=true)