# Bookstore OOP Lab

## Overview

This project uses Python object-oriented programming to model two products sold in a bookstore: books and coffee.

## Features

### Book class
- Stores a book's title and page count.
- Validates that the page count is an integer.
- Provides a `turn_page()` method that prints a page-turning message.

### Coffee class
- Stores the coffee size and price.
- Accepts Small, Medium, or Large as valid sizes.
- Provides a `tip()` method that prints a message and increases the price by 1.

## Project Structure

```text
python-oop1-lab/
├── lib/
│   ├── book.py
│   ├── coffee.py
│   └── testing/
│       ├── book_test.py
│       └── coffee_test.py
├── README.md
└── pytest.ini
```

## Requirements

- Python 3
- pytest

## Run the Tests

From the project root, run:

```bash
pytest -v
```

The project tests cover book creation, page-count validation, turning pages, coffee creation, size validation, and tipping.

## Example Usage

```python
from lib.book import Book
from lib.coffee import Coffee

book = Book("Python Basics", 200)
book.turn_page()

coffee = Coffee("Medium", 3.50)
coffee.tip()
print(coffee.price)
```

## Screenshot:`pytest -v`.

![alt text](<Screenshot 2026-10-18 101220.png>)




## Author

Rozeline Gitau
