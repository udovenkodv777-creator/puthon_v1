# Python 

## Модуль 4

----------------------
Для загрузки на GitHub

1 - git add . - добавляет файлы в индекс
2 - git commit -m "Add new file" - добавляет комментарий к индексу 
3 - git push -u origin main - добавить в github 

---
Для выгрузки из GitHub
4 - git pull https://github.com/udovenkodv777-creator/puthon_v1.git

---

27/04/26
---

:wq - сохранить в Vim при конфликтах 

<=======
<<<<<<< HEAD
Text !!
=====> 
=======
ПОПЫТКА 2 - ПРАКТИКА СОХРАНЕНИЯ ИЗМЕНЕНИЙ В ФАЙЛАХ!
=====>
>>>>>>> 01f0e88f6acabd519aa6d6160b0d04412da621b7


---

28/04/26

Если на сервере (в GitHub) появились изменения, которых нет у вас на компьютере. Git не разрешает делать push, чтобы вы случайно не стерли чужую (или свою же, сделанную с другого устройства) работу.

нужно сделать прямо сейчас:
1. Заберите изменения из облака:
bash
git pull origin main
2. Если возникнет ошибка "refusing to merge unrelated histories":
bash
git pull origin main --allow-unrelated-histories
3. Отправьте свои данные в GitHub:
После успешного выполнения pull ваш код и код из облака "склеятся", и тогда push сработает:
bash
git push origin main

---