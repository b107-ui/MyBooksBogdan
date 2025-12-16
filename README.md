<!DOCTYPE html>
<html lang = "uk">
    <head>
        <meta charset = "utf-8">
        <title>Моя перша вебсторінка</title>
        <link rel = "stylesheet" href = "css/style.css" />
    </head>
    <body>
        <h1>Мої улюблені книги</h1>
        <p>Радію, що Ви  на моїй сторінці про мої улюблені книги.</p>
        <p>Сподіваюся, вам буде цікаво.</p>
        <hr>
        <h2>Чому я люблю читати?</h2>
        <p>Читання книг приносить мені велике задоволення. 
        Це дає можливість зануритися в нові світи, 
        дізнатися багато цікавого та розвивати свою уяву.
        </p>
        <hr>
        <h2>Перелік моїх улюблених книг</h2>
        <ol>
            <li>Володар кілець</li>
            <li>Палаючий острів</li>
            <li>Мандрівник з Марсу</li>
        </ol>
        <hr>
        <h2>Жанри, які я люблю</h2>
        <ul>
            <li>Фентезі</li>
            <li>Наукова фантастика</li>
            <li>Детективи</li>
        </ul>
        <h2>Обкладинки книг</h2>
        <img src="https://upload.wikimedia.org/wikipedia/uk/a/a3/The_Return_of_the_King.jpg" 
        alt="Володар перснів" width="200" height="300">
        <img src="https://bigteacher3.github.io/img/BurningIsland.jpg" alt="Палаючий острів" width="200" height="300">
        <img src="https://bigteacher3.github.io/img/Traveler_from_Mars.jpg" alt="Палаючий острів" width="200" height="300">
        <h2>Інформація про книги</h2>
        <table border="1" cellpadding="10" cellspacing="0">
            <tr>
                <th>Назва книги</th>
                <th>Автор</th>
                <th>Жанр</th>
            </tr>
            <tr>
                <td>Володар перснів</td>
                <td>Дж. Р. Р. Толкін</td>
                <td>Фентезі</td>
            </tr>
            <tr>
                <td>Палаючий острів</td>
                <td>О. Казанцев</td>
                <td>Наукова фантастика</td>
            </tr>
            <tr>
                <td>Мандрівник з Марсу</td>
                <td>Р. Гайдеман</td>
                <td>Фентезі</td>
            </tr>
        </table>
        <h2> Де купити ці книги?</h2>
        <p>
            <p>Ви можете придбати ці книги на <a href="https://bookclub.ua/"
            target="_blank">КСД</a>.</p>
        <p>
        <ul>
            <li><a href = "https://bookclud.ua/" target = "_blank">КСД</a></li>
            <li><a href = "https://ridna-mova.com/" target = "_blank">Рідна мова</a></li>
            <li><a href = "https://book-ye.com.ua/" target = "_blank">Книгарня Є</a></li>
        </ul>
        <h2>Зворотній звʼязок</h2>
        <form action="submit form.php" methood="post">
            <label for="name">Ім`я:</label>
            <input type="text" id="name">
            
            <label for="email">Електронна пошта:</label>
            <input type="email" id="email">
            
             <label for="message">Повідомлення:</label>
            <textarea id="message" rows="4"></textarea>
            
            <button type="submit">Відправити</button>
        </form>
    </body>
</html>
body {
    font-family: 'Roboto', sans-serif;
    margin: 0;
    padding: 20px;
    background-color: #f4f4f4;
    color: #333;
}
h1 {
    color: #0056b3;
    text-align: center;
    margin-bottom: 20px;
}
h2 {
    color: #333;
    border-bottom: 2px solid #0056b3;
    padding-bottom: 10px;
    margin-top: 40px;
}
p {
    font-size: 18px;
    line-height: 1.6;
}
ol, ul {
    margin-left: 20px;
    margin-bottom: 20px;
}
li {
   margin-bottom: 5px;
}
img {
   margin-right: 15px;
    border-radius: 5px;
    box-shadow: 0 0 15px rgba(0, 0, 0, 0.5);
}
a {
    color: #0056b3;
    text-decoration: none;
}
a:hover {
    color: #003d80;
    text-decoration: underline;
}
table {
    margin-bottom:20px; 
    background-color: #fff; 
    box-shadow: 0 0 15px rgba(0, 0, 0, 0.5);
}
th, td {
    padding: 15px;
    text-align: left;
    border-bottom: 1px solid #ddd;
}
th {
    background-color: #005663; 
    color: #fff;
}
form {
    background-color: #fff;
    padding: 20px;
    border-radius: 5px;
    box-shadow: 0 0 15px rgba(0, 0, 0, 0.5);
    margin-bottom: 40px;
}
label {
    display: block;
    margin-bottom: 10px;
    font-weight: bold;
}
input, textarea {
    width: 100%;
    padding: 10px;
    margin-bottom: 20px;
    border: 1px solid #ddd;
    border-radius: 5px;
    box-sizing: border-box;
}
button {
    background-color: #0056b3;
    color: white;
    padding: 10px 20px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
    font-size: 16px;
}
button:hover {
    background-color: #003d80;
}
