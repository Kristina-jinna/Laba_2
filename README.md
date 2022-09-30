# Практическая работа 2. Git

Данная практическая разделена на 3и части, необходимо выполнить все 3и части (на защите показывать все шаги и использовать определенный набор команд). 
При выполнении данной работы использовать только терминал. 

# Часть 1. Составление архитектуры проекта (базовые операции git)

Необходимо создать репозиторий со следующей архитектурой как на рисунке (смотри в корнепой папке репы Рисунок 1). Запушите проект на GitHub/GitLab.

При этом необходимо на каждый новый добавленый файл создавать новый коммит, у всех коммитов должны быть адекватные/говорящие названия.

- Создайте репозиторий внутри папки (инициализация). 

- Настройте пользователя Git на уровне репозитория.

  -- Для этого вам необходимо настроить user_name и email пользователя, зафиксировать/проверить изменеия в .git/config.
  -- Использовать для демонтрации только команды терминала.
  -- Объясните какая информация храниться в этом файле.

- Изучите содержимое папки .git/objects.
 
  -- Продемонстрируйте .git/index и поясните когда появляется файл индекса. Продемонстрируйте .git/objects и убедитесь, что указатель HEAD указывает на ветку main
  -- Демонстрация разницы между коммиатами. 



# Часть 2. Restore, rm, reset, checkout, commit, revert

- Для выполения данной части, вам необходимо склонировать проект из Части 1 в отдельную папку и вам понадобятся ветки которые указаны на Рисунке 2. 

- Работа с веткой feature - добавьте изменения в код ветки feature, добавить на гит данные изменения с использованием коммита. Далее предположим, что в данном коммите  допущена ошибка. Откатите этот коммит.

- Работа с веткой develop - добавьте два отдельных коммита в ветку develop.  Объедините их в один коммит и напишите к нему пояснение.

- Постройте полный граф истории, чтобы познакомиться со структурой коммитов.

- Работа с веткой develop

  -- Влейте ветку develop в ветку main явным образом (с созданием merge-коммита).
  -- Удалите коммит слияния, чтобы затем выполнить слияние в fast-forward режиме.
  -- Влейте ветку develop в ветку main неявным образом (без создания merge-коммита - в режиме fast-forward).

- Работа с веткой release

  -- Выполните интерактивный ребейз ветки release на ветку main - объедините все коммиты в один и поменяйте их общее сообщение. 
Разрешите конфликты.
  -- Выполните fast-forward слияние ветки release в ветку main.
  
  # Часть 3. 
