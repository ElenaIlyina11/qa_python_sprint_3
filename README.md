# Автоматизация тестов для сайта https://stellarburgers.nomoreparties.site/

### Для начала работы:
1. Установи webdriver: 
```
https://www.selenium.dev/documentation/webdriver/getting_started/install_drivers/
Мы используем webdriver, который доступен из PATH
```
2. Установи зависимости из requirements.txt
```
pip3 install -r requirements.txt
```
3. Запусти тесты из корневого каталога проекта:
```
pytest -v ./tests/
```

### Содержимое проекта:
```
README.md - этот файл
requirements.txt - зависимости, основные
./tests/ - каталог с тестами
./tests/conftest.py - конфигурация проекта, фикстуры, переиспользуемые функции
./tests/locators.py - локаторы которые используются в проекте
./tests/test_login.py - тесты которые проверяют аутентификация
./tests/test_logout.py - тесты которые проверяют выход из аккаунта
./tests/test_navigate_from_pa_to_constructor.py - тесты для проверки навигации из личного аккаунта в конструктор
./tests/test_navigate_into_constructor.py - тесты для проверки навигации по конструктору бургеров
./tests/test_navigate_to_personal_account.py - тесты для проверки навигации в персональный аккаунт
./tests_registration.py - тесты для проверки регистрации
```