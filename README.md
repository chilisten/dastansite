Это проект на Django. В данном README содержатся инструкции по установке и запуску проекта.
1. Клонируйте репозиторий:

 ```bash
    git clone https://github.com/chilisten/dastansite.git
    cd Dastasitedap
    ```

2. Создайте виртуальное окружение и активируйте его:

    ```bash
    python -m venv venv
    source venv/bin/activate   # Для Windows: venv\Scripts\activate
    ```

3. Установите зависимости:



   
    ```bash
    pip install -r requirements.txt
    ```

4. Выполните миграции базы данных:



   
    ```bash
    python manage.py migrate
    ```


5
5. Создайте суперпользователя:

    ```bash
    python manage.py createsuperuser
    ```


6
6. Запустите сервер разработки:



   
    ```bash
    python manage.py runserver
    ```

