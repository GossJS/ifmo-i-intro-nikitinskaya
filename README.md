# ifmo_I_intro
исследование в области веб-языков и моделирования ИС

Адрес текста ЛР:
https://kodaktor.ru/08092017

## Что тут есть
- [Майндмэп про мои навыки в вебе](web-skills.png)
- [XML-представление майндмэпа](web-skills.xml)
- [Мокап главной странички моего сайта](site-mockup.png)

## Ссылка на c9
- [https://c9.io/veranikitinskaya](https://c9.io/veranikitinskaya)

## HTML5 vs. DTD

HTML 4 был основан на SGML - стандартном обобщенном языке разметки, Standard Generalized Markup Language. Это стандарт, на котором можно описывать другие языки разметки. DTD является частью SGML-документа и описывает собственно синтаксис разметки.

Отличие HTML5 состоит в том, что он более не основывается на SGML. Документ HTML5 включает в себя декларацию типа документа, `<!DOCTYPE html>`. Она похожа на объявление типа документа SGML, но таковой не является. Эта декларация не указывает, где находится некий внешний DTD, содержащий описание синтаксических правил, которые нужно использовать для парсинга документа. Декларация HTML5 просто сообщает о версии html и запускает процесс парсинга и рендеринга в браузере по единым стандартам.

Соответственно, для HTML5 не используется DTD, который содержал бы правила формальной грамматики. Кроме того, в силу более свободного синтаксиса HTML5 составить для него полный DTD не представляется возможным.

_Источники: w3.org, w3schools.com, "Web Standards: Mastering HTML5, CSS3, and XML" (L. Sikos)_
