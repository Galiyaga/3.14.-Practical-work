[< к содержанию](./readme.md)

## **Перемещение/переименование файлов**
___

> Перед тем, как перейти к командам, важно упомянуть, что в **git** не существует переименования. Переименование воспринимается как удаление старого файла и *создание нового*. Факт переименования может быть определен только после индексации изменения.

1. Команда **git mv text.txt test_new.txt** переименовывает файл *«text.txt»* в *«test_new.txt»* и индексирует это изменение.

2. **git mv readme_new.md folder/** перемещает файл *readme_new.md* в директорию *folder/* (должна существовать) и индексирует это изменение.

