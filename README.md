<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>WEB</title>
    <!-- <link rel="stylesheet" href="style.css"> -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>
  <div class="container-fluid">
        <!-- Навигация для десктопа (видна только на десктопах) -->
        <nav class="d-none d-lg-block mb-3 order-lg-1">
            <ul class="nav bg-secondary p-3 rounded">
                <li class="nav-item">
                    <a class="nav-link text-white" href="#">Ссылка меню 1</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link text-white" href="#">Ссылка 2</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link text-white" href="#">Ссылка 3</a>
                </li>
            </ul>
        </nav>

            <header class="bg-secondary p-3 rounded">
                <div class="d-flex align-items-center">
                    <img src="logo.png" alt="Описание картинки для скрин-ридеров и поисковиков" class="me-5" width="100" height="100">
                    <h1 class="h4 ms-3 text-white">Название сайта</h1>
                </div>
            </header>

    <!-- Навигация для мобильных-->
     <div class="container-lg">
        <nav class="d-block d-lg-none mt-4">
          <ul class="nav flex-column flex-lg-row bg-secondary p-3 rounded">
              <li class="row">
                  <a class="nav-link text-white" href="#">Ссылка меню 1</a>
              </li>
              <li class="row">
                  <a class="nav-link text-white" href="#">Ссылка 2</a>
              </li>
              <li class="row">
                  <a class="nav-link text-white" href="#">Ссылка 3</a>
              </li>
          </ul>
      </nav>
     </div>
