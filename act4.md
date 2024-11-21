print("Macuixtle Velazquez David\n")
class Persona():
  def __init__(self,nom,ape):
    self.nombre=nom
    self.apellido=ape

  def nombre_completo(self):
    return f"{self.nombre} {self.apellido}"

class Estudiante(Persona):
  def __init__(self,nom,ape,carr):
    super().__init__(nom,ape)
    self.carrera=carr

  def mostrar_carrera(self):
    return f"{self.carrera}"

estudiante1 = Estudiante("David","Macuxitle","Mate")
print(estudiante1.nombre_completo())
print(estudiante1.mostrar_carrera())

![image](https://github.com/user-attachments/assets/284031df-b492-4164-b25f-8382347572dc)
![image](https://github.com/user-attachments/assets/d8e7a103-2876-4916-8119-bc62fc36aa99)
