# Импакт анализ (анализ влияния, Impact Analysis)

_Анализ влияния (impact analysis): Оценка изменений в документации разработки и тестирования, а также компонентов с целью внесения данных изменений в определенные требования. (ISTQB)_

Impact Analysis (импакт анализ) - это исследование, которое позволяет указать затронутые места (affected areas) в проекте при разработке новой или изменении старой функциональности, а также определить, насколько значительно они были затронуты.

Затронутые области требуют большего внимания во время проведения регрессионного тестирования.

Импакт анализ может быть полезным в следующих случаях:

* есть изменения в требованиях;
* получен запрос на внесение изменений в продукт;
* ожидается внедрение нового модуля или функциональности в существующий продукт;
* каждый раз, когда есть изменения в существующих модулях или функциональностях продукта.

Как мы знаем, в настоящее время продукты становятся все более большими и комплексными, а компоненты все чаще зависят друг от друга. Изменение строчки кода в таком проекте может "сломать" абсолютно все.

Информация о взаимосвязи и взаимном влиянии изменений могут помочь QA:

* сфокусироваться на тестировании функциональности, где изменения были представлены;
* принять во внимание части проекта, которые были затронуты изменениями и, возможно, пострадали;
* не тратить время на тестирование тех частей проекта, которые не были затронуты изменениями.

Есть 3 типа импакт анализа:

* Анализ влияния зависимостей (Dependency impact analysis) фокусируется на обнаружении зависимостей: потенциальных последствий изменений или частей продукта, которые необходимо переработать при реализации этих изменений
* Эмпирический анализ влияния направлен на оценку рисков, связанных с изменениями продукта, с точки зрения всего процесса разработки, включая потребность в дополнительном времени и ресурсах для разработки
* Анализ влияния прослеживаемости (Traceability impact analysis), согласно определению в глоссарии ISTQB, оценивает, что необходимо изменить на разных уровнях документации, чтобы внести конкретное изменение в продукт.

...

Источники:

* [Dependency Impact Analysis in Software Testing and Development: What It Is and How to Do It](https://www.apriorit.com/qa-blog/252-impact-analysis)
* [Impact Analysis: 6 шагов, которые облегчат тестирование изменений](https://habr.com/ru/post/539208/)
* [Impact Mapping на практике](https://habr.com/ru/post/246401/), [https://www.impactmapping.org/](https://www.impactmapping.org)

Доп. материал:

[The Rise of Test Impact Analysis](https://martinfowler.com/articles/rise-test-impact-analysis.html)