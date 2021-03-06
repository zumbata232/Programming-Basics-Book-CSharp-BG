### Оператор return

За да получим резултат от метода, на помощ идва операторът **`return`**. Той трябва да бъде **използван в тялото** на метода и указва на програмата да **спре изпълнението** му и да **върне** на извиквача на метода определена **стойност**, която се определя от израза след въпросния оператор **`return`**.

В примера по-долу имаме метод, който чете две имена от конзолата, съединява ги и ги връща като резултат. Връщаната стойност е от тип **`string`**:

![](/assets/chapter-10-images/11.Return-operator-01.png)

Операторът **`return`** може да бъде използван и във **`void`** методи. Тогава самият метод ще спре изпълнението си, без да връща никаква стойност, а след него не трябва да има израз, който да бъде върнат. В този случай употребата на **`return`** е единствено за излизане от метода.

**Има случаи**, в които **`return`** може да бъде извикван от няколко места в метода, но само ако има **определени** входни условия.