# Delete Operation

```python
from bookshelf.models import Book

# Get the updated book and delete it
book = Book.objects.get(title="Nineteen Eighty-Four")
book.delete()

# Confirm deletion by checking count
books = Book.objects.all()
print(books.count())  # Output: 0
