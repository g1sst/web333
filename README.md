<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <title>Задание 3</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
  <div class="header">
    <header>
      <img src="logo.png" alt="Описание картинки для скрин-ридеров и поисковиков" />
      <h1 id="name">Название сайта</h1>      
  </header>
    <nav>
      <ul>
        <li><a href="#">Ссылка меню 1</a></li>
        <li><a href="#">Ссылка 2</a></li>
        <li><a href="#">Ссылка 3</a></li>
      </ul>
   </nav>
  </div>
    
    <main>
      <div class="table">
        <table>
          <h2>Таблица</h2>
          <thead>
            <tr class="nechet">
                <th>№</th>
                <th>Заголовок 1</th>
                <th>Заголовок 2</th>
                <th>Заголовок 3</th>
                <th>Заголовок 4</th>
            </tr>
            <tr class="nechet">
                <td>1</td>
                <td></td>
                <td></td>
                <td></td>
                <td></td>
            </tr>
            <tr class="chet">
                <td>2</td>
                <td></td>
                <td></td>
                <td></td>
                <td></td>
            </tr>
            <tr class="nechet">
                <td>3</td>
                <td></td>
                <td></td>
                <td></td>
                <td></td>
            </tr>
            <tr class="chet">
                <td>4</td>
                <td></td>
                <td></td>
                <td></td>
                <td></td>
            </tr>
            <tr class="nechet">
                <td>5</td>
                <td></td>
                <td></td>
                <td></td>
                <td></td>
            </tr>
            <tr class="chet">
                <td>6</td>
                <td></td>
                <td></td>
                <td></td>
                <td></td>
            </tr>
        </tbody>
        </table>
        <br /> 
      </div>

      <h2>Список гиперссылок</h2>
        <div class="links">
          <br/>
          <ul>
            <li><a href="http://kubsu.ru">kubsu.ru (HTTP)</a></li><br />
            <li><a href="http://kubsu.ru">kubsu.ru (HTTP)</a></li><br />
	    <li><a href="http://kubsu.ru">kubsu.ru (HTTP)</a></li><br />
            <li><a href="http://kubsu.ru">kubsu.ru (HTTP)</a></li><br />
            <li><a href="http://kubsu.ru">kubsu.ru (HTTP)</a></li><br />
	    <li><a href="http://kubsu.ru">kubsu.ru (HTTP)</a></li><br />
        </ul>
        </div>
      <div class="form">
        <h2>Форма</h2>
        <form action="/" method="POST">
          <label>
            ФИО:<br />
            <input 
              name="fio" 
              type="text" 
              placeholder="Введите ФИО"
            />
          </label>
          <br /><br />
    
          <label>
            Телефон:<br />
            <input
              name="phone"
              type="tel"
              placeholder="Введите телефон"
            />
          </label>
          <br /><br />
    
          <label>
            e-mail:<br />
            <input 
              name="email" 
              type="email" 
              placeholder="Введите почту"
            />
          </label>
          <br /><br />
    
          <label>
            Дата рождения:<br />
            <input 
              name="birthdate" 
              type="date"
            />
          </label>
          <br /><br />
    
          Пол:<br />
          <label>
            <input 
              type="radio" 
              name="gender" 
              value="male"
            />
            Мужской
          </label>
          <label>
            <input 
              type="radio" 
              name="gender" 
              value="female"
            /> 
            Женский
          </label>
          <br /><br />
    
          <label>
            Любимый язык программирования:<br />
            <select name="languages[]" multiple="multiple">
              <option value="pascal" selected="selected">Pascal</option>
              <option value="c" selected="selected">C</option>
              <option value="cpp" selected="selected">C++</option>
              <option value="javascript" selected="selected">JavaScript</option>
              <option value="php" selected="selected">PHP</option>
              <option value="python" selected="selected">Python</option>
              <option value="java" selected="selected">Java</option>
              <option value="haskell" selected="selected">Haskell</option>
              <option value="clojure" selected="selected">Clojure</option>
              <option value="prolog" selected="selected">Prolog</option>
              <option value="scala" selected="selected">Scala</option>
            </select>
          </label>
          <br /><br />
    
          <label>
            Биография:<br />
            <textarea 
              name="bio"  
              placeholder="Напишите что-то о себе"
            ></textarea>
          </label>
          <br />
    
          <label>
            <input 
              type="checkbox" 
              name="contract" 
              value="agreed"
            />
            Подтвердить
          </label>
          <br />
    
          <input 
              type="submit" 
              value="Отправить"
            />
        </form>
      </div>
    </main>

    <footer>
        <p>FOOTER</p>
    </footer>

</body>
</html>
