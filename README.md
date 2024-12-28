# SocialBtns
***Описание мода:***  
SocialBtns - мод который позволяет добавлять свои социональные сети слева внизу.  
(*Подходит для GDPS серверов или для FanMade проектов*)  
  
![](/assets/images/socialbtns.png)  

***Установка мода:***  
- Скачиваем файл "socialbuttons.zip" и распаковываем  
- Перекидываем ".geode" в папку с Geometry Dash
- Ресурсы ".png, .json" перекидываем в папку "Resources" где находиться Geometry Dash

***Настройка мода:***  
Открываем ".json" и видим код, но нам нужен только эти строчки:  
```
{
    "isBtn": 1,
    "texture": "yt.png",
    "link": "https://youtube.com"
}
```
*"isBtn"* озночает включение и выключение кнопки. Тоесть *"isBtn": 1* озночает что кнопка включено, а *"isBtn": 0* озночает что кнопка выключено.  
*"texture": "yt.png",* озночает какая текстурка будет отображено. Например *"yt.png"* это кнопка ютуба и т.к в ".json" прописано текстурка ютуба, то оно и будет отображено.  
Вы можете ставить свои текстурку, заменив *"yt.png"*, но не меняем разрешение.  

![](/assets/images/ytpng.png)  

*"link":* озночает куда направляет сама кнопка при нажатий. Например в коде написано *"link": **"httрs://yоutube.cоm"*** озночает что при нажатий кнопки оно будет направлять на ютуб.
