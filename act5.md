print("Macuixtle Velazquez David\n")
class Fabrica():
  def __init__(self, llantas, color, precio):
    self._llantas=llantas
    self._color=color
    self._precio=precio

class Moto(Fabrica):
  def cantidad(self):
    print("La cantidad de llantas: {}\nEl color es: {}\nEl precio es: {}".format(self._llantas,self._color,self._precio))
    
    print("OBJETO=moto")

moto=Moto(2, "Gris", "$200")
moto.cantidad()

class Carro(Fabrica):
  def cantidad(self):
    print("La cantidad de llantas: {}\nEl color es: {}\nEl precio es: {}".format(self._llantas,self._color,self._precio))

    print("OBJETO=carro")

carro=Carro(4, "Negro", "$600")
carro.cantidad()

class Bici(Fabrica):
  def cantidad(self):
    print("La cantidad de ruedas: {}\nEl color es: {}\nEl precio es: {}".format(self._llantas,self._color,self._precio))

    print("OBJETO=Bici")

carro=Bici(4, "Negro", "$400")
carro.cantidad()

![image](https://github.com/user-attachments/assets/c6214535-73d5-47f6-9708-e152472c46fe)
![image](https://github.com/user-attachments/assets/e609a8b6-8bda-4ebf-90da-9c9f26db5a15)
