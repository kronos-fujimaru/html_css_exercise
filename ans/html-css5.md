### 解答例

```html
<!DOCTYPE html>
<html>
<head>
    <title>HTML/CSS Exercise</title>
    <script type="text/javascript">
    <!--
    function add() {
        var item = document.getElementById('item');
        var price = document.getElementById('price');
        var fruitsList = document.getElementById('fruitsList');

        var li = document.createElement('li');
        var text = document.createTextNode(item.value + " " + price.value + "円");
        li.appendChild(text);
        fruitsList.appendChild(li);
    }

    function changeColor() {
        var title = document.getElementById('title');
        if (title.style.color === "red") {
            title.style.color = "black";
        } else {
            title.style.color = "red";
        }
    }
    //-->
    </script>
</head>
<body>
    <h1 id="title" onmouseover="changeColor()">フルーツ一覧</h1>
    <ul id="fruitsList">
        <li>Apple 150円</li>
        <li>Banana 60円</li>
        <li>Cherry 300円</li>
    </ul>
    <form>
        商品名：<input id="item" type="text" name="item"><br>
        価格：　<input id="price" type="number" name="price"><br>
        <br>
        <input type="button" value="追加" onclick="add()">
    </form>
</body>
<html>
```
