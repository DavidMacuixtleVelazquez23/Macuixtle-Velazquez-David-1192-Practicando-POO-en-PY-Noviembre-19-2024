print("Macuixtle Velazquez David\n")
class Universidad():
  def __init__(self,Nombre):
    self.Nombre=Nombre

class Carerra():
  def carrera(self,especialidad):
    self.especialidad=especialidad

class Estudiante(Universidad,Carerra):
  def datos(self,nombre,edad):
    self.nombre=nombre
    self.edad=edad
    print(f"El nombre del estudiante es {self.nombre}, tiene {self.edad} años, su especialidad es {self.especialidad}. Estudia en la Universidad {self.Nombre}")

persona=Estudiante("Hardvard")
persona.carrera("Ingeniería mecatronica")
persona.datos("Mike", 19)

![image](https://github.com/user-attachments/assets/834bb9e8-a73a-4b1e-8a57-2248e837e55f)
![image](https://github.com/user-attachments/assets/82aab5f9-6033-448f-bdf5-293b0b39325b)
