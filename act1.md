print("Macuixtle Velazquez David\n")
class Estudiante():
    def __init__(self , nombre , nota):
        self.nombre=nombre
        self.nota=nota

    def imprimir(self):
        print(f"Nombre:{self.nombre} \nNota: {self.nota}")

    def resultados(self):
        if self.nota >= 7:
            print("Has APROBADO!")
        else:
            print("Has REPROBADO!")

estudiante1=Estudiante("David" , 5)
estudiante1.imprimir()
estudiante1.resultados()

estudiante2=Estudiante("pUGA" , 7)
estudiante2.imprimir()
estudiante2.resultados()

![image](https://github.com/user-attachments/assets/e1ba162a-605b-45d1-af9f-53740b0a97d5)
![image](https://github.com/user-attachments/assets/f696078a-f26a-4a2b-a9d7-d9ca472f78bf)
