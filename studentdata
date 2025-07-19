# StudentData
class Person:
    def _init_(self,name):
        self.__name = name
    def get__name(self):
        return self.__name
    def set__name(self,name):
        self.__name = name

class Student(Person):
    def _init_(self, name,roll,branch):
        super()._init_(name)
        self.__roll = roll
        self.__branch = branch
    
    def get__roll(self):
        return self.__roll
    def set__name(self,roll):
        self.__roll = roll

    def get__branch(self):
        return self.__branch
    def set__name(self,branch):
        self.__branch = branch


class PGStudent(Student):
    def _init_(self, name, roll, branch):
        super()._init_(name, roll, branch)

    def __str__(self):
        return f"Student:{self.get_name()},rollno:{self.get__roll()},branch:{self.get__branch()}"
