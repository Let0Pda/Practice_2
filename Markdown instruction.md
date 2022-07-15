Заголовок

# Первого уровня
## Вторго уровня
### Третьего уровня

Цитата

Списки

Ссылка

Картинка

Работа с текстом

Код

Код в строке - обратными кавычками `

I strongly recommend against using any `<blink>` tags.

I wish SmartyPants used named entities like `—`
instead of decimal-encoded entites like `—`.

Код в блоке кода

```javascript  
left = typeof left != "number" ? 0 : left;
right = typeof right != "number" ? items.length - 1 : right;

index = partition(items, left, right);

if (left < index - 1) {
    quickSort(items, left, index - 1);
}  
```.

Можно вставлять HTML код

<blockquote>
        <p>Сырая цитата</p>
</blockquote>

<pre class="line-numbers">
<code class="language-javascript">function sayHi(name) {
  var phrase = "Привет, " + name;
  alert( phrase );
}
</code>
</pre>
