### Задача: пренасяне на тухли

Строителни работници трябва да пренесат общо **x тухли**. **Работниците** са **w** на брой и работят едновременно. Те превозват тухлите в колички, всяка с **вместимост m** тухли. Напишете програма, която прочита целите числа **x**, **w** и **m** и пресмята **колко най-малко курса** трябва да направят работниците, за да превозят тухлите.

#### Вход

От конзолата се четат **3 цели числа** (по едно на ред):
- **Броят тухли x** се чете от първия ред.
- **Броят работници w** се чете от втория ред.
- **Вместимостта на количката m** се чете от третия ред.

Всички входни числа са цели и в диапазона [**1 … 1000**].

#### Изход

Да се отпечата на конзолата **минималният брой курсове**, необходими за превозване на тухлите.

#### Примерен вход и изход

|Вход|Изход|Обяснения|
|----|----|----|
|120<br>2<br>30|2|Имаме **2** работника, всеки вози по **30** тухли на курс. Общо работниците возят по **60** тухли на курс. За да превозят **120** тухли, са необходими точно **2** курса.|

|Вход|Изход|Обяснения|
|----|----|----|
|355<br>3<br>10|12|Имаме **3** работника, всеки вози по **10** тухли на курс. Общо работниците возят по **30** тухли на курс. За да превозят **355** тухли, са необходими точно **12** курса: **11** пълни курса превозват **330** тухли и последният **12**-ти курс пренася последните **25** тухли.|

|Вход|Изход|Обяснения|
|----|----|----|
|5<br>12<br>30|1|Имаме **5** работника, всеки вози по **30** тухли на курс. Общо работниците возят по **150** тухли на курс. За да превозят **5** тухли, е достатъчен само **1** курс (макар и непълен, само с 5 тухли).|