### 解答例

```html
<!DOCTYPE html>
<html>
<head>
    <title>HTML/CSS Exercise</title>
    <style>
    <!--
        header {
            color:#FFF;
            text-shadow:3px 3px 3px #000;
            text-align:center;
            background-color:#00F;
            width:800px;
            padding:1px 0px;
        }
        article {
            text-align:center;
            width:800px;
        }
        footer {
            color:#FFF;
            text-align:center;
            background-color:#00F;
            width:800px;
            padding: 3px 0px;
        }
        table {
            background-color:#FFF;
            border-collapse:collapse;
            box-shadow:3px 3px;
            margin: auto;
        }
        th {
            border:1px #000 solid;
        }
        td {
            border:1px #000 solid;
        }
        input[type="number"] {
            width:80px;
            text-align:right;
        }
    -->
    </style>
</head>
<body>
    <header>
        <h1>ケロノス家具通販</h1>
    </header>
    <article>
        <p>注文数を入力してください</p>
        <b>商品一覧</b>
        <table>
            <tr>
                <th>カテゴリ</th>
                <th>商品名</th>
                <th>サイズ(cm)</th>
                <th>画像</th>
                <th>価格</th>
                <th>注文数</th>
            </tr>
            <tr>
                <td rowspan="2">キッチン</td>
                <td>キッチンテーブル</td>
                <td>80 x 80 x 70</td>
                <td><img src="img/table.png" alt="kitchen-table" width="80"></td>
                <td>29,800円</td>
                <td><input type="number" name="num" min="0" value="0"></td>
            </tr>
            <tr>
                <td>デスク</td>
                <td>100 x 60 x 70</td>
                <td><img src="img/desk.png" alt="desk" width="80"></td>
                <td>15,800円</td>
                <td><input type="number" name="num" min="0" value="0"></td>
            </tr>
            <tr>
                <td rowspan="3">リビング</td>
                <td>イス</td>
                <td>45 x 40 x 90</td>
                <td><img src="img/chair.png" alt="chair" width="50"></td>
                <td>9,800円</td>
                <td><input type="number" name="num" min="0" value="0"></td>
            </tr>
            <tr>
                <td>ベッド</td>
                <td>200 x 100 x 40</td>
                <td><img src="img/bed.png" alt="bed" width="80"></td>
                <td>39,800円</td>
                <td><input type="number" name="num" min="0" value="0"></td>
            </tr>
            <tr>
                <td>ソファー</td>
                <td>150 x 85 x 60</td>
                <td><img src="img/sofa.png" alt="sofa" width="80"></td>
                <td>42,800円</td>
                <td><input type="number" name="num" min="0" value="0"></td>
            </tr>
        </table>
        <p><input type="submit" value="注文確認"></p>
    </article>
    <footer>
        <label>Copyright (c) 2020. Kelonos Co, Ltd All Rights Reserved.</label>
    </footer>
</body>
<html>
```
