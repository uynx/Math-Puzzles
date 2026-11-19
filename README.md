# Math-Puzzles

Two Python scripts I wrote for my math puzzles class to simulate and demonstrate two classic puzzles at scale using only the Python standard library.

## Scripts

* `mathpuzzles1.py`: simulates the blindfolded red and black coin-pile puzzle (with 25 red coins, take 25 coins and flip all 25 so both piles end up with the same number of red coins).
* `mathpuzzles2.py`: simulates the 10-person, 10-color hat puzzle using modular arithmetic (`sum % 10 == index`) so at least one person is guaranteed to guess right.

## Running them

```bash
python3 mathpuzzles1.py
python3 mathpuzzles2.py
```
