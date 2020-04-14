### 解答例

```html
<!DOCTYPE html>
<html>
<head>
    <title>HTML/CSS Exercise</title>
    <script type="text/javascript">
    <!--
    function calc() {
        var symbol = document.getElementsByClassName('symbol');
        var num1 = parseInt(document.getElementById('num1').value);
        var num2 = parseInt(document.getElementById('num2').value);

        if (symbol[0].checked) {
            alert(num1 + num2);
        } else if (symbol[1].checked) {
            alert(num1 - num2);
        } else if (symbol[2].checked) {
            alert(num1 * num2);
        } else {
            alert(num1 / num2);
        }
    }
    //-->
    </script>
</head>
<body>
    <h1>計算プログラム</h1>
    <table>
        <tr>
            <td><input id="num1" type="number" name="num1">&emsp;</td>
            <td width="50">
                <input class="symbol" type="radio" name="symbol" value="1" checked>＋<br>
                <input class="symbol" type="radio" name="symbol" value="2">－<br>
                <input class="symbol" type="radio" name="symbol" value="3">×<br>
                <input class="symbol" type="radio" name="symbol" value="4">÷
            </td>
            <td><input id="num2" type="number" name="num2"></td>
            <td>&emsp;<input type="submit" value="計算" onclick="calc()"></td>
        </tr>
    </table>
</body>
<html>
```
