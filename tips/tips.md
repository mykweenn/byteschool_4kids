# Небольшая памятка

### 1. **Синтаксис**: GDScript имеет простой и понятный синтаксис, похожий на Python. Он не требует объявления типов переменных.

#### Типы переменных:

   **int** (целое число):

   ``` gdscript
   var score : int = 100
   ```

**float** (число с плавающей точкой):

   ``` gdscript
   var pi : float = 3.14
   ```

**String** (строка):
   ``` gdscript
   var playerName : String = "Player1"
   ```

**bool** (логическое значение):
   ``` gdscript
   var isGameOver : bool = false
   ```

**Array** (массив):
   ``` gdscript
   var numbers : Array = [1, 2, 3, 4, 5]
   ```

**Dictionary** (словарь):
   ``` gdscript
   var playerData : Dictionary = {"name": "Alice", "score": 100}
   ```

**Vector2** (двумерный вектор):
   ``` gdscript
   var position : Vector2 = Vector2(10, 20)
   ```

**Color** (цвет):
   ``` gdscript
   var backgroundColor : Color = Color(0.2, 0.3, 0.5)
   ```

   
### 2. **Переменные**: Переменные объявляются с помощью ключевого слова var. Пример:

   ``` gdscript
   var health = 100
   ```

### 7. **Функции**: Функции объявляются с помощью ключевого слова func. Пример: 

   ``` gdscript
   func _ready():
       print("Готово!")
   ```

### 8. **Условные операторы**: Используй `if`, `elif` и `else` для выполнения различных действий в зависимости от условий.
   ``` gdscript
   func checkHealth(health):
    if health > 75:
        print("Здоровье отличное!")
    elif health > 50:
        print("Здоровье нормальное.")
    elif health > 25:
        print("Здоровье низкое.")
    else:
        print("Опасное состояние здоровья!")
   
   # Пример вызова функции с разными значениями здоровья
   checkHealth(80)  # Выведет "Здоровье отличное!"
   checkHealth(60)  # Выведет "Здоровье нормальное."
   checkHealth(20)  # Выведет "Опасное состояние здоровья!"
   ```   

   
### 9. **Циклы**: Используй `for` и `while` для выполнения действий в цикле.

   ``` gdscript
   func countToTen():
       for i in range(1, 11):  # Цикл от 1 до 10
           print(i)
   
   func printNames(names):
       for name in names:  # Цикл по элементам списка
           print(name)
   
   func main():
       countToTen()  # Выведет числа от 1 до 10
       var studentNames = ["Анна", "Петр", "Иван", "Мария"]
       printNames(studentNames)  # Выведет имена студентов из списка
   ```

   
### 10. **Сигналы**: GDScript поддерживает сигналы для обработки событий. Используй `signal` для объявления сигнала и `emit_signal()` для его вызова.

### 11. **Узлы и узловые переменные**: GDScript используется вместе с Godot Engine для работы с узлами (Node). Используй узловые переменные для доступа к другим узлам в вашей игре.

### 12. **Методы жизненного цикла**: Используй методы `_ready()`, `_process(delta)`, `_physics_process(delta)` и другие для управления поведением вашего узла в различных состояниях.

### 13. **Комментарии**: Используй # для однострочных комментариев и """ """ для многострочных комментариев.

