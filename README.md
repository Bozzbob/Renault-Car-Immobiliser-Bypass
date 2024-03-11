# Renault-Car-Immobiliser-Bypass
How to bypass a Renault car immobiliser using its bypass de-activation code For use with cars that have an infra-red key
#
What is it?
Some Renault cars have an inbuilt system that enables you to override the immobiliser should the infra-red key fob cease to work. This is useful to emergency and recovery services should they need to move a dead vehicle.
The Immobiliser Bypass Code is a four digit numeric code that is unique to each car. This code can be obtained by running a small downloadable Windows 32 bit software application and entering the specifics of your car.
This technique can only be used to override the immobiliser on a vehicle for which you have the key or key number so don't go thinking you can use this method to steal cars!
So, if you have found that the infra-red key fob for your Renault car is no longer de-activating the immobiliser, this bypass technique can be used as a temporary work around to start the car until you can get it fixed properly by a dealer.
#German
viele kennen sicher das Problem das die Wegfahrsperre sich nicht mehr durch den Schlüssel entsperren lässt. In diesem Fall kann ein Code über die Zentralverriegelung eingegeben werden. Dadurch lässt sich das Auto wieder starten. Für viele ein alter Hut, aber ich habe dennoch sehr lange gebraucht um alle Informationen zu finden und deswegen möchte ich hier ein Tutorial bereitstellen. Außerdem habe ich das Programm so angepasst das es nun auch auf 64 Bit Systemen funktioniert (Windows 10 usw.).

    Die Wegfahrsperre entsperren

    1. Finde deinen Key-Code heraus: Schlüssel öffnen und nach einem Code suchen der aus Zahlen und Buchstaben besteht. Zum Beispiel S2E6E

    Alle gültigen Code Bereiche:
    Transponder SIEMENS, 8 -Zeichen, YR000000 - YXXXXXXX
    Valeo IR Alt, 5 Zeichen, 00000 - 88888
    Megane IR Siemens, 5 Zeichen, S1111 - SUUUU
    Sagem Transponder RF, 8 Zeichen, A0000000 - EZZZZZZZ
    Twingo IR TRW, 7 Zeichen, WBAAABA - WZZZYZZ
    Valeo Transponder IR, 8 Zeichen, ZR000000 - ZXXXXXXX
    Valeo IR, 7 Zeichen, P000000 - VFFFFFF
    Valeo Transponder RF, 8 Zeichen, FR000000 - FXXXXXXX

    2. Finde deinen Fahrzeug Typ. Der steht auf einer Plakette. Wo genau kann man hier auf Englisch nachlesen: http://renaulthelp.110mb.com/
    unter "How do I find my car type number?"

    3. Lade das Zip Paket herunter: RenaultImmCode_32Bit_64Bit.zip
    4. Starte das Programm mit der Datei "start.bat". Ich habe hier etwas gebastelt damit das uralte Programm (aus dem Jahr 1997) noch mit unseren neuen PCs funktioniert
    5. Gib das Passwort ein: trantir
    6. Gib deinen Fahrzeugtyp ein (z.B. BA11)
    7. Gib deinen Key Code ein (z.B. S2E6E)
    8. Du solltest nun deinen vierstelligen Freischaltcode erhalten (z.B. 3598)
    9. Starte die Elektronik in deinem Auto und schließ die Türen (womit nicht verriegeln gemeint ist).
    10. Gib deinen Code ein: Drücke die Taste der Zentralverriegelung so lange bis die Lampe der Wegfahrsperre drei mal geblinkt hat. Also gedrückt halten und erst loslassen wenn es drei mal geblinkt hat. Natürlich musst du deine erste Zahl verwenden und nicht die aus meinem Beispiel
    11. Drücke die Taste der Zentralverriegelung so lange bis die Lampe der Wegfahrsperre fünf mal geblinkt hat.
    12. Drücke die Taste der Zentralverriegelung so lange bis die Lampe der Wegfahrsperre neun mal geblinkt hat.
    13. Drücke die Taste der Zentralverriegelung so lange bis die Lampe der Wegfahrsperre acht mal geblinkt hat.
    14. Fertig, du kannst dein Auto wie gewohnt starten.

    Einen Schlüssel neu anlernen

    1. Entsperre deine Wegfahrsperre (siehe Punkte 1 bis 14.)
    2. Zieh den Schlüssel ab
    3. Halte die Zentralverrieglung dauerhaft gedrückt (die Lampe der ZV sollte nun dauerhaft leuchten)
    4. Halte deinen Schlüssel neben den IR-Sensor deines Autos (neben dem Rück-Spiegel)
    5. Drücke den Knopf des Schlüssels schnell hinter einander.
    6. Diese Schritte sollten innerhalb von 10 Sekunden passieren. Falls es nicht klappt nochmal 3. bis 5. wiederholen. Es kann immer wiederholt werden, sobald die Lampe der ZV schnell blinkt)

    Wichtige Hinweise
    Bei manchen Autos dient zum Eingeben des Codes das Gaspedal
    Bei manchen Autos dient zum Eingeben des Codes das Gaspedal & der Knopf zum Scheibenwischen (gleichzeitig)
    Bei verschiedenen Autos gibt man den Code per Radio ein. In dem Fall kann diese Anleitung nicht verwendet werden.
    Bei manchen Autos kann man den Code gar nicht eingeben

    Das ist nur eine temporäre Lösung. Warum euer Schlüssel nicht mehr geht kann viele Gründe haben. Primär bekannt:
    - bei niedrigen Temperaturen wechselt der Schlüssel seinen Code
    - bei Wasserschaden am Steuergerät reagiert es nicht auf IR Signale
    - die Diode am Schlüssel ist defekt
    - die Batterie am Schlüssel muss gewechselt werden (rote Lampe leuchtet dann nicht mehr am Schlüssel)
