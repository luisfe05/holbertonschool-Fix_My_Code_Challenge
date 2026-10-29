# Fix My Code Challenge

Proyecto "Fix my code": se parte de código existente que tiene errores y se corrige sin reescribirlo desde cero. Cada tarea cambia solo las líneas necesarias para que el programa se comporte como indica el enunciado.

## Archivos y Tareas

| Tarea | Archivo | Error corregido |
| :--- | :--- | :--- |
| **0. FizzBuzz** | `challenge/0-fizzbuzz.py` | La condición `% 3` se evaluaba antes que la de `% 3 and % 5`, así que 15 imprimía `Fizz`. Se invirtió el orden de las condiciones. |
| **1. Print square** | `challenge/1-print_square.js` | `parseInt(..., 16)` leía el tamaño en base 16 (10 → 16). Se cambió a base 10. |
| **2. Sort** | `challenge/2-sort.rb` | Se insertaba en `i - 1` (una posición antes). Se cambió a `i`. |
| **3. User password** | `challenge/3-user.py` | El setter guardaba en `_password` en lugar de `__password`, y la validación comparaba el hash en mayúsculas contra uno guardado en minúsculas. |
| **4. Double linked list** | `challenge/4-delete_dnodeint/` | Al borrar un nodo intermedio se enlazaba mal (`prev->prev` en vez de `prev->next`) y se leía `next` después de `free` (use-after-free). |

## Autor
* **Luis Gonzalez** - Holberton School
# holbertonschool-Fix_My_Code_Challenge
