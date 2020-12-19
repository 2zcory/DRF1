#

## Thứ tự các command

```cmd
$ py -m venv venv

// Nghĩ là để tạo môi trường py trên vsc
```

```
$ venv\Scripts\activate

// sử dụng các lệnh để khởi tạo django
```

```
$ pip install django

$ django-admin startproject core .
// Tạo thư mục core

$ py manage.py startapp blog
// Tạo blog

$ py manage.py startapp blog_api

$ py manage.py runserver

$ py manage.py makemigrations
// Thực hiện lệnh tạo models ở migrations

$ py manage.py migrate
// Tạo db

$ py manage.py createsuperuser

$ pip install coverage

$ coverage run --omit='*/venv/*' manage.py test

$ coverage html

$ pip install django-cors-headers
```

test html
test api