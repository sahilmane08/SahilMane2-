# SahilMane2-
Oop's  points
there is the 2 Parts of the OOp's 
1) Class
2) Object

   four pillers of object orieanted programming

   1) inheritance
   2) encapsulation
   3) polymorphism
   4) abstraction
      These are the 4 Types of oop's

This is the Example of Inheritance
class A:
  def __init__(self, name, id):
    self.name = name 
    self.id = id 

  def xx(self):
    print(f"My Name is {self.name} && My Id is {self.id}")


class B(A):
  def __init__(self, name, id, password, password):
    super().__init(name, id)
    self.password = password
  def x1(self):
    print(f"My Name is {self.name} && My id is {self.id} && My password is {self.password}")


obj1 = B("Sahil", 21121, "sahil21121")
obj1.x1()




This is the Example of Encapsulation.. 
class A:
  def __init__(self, name, id, password):
    self.__name = name 
    self.__id = id 
    self.__password = password 

  def setname(self, name):
  self.__name = name 

  def setid(self, id):
    self.__id = id 

  def setpassword(self, password):
    self.__password = password 

  def getname(self):
    return self.__name 

  def getid(self):
    return self.id 

  def getpassword(self):
    return self.__password

  def xx(self):
    print(f"My Name is {self.__name} My id is {self.__id} My Password is {self.__password}")

obj1 = A("Sahil", 21, "Sahil21")
obj1.xx()
obj1.setname("Vaishnav")
obj1.setid(211)
obj1.setpassword("Vaishnav211")
obj1.xx()



    
