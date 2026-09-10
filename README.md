# lab2-
# 2.1  Подготовка 
![src1](https://github.com/user-attachments/assets/a2b8d91c-8038-4180-b205-dc1132274437)
# 2.2 Перенаправление потоков ввода/вывода
# 2.2.1 Создание data.txt
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/9563d6ba-5bc2-491c-9443-05effdc5661c" />
# 2.2.2 Вывел содержимое data.txt на экран с помощью cat.
![src1](https://github.com/user-attachments/assets/5819be95-2241-4e5d-9f54-79f58fd7cbfb)
# 2.2.3 Написал вывод команды ls -l в файл list.txt
![src1](https://github.com/user-attachments/assets/6c5671af-b63c-4b18-9757-de66949eaa3e)
# 2.2.4 Выполнил команду ls /nonexistent
![src1](https://github.com/user-attachments/assets/81419c89-8787-41ed-ada8-579bef5daf80)
# 2.2.5 Используя grep, отфильтровал из data.txt строки, содержащие "a", и записал результат в filtered.txt
![src1](https://github.com/user-attachments/assets/0a8e47ac-8fa5-4479-bee2-aa6c3933a084)
# 2.2.6 С помощью >> добавил в filtered.txt строку "grape 15"
![src1](https://github.com/user-attachments/assets/ebba73cc-8a45-405c-908d-d33883c01554)
# 2.3  Работа с разными интерпретаторами  
# 2.3.1 Запустил оболочку sh (sh). Выполнил echo $SHELL. 
![src1](https://github.com/user-attachments/assets/29fcaa99-97d8-42ee-a5bf-7fed06452831)
# 2.3.2 Запустил zsh. Выполнил echo $SHELL
![src1](https://github.com/user-attachments/assets/b3fe0477-4438-4217-a37b-2d8f9fe46448)
# 2.3.2.1 Создал временный алиас ll='ls -la' и проверил его. 
![src1](https://github.com/user-attachments/assets/0556fc67-7619-4224-b527-db90f86a9dac)
# 2.3.2.2 Создал переменную окружения export MY_VAR="hello from zsh". 
![src1](https://github.com/user-attachments/assets/0649697d-a4c0-481d-b145-4a1625858272)
# 2.3.2.3 Запускаем Bash из Zsh
![src1](https://github.com/user-attachments/assets/3a934ec0-5dd5-4d98-8953-8ffd1ea987d4)
# 2.3.3 fish
![src1](https://github.com/user-attachments/assets/a7ef63d4-a937-446b-8d63-fc40a5cc4ba1)
# 2.3.3.1 alias в fish
![src1](https://github.com/user-attachments/assets/a0e7d119-fe94-4e25-89e0-ae6bcf7e3c3b)
# 2.3.3.2 Переменная окружения
![src1](https://github.com/user-attachments/assets/96580fa4-d98d-4bdc-b51e-fe681ea801b4)
# 2.3.4 Проверил: echo $MY_VAR. Выйдите из fish.
![src1](https://github.com/user-attachments/assets/5912ffd2-5853-47e1-bd17-f2072a55ca05)
# 2.3.5 Отчёт
В Bash и Zsh алиас создаётся с помощью команды alias, например alias ll='ls -la'. В fish используется другой синтаксис- alias ll 'ls -la'. Переменные окружения также задаются по-разному: в Bash/Zsh используется export MY_VAR="...", а в fish-set -x MY_VAR "...".
# 2.4 Объединение команд и конвейеры
# 2.4.1 
![src1](https://github.com/user-attachments/assets/20e4f78b-015e-48ce-b808-53f253d42674)
# 2.4.2 
![src1](https://github.com/user-attachments/assets/6492a459-505b-4ce1-9ddc-247405eca1ad)
# 2.4.3 Сымитируйте ошибку: rm notexist.txt || echo "File not found"
![src1](https://github.com/user-attachments/assets/044ad613-93ed-4f55-8427-8c53abe8b654)
# 2.4.4 конвейер из трёх команд
![src1](https://github.com/user-attachments/assets/d03fdf70-917b-4ccf-92d1-1a2027f1fe88)
# 2.4.5 Количество процеессов
![src1](https://github.com/user-attachments/assets/bcef7b9e-5217-4f14-871a-f3c1666d5c88)
# 2.5 Создание временных алиасов 
# 2.5.1 В текущей сессии bash создайте алиас lll='ls -l | grep "^d"'.
![src1](https://github.com/user-attachments/assets/e7e7c3cc-8d43-41e0-998b-727ed51c929a)
# 2.5.2 
![src1](https://github.com/user-attachments/assets/15a08a34-bdb8-4d79-8563-c41303bcfec3)
# 2.5.3
![src1](https://github.com/user-attachments/assets/49d7445a-5fc7-4a72-8245-b4b0e617814f)
# 2.5.4
![src1](https://github.com/user-attachments/assets/ecaf2f67-82fc-494b-9313-e5dfe0bef0c1)
# 2.6 Создание постоянных алиасов
# 2.6.1 Отредактируйте файл ~/.bashrc. 
![src1](https://github.com/user-attachments/assets/1797eb88-da2d-470b-a950-9c6163cfb8c2)
# 2.6.2 Примените изменения: source ~/.bashrc.
![src1](https://github.com/user-attachments/assets/ff585538-a938-478c-85f7-c21a5ea2d975)
# 2.6.3 Проверьте работу алиасов: up (можно отменить Ctrl+C), myip. 
![src1](https://github.com/user-attachments/assets/7bc804c6-350a-43bf-83cb-c2f433db5530)
# 2.6.4 
# zsh
![src1](https://github.com/user-attachments/assets/c779991b-ea17-4bca-bb1c-b1f3e4dd1dfe)
# fish
![src1](https://github.com/user-attachments/assets/246648ed-1ba6-4ba9-ad35-77a3023ba52c)
# 2.7 Временные переменные окружения
# 2.7.1 В bash создайте локальную переменную TEMP_VAR="temporary". 
![src1](https://github.com/user-attachments/assets/b36abd55-6387-4bb5-902c-84515bca9740)
# 2.7.2 Выполните echo $TEMP_VAR.
![src1](https://github.com/user-attachments/assets/36663de0-fe25-475c-ac07-e6934086a7d3)
# 2.7.3 Запустите bash (дочерняя оболочка) и попробуйте вывести echo $TEMP_VAR. 
![src1](https://github.com/user-attachments/assets/68ca7118-6a76-4946-a8e0-fb00cee4b63c)
Ничего не происходит потому что я зашёл в ещё один bash в нутри bash и тут ничего нет
# 2.7.4 Выйдите из дочерней оболочки (exit). Создайте экспортируемую переменную: 
![src1](https://github.com/user-attachments/assets/893fe2be-6a61-4cf8-9cd4-c7c441a42cbf)
# 2.7.5 Запустите bash и проверьте echo $GLOBAL_VAR.
![src1](https://github.com/user-attachments/assets/e8afe2aa-f2c9-4d2b-a1fd-03757c99ed27)
# 2.7.6 Удалил переменную: unset GLOBAL_VAR.
![src1](https://github.com/user-attachments/assets/7257a642-df30-4e22-ba72-88679f0e7ed9)
# 2.8 Постоянные переменные окружения
# 2.8.1 Добавьте в ~/.bashrc строку
![src1](https://github.com/user-attachments/assets/6936c80a-0f35-4a2d-8fbc-2e31f170c3f6)
# 2.8.2 Выполните source ~/.bashrc. 
# 2.8.3 Проверьте: echo $EDITOR. 
![src1](https://github.com/user-attachments/assets/71f8af46-3844-48c6-a92f-1a8ee22df48c)
# 2.8.4 Добавьте также export WORKSPACE="$HOME/lab2". 
![src1](https://github.com/user-attachments/assets/ea97a054-c96c-454c-bf6c-8120c8cb405b)
# 2.8.5 Проверьте, что после перезапуска терминала эти переменные остаются. 
![src1](https://github.com/user-attachments/assets/f7c61594-1114-4fc2-a56a-13dc4b3a7418)
# 2.9 Комплексный скрипт (закрепление) 
![src1](https://github.com/user-attachments/assets/07749757-94fc-4ec3-9a18-36a0de1241ca)
![src1](https://github.com/user-attachments/assets/cf1eb01b-5a9e-4b08-863c-a97be3c8ea9f)
![src1](https://github.com/user-attachments/assets/d3b181e0-c443-4930-9e54-bacfafbfb385)
![src1](https://github.com/user-attachments/assets/ec090bfe-11bd-4a9c-9f57-1e0a2c2a50a4)
![src1](https://github.com/user-attachments/assets/1aa12bab-accd-4fb8-a4d6-2eef1b8d9b14)
# 4 Контрольные вопросы
# 4.1 Чем отличается перенаправление > от >>? Приведите пример.
> перезаписывает файл, >> дописывает в конец (пример: echo "Hi" > f.txt, затем echo "Bye" >> f.txt)
# 4.2  В чём разница между команда1 ; команда2 и команда1 && команда2? 
команда1 ; команда2 — выполняются подряд вне зависимости от успеха; команда1 && команда2 — вторая только при успехе первой (пример: mkdir d && cd d).
# 4.3  Как объединить стандартные потоки stdout и stderr в один файл?
Объединить stdout и stderr: cmd > file 2>&1 или cmd &> file.
# 4.4 Что такое алиас? Как сделать его постоянным в bash, zsh, fish? 
Алиас — псевдоним команды; в bash/zsh добавляют в ~/.bashrc/~/.zshrc, в fish — в ~/.config/fish/config.fish.
# 4.5  Зачем нужно export перед переменной? Как сделать переменную окружения постоянной? 
export делает переменную видимой для дочерних процессов; для постоянства прописывают export VAR=val в конфиг оболочки.
# 4.6 Какая команда позволяет посмотреть все текущие переменные окружения? 
Посмотреть переменные окружения: env или printenv.
# 4.7 Как передать вывод одной команды на ввод другой? Приведите пример. 
Передать вывод одной команды на ввод другой — через конвейер | (пример: ls | grep txt).
# 4.8 Назовите основные отличия fish от bash в синтаксисе алиасов и переменных (по наблюдениям). 
В fish синтаксис алиасов и переменных отличается: алиасы часто задают через функции, переменные — командой set -x.
# 4.9  Как в одном процессе перенаправить stdin из файла и одновременно stdout в другой файл?
Перенаправить stdin из файла и stdout в другой файл в одном процессе: cmd < in.txt > out.txt
