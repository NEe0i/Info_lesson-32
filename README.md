# Info_lesson-32 
1. Фон-Неймановская архитектура была разработана в 1940-х годах, и многие эксперты признают вклад других исследователей, таких как Гарднер Мердок, Сара Б. Клат и других, которые также активно работали над концепциями, касающимися структуры ЭВМ
2. Единая память: Программа и данные хранятся в одной и той же памяти,

   Последовательность выполнения: Инструкции выполняются последовательно,

   Ввод и вывод: Поддержка управления вводом и выводом,

   Состояние машины: Состояние машины определяется её памятью и счетчиком
   
3. Процессор: Обрабатывает данные и выполняет арифметические и логические операции.
   
   Память: Хранит данные и программы.
   
   Устройства ввода/вывода: Обеспечивают взаимодействие с пользователем и внешними устройствами.
   
   Шина данных: Передает данные между компонентоми

4. представлении информации с использованием двух символов: 0 и 1
5. Числа кодируются в двоичном формате. Тексты кодируются с использованием стандартов, таких как ASCII или UTF-8, которые также основаны на двоичном кодировании. Графика представлен как пиксели, каждый из которых также кодируется в двоичном формате
6. Чтобы перевести десятичное число в двоичное:

 Делите число на 2 
 
 Записывайте остаток.
 
 Повторяйте, пока число не станет равным 0.
 
 Читайте остатки снизу вверх.

 Для перевода обратно:

 Читайте двоичное число справа налево.

 Умножайте каждую единицу на 2 в степени позиции (начиная с 0) и складывайте результаты. 

7. это минимальная адресуемая единица памяти, которая хранит данные. Адрес ячейки — это уникальный идентификатор
8. варьировалась от 8 бит в первых системах до 64 бит в современных устройствах.
9. для упрощения обращения к данным и управления памятью
10. Да, это возможно. Современные ячейки памяти, такие как флеш-память и ОЗУ, организованы таким образом, что отдельные биты могут модифицироваться без влияния на соседние биты.
11. Целые числа (int): разрядность 32 бита, 4 байта.
    
    Символы (char): разрядность 8 бит, 1 байт.
    
    Числа с плавающей запятой (float): разрядность 32 бита, 4 байта.
    
    Двойные числа (double): разрядность 64 бита, 8 байт.

12. это структура, в которой память организована в слои с различной скоростью и объемом.
13. она построена для хранения больших объемов данных, а не для быстрого доступа к небольшому объему
14. иструкции программы и данные, которые они используют, хранятся в одной памяти, что позволяет компьютеру извлекать и выполнять инструкции последовательно
15. в оперативной памяти (ОЗУ), на жестком диске, твердотельном накопителе
16. применять в определенных контекстах, таких как кодирование 
17. все операции, выполняемые компьтером, основаны на заранее заданной последовательности команд
18. 1Извлечение команды из памяти. 2Декодирование команды. 3Выполнение команды. 4Сохранение результата, если требуется, в памяти
19. это регистр, который хранит адрес следующей команды для выполнения. Он обеспечивает последовательное выполнение команд, увеличиваясь на единицу
20. При включении компьютера происходит загрузка начальных программ (BIOS или UEFI), которые проверяют оборудование и загружают операционную систему из памяти (например, с диска) в оперативную память
21. да, для реализации циклов, условий и других управляющих структур
22. да
23. это архитектурный подход, который позволяет одновременно обрабатывать несколько этапов исполнения различных команд
24. поскольку заранее предсказанная следующая команда может оказаться неверной, и системе придется откат
25. Некоторые основы, такие как использование двоичной арифметики и принцип хранения программ, продолжают работать без изменений. Однако многое было изменено, например, в организации памяти и архитектуре для повышения скорости и эффективности. Это требовалось из-за роста сложности вычислений и потребности в эффективных ресурсах
26. это концептуальная организация компьютера, включая набор инструкций, способы работы с памятью и взаимодействие между компонентам
27. позволяет создавать совместимые устройства и программное обеспечение, что упрощает обучение пользователей и облегчает работу разработчиков
28. Семейства вычислительных машин включают x86, ARM, SPARC, MIPS, PowerPC и другие, каждая из которых имеет свои особенности и применения


ЗАДАЧИ 

1. А) Установить младший бит в единицу:
   
Считать байт из памяти в регистр A

В регистр A выполнить операцию "ИЛИ" с маской 00000001

Записать байт обратно в память из регистра A

Б) Сбросить младший бит в ноль:

-Считать байт из памяти в регистр A

-В регистр A выполнить операцию "И" с маской 11111110

-Записать байт обратно в память из регистра A 

2. 40:8=5
3. 65535
4. 4116
5. A=41, B=42 и т.д., в зависимости от содержания
6. Сравнивая коды команд, вы сможете найти совпадения с кодами, которые вы нашли в текстовом и графическом файлах, если коды команд совпадают с кодами символов, используемыми в текстовых файлах
