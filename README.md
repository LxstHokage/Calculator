# Калькулятор

Проект представляет собой окно Windows form, выполняющее базовые функции калькулятора.

В окне расположены кнопки "+", "-", "*", "\" и "="

При нажатии  на каждую из них осуществляется соотвествующая алгебраическая операция.

# Пример работы:
- Ввод числа
- Выбор операции
- Ввод второго числа
- Нажать "=" - вывод результата

Фрагмент кода, отвечающий за распознавание операции
```
if (operation == "+") textResult->Text = Convert::ToString(number1 + number2);
	if (operation == "-") textResult->Text = Convert::ToString(number1 - number2);
	if (operation == "*") textResult->Text = Convert::ToString(number1 * number2);
	if (operation == "/") textResult->Text = Convert::ToString(number1 / number2);
 ```

Внешний вид калькулятора

![image](https://github.com/LxstHokage/Calculator/assets/109164076/f28afdba-ddcc-463f-b2af-3eea61c9a096)



Контакты автора:

[VK](https://vk.com/lxsthokage)
[Telegram](https://t.me/lasthxkage)
