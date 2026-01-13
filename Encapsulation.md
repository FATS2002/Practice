##### python day- 25.1
###### binding the data(var information) along with methods.

###### refer notes 25.1(Encapsulation)



##### en-1(public member)
````
class Student:
    def __init__(self, name):
        self.name = name  # public variable(instance method)

    def display(self):  # public method
         print(self.name)


s = Student("Rahul")
s.display()
print(s.name)  # accessible
````
##### output
````
Rahul
Rahul
````



##### en-2 (`_`) (protected member) use it during inheritance 

````
class Employee:
    def __init__(self, salary):
        self._salary = salary  # protected variable


class Manager(Employee):
    def show_salary(self):
        print(self._salary)


m = Manager(50000)
m.show_salary()
````


##### en-3  (private)
````
class BankAccount:
    def __init__(self):
        self.__balance = 0  # private variable

    def deposit(self, amount):
        self.__balance += amount

    def show_balance(self):
        print("Balance:", self.__balance)


acc = BankAccount()
acc.deposit(1000)
acc.show_balance()
# print(acc.__balance)  # It will throw error
print(acc._BankAccount__balance)

````

##### output:
````
````
##### setters and getters
````
class Student:
    def __init__(self):
        self.__marks = 0

    def set_marks(self, marks):
        if marks >= 0:
            self.__marks = marks

    def get_marks(self):
        return self.__marks


s = Student()
s.set_marks(85)
print(s.get_marks())
````

##### encapsulation using '@property' decorator

````
class Person:
    def __init__(self):
        self.__age = 0  # private

    @property
    def age(self): 
        return self.__age

    @age.setter
    def age(self, value):
        if value >= 0:
            self.__age = value


p = Person()
p.age = 25
print(p.age)

````
#@property
````
class Person:
    def __init__(self):
        self.__age = 0  # private

    @property
    def age(self): 
        return self.__age

    @age.setter
    def age(self, value):
        if value >= 0:
            self.__age = value


p = Person()
p.age = 25
print(p.age)
````














