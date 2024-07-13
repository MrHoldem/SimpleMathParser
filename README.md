# EN-RU

# EN
# Simple Mathematical Parser (multifunctional)

Version 1.6
Version Features:
- Now you can set your expressions with: exp = "sin(x)/x";
- Also you can add functions with addFunction("nameFunction", "e^x + cos(x)");
- Operators +,-,*,/,^ were overloaded (it returns std::string with target expresion)


Version 1.5 (Gold)
Version Features:
- expression expression
- Ability to remove constants and functions
- You can add your own functions to individual instances of the parser.
- All constants and functions are encapsulated in the Oper class. And the changes in the constants concern only one instance of the class.
- The code has been translated to smart pointers (to ensure no leaks)

Parser for processing mathematical expressions (C ++)

* Advantages:
- Any number of spaces, multiplication signs are optional)
- Fast enough (when used repeatedly, it shows that it is better than other parsers of a recursive type.
- Easily expand math functions
- Adding your own constants
- Support for expressions with unknown x

Disadvantage (but with reservation):
Many times slower than top mathematical parsers for C ++. Functionality and extensibility strongly affect the time factor.
I will give an example:
Parser believes that for the unimaginable microseconds of 1869, if you consider that all the time and 181 are one microsecond, if you count only the calculation time:
4p (M / (2pRT)) ^ (3/2) * v ^ 2 * e ^ (- Mv ^ 2 / (2RT))
This means that it is the speed, and not the ability to dynamically expand the parser, to better look in the direction of other options (there are those that believe that the same expressions are less than 400 units).
However, there is a condition: complexity, as well as time and execution time, increase at about this speed.


Read all the information on how to use the library in the Wiki section or see the example in main.cpp



# RU
# Простой Математический Парсер (многофункциональный)

Версия 1.5 (Золотая)
Особенности версии:
- Теперь можно добавлять в качестве функций отдельные выражение Expression
- Возможность удаления констант и функций
- Теперь вы можете добавлять свои собственные функции в отдельные экземпляры парсера
- Все константы и функции инкапсулированы в класс Oper. И измнения констант касаются лишь одного экземлпяра класса.
- Код был переведён на умные указатели (для обеспечения отсутствия утечек)

Простой в использовании (но мощный внутри) парсер  для обработки математических выражений (С++) 

*Достоинства:
- Очень неприхотлив к входной строке (любое количество пробелов, знаки умножения ставить необязательно)
- Достаточно быстрый (при многократном использовании показывает себя куда лучше других парсеров рекурсивного типа. Синтаксический анализ производится лишь один раз при установке нового выражения)
- Легко расширяем (вы без труда можете научить парсер обрабатывать любые ваши (либо стандартные) математические функции)
- Добавление собственных констант
- Поддержка выражений с неизвестным x

*Недостаток (но с оговоркой):
В разы медленнее топовых математических парсеров для C++. Функциональность и расширяемость сильно сказываются на факторе времени.
Приведу пример: 
Такое выражение (распределение Максвелла по скоростям) парсер считает за невообразимые 1869 микросекунд если считать полное время и 181 одну микросекунду, если считать лишь время вычислений: 
4p(M / (2pRT))^(3/2) * v^2 * e^(-Mv^2/(2RT)).
Поэтому если вам важна именно скорость, а не возможность динамически расширять парсер, то лучше посмотреть в сторону других вариантов (есть те, что считают такие же выражения менее чем за 400 наносекунд).
Однако есть оговорка: сложность, а вместе с ней и время выполнения увеличиваются примерно с такой скоростью O(n) = sqrt(x), значит, вы можете не бояться за слишком сложные выражения, так как они не смогут перескочить через допустимые лимиты.


Читайте всю информацию о том, как использовать библиотку в разделе Wiki либо же смотрите пример в main.cpp

