print("Macuixtle Velazquez David\n")
class Persona:
 def __init__(self, n, e):
    self.nombre=n
    self.edad=e

 def cumpleaños(self):
    self.edad += 0.5

p=Persona(input("Ingrese nombre:"),int(input("Ingrese edad: ")))
p.cumpleaños()
p.cumpleaños()
print(f"{p.nombre} cumple {p.edad} años")

![image](https://github.com/user-attachments/assets/d8d83905-4d31-4e52-b710-5a369da879c2)
![image](https://github.com/user-attachments/assets/a8097d34-697d-4821-af4b-ffbcfed70584)
