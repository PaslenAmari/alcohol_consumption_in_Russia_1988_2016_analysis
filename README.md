# alcohol_consumption_in_Russia_1988_2016_analysis
Анализ потребления алкоголя в России за 1988-2016гг

Данный датасет представляет данные по потреблению алкоголя в России за 1988-2016гг. Он содержит данные по потреблению следующих крепких напитков: вина, пива, водки, бренди и шампанского.

"year" - год (в диапазоне 1998-2016)
"region" - название федерального субъекта РФ. Это может быть область, республика, край, автономный округ, город федерального значения и  автономная область
"wine" - продажа вина в литрах по годам на душу населения
"beer" - продажа пива в литрах по годам на душу населения
"vodka" - продажа водки в литрах по годам на душу населения
"champagne" - продажа шампанского в литрах по годам на душу населения
"brandy" - продажа бренди в литрах по годам на душу населения

Информация по датасету:
![image](https://github.com/PaslenAmari/alcohol_consumption_in_Russia_1988_2016_analysis/assets/106679149/9710ac8d-3016-412a-8d24-726bd1ef66b4)
![image](https://github.com/PaslenAmari/alcohol_consumption_in_Russia_1988_2016_analysis/assets/106679149/52f29f67-ee2f-41d7-b33e-e132675785b1)

![image](https://github.com/PaslenAmari/alcohol_consumption_in_Russia_1988_2016_analysis/assets/106679149/3e132752-1670-438d-aa4d-45ea975efbf2)

Проведем анализ по пропущенным значениям
![image](https://github.com/PaslenAmari/alcohol_consumption_in_Russia_1988_2016_analysis/assets/106679149/e93d5841-0c2f-4907-aa76-96b6280e9951)
Данные с пропущенными значениями обработали.

Построили распределение по признакам датасета
![image](https://github.com/PaslenAmari/alcohol_consumption_in_Russia_1988_2016_analysis/assets/106679149/712798cb-fca4-4ce8-ac8e-badabb9ab6e2)
![image](https://github.com/PaslenAmari/alcohol_consumption_in_Russia_1988_2016_analysis/assets/106679149/e1530e7d-be28-449c-afe5-92dd9a0791b8)

Гипотезу сформировали следующую:
"Самый популярный алкогольный напиток в России в большинстве регионов по анализируемым годам - это водка"

![image](https://github.com/PaslenAmari/alcohol_consumption_in_Russia_1988_2016_analysis/assets/106679149/0b5bbbb8-edff-4518-94c3-d0b3433fcd7c)

Построили корреляцию по регионам России по напитку "vodka"
![image](https://github.com/PaslenAmari/alcohol_consumption_in_Russia_1988_2016_analysis/assets/106679149/84084e99-ddd7-4789-870e-67e817c7087d)

Выбрали топ-10 регионов по потребоению данного напитка
![image](https://github.com/PaslenAmari/alcohol_consumption_in_Russia_1988_2016_analysis/assets/106679149/cc31484e-60b1-4e84-ab8c-754acded3e07)

Ну и дополнительно посмотрели динамику потребления данного напитка в одном из регионов
![image](https://github.com/PaslenAmari/alcohol_consumption_in_Russia_1988_2016_analysis/assets/106679149/3058ad97-8393-4f09-97db-3f4bd5fc8ea3)

Посмотрели корреляции потребления водки от других напитков
![image](https://github.com/PaslenAmari/alcohol_consumption_in_Russia_1988_2016_analysis/assets/106679149/0eff1789-cfd0-4f65-8ab8-90455d103ed1)
![image](https://github.com/PaslenAmari/alcohol_consumption_in_Russia_1988_2016_analysis/assets/106679149/ba0ec51b-59ce-4f67-b637-89f6666e9d4e)
![image](https://github.com/PaslenAmari/alcohol_consumption_in_Russia_1988_2016_analysis/assets/106679149/4d497652-1371-4fe2-9b6f-248929fdabbd)

Вывод:


- мы рассмотрели потребление водки по регионам в разрезе 1998-2016 года - увидели тенденцию к снижению потребления с переломным моментом примерно в 2010 году, скорее всего россияне отказываются от водки в пользу других алкогольных продуктов.
- корреляция потребления водки с потреблением других крепких напитков есть, просто она слабовыраженная.
- в среднем, количество потребления водки в год на душу населения имеет ниспадающий (убывающий) характер для Республики Татарстан (РТ).
- больше всего из потребляемого алкоголя приходится на пиво - не сильно градусного и достаточно недорого, что закономерно для условий достатка среднестатистического россиянина.

Из чего можно сделать вывод, что наша гипотеза о том. что самый популярный алкогольный напиток в России это водка, ошибочен.
