##### django day2:-


##### *create project*
```
rakshithr@RAKSHITHRs-MacBook-Pro djangoprojects % django-admin startproject firstproject
rakshithr@RAKSHITHRs-MacBook-Pro djangoprojects % ls
firstproject
rakshithr@RAKSHITHRs-MacBook-Pro djangoprojects % cd firstproject
rakshithr@RAKSHITHRs-MacBook-Pro firstproject % 
```
##### creating apps under project directory:-
```
rakshithr@RAKSHITHRs-MacBook-Pro firstproject % python manage.py runserver  # works in windows
zsh: command not found: python
rakshithr@RAKSHITHRs-MacBook-Pro firstproject % python3 manage.py runserver  # works in linux for python3

Watching for file changes with StatReloader
```
##### create apps (app1 app2 app3)
```
python manage.py startapp firstapp
```
##### example:
```
rakshithr@RAKSHITHRs-MacBook-Pro secondproject % python3 manage.py startapp firstapp
rakshithr@RAKSHITHRs-MacBook-Pro secondproject % ls
firstapp        manage.py       secondproject
rakshithr@RAKSHITHRs-MacBook-Pro secondproject % python3 manage.py startapp secondapp
rakshithr@RAKSHITHRs-MacBook-Pro secondproject % python3 manage.py startapp thirdapp 
rakshithr@RAKSHITHRs-MacBook-Pro secondproject % 
```

##### url and path (url works for old django version and path works for new django version)
```
urlpatterns = [
    path('admin/', admin.site.urls), 
    path('',views.display),
]


```

##### one project and multiple apps:-
```
PROJECT2:-

Inside 1 project (3 APPLICATIONS)

1st app and  (this is from 1st app and fun1)
2nd app and(this is from 1st app and fun2)
3rd app(this is from 1st app and fun2)



2nd  app:3 FUNCTIONS
1stapp_v1(this is from 2nd app and fun1)
2ndapp_v2 (this is from 2nd app and fun2)
3rdapp_v3(this is from 2nd app and fun3)
3rd app: views.py
1ST APP_v1(this is from 3rd app and fun1)
2ND APP_v2(this is from 3rd app and fun2))
3RD APP V3 (this is from 3rd app and fun3))

3rd app(views.py)
1st_app:-print "This is from firstapp Func1"
2nd_app:-print "This is from Secondapp Func2"
3rd_app:- print" This is from thirdapp Func3"

```

##### url.py
```
```
##### views.py
```
from django.contrib import admin
from django.urls import path
from firstapp import views as first_views  # importing views from firstapp
from secondapp import views as second_views # importing views from secondapp
from thirdapp import views as third_views # importing views from thirdapp

urlpatterns = [
    path('admin/', admin.site.urls),
    #firstapp
    path('first/fun1/', first_views.fun1),
    path('first/fun2/', first_views.fun2),
    path('first/fun3/', first_views.fun3),
    # secondapp
    path('second/fun1/', second_views.fun1),
    path('second/fun2/', second_views.fun2),
    path('second/fun3/', second_views.fun3),
    # thirdapp
    path('third/fun1/', third_views.fun1),
    path('third/fun2/', third_views.fun2),
    path('third/fun3/', third_views.fun3),
]
```
##### calling functions
```

http://127.0.0.1:8000/first/fun1/   # calling firstapp fun1
http://127.0.0.1:8000/first/fun2/  # calling firstapp fun1
http://127.0.0.1:8000/first/fun3/ # calling firstapp fun1

http://127.0.0.1:8000/second/fun1/   # calling app fun1
http://127.0.0.1:8000/second/fun2/  # calling firstapp fun1
http://127.0.0.1:8000/second/fun3/ # calling firstapp fun1

```








##### quit the development server
```
control + c
```

 ##### linux commands:
 

*pwd </br>
scp firstproject>secondproject</br>
rm - rf</br>
rm -m project1 project2</br>
cd .. : previos directory </br>
cd - change director. ex</br>*

###### *remove command*
```
rm -r project1 project2
```
