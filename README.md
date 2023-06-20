# M114

- [Tag-1](#Tag-1)
- [Tag-2](#Tag-2)
- [Tag-3](#Tag-3)
- [Tag-4](#Tag-4)
- [Tag-5](#Tag-5)
- [Tag-6](#Tag-6)




 
---------

## Tag-1
Zu beginnn haben wir ein Kahoot gemacht, um unser Vorwissen zu testen.
Dateien bestehen aus Bytes. Ob es ein Video oder ein Bild etc ist, entscheidet die Dateiendung.


Hexed.it(https://hexed.it/) um Dateien als bits zu sehen.


Dann haben wir angeschaut das man die Schachbrett idee, mit den Reiskörner auf grund zu kleiner Datentypen nicht geht.
Hier der Code:
```
public class Main {
    public static void main(String[] args) {
        System.out.println((long) pow(2, 64));
    }
}
```

10er System 1,2,3,4,5,...


2er System - Dual/Binär 010101


Oktal 


Hexadezimal 1,2,3,D,E,F,...


#### Aufgaben
2.
911 ist in binär 56 rest 111001111

3.
10110110 ist in dezimal 1*128 + 0*64 + 1*32 + 1*16 + 0*8 + 1*4 + 1*2 + 0*0 = 182

4.
1110'0010'1010'0101 in hexa dezimal ist: E2A5

5.
1101'1001 + 0111'0101 ist gleich:
128 + 64 + 16 + 8 + 1 = 217
64 + 32 + 16 + 4 + 1 = 117
217 + 117 = 334
166 --> 0
83 --> 1
41 --> 1
20 --> 1
10 --> 0
5 --> 0
2 --> 1
1 --> 0
1 --> 1
Lösung 101001110

## Tag-2
Mit dem 2er Komplement kann man Ganze Zahlen in Binär zu ihrem Negativem Counterpart darstellen. Es besteht aus 2 Schritten.

Beispiel mit Nummer 2
1. Zahl negieren (in Binär 1 zu 0 und 0 zu 1) -> 2 = 0010 => 1101
2. Plus 1 -> 1101 + 0001 => <u> 1110 = -2
 
 ## Tag-3
 Bildcodierung
 
- Elektromagnetische Wellen werden mit der Wellenlänge oder der Frequenz angegeben.
- Licht besteht aus elektromagnetischen Wellen.
- Nur ein Teil der Frequenzen des Lichts sind für das menschliche Auge sichtbar.
 
 Farben können in verschiedenen codeformaten dargestellt werden(bsp: HEX: weiss = #ffffff)
 
 Es gibt verschiedene Farbkanäle, die einen können nur schwarz und weiss darstellen, andere können natürlich auch farbig.
 
 dpi = Dots per Inch
 ppi = Pixel per Inch --> gut zu wissen beim kaufen eines Bildschirmes.
 
 ## Tag-4
 Bestimmung der Farben für die RGB-Farbcodes:

    - #FF0000 entspricht der Farbe Rot.
    - #00FF00 entspricht der Farbe Grün.
    - #0000FF entspricht der Farbe Blau.
    - #FFFF00 entspricht der Farbe Gelb.
    - #00FFFF entspricht der Farbe Cyan.
    - #FF00FF entspricht der Farbe Magenta.
    - #000000 entspricht der Farbe Schwarz.
    - #FFFFFF entspricht der Farbe Weiß.
    - #00BC00 entspricht einer Farbnuance von Grün.

Bestimmung der Farben für die prozentualen CMYK-Angaben:

    - C:0%, M:100%, Y:100%, K:0% entspricht der Farbe Cyan.
    - C:100%, M:0%, Y:100%, K:0% entspricht der Farbe Gelb.
    - C:100%, M:100%, Y:0%, K:0% entspricht der Farbe Magenta.
    - C:0%, M:0%, Y:100%, K:0% entspricht der Farbe Blau.
    - C:100%, M:0%, Y:0%, K:0% entspricht der Farbe Rot.
    - C:0%, M:100%, Y:0%, K:0% entspricht der Farbe Grün.
    - C:100%, M:100%, Y:100%, K:0% entspricht der Farbe Weiß.
    - C:0%, M:0%, Y:0%, K:100% entspricht der Farbe Schwarz.


 # Tag-5

![grafik](https://github.com/niculinstei/M114/assets/91120707/3cc06017-6a15-4d12-808d-7feb55d158fd)

# Tag-6
Es gibt verschiedene Verfahren, um den Datenspeicher und die Auslastung des Übertragungskanals für Bilder und Bewegtbilder zu reduzieren. Hier sind einige einfache Beispiele:

1. Komprimierung: Durch Komprimierung können die Dateigrößen von Bildern und Filmen verringert werden. Beispielsweise können Dateien im JPEG-Format komprimiert werden, um Speicherplatz zu sparen. Dabei werden weniger wichtige Details entfernt, um Platz zu sparen, was zu einer geringeren Bildqualität führen kann.

2. Auflösungsreduktion: Eine weitere Möglichkeit besteht darin, die Auflösung von Bildern oder Filmen zu verringern. Wenn beispielsweise ein hochauflösendes Bild auf eine geringere Auflösung skaliert wird, werden weniger Daten benötigt, um das Bild darzustellen. Dies kann jedoch zu einem Verlust an Bildschärfe und Details führen.

3. Verlustlose Komprimierung: Bei der verlustlosen Komprimierung werden Techniken verwendet, um die Dateigröße zu reduzieren, ohne dabei Informationen zu verlieren. Dies geschieht oft durch die Entfernung von Redundanzen in den Daten. Ein Beispiel für ein verlustloses Kompressionsverfahren ist das ZIP-Format.

4. Video-Streaming: Beim Streaming von Filmen werden die Daten in Echtzeit übertragen und nicht auf dem Gerät gespeichert. Dies ermöglicht eine sofortige Wiedergabe, ohne dass die gesamte Datei heruntergeladen werden muss. Die Datenübertragung kann an die verfügbare Internetgeschwindigkeit angepasst werden, um eine moderatere Auslastung des Übertragungskanals zu erreichen.

5. Farbunterabtastung: Eine Methode zur Reduzierung des Datenvolumens von Bildern besteht darin, die Farbunterabtastung zu verwenden. Anstatt jede Farbe genau zu erfassen, können Farbinformationen zusammengefasst werden, um den Speicherbedarf zu verringern. Dies kann zu einem Verlust an Farbgenauigkeit führen.

Diese Verfahren dienen als einfache Beispiele und es gibt noch viele weitere fortgeschrittenere Techniken, um die Datenspeicherung und Übertragungseffizienz von Bildern und Bewegtbildern zu verbessern.
