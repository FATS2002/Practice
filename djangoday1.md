##### django day1:-


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
##### create apps
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
