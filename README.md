<!DOCTYPE html>
<html lang="uk">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Каталог товарів</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
        }
        header {
            text-align: center;
            margin-bottom: 20px;
        }
        img {
            max-width: 100%;
            height: auto;
        }
        table {
            width: 100%;
            border-collapse: collapse;
            margin: 20px 0;
        }
        table, th, td {
            border: 1px solid black;
        }
        th, td {
            padding: 10px;
            text-align: center;
        }
    </style>
</head>
<body>
    <header>
        <h1>Каталог товарів</h1>
        <img src="Книги.png" alt="Категорії товарів">
    </header>

    <section>
        <h2>Категорії товарів</h2>
        <ul>
            <li>Електроніка</li>
            <li>Книги</li>
            <li>Одяг</li>
        </ul>
    </section>

    <section>
        <h2>Популярні товари</h2>
        <table>
            <thead>
                <tr>
                    <th>Назва</th>
                    <th>Категорія</th>
                    <th>Ціна</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>Смартфон</td>
                    <td>Електроніка</td>
                    <td>$500</td>
                </tr>
                <tr>
                    <td>Роман "1984"</td>
                    <td>Книги</td>
                    <td>$15</td>
                </tr>
                <tr>
                    <td>Футболка</td>
                    <td>Одяг</td>
                    <td>$20</td>
                </tr>
            </tbody>
        </table>
    </section># -