</div>
    
    <main class="container lg">
        <div class="d-block d-lg-none mt-4 p-2">
            <h2>Таблица</h2>
            <table class="table table-success table-striped">
                <thead>
                    <tr class="table-secondary">
                        <th>#</th>
                        <th>Заголовок 1</th>
                        <th>Заголовок 2</th>
                        <th colspan="2">Заголовок 3 и Заголовок 4</th>
                    </tr>
                </thead>
                <tbody>
                    <tr class="table-light">
                        <td>1</td>
                        <td rowspan="2"></td>
                        <td></td>
                        <td></td>
                        <td></td>
                    </tr>
                    <tr class="table-secondary">
                        <td>2</td>
                        <td></td>
                        <td></td>
                        <td></td>
                    </tr>
                    <tr class="table-light">
                        <td>3</td>
                        <td></td>
                        <td></td>
                        <td></td>
                        <td></td>
                    </tr>
                    <tr class="table-secondary"> 
                        <td>4</td>
                        <td></td>
                        <td></td>
                        <td></td>
                        <td></td>
                    </tr>
                    <tr class="table-light">
                        <td>5</td>
                        <td></td>
                        <td></td>
                        <td></td>
                        <td></td>
                    </tr>
                    <tr class="table-secondary">
                        <td>6</td>
                        <td></td>
                        <td></td>
                        <td></td>
                        <td></td>
                    </tr>
                </tbody>
            </table>
        </div>
          <br /> 
        <!-- Ссылки -->
        <h2>Список гиперссылок</h2>
        <div class="container my-5">
          <div class="bg-secondary text-white p-4 rounded ">
              <ul class="list-unstyled">
                  <li><a class="link-light link-offset-2 link-underline-opacity-25 link-underline-opacity-100-hover" href="http://kubsu.ru">Абсолютная ссылка на главную страницу сайта kubsu.ru (HTTP)</a></li>
                  <li><a class="link-light link-offset-2 link-underline-opacity-25 link-underline-opacity-100-hover" href="https://kubsu.ru">Абсолютная ссылка на главную страницу сайта kubsu.ru (HTTPS)</a></li>
                  <li><a class="link-light link-offset-2 link-underline-opacity-25 link-underline-opacity-100-hover" href="https://example.com"><img src="image.jpg" width="400" class="img-fluid"></a></li>
                  <li><a class="link-light link-offset-2 link-underline-opacity-25 link-underline-opacity-100-hover" href="index.html">Сокращенная ссылка на внутреннюю страницу</a></li>
                  <li><a class="link-light link-offset-2 link-underline-opacity-25 link-underline-opacity-100-hover" href="/">Сокращенная ссылка на главную страницу</a></li>
                  <li><a class="link-light link-offset-2 link-underline-opacity-25 link-underline-opacity-100-hover" href="#fragment">Ссылка на фрагмент текущей страницы</a></li>
                  <li><a class="link-light link-offset-2 link-underline-opacity-25 link-underline-opacity-100-hover" href="page.html?param1=value1&param2=value2&param3=value3">Ссылка с тремя параметрами в URL</a></li>
                  <li><a class="link-light link-offset-2 link-underline-opacity-25 link-underline-opacity-100-hover" href="page.html?id=123">Ссылка с параметром id в URL</a></li>
                  <li><a class="link-light link-offset-2 link-underline-opacity-25 link-underline-opacity-100-hover" href="relative.html">Относительная ссылка на страницу в текущем каталоге</a></li>
                  <li><a class="link-light link-offset-2 link-underline-opacity-25 link-underline-opacity-100-hover" href="about/relative.html">Относительная ссылка на страницу в каталоге about</a></li>
                  <li><a class="link-light link-offset-2 link-underline-opacity-25 link-underline-opacity-100-hover" href="../up.html">Относительная ссылка на страницу в каталоге уровнем выше текущего</a></li>
                  <li><a class="link-light link-offset-2 link-underline-opacity-25 link-underline-opacity-100-hover" href="../../upup.html">Относительная ссылка на страницу в каталоге двумя уровнями выше</a></li>
                  <li>Пример <a class="link-light link-offset-2 link-underline-opacity-25 link-underline-opacity-100-hover" href="context.html">контекстной</a> ссылки в тексте абзаца.</li>
                  <li><a class="link-light link-offset-2 link-underline-opacity-25 link-underline-opacity-100-hover" href="https://example.com#fragment">Ссылка на фрагмент страницы стороннего сайта</a></li>
                  <li>
                      <img src="imagemap.png" usemap="#imagemap" class="img-fluid" width="400">
                      <map name="imagemap">
                          <area shape="rect" coords="0,0,100,100" href="rect.html">
                          <area shape="circle" coords="150,150,50" href="circle.html">
                      </map>
                  </li>
                  <li><a class="link-light link-offset-2 link-underline-opacity-25 link-underline-opacity-100-hover" href="">Ссылка с пустым href</a></li>
                  <li><a>Ссылка без href</a></li>
                  <li><a class="link-light link-offset-2 link-underline-opacity-25 link-underline-opacity-100-hover" href="nofollow.html" rel="nofollow">Ссылка, по которой запрещен переход поисковикам</a></li>
                  <li><a class="link-light link-offset-2 link-underline-opacity-25 link-underline-opacity-100-hover" href="noindex.html" rel="noindex">Запрещенная для индексации поисковиками</a></li>
              </ul>

              <h3 class="mt-4">Нумерованный список ссылок</h3>
              <ol>
                  <li><a class="link-light link-offset-2 link-underline-opacity-25 link-underline-opacity-100-hover" href="link1.html" title="1">Ссылка 1</a></li>
                  <li><a class="link-light link-offset-2 link-underline-opacity-25 link-underline-opacity-100-hover" href="link2.html" title="2">Ссылка 2</a></li>
                  <li><a class="link-light link-offset-2 link-underline-opacity-25 link-underline-opacity-100-hover" href="link3.html" title="3">Ссылка 3</a></li>
              </ol>

              <a class="link-light link-offset-2 link-underline-opacity-25 link-underline-opacity-100-hover mt-4 d-block" href="ftp://username:password@ftp.example.com/file.txt">Ссылка на файл на сервере FTP с авторизацией</a>
          </div>
      </div>
        <br/>

        <!-- видно тольк десктопам -->
        <div class="d-none d-lg-block mb-3 order-lg-1">
          <h2>Таблица</h2>
          <div class="container my-5">
            <table class="table table-success table-striped">
                <thead>
                    <tr class="table-secondary">
                        <th>#</th>
                        <th>Заголовок 1</th>
                        <th>Заголовок 2</th>
                        <th colspan="2">Заголовок 3 и Заголовок 4</th>
                    </tr>
                </thead>
                <tbody>
                    <tr class="table-light">
                        <td>1</td>
                        <td rowspan="2"></td>
                        <td></td>
                        <td></td>
                        <td></td>
                    </tr>
                    <tr class="table-secondary">
                        <td>2</td>
                        <td></td>
                        <td></td>
                        <td></td>
                    </tr>
                    <tr class="table-light">
                        <td>3</td>
                        <td></td>
                        <td></td>
                        <td></td>
                        <td></td>
                    </tr>
                    <tr class="table-secondary"> 
                        <td>4</td>
                        <td></td>
                        <td></td>
                        <td></td>
                        <td></td>
                    </tr>
                    <tr class="table-light">
                        <td>5</td>
                        <td></td>
                        <td></td>
                        <td></td>
                        <td></td>
                    </tr>
                    <tr class="table-secondary">
                        <td>6</td>
                        <td></td>
                        <td></td>
                        <td></td>
                        <td></td>
                    </tr>
                </tbody>
            </table>
        </div>
          <br /> 
        </div>

      <!-- Form-->
      <h2>Форма</h2>
      <div class="container my-5">
        <div class="bg-secondary text-white p-4 rounded">
            <form action="/" method="POST">
                <div class="mb-3">
                    <label for="fio" class="form-label">ФИО:</label>
                    <input class="form-control" name="fio" type="text" id="fio" placeholder="Введите ваше ФИО" />
                </div>
                
                <div class="mb-3">
                    <label for="phone" class="form-label">Телефон:</label>
                    <input class="form-control" name="phone" type="tel" id="phone" placeholder="Введите ваш телефон" />
                </div>
                
                <div class="mb-3">
                    <label for="email" class="form-label">E-mail:</label>
                    <input class="form-control" name="email" type="email" id="email" placeholder="Введите вашу почту" />
                </div>
                
                <div class="mb-3">
                    <label for="birthdate" class="form-label">Дата рождения:</label>
                    <input class="form-control" name="birthdate" type="date" id="birthdate" />
                </div>
                
                <fieldset class="mb-3">
                    <legend class="col-form-label pt-0">Пол:</legend>
                    <div class="form-check">
                        <input class="form-check-input" type="radio" name="gender" id="male" value="male" />
                        <label class="form-check-label" for="male">Мужской</label>
                    </div>
                    <div class="form-check">
                        <input class="form-check-input" type="radio" name="gender" id="female" value="female" />
                        <label class="form-check-label" for="female">Женский</label>
                    </div>
                </fieldset>

                <div>
                  <label for="languages" class="block-label">Любимый язык программирования:</label></br>
                <select id="languages" name="languages[]" multiple size="5" class="form-select" aria-label="Default select example">
                    <option value="pascal">Pascal</option>
                    <option value="c">C</option>
                    <option value="cpp">C++</option>
                    <option value="javascript">JavaScript</option>
                    <option value="php">PHP</option>
                    <option value="python">Python</option>
                    <option value="java">Java</option>
                    <option value="haskel">Haskel</option>
                    <option value="clojure">Clojure</option>
                    <option value="prolog">Prolog</option>
                    <option value="scala">Scala</option>
                </select>
                </div>
                
                
                <div class="mb-3">
                    <label for="bio" class="form-label">Биография:</label>
                    <textarea class="form-control" name="bio" id="bio" placeholder="Напишите о себе" rows="4"></textarea>
                </div>
                
                <div class="mb-3 form-check">
                    <input type="checkbox" class="form-check-input" id="contract" name="contract" value="agreed" />
                    <label class="form-check-label" for="contract">С контрактом ознакомлен (а)</label>
                </div>

                <button type="submit" class="btn btn-primary">Сохранить</button>
            </form>
        </div>
    </div>

    </main>
    <div class="ontainer-fluid">
      <div class="bg-secondary text-white p-4 rounded">
        <footer>
            <p>© Bogomolov Nik</p>
        </footer>
      </div>
    </div>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
