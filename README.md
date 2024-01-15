# 6-semestr
лк1 15.01.24

git bash - Это команды для работы с гит из терминала

Установка https://git-scm.com/downloads

Proxy server  git config --global http.proxy 10.0.50.52:3128

https://smartiqa.ru/courses/git/answer-key - Практические задания

![Screenshot_1](https://github.com/zun669/6-semestr/assets/98329205/b3de78dc-3ac7-41d7-8bb5-56035eb11ec3)

Создание репозитория на компьютере: Инециализация Git Init
![Screenshot_2](https://github.com/zun669/6-semestr/assets/98329205/c508bb78-8e5e-4dbb-9753-3531fe462af3)

cmd //c tree .git Показывает структуру папки Git
git status //Показывает статус репозитория 
On branch master //Указывает имя ветки  

No commits yet //Нет сохранённых версий 

Untracked files: //Не отслеживаемые файлы
  (use "git add <file>..." to include in what will be committed) //Нужна команда добавить чтобы зафиксировать версию для сохранений 
список файлов для сохранения:        
        index.html 
        pictures/ 

nothing added to commit but untracked files present (use "git add" to track) //Найдены файлы для добавления 

Настраиваем пользователя Git
# Задаем имя и email пользователя для текущего репозитория 23-20
$ git config --global user.name PK20-12
$ git config --global user.email PK20-12@gmail.com

Отключение прокси
git config --global --unset http.proxy
git config --global --unset https.proxy
git config --global --unset core.gitproxy

![Screenshot_3](https://github.com/zun669/6-semestr/assets/98329205/7f7ee3de-a371-48bb-8573-f0ac56fb7372)
git add * //Добавление всех файлов

git commit -m "G-02: Initial"
Для фиксации версии нужно указать её название, для этого создаётся сообщение -m 

git log
![Screenshot_4](https://github.com/zun669/6-semestr/assets/98329205/400e3242-5ee2-4cf5-b1d3-a5dabf629bab)

Подтверждение Git 
