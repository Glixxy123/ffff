<!DOCTYPE html>
<html lang="ukr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="author" content="Arseniy Petrenko">
    <title>Розклад уроків</title>
    <style>
        body {
            font-family: 'Times New Roman', serif;
            background: url('https://img.freepik.com/free-vector/white-lined-paper-background_1017-33367.jpg') repeat;
            text-align: center;
            margin: 0;
            padding: 20px;
        }
        h1 {
            color: #2d2d2d;
            text-decoration: underline;
        }
        table {
            width: 75%;
            margin: auto;
            border-collapse: collapse;
            background: rgba(255, 255, 255, 0.9);
            box-shadow: 5px 5px 15px rgba(0, 0, 0, 0.2);
            border: 2px solid #2d2d2d;
        }
        th, td {
            border: 1px solid #5a5a5a;
            padding: 10px;
            text-align: center;
            font-size: 18px;
        }
        th {
            background: #f8f9fa;
            font-weight: bold;
        }
        tr:nth-child(even) {
            background: #fcfcfc;
        }
        tr:nth-child(odd) {
            background: #f1f1f1;
        }
        td:first-child {
            font-weight: bold;
        }
    </style>
</head>
<body>

    <h1>Розклад уроків</h1>

    <table>
        <tr>
            <th>День тижня</th>
            <th>№</th>
            <th>Час</th>
            <th>Предмет</th>
        </tr>

        <!-- Понеділок -->
        <tr><td rowspan="6">Понеділок</td><td>1</td><td>09:00 - 09:45</td><td>-</td></tr>
        <tr><td>2</td><td>10:00 - 10:45</td><td>Хімія</td></tr>
        <tr><td>3</td><td>11:00 - 11:45</td><td>Інформатика</td></tr>
        <tr><td>4</td><td>12:00 - 12:45</td><td>Фізкультура</td></tr>
        <tr><td>5</td><td>13:00 - 13:45</td><td>Фізика</td></tr>
        <tr><td>6</td><td>14:00 - 14:45</td><td>Зарубіжна література</td></tr>

        <!-- Вівторок -->
        <tr><td rowspan="8">Вівторок</td><td>1</td><td>09:00 - 09:45</td><td>Захист України</td></tr>
        <tr><td>2</td><td>10:00 - 10:45</td><td>Алгебра</td></tr>
        <tr><td>3</td><td>11:00 - 11:45</td><td>Фізкультура</td></tr>
        <tr><td>4</td><td>12:00 - 12:45</td><td>Фізика</td></tr>
        <tr><td>5</td><td>13:00 - 13:45</td><td>Історія</td></tr>
        <tr><td>6</td><td>14:00 - 14:45</td><td>Географія</td></tr>
        <tr><td>7</td><td>15:00 - 15:45</td><td>Мистецтво</td></tr>
        <tr><td>8</td><td>16:00 - 16:45</td><td>Англійська мова</td></tr>

        <!-- Середа -->
        <tr><td rowspan="8">Середа</td><td>1</td><td>09:00 - 09:45</td><td>-</td></tr>
        <tr><td>2</td><td>10:00 - 10:45</td><td>Геометрія</td></tr>
        <tr><td>3</td><td>11:00 - 11:45</td><td>Геометрія</td></tr>
        <tr><td>4</td><td>12:00 - 12:45</td><td>Громадянська освіта</td></tr>
        <tr><td>5</td><td>13:00 - 13:45</td><td>Біологія</td></tr>
        <tr><td>6</td><td>14:00 - 14:45</td><td>Географія</td></tr>
        <tr><td>7</td><td>15:00 - 15:45</td><td>Українська мова</td></tr>
        <tr><td>8</td><td>16:00 - 16:45</td><td>Українська література</td></tr>

        <!-- Четвер -->
        <tr><td rowspan="7">Четвер</td><td>1</td><td>09:00 - 09:45</td><td>Історія</td></tr>
        <tr><td>2</td><td>10:00 - 10:45</td><td>Українська мова</td></tr>
        <tr><td>3</td><td>11:00 - 11:45</td><td>Українська мова</td></tr>
        <tr><td>4</td><td>12:00 - 12:45</td><td>Фізкультура</td></tr>
        <tr><td>5</td><td>13:00 - 13:45</td><td>Фізика</td></tr>
        <tr><td>6</td><td>14:00 - 14:45</td><td>Українська література</td></tr>
        <tr><td>7</td><td>15:00 - 15:45</td><td>Українська література</td></tr>

        <!-- П’ятниця -->
        <tr><td rowspan="7">П’ятниця</td><td>1</td><td>09:00 - 09:45</td><td>Мистецтво</td></tr>
        <tr><td>2</td><td>10:00 - 10:45</td><td>Біологія</td></tr>
        <tr><td>3</td><td>11:00 - 11:45</td><td>Англійська мова</td></tr>
        <tr><td>4</td><td>12:00 - 12:45</td><td>Громадянська освіта</td></tr>
        <tr><td>5</td><td>13:00 - 13:45</td><td>Українська мова</td></tr>
        <tr><td>6</td><td>14:00 - 14:45</td><td>Українська література</td></tr>
        <tr><td>7</td><td>15:00 - 15:45</td><td>Класна година</td></tr>
    </table>

</body>
</html>

