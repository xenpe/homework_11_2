# Тестирование

Проект был протестирован с использованием библиотеки `pytest`.

В проекте реализованы следующие тесты:

Тесты для функции маскирования карт (get_mask_card_number):

Проверка корректного маскирования номеров карт.
Проверка граничных случаев и нестандартных входных данных.
Обработка исключений для номеров карт, длина которых не соответствует 16 цифрам.
Тесты для функции маскирования счетов (get_mask_account):

Проверка корректного маскирования номеров счетов.
Обработка случаев с разными длинами номеров.
Обработка исключений для номеров счетов, длина которых меньше 4 цифр.

  
   