# RegistryController
## Тема: 
  Розробка утиліти для очищення реєстру системи.
## Мета:
  Метою створення програми є забезпечення користувачам можливості ефективно очищати реєстр системи від застарілих або непотрібних записів, що дозволить підтримувати оптимальну продуктивність та швидкодію комп'ютера.
## Цілі:
- Забезпечити простий та зручний інтерфейс користувача для роботи з реєстром системи.
- Здійснити аналіз реєстру для виявлення невалідних або застарілих записів.
- Надати можливість видалення непотрібних записів з реєстру для оптимізації його роботи.
## Технічна частина, що використовується в проєкті
   ### Backend
- В якості мови програмування використовується C++.
- Для зчитування та аналізу реєстру використовуються функції з бібліотеки Windows.h.
- RegistryReader: Цей клас відповідає за зчитування даних з реєстру за заданим шляхом. Він містить метод readRegistry, який приймає шлях до реєстру як вхідний параметр та повертає вектор пар ключ-значення, які представляють записи з реєстру.
- RegistryAnalyzer: Цей клас відповідає за аналіз записів реєстру для виявлення невалідних або застарілих записів. Він містить метод analyzeRegistry, який приймає вектор записів з реєстру як вхідний параметр та повертає вектор невалідних записів.
- RegistryCleaner: Цей клас відповідає за видалення невалідних записів з реєстру. Він містить метод cleanRegistry, який приймає шлях до реєстру та вектор невалідних записів як вхідні параметри та видаляє ці записи з реєстру.
   ### Console Interface
- Консольний інтерфейс дозволяє користувачеві вибирати опції програми та взаємодіяти з нею.
- Користувач може зчитувати реєстр, аналізувати його та видаляти непотрібні записи.
  # Опис роботи програми
    ## Зчитування реєстру
- Програма дозволяє користувачеві зчитувати вміст реєстру за вказаним шляхом.
    ## Аналіз реєстру
 - Після зчитування реєстру програма аналізує його для виявлення невалідних або застарілих записів.
    ## Очищення реєстру
 - Після аналізу користувач може видалити непотрібні записи з реєстру для підтримки його оптимальної роботи.
   ## Очікуваний результат
 - Створити утиліту для очищення реєстру системи від застарілих та непотрібних записів, що дозволить зберігати оптимальну продуктивність та швидкодію комп'ютера.
