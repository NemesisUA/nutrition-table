
# Template literals

Template literals are literals delimited with backticks (`), allowing embedded expressions called substitutions.

- *Untagged* template literals result in strings, which makes them useful for string interpolation (and multiline strings, since unescaped newlines are allowed).
- *Tagged* template literals call a function (the tag function) with an array of any text segments from the literal followed by arguments with the values of any substitutions, which is useful for DSLs.

https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Template_literals


## return a string that represents some HTML code

It's very common in JavaScript to return a string that represents some HTML code. In fact, we'll be doing this quite often in the DOM Chapters. String interpolation comes in handy here because it supports multi-line strings and interpolation.

Complete the function renderTableRow such that it returns the following HTML:

```
  <tr>
    <td>label here</td>
    <td>value here</td>
  </tr>
 ```
 
 https://learnjavascript.online/app.html
 
 
 ## Using CSS custom properties (variables)
 
 **CSS переменные (пользовательские CSS-свойства)** это сущности, определяемые автором CSS, хранящие конкретные значения, которые можно повторно использовать в документе. Они устанавливаются с использованием custom property нотации (например. **--main-color: black;**) и доступны через функцию var() (например. **color: var(--main-color);**) .
 
 CSS переменные подчиняются каскаду и наследуют значения от своих родителей.
  
 ```json
 :root {
  --main-bg-color: brown;
}

.some-block {
  color: white;
  background-color: var(--main-bg-color);
}
```

https://developer.mozilla.org/en-US/docs/Web/CSS/Using_CSS_custom_properties

### **To read:**
[Почему мы предпочитаем CSS(--variable) переменным SASS($variable)?](https://habr.com/ru/post/456302/)
