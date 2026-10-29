# Fix My Code Challenge

## Description
Starting from existing code that contains bugs, each task fixes it without rewriting it from scratch: only the lines needed to make the program behave as the task describes are changed.

## Tasks

| Task | Description | File |
| :--- | :--- | :--- |
| **0. FizzBuzz** | The `% 3` check ran before the `% 3 and % 5` check, so 15 printed `Fizz`. The order of the conditions was swapped. | `challenge/0-fizzbuzz.py` |
| **1. Print square** | `parseInt(..., 16)` read the size in base 16 (10 became 16). Changed to base 10. | `challenge/1-print_square.js` |
| **2. Sort** | The value was inserted at `i - 1` (one position too early). Changed to `i`. | `challenge/2-sort.rb` |
| **3. User password** | The setter stored into `_password` instead of `__password`, and validation compared an uppercase hash against a lowercase stored one. | `challenge/3-user.py` |
| **4. Double linked list** | Deleting a middle node linked the wrong pointers (`prev->prev` instead of `prev->next`) and read `next` after `free` (use-after-free). | `challenge/4-delete_dnodeint/` |

## Author
* **Luis Gonzalez** - Holberton School
