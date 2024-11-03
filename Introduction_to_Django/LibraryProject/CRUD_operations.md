>>> from bookshelf.models import Book
>>> new_book=Book.objects.create(title="1984", author="George Orwell",publication_year=1949)        
>>> new_book.save()
>>> book = Book.objects.get(id=1)
>>> print(book)
# 1984 by George Orwell (1949)
>>> book = Book.objects.get(title="1984") 
>>> book.title = "Nineteen Eighty-Four" 
>>> book.save()
>>> book.delete()
(1, {'bookshelf.Book': 1})
>>>