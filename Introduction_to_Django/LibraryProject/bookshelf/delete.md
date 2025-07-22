
---

### 4. `delete.md`

```markdown
# Delete Operation

```python
book = Book.objects.get(title="Nineteen Eighty-Four")
book.delete()

books = Book.objects.all()
print(books.count())  # Output: 0
