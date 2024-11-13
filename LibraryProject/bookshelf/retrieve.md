# Create Operation

To retrieve a `Book` instance in the Django shell, use the following command:

```python
book = Book.objects.create(title="1984", author="George Orwell", published_date=1949)
```

# Output 

<QuerySet [<Book: Book object (2)>]>