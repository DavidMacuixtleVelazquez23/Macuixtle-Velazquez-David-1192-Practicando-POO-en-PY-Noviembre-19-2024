print("Macuixtle Velazquez David\n")
class Marino():
  def hablar(self):
    print("Hola soy un animal marino!")

class Pulpo(Marino):
  def hablar(self):
    print("Hola soy un pulpo!")

class Foca(Marino):
  def hablar(self,mensaje):
    self.mensaje=mensaje
    print(mensaje)

class Bob_espoja(Marino):
  def hablar(self,mensaje):
    self.mensaje=mensaje
    print(mensaje)

marino=Marino()
marino.hablar()

pulpo=Pulpo()
pulpo.hablar()

foca=Foca()
foca.hablar("Hola soy una foca!")

bob=Bob_espoja()
foca.hablar("Hola soy spongebob AJAJAAJJJA!\n")

![image](https://github.com/user-attachments/assets/9f6a57e5-13c4-410c-a733-51dcc92f5846)
![image](https://github.com/user-attachments/assets/ff1dd291-ef8a-45c4-82fb-754cc351a00e)
