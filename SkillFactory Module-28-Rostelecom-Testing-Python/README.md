# SkillFactory Module-28-Rostelecom-Testing-Python
Rostelecom

Итоговый проект на курсе автоматизации тестирования QAP в Skillfactory

Задание:

Протестировать требования.

Разработать тест-кейсы (не менее 15). Необходимо применить несколько техник тест-дизайна.

Провести автоматизированное тестирование продукта (не менее 20 автотестов). Заказчик ожидает по одному автотесту на каждый написанный тест-кейс. Оформите свой набор автотестов в GitHub.

Оформить описание обнаруженных дефектов. Во время обучения вы работали с разными сервисами и шаблонами, используйте их для оформления тест-кейсов и обнаруженных дефектов. (если дефекты не будут обнаружены, то составить описание трех дефектов)


• Были протестированы требования заказчика, и выявлено порядка 30 ошибок, все дефекты были выведены в ввиде комментариев в google docx
https://docs.google.com/document/d/12Bf73gmyY5JWG3clTj8IKoNIQ_QjBl_d/edit?usp=sharing&ouid=113495494993936497942&rtpof=true&sd=true

• Разработаны тест-кейсы и потенциальные баги.
• При разработке тест-кейсов были применены следующие техники тест-дизайна: 
эквивалентное разбиение, 
анализ граничных значений, 
таблица принятия решений,


• Тест-кейсы созданы с помощью инструмента Google-таблицы: https://docs.google.com/spreadsheets/d/1KFP8AjHIrSuj2tJ2-HgrX4FZ-UjAjg3ANCnViOMJ9kY/edit?usp=sharing

• Были написаны автотесты.

• Для тестирования фукнционала сайта был использована библиотека Selenium.

• Для определения локаторов использовались следующие инструменты: DevTools, Element Locator(расширение), генератор случайной строки (Random String Generator)

• При написании автотестов дополнительно установлены библиотеки: pytest(7.2.0), selenium (4.7.2), pytest-selenium(4.0.0).

Для того чтобы запустить тесты, необходимо сделать следующее:
Установить все требования: pip install -r requirements.txt

Загрузите свой Selenium WebDriver с https://chromedriver.chromium.org/downloads (выберите версию, совместимую с вашим браузером)

Запустить тест: python -m pytest -v --driver Chrome --driver-path 'ur dirver path' 'ur test file path'