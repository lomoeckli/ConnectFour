# Testprotokoll Louis

## Programmabsturz
### Schritte:
- Spiel starten
- Eine zu grosse Zahl (in meinem Fall 7) eingeben

### Erwartetes Ergebnis:
- Fehlermeldung (z.B. "Diese Zahl ist zu gross. Gib eine Zahl zwischen 0 und 6 ein.")

### Tatsächliches Ergebnis:
- Programmabsturz (siehe Bild unten)

![image](https://github.com/user-attachments/assets/41312c3d-431f-4562-8e28-518f0117565f)

## Logikfehler
### Schritte:
- Spiel starten
- Eingabe Player x: 2
- Eingabe Player o: 1
- Eingabe Player x: 0
- Eingabe Player o: 0
- Eingabe Player x: 1
- Eingabe Player o: 5
- Eingabe Player x: 2

Zwischenstand Spielbrett:

![image](https://github.com/user-attachments/assets/7edf4c24-3d4d-4525-9744-ec5949300075)

- Eingabe Player x: 0

  
### Erwartetes Ergebnis:
- Spielbrett wird angezeigt
- Player o wird nach seiner nächsten Eingabe gefragt ("Player o:")

### Tatsächliches Ergebnis:
- Spielbrett wird angezeigt
- Player x: A winner is you! (siehe Bild unten)

![image](https://github.com/user-attachments/assets/973a0066-4d67-404c-b146-3f5768517575)
