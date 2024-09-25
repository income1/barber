# Барбершоп BARS

Мобильный сайт для записи клиентов в барбершоп "BARS". Администраторы и барберы могут использовать этот сайт для просмотра и управления записями клиентов.

## HTML код

```html
<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>BARS - Записи</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f5f5f5;
            margin: 0;
            padding: 0;
        }
        h1 {
            text-align: center;
            color: #005f9e;
        }
        .appointment-list {
            margin: 20px auto;
            max-width: 600px;
            background-color: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
        }
        table {
            width: 100%;
            border-collapse: collapse;
        }
        table, th, td {
            border: 1px solid #ddd;
        }
        th, td {
            padding: 10px;
            text-align: left;
        }
        .status {
            color: red;
        }
        @media only screen and (max-width: 600px) {
            body {
                font-size: 14px;
                padding: 10px;
            }
            .appointment-list {
                width: 100%;
            }
            th, td {
                font-size: 12px;
            }
        }
    </style>
</head>
<body>
    <h1>Записи на сегодня</h1>
    <div class="appointment-list">
        <table>
            <thead>
                <tr>
                    <th>Время</th>
                    <th>Клиент</th>
                    <th>Барбер</th>
                    <th>Статус</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>10:00</td>
                    <td>Иван Иванов</td>
                    <td>Лаура</td>
                    <td class="status">Скоро подойдет</td>
                </tr>
                <tr>
                    <td>11:00</td>
                    <td>Алексей Петров</td>
                    <td>Алмас</td>
                    <td>Пришел</td>
                </tr>
            </tbody>
        </table>
    </div>
</body>
</html>
