[urls.py](https://github.com/user-attachments/files/33271487/urls.py)
from django.contrib import admin
from django.urls import path, include

urlpatterns = [
    path('admin/', admin.site.urls),
    path('', include('tienda.urls')),  # O la ruta principal de tu tienda
]
