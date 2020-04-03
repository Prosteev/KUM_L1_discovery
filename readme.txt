Tue 18 Feb 2020 11:05:09 PM MSK
    создал проект - выбрал не MCU, а плату DISCOVERY из списка
Wed 19 Feb 2020 11:14:21 PM MSK
    отдал ТМР1 на time base
    отключил Connectivity (SPI USB ...) включенные по умолчанию

Sat 21 Mar 2020 11:01:22 PM MSK
    подключил плату
    собрал проект
    запустил отладку - ошибка 
Program file does not exist
    stackoverflow:

    Right click on your project --> Properties
    Run/Debug settings
    Delete whatever is set as "launch configuration for '........'
    Project --> Clean
    Project --> Build Project

Select a way to debug ...
    STM32 Cortex-M C/C++ App
    Debug Settings - не менял

ЕСТЬ ОТЛАДКА!!!!!!!!!!!!!!!!!
