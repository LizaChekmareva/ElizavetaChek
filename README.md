/* Общие стили */
body {
    font-family: sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
   }
   
   /* Навигационное меню */
   .navbar {
    background-color: #333;
    color: #fff;
    padding: 10px;
    text-align: center;
   }
   
   .navbar ul {
    list-style-type: none;
    margin: 0;
    padding: 0;
   }
   
   .navbar li {
    display: inline-block;
    margin: 0 10px;
   }
   
   .navbar a {
    color: #fff;
    text-decoration: none;
   }
   
   .navbar a:hover {
    text-decoration: underline;
   }
   
   /* Верхний баннер */
   .banner {
    background-color: #fff;
    padding: 20px;
    text-align: center;
   }
   
   .banner img {
    border-radius: 50%;
   }
   
   /* О себе */
   .about {
    padding: 20px;
    text-align: center;
   }
   
   /* Контакты */
   .contacts {
    padding: 20px;
    text-align: center;
   }
   
   .contacts ul {
    list-style-type: none;
    margin: 0;
    padding: 0;
   }
   
   .contacts li {
    margin-bottom: 10px;
   }
   
   .contacts a {
    color: #007bff;
    text-decoration: none;
   }
   
   .contacts a:hover {
    text-decoration: underline;
   }
   
   /* Футер */
   .footer {
    background-color: #333;
    color: #fff;
    padding: 10px;
    text-align: center;
    position: fixed;
    bottom: 0;
    width: 100%;
   }
   
   /* Стили для "Чем занимаюсь вечерами" */
   .links__container {
    list-style: none;
    padding: 0;
    margin: 0;
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
   }
   
   .links__link {
    display: flex;
    justify-content: center;
    align-items: center;
    width: 150px;
    height: 100px;
    margin: 10px;
    background-color: #fff;
    border-radius: 10px;
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
    transition: transform 0.2s ease;
   }
   
   .links__link:hover {
    transform: translateY(-5px);
   }
   
   .links__title {
    font-size: 16px;
    font-weight: bold;
   }
   
   /* Стили для "И чтобы не сойти с ума" */
   .links__container2 {
    list-style: none;
    padding: 0;
    margin: 0;
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
   }
   
   .links__link2 {
    display: flex;
    justify-content: center;
    align-items: center;
    width: 150px;
    height: 100px;
    margin: 10px;
    background-color: #fff;
    border-radius: 10px;
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
    transition: transform 0.2s ease;
   }
   
   .links__link2:hover {
    transform: translateY(-5px);
   }
   
   .links__title2 {
    font-size: 16px;
    font-weight: bold;
   }
   
   /* Выравнивание заголовков по центру */
   .links__header {
    text-align: center;
   }
   
