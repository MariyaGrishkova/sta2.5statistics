**Дано:**
Счетчики:
1. INSTRUCTION
2. LINE
3. BRANCH

Описание счётчиков:
* INSTRUCTION - считает количество инструкций в байт коде, которые выполняются
* LINE - проверяет исполненный код по полям. Если выполнена хотябы одна инструкция в поле - код выполнен
* BRANCH - проверяет процент покрытия кода в ветках (if, else, switch), так как у нас код с условием if выбран для проверки покрытия кода. 