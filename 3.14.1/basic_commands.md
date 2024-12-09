[< к содержанию](./README.md)
# Основные команды GIT
<table>
  <tr>
    <th>Команда</th>
    <th>Синтаксис</th>
  </tr>
  <tr>
    <td>Задать имя пользователя
    </td>
    <td>git config --global user.name "Tara Routray"</td>
    </tr>
  <tr>
    <td>Задать адрес электронной почты</td>
    <td>git config --global user.email "dev@tararoutray.com"</td>
  </tr>
  <tr>
    <td> Инициализация репозитория
    </td>
    <td>git init</td>
    </tr>
  <tr>
    <td>Добавление отдельных файлов или всех файлов в область подготовленных файлов</td>
    <td>git add somefile.js или  git add .</td>
  </tr>
  <tr>
    <td> Проверка статуса репозитория
    </td>
    <td>git status</td>
    </tr>
  <tr>
    <td>Создание коммита</td>
    <td>git commit -m "Your short summary about the commit"</td>
  </tr>
  <tr>
    <td> Проверка статуса репозитория
    </td>
    <td>git status</td>
    </tr>
  <tr>
    <td>Создание коммита</td>
    <td>git commit -m "Your short summary about the commit"</td>
  </tr>
  <tr>
    <td>Просмотр истории коммитов с изменениями
    </td>
    <td>git log -p</td>
    </tr>
  <tr>
    <td>Просмотр заданного коммита</td>
    <td>git show 1af17e73721dbe0c40011b82ed4bb1a7dbe3ce29</td>
  </tr>
  <tr>
    <td>Просмотр изменений до коммита
    </td>
    <td>git diff</td>
    </tr>
  <tr>
    <td>Удаление отслеживаемых файлов из текущего рабочего дерева</td>
    <td>git rm dirname/somefile.js</td>
  </tr>
  <tr>
    <td>Переименование файлов
    </td>
    <td>git mv dir1/somefile.js dir2</td>
    </tr>
  <tr>
    <td>Отмена подготовленных и неподготовленных изменений</td>
    <td>git checkout somefile.js</td>
  </tr>
  <tr>
    <td>Изменение последнего коммита
    </td>
    <td>git commit --amend -m "Updated message for the previous commit"</td>
    </tr>
  <tr>
    <td>Откат последнего коммита</td>
    <td>git revert HEAD</td>
  </tr>
  <tr>
    <td>Откат заданного коммита</td>
    <td>git revert 1af17e</td>
    </tr>
  <tr>
    <td>Создание новой ветки и переход в неё</td>
    <td>git branch new_branch_name</td>
  </tr>
  <tr>
    <td>Просмотр списка веток</td>
    <td>git branch</td>
    </tr>
  <tr>
    <td>Удаление ветки</td>
    <td>git branch -d existing_branch_name</td>
  </tr>
  <tr>
    <td>Слияние двух веток</td>
    <td>git merge existing_branch_name</td>
    </tr>
  <tr>
    <td>Прекращение слияния при конфликте</td>
    <td>git merge --abort</td>
  </tr>
  <tr>
    <td>Добавление удалённого репозитория</td>
    <td>git remote add awesomeapp https://github.com/...</td>
    </tr>
  <tr>
    <td>Получение дополнительных сведений об удалённом репозитории</td>
    <td>git remote show origin</td>
  </tr>
  <tr>
    <td>Отправка изменений в удалённый репозиторий</td>
    <td>git push origin main</td>
    </tr>
  <tr>
    <td>Получение изменений из удалённого репозитория</td>
    <td>git pull</td>
  </tr>
  <tr>
    <td>Слияние удалённого репозитория с локальным</td>
    <td>git merge origin</td>
    </tr>
  <tr>
    <td>Отправка новой ветки в удалённый репозиторий</td>
    <td>git push -u origin new_branch</td>
  </tr>
  <tr>
    <td>Удаление удалённой ветки</td>
    <td>git push --delete origin existing_branch</td>
    </tr>
  <tr>
    <td>Использование перебазирования</td>
    <td>git rebase branch_name</td>
  </tr>
</table>