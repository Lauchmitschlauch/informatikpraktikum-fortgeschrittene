# informatikpraktikum-fortgeschrittene
Schule Rothrist



Herzlich willkommen.


#Dies ist ein kleines "Geisterspiel" viel Spass
from random import randint
from time import sleep
name=input("Was ist dein Name junger Padawan?")
begruessung="Guten Morgen,junger Padawan haben sie gut geschlafen"
begruessung = begruessung + ' ' + name + '?'

print(begruessung)


du_bist_weise_junger_Padawan=True
BesiegteSiths = 0

### Wenn du weise bist, dann bist du weise, bis du die falsche Raumkapsel nimmst.

while du_bist_weise_junger_Padawan:
    Torzumjedi=randint(1,3)
    print("SCHWEIZSCHWEIZSCHWEIZSCHWEIZSCHWEIZSCHWEIZSCHWEIZSCHWEIZSCHWEIZSCHWEIZSCHWEIZSCHWEIZSCHWEIZSCHWEIZ")
    sleep (1)
    print("Vor dir sind drei Raumkapseln.")
    sleep (1)
    print("Hinter einer Tür ist ein Sith, junger Padawan")
    sleep (1)
    print("Für welche der Raumkapseln entscheidest du dich?")
    Raumkapseln = input("1, 2 oder 3? ")
    Raumkapsel_nummer= int(Raumkapseln)
    if Raumkapsel_nummer==Torzumjedi:
        print("ACHHHHHHHTUNG, Jedi, SCHNELL IN DECKUNG")
        print("Zu langsam, junger Padawan, leider bist du soeben auf dem Todesstern gestorben.")
        du_bist_weise_junger_Padawan=False
    else:
	    print("Gut gemacht"+name)
### Sagt, dass du es gut gemacht hast, wenn du die richtige Raumkapsel gewählt hast.
   ### Wenn du die falsche Raumkapsel gewählt hast, dann springt es zum letzten Abschnitt des Codes.
  ### BesiegteSiths = BesiegteSiths+ 1

print(" ")
print(name+", du hast leider die Jedi Akademie nicht bestanden.Schande über dich. Nur")
print(BesiegteSiths)
print ("Punkte")
