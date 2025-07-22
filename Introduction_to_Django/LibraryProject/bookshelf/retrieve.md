
---

### 2. `retrieve.md`

```markdown
# Retrieve Operation

```python
books = Book.objects.all()
for book in books:
    print(book.title, book.author, book.publication_year)

# Expected Output:
# 1984 George Orwell 1949
