#IO-bound
##Выполнение синхронно в один поток:
###Диспетчер задач:
![img.png](screens/img_1.png)
###Время выполнения:
![img_1.png](screens/img_2.png)
##Выполнение используя ThreadPoolExecutor:
##max_workers = 5
###Диспетчер задач:
![img_2.png](screens/img_3.png)
###Время выполнения:
![img_3.png](screens/img_4.png)
##max_workers = 10
###Диспетчер задач:
![img_18.png](screens/img_5.png)
###Время выполнения:
![img_4.png](screens/img_6.png)
##max_workers = 100
###Диспетчер задач:
![img_19.png](screens/img_7.png)
###Время выполнения:
![img_5.png](screens/img_8.png)
####При преобразованиях можно заметить, что время выполнения значительно уменьшается, но загрузка памяти отличается всего лишь на пару процентов, процессор в основном одинаков, но бывают скачки и получается заметное отличие.
#CPU-bound
##Выполнение на одном ядре:
###Диспетчер задач:
![img.png](screens/img_9.png)
###Время выполнения:
![img.png](screens/img_10.png)
##max_workers=2
###Диспетчер задач:
![img.png](screens/img_11.png)
###Время выполнения:
![img.png](screens/img_12.png)
##max_workers=4
###Диспетчер задач:
![img.png](screens/img_13.png)
###Время выполнения:
![img.png](screens/img_14.png)
##max_workers=5
###Диспетчер задач:
![img.png](screens/img_15.png)
###Время выполнения:
![img.png](screens/img_16.png)
##max_workers=10
###Диспетчер задач:
![img.png](screens/img_17.png)
###Время выполнения:
![img.png](screens/img_18.png)
##max_workers=100
![img.png](screens/img_19.png)
####Можно заметить,что значительно меняется загрузка процессора, время выполнения с увеличением количества max_workers уменьшается. Максимальное количество max_workers - 61 из-за особенностей операционной системы.










