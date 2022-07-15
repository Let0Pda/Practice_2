Заголовок

# Первого уровня
## Вторго уровня
### Третьего уровня

Цитата

> Вы держитесь здесь, вам всего доброго, 
> хорошего настроения и здоровья

Ненумерованный список

* Украл
* Выпил
* В тюрьму

Нумерованный список

1. Пришёл
2. Увидел
3. Победил

Ссылка

[Тыкни](https://gb.ru/lessons/249742)

Если ссылок много, то можно так:

*Если срочно НАДО, то можешь искать тут* [Google][1] _тут_
[Yandex][2] *и тут* [MSN][3].

[1]: http://google.com/        "Google"
[2]: https://yandex.ru/        "Yandex"
[3]: http://search.msn.com/    "MSN Search"


Картинка

![А сперва задумывалось про это](https://pigmine.ru/wp-content/uploads/e/7/8/e78fb35ac51fbdeddd1cb3f19c9fcaa6.jpeg)

Работа с текстом:

Абзац с новой строки

Вариант 1 - два пробела в конце предыдушего абзаца  
Вариант 2 - пустая строка между абзацами

Выделение текста:

*курсив*

**жирный**

Таблицы -  (*неудобная вещь в markdown*)

Первый заголовок  | Второй заголовок
----------------- | -------------
Содержимое        | Содержимое 
Содержимое        | Содержимое 

Затекстовая ссылка

— Скажи-ка, дядя, ведь не даром[^1]  
[^1]: М.Ю.Лермонтов. Бородино

**Markdown**[^wiki_markdown] — облегчённый язык разметки.  
[^wiki_markdown]: [ru.wikipedia.org](/wiki/Markdown "ru.wikipedia.org")


Аббревиатуры

*[BGP]:  Border Gateway Protocol  
*[HTML]: Hyper Text Markup Language

Горизонтальная линия

---

Картинка или ссылка с классом и идентификатором

![alt-текст](http://example.ru/image.jpg){#id .class}
[Тяпк](http://tyapk.ru){#id .class}

Экранирование спецсимволов обратным слешем \

\   backslash
`   backtick
*   asterisk
_   underscore
{}  curly braces
[]  square brackets
()  parentheses
#   hash mark
+   plus sign
-   minus sign (hyphen)
.   dot
!   exclamation mark

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
