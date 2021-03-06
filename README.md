# SlidingBlocksGoGame

### Играта Sliding blocks представлява следното:
- имате дъска за игра (3х3 или 4х4);
- при 3х3 дъска разполагате с числа от 0 до 8 или букви от a до h и празна позиция; при дъска 4х4 съответно с числа от 0 до 15 или букви от а до o и празна позиция; 
- числата или буквите са разбъркани по случаен начин или въведени от потребителя. 
- целта на играта е плочките да бъдат наредени от 1 до 8, като празната клетка бъде в крайно положение [2,2] или в [0,0]. Аналогично за останалите имплементирани варианти.
- един ход представлява промяна на положението на празната клетка нагоре, надолу, вляво или вдясно от нея.

### Реализирани функционалности:
- възможност за избиране на автоматично или ръчно попълване на матрицата
- възможност за избиране на игра с букви или цифри

### Инсталация:
 - Инсталирайте си Go
 - За да използвате проекта, въведете команда <i> go get github.com/DayanaVV/SlidingBlocksGoGame </i>
    - ако имате проблем с команда <i>go get</i>, клонирайте репото и преместете папка <i>pkg</i> от проекта в <i>C:\Go\src</i> и променете <i>import</i> на <i> "pkg/slidingBlocksBoard" </i> във файлове <i>project.go</i> и <i>project_test.go</i>
 - Навигирайте до мястото, където сте клонирали репото
 - За да пуснете проекта, въведете командата <i> go run project.go </i>
    
### Бъдещи подобрения
 - Създаване на сървър чрез <i>net/http</i> библиотека
 - Възможност за играене на играта от няколко играча
 - Оправяне на А* алгоритъма, така че да може да реши играта
