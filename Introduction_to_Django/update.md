>>> book = Book.objects.get(title="1984")
>>> book.title = "Ninteen Eighty-Four"
>>> book.save()
# Ninteen Eighty-Four by George Orwell (1949)
