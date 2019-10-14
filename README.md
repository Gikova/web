<html lang = "ru">
    <head>
        <meta http-equiv="content-type" content="text/html; charset=utf-8" />
        <meta name = "viewport" content = "width=device-width,initial-scale=1"/>
        <title>Название страницы</title>
        <link rel = "stylesheet" href = "style.css">
        
        
    </head>     
    <body> 
         <div class = "shapka"><span class = "logo"><img src="https://pngicon.ru/file/uploads/ljagushonok-pepe.png" alt="Пепе" height = "200" width ="200" id="leftimg" ></span><div> <h1>Memes</h1></div></div>
       
        <div id="navbar">
        <a href="#">Главная</a> |
        <a href="#">Новости</a> |
        <a href="#">Контакты</a> |
        <a href="#">О нас</a></div>
        <strong>ЗАДАНИЕ 1.Сверстать HTML 5 страницу с нумерованным списком гиперссылок и формой</strong>
        <p id = "1">Заголовок</p>
         
        <p id = "2">Ссылки</p>
        <ol>
                
                
            <li><a href = "http://example.com/"> абсолютную гиперссылку на главную страницу сайта example.com </a></li>
            <li><a href = "https://example.com/"> абсолютную на главную сайта example.com в протоколе https </a></li>
            <li><a href = "ftp://example.com/file.zip"> ссылку на файл на сервере FTP без авторизации </a></li>
            <li><a href = "ftp://login:black@admin.ru/admin.txt"> ссылку на файл на сервере FTP с авторизацией </a></li>
            <li><p id = "Кошки_в_истории,_религии_и_мифологии"></p>
            <a href = "https://ru.wikipedia.org/wiki/Кошка#Кошки_в_истории,_религии_и_мифологии"> ссылку на фрагмент страницы некоторого сайта </a></li>
            <li><p id = "suda">Сюда</p>
            <a href = "#suda"> ссылку на фрагмент текущей страницы </a></li>
            <li><a href = "http://books.com?orange=6655321&ampking=112263"> ссылку с двумя параметрами в URL </a></li>
            <li><a href = "#1" title ="заголовок"> >заголовок </a> 
            <a href = "#2" title ="ссылки"> >ссылки </a> 
            <a href = "#3" title ="форма"> >форма </a></li>
            <li><a> ссылку без href </a></li>
            <li><a href = ""> ссылку с пустым href </a></li>
            <li><a href = "http://bigpicture.ru/?p=527019" rel = "nofollow"> ссылку, по которой запрещен переход поисковикам </a></li>
            <li><!--noindex--><a href = "http://bigpicture.ru/?p=527019" rel = "nofollow"> запрещенную для индексации поисковиками </a><!--/noindex--></li>
            <li> контекстную в тексте абзаца
            <p> Существует легенда, что кошка была единственным животным, отсутствовавшим в тот момент, когда <a href = "https://ru.wikipedia.org/wiki/Будда">Будда</a> был на пути к освобождению от своего человеческого тела. Все животные, кроме кошки и змеи, собрались вокруг его тела. Кошка же в это время была занята ловлей мышей. Такое небрежное отношение к Будде и стало причиной негативного отношения к кошкам. Однако, у этой легенды есть и другая трактовка. Согласно ей, находившаяся рядом с Буддой крыса принялась лизать масло из лампы, кошка же поймала её и съела. Это деяние было благом, так как кошка спасла благовонное масло. С тех пор кошка считается приносящей как добро, так и зло. 
            </p></li>
            <li>ссылку-изображение 
            <a href = "https://www.youtube.com/watch?v=C93emkSw9Og" target = "_blank"><img src = "https://yt3.ggpht.com/a/AGF-l785XA1lPweIj30HIWzK4mMMlNbKd75H_EhRSg=s900-mo-c-c0xffffffff-rj-k-no" alt = "Spider" width="200" height="180"></a>
            </li>
            <li><p>ссылки из прямоугольных и круглых областей картинки (HTML-тег map)</p>
            <img src = "https://otvet.imgsmail.ru/download/245354155_309ffb2d0fbe0d3706181c879d0979d2_800.png" usemap="#box" alt ="Котолшебник" width="200" height="200"> 
            <map name="box">
            <area shape="rect" coords="110,70,200,140" alt = "meow" href="https://dok7xy59qfw9h.cloudfront.net/734/847/560/-349996985-1sr9i54-195sa3k2ggh2ie5/original/file.jpg" title="Мяугия">
            <area shape="circle" coords="50,80,30" alt = "meow-meow" href="https://yandex.ru/images/_crpd/7JRY3cL61/74ee7ex6Vv/nceuQoIlXdAYtFpS5jOm--pfFXy8vamPeVwDqPh_QCO-Z08Ke5hmwQmT23Hyc639_j5WfCw7UqU8OtkAEYKzet-FuViYc02AX-1JR_Bq8ae3F0Yi6OemxHVJSuH-dkdr" title="Мордашка">
            </map></li>
            <li><a href = "index.html"></a> относительную на страницу в текущем каталоге</li>
            <li><a href = "/about/index.html"> относительную на страницу в каталоге about</a></li>
            <li><a href = "../index.html"> относительную на страницу в каталоге уровнем выше текущего</a></li>
            <li><a href = "../../index.html"> относительную на страницу в каталоге двумя уровнями выше;</a></li>               
            <li><a href = "/"> сокращенную на главную</a></li>
            <li><a href = "/anime/loli/about/index.html"> сокращенную ссылку на внутреннюю</a></li>    
        </ol>
        <div class = "lol">
        <table id = "t" class = "lol2">
            <tbody>
            <tr class = "t1">
                <th>Ячейка 1</th>
                <th>Ячейка 2</th>
                <th>Ячейка 3</th>
                <th>Ячейка 4</th>
            </tr>
            <tr>
                <td colspan = "2">Ячейка 5</td>
                <td>Ячейка 6</td>
                <td>Ячейка 7</td>
              
            </tr>
             <tr class = "t1">
                <th>Ячейка 8</th>
                
                <th colspan ="2">Ячейка 9</th>
                <th>Ячейка 10</th>
            </tr>
            <tr>
                <td>Ячейка 11</td>
                <td>Ячейка 12</td>
                <td>Ячейка 13</td>
                <td>Ячейка 14</td>
            </tr>
             <tr class = "t1">
                <th>Ячейка 15</th>
                <th>Ячейка 16</th>
                <th>Ячейка 17</th>
                <th>Ячейка 18</th>
            </tr>
            <tr>
                <td>Ячейка 19</td>
                <td>Ячейка 20</td>
                <td>Ячейка 21</td>
                <td>Ячейка 22</td>
            </tr>
</tbody>  

        </table>
        <div class = "lol1">
        <p id = "3">Форма</p>
        
               
        <form>
    
            <p><strong>Имя</strong></p>
            <p><input size = "40" value = "Noname"></p>
            <p><strong>E-mail</strong></p>
            <p><input type = "email" size = "40"  value = "Noname@memes.ru" name = "Login"></p>
            <p><strong>Дата</strong></p>
            <p><input type = "date"   ></p>
            <p><strong>Пол</strong></p>
            <p><input type = "radio" name = "gender" value = "F">Ж
            <input type = "radio" name = "gender" value = "M">М
            <input type = "radio" name = "gender" value = "П">Паркет</p>
            <p><strong>Сколько конечностей?</strong></p>
            <p><input type = "radio" name = "limbs" value = "1">1
            <input type = "radio" name = "limbs" value = "2">2
            <input type = "radio" name = "limbs" value = "3">3
            <input type = "radio" name = "limbs" value = "4">4
            <input type = "radio" name = "limbs" value = "more">больше</p>
            <p><strong>Сверхсила</strong></p>
            <select size = 4 multiple>
            <option selected value = "s1">Бессмертие</option>
            <option  value = "s2">Прхождение сквозь стены</option>
            <option  value = "s3">Левитация</option>
            <option  value = "s4">Программирование на машине MIX</option>
            </select>
            <p><strong>Биография</strong></p>
            <p><textarea name = "comment"  cols = "50" rows = "10"></textarea></p>
            <p><input type = "checkbox" value = "yes">Ознакомлен с правилами пользования</p>
            <p><input type = "button" value = "Отправить"></p>
        </form>
        </div>
        </div>
        <div id="footer">
            Гикова Ангелина
        </div>
    </body>
</html>
