[< к содержанию](./readme.md)

## **Переключение коммитов**
***
1. Команда __*git checkout [*хеш коммита*]*__ переключает на коммит с указанным хешем (переместить HEAD на указанный коммит, рабочую директорию вернуть к состоянию, на момент этого коммита)
2. Команда __*git checkout master*__ переключает на коммит, на который указывает master (переместить HEAD на коммит, на который указывает master, рабочую директорию вернуть к состоянию на момент этого коммита)
3. Для переключения коммита с целью продолжить работу на ней, отребуется создание новой ветки, начинающейся с указанного коммита:

```bash
git checkout -b new-branch [хеш коммита]
```
Данная команда создает ветку *new-branch*, начинающуюся с коммита c указанным хешем (переместить HEAD на указанный коммит, рабочую директорию вернуть к состоянию, на момент этого коммита, создать указатель на эт.от коммит (ветку) с указанным именем)