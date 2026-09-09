# lab2-
# 2.1  Подготовка 
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/a2b8d91c-8038-4180-b205-dc1132274437" />
# 2.2 Перенаправление потоков ввода/вывода
# 2.2.1 Создание data.txt
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/9563d6ba-5bc2-491c-9443-05effdc5661c" />
# 2.2.2 Вывел содержимое data.txt на экран с помощью cat.
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/5819be95-2241-4e5d-9f54-79f58fd7cbfb" />
# 2.2.3 Написал вывод команды ls -l в файл list.txt
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/6c5671af-b63c-4b18-9757-de66949eaa3e" />
# 2.2.4 Выполнил команду ls /nonexistent
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/81419c89-8787-41ed-ada8-579bef5daf80" />
# 2.2.5 Используя grep, отфильтровал из data.txt строки, содержащие "a", и записал результат в filtered.txt
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/0a8e47ac-8fa5-4479-bee2-aa6c3933a084" />
# 2.2.6 С помощью >> добавил в filtered.txt строку "grape 15"
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/ebba73cc-8a45-405c-908d-d33883c01554" />
# 2.3  Работа с разными интерпретаторами  
# 2.3.1 Запустил оболочку sh (sh). Выполнил echo $SHELL. 
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/29fcaa99-97d8-42ee-a5bf-7fed06452831" />
# 2.3.2 Запустил zsh. Выполнил echo $SHELL
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/b3fe0477-4438-4217-a37b-2d8f9fe46448" />
# 2.3.2.1 Создал временный алиас ll='ls -la' и проверил его. 
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/0556fc67-7619-4224-b527-db90f86a9dac" />
# 2.3.2.2 Создал переменную окружения export MY_VAR="hello from zsh". 

# 2.3.2.3 Запускаем Bash из Zsh

# 2.3.3 fish
# 2.3.3.1 alias в fish

# 2.3.3.2 Переменная окружения

# 2.3.4 Проверил: echo $MY_VAR. Выйдите из fish.

# 2.3.5 Отчёт
В Bash и Zsh алиас создаётся с помощью команды alias, например alias ll='ls -la'. В fish используется другой синтаксис- alias ll 'ls -la'. Переменные окружения также задаются по-разному: в Bash/Zsh используется export MY_VAR="...", а в fish-set -x MY_VAR "...".
# 2.4 Объединение команд и конвейеры
# 2.4.1 
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/20e4f78b-015e-48ce-b808-53f253d42674" />
# 2.4.2 
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/6492a459-505b-4ce1-9ddc-247405eca1ad" />
# 2.4.3 Сымитируйте ошибку: rm notexist.txt || echo "File not found"
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/044ad613-93ed-4f55-8427-8c53abe8b654" />
# 2.4.4 конвейер из трёх команд
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/d03fdf70-917b-4ccf-92d1-1a2027f1fe88" />
# 2.4.5 Количество процеессов
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/bcef7b9e-5217-4f14-871a-f3c1666d5c88" />
# 2.5 Создание временных алиасов 
# 2.5.1 В текущей сессии bash создайте алиас lll='ls -l | grep "^d"'.
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/8e5ec9a1-281b-498c-9eb3-23aba3c5b7f6" />
# 2.5.2 
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/15a08a34-bdb8-4d79-8563-c41303bcfec3" />
