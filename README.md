# SocialBtns
***Описание мода:***  
SocialBtns - мод который позволяет добавлять свои социальные сети слева внизу.  
(*Подходит для GDPS серверов или для FanMade проектов*)  
  
![](/assets/images/socialbtns.png)  

***Установка мода:***  
- Скачиваем файл "socialbuttons.zip" и распаковываем  
- Перекидываем ".geode" в папку с Geometry Dash
- Ресурсы ".png, .json" перекидываем в папку "Resources" где находиться Geometry Dash

***Настройка мода:***  
Открываем ".json" и видим код, но нам нужны только эти строчки:  
```
{
    "isBtn": 1,
    "texture": "yt.png",
    "link": "https://youtube.com"
}
```
- *"isBtn"* это включение и выключение кнопки. Тоесть *"isBtn": 1* означает что кнопка включено, а *"isBtn": 0* что кнопка выключено.  
- *"texture": "yt.png",* означает какая текстурка будет отображено. Например *"yt.png"* это кнопка ютуба и т.к в ".json" прописано текстурка ютуба, то оно и будет отображено.  
Вы можете ставить свои текстурку, заменив *"yt.png"*, но не меняем разрешение.  

![](/assets/images/ytpng.png)  

- *"link":* это означает куда направляет сама кнопка при нажатий. Например *"link": **"httрs://yоutube.cоm"*** означает что при нажатий кнопки перекидывает на ютуб.
