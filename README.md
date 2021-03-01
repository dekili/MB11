# MB 11 - MATLAB

## Table of Contents
  * [1 MATLAB Download & Installation](#1-matlab-download---installation)
    + [1.1 tl;dr](#11-tl-dr)
    + [1.2 Informationen zur MATLAB Campuslizenz](#12-informationen-zur-matlab-campuslizenz)
    + [1.3 Download über MathWorks](#13-download--ber-mathworks)
    + [1.4 Installation](#14-installation)
  * [2 Quick Tutorial](#2-quick-tutorial)
    + [2.1 MATLAB Entwicklungsumgebung](#21-matlab-entwicklungsumgebung)
    + [2.2 Programmieren mit MATLAB](#22-programmieren-mit-matlab)
      - [2.2.1 Generieren neuer Objekte](#221-generieren-neuer-objekte)
      - [2.2.1 Generierung von Matrizen](#221-generierung-von-matrizen)
      - [2.2.2 Indexierung](#222-indexierung)
      - [2.2.3 Grundlegende Matrix Operationen](#223-grundlegende-matrix-operationen)
        * [>>Aufgaben<<](#--aufgaben--)
      - [2.2.4 Kontrollstrukturen](#224-kontrollstrukturen)
        * [If-Bedingungen](#if-bedingungen)
        * [for-Schleifen](#for-schleifen)
        * [**>>Aufgaben<<**](#----aufgaben----)


## 1 MATLAB Download & Installation

### 1.1 tl;dr

* Erstellen Sie auf dem [MathWorks-Portal der TU Darmstadt](https://de.mathworks.com/academia/tah-portal/tu-darmstadt-31483887.html) einen Account auf Ihre studentische E-Mail-Adresse.
* Laden Sie in Ihrem MathWorks-Account den Installer der aktuellen MATLAB-Version (2020b, Update 4) für Ihr Betriebssystem herunter.
* Starten Sie den Installer mit Administrator-Rechten.
* Installieren die MATLAB mit folgender Auswahl an Toolboxes:
  * *Image Processing Toolbox*
  
  * *Signal Processing Toolbox*
  
  * *Statistics & Machine Learning Toolbox*
  
<br>    

### 1.2 Informationen zur MATLAB Campuslizenz

"Seit dem 01. Oktober 2020 verfügt die TU Darmstadt über eine neue  campusweite Lizenz für **MATLAB** (*MATrix LABoratory*), *Simulink* und alle  begleitenden Toolboxen sowie eine Reihe von E-Learning-Materialien für  akademische Forschung, Lehre und Studium.

Mit MATLAB können Daten verarbeitet, analysiert und visualisiert werden sowie numerische Berechnungen vorgenommen werden.

Die Software kann von allen Beschäftigten und Studierenden der TU  Darmstadt sowohl auf universitätseigenen wie auch privaten Endgeräten **kostenfrei** genutzt werden.

Für die Nutzung der Campuslizenz haben Sie zwei Optionen:  

* mit persönlichem Account auf dem [MathWorks-Portal der TU Darmstadt](https://de.mathworks.com/academia/tah-portal/tu-darmstadt-31483887.html) 
* über den bestehenden Lizenzserver. Ausführliche Anleitungen finden Sie [auf unserer Webseite.](https://www.hrz.tu-darmstadt.de/services/it_services/campus_software/matlab/index.de.jsp)

Die Campuslizenz wird vom Präsidium und den Hauptnutzerbereichen finanziert und ist zunächst bis zum 30. September 2021 gültig."

([Quelle](https://www.hrz.tu-darmstadt.de/hrz_aktuelles/news_details_109312.de.jsp), zuletzt abgerufen am 25.02.2021)

<br>

### 1.3 Download über MathWorks

Für die Nutzung der Campuslizenz ist ein **persönlicher Account** auf dem [MathWorks-Portal der TU Darmstadt](https://de.mathworks.com/academia/tah-portal/tu-darmstadt-31483887.html) notwendig.
Besuchen Sie den angegebenen Link und klicken Sie auf den Button *"Sign in to get started"*:

<img src="img\1 Mathworks & Download\1.jpg" alt="A1" align=center width="1080" />

<br>

Um MATLAB herunterzulande, benötigen Sie einen **MathWorks Account**. Falls Sie noch keinen Account besitzen, klicken Sie unter der E-Mail-Adressleiste auf "Account erstellen!". Verwenden Sie bei der Erstellung dringend Ihre **studentischen E-Mail-Adresse** (...@stud.tu-darmstadt.de).

<img src="img\1 Mathworks & Download\2.jpg" alt="A2" align=center width="1080" />

<br>

Geben Sie nun ihre studentische E-Mail-Adresse und die folgenden weiteren Informationen an:

<img src="img\1 Mathworks & Download\3.jpg" alt="A3" align=center width="1080" />

<br>

Sobald Ihr Account eingerichtet wurde, finden Sie unter Ihrem Account Ihre individuelle MATLAB Lizenz. Um diese herunterzuladen, klicken Sie rechts neben dem Lizenzeintrag auf den Pfeil nach unten: 

<img src="img\1 Mathworks & Download\4.jpg" alt="A4" align=center width="1080" />

<br>

Nun können Sie den Installer für die aktuellste MATLAB-Version (2020b, Update 4) herunterladen. Dieser wird für alle gängigen Betriebssysteme (Windows, Mac, Linux) angeboten:

<img src="img\1 Mathworks & Download\5.jpg" alt="A5" align=center width="1080" />

<br>

### 1.4 Installation

Starten Sie die heruntergeladene Anwendung (*matlab_R2020b_win64.exe*) mit **Administrator-Rechten**; z.B. in Windows: Rechtsklick auf den Installer und den Eintrag "als Administrator ausführen" auswählen. 

Nachdem sich das Installer-Fenster geöffnet hat, geben Sie wieder Ihre studentische E-Mail-Adresse an, unter der Sie zuvor Ihren MathWorks-Account erstellt haben:

<img src="img\2 Installer\1.jpg" alt="B1" align=center width="1080" />

<br>

Um die Lizenzvereinbarungen zu akzeptieren, klicken Sie auf "Yes" und Next":

<img src="img\2 Installer\2.jpg" alt="B2" align=center width="1080" />

<br>

Wählen Sie nun Ihre individuelle MATLAB Lizenz aus und klicken Sie auf "Next":

<img src="img\2 Installer\3.jpg" alt="B3" align=center width="1080" />

<br>

Wählen Sie Ihren Installationsordner für MATLAB aus. Falls möglich, sollten Sie den bereits angegebenen Ordnerpfad verwenden.  

<img src="img\2 Installer\4.jpg" alt="B4" align=center width="1080" />

<br>

Neben der MATLAB Entwicklungsumgebung benötigen wir für die Datenanalyse **weitere Toolboxes**. Wählen Sie dazu die folgenden Toolboxes zur Installation aus:

- *Image Processing Toolbox*
- *Signal Processing Toolbox*
- *Statistics & Machine Learning Toolbox*

Bestätigen Sie auf den darauf folgenden Seiten und schließen Sie die Installation ab.

<img src="img\2 Installer\5.jpg" alt="B5" align=center width="1080" />

<br><br>


## 2 Quick Tutorial



Starten Sie nun die MATLAB-Anwendung *MATLAB R2020b.exe*. Sollte die Installation erfolgreich gewesen sein, erscheint nun nach kurzer Ladezeit die **MATLAB-Entwicklungsumgebung**. 

- [ ] Öffnen Sie zunächst ein leeres Skript über den Button *Blank script* (links oben) bzw. die Tastenkombination `Strg+N`.

<br>

### 2.1 MATLAB Entwicklungsumgebung

Die **MATLAB-Entwicklungsumbebung** ist in folgende vier Fenster unterteilt:

- *File Browser* (links)
  Dateiexplorer von MATLAB; dient zur Anzeige des Inhalts im aktuellen Verzeichnis; 
  Dateioperationen wie ̈Öffnen, Löschen, Umbenennen und Kopieren sind hier ebenfalls möglich.
- *Editor* (Mitte oben)
  Hier findet das eigentliche Programmieren statt. Zeigt den Inhalt von Script-Files an. Diese Scripts lassen sich wie Text-Dateien öffnen und speichern.
- *Command Window* (Mitte unten)
  Dient einerseits als Eingabefenster, um Befehle, Funktionen und Skripte auszuführen; andererseits werden deren Ergebnisse in diesem Fenster auch ausgegeben. 
- *Workspace* (rechts)
  Hier werden alle definierten Objekte angegeben sowie ihr Typ und ihre Dimensionalität.

<img src="img\3 MATLAB\1.jpg" alt="C1" align=center width="1080" />

<br>

### 2.2 Programmieren mit MATLAB

Im Folgenden werden einige wesentliche Schritte bei der Programmierung mit MATLAB erläutert. 



> HINWEIS
>
> Um Code abspeichern zu können, sollte ausschließlich im Editor-Fenster gearbeitet werden.



#### 2.2.1 Generieren neuer Objekte

In MATLAB lassen sich neue Objekte mittels des Operators  `=` definieren. Dazu erstellen wir hier als Beispiel eine neue Matrix `a`. 
Genauer gesagt ein Skalar, also eine 1x1 Matrix. Das Skalar soll den Wert 5 annehmen.

- [ ] Geben Sie im Script folgende Zeile ein: `a = 5`

- [ ] Markieren diese vollständig.
- [ ] Drücken Sie`F9`, um den markierten Bereich auszuführen.

<img src="img\3 MATLAB\2.jpg" alt="C2" align=center width="1080" />

<br>

Mehrere Dinge sind nun gleichzeitig geschehen:

1. Im Command Window wird der übergebene Code noch einmal wiedergegeben: `>> a = 5`

2. Zudem wird im Command Window das Ergebnis der Operation ausgegeben:

   > a =    
   >    
   > ​	 5    

3. Im Workspace wurde ein neues Objekt mit Namen `a` und Wert 5 erstellt.

<br>

#### 2.2.1 Generierung von Matrizen

Die neu erstellte Matrix `a` lässt sich nun beliebig erweitern:

```
a(1,2) = 1
```

<br>

Damit wird `a` erweitert zu einer 1x2 Matrix. Die Ausgabe würde nun folgendermaßen aussehen:

> a =    
>    
> ​	 5     1    

<br>

Auch existieren in MATLAB bereits vordefinierte Werte, wie z.B. für pi.

```
a(2,1)=pi
```

> a =     
>    
> ​	5.0000    	1.0000    
> ​	3.1416        0    

<br>

Anhand des vorherigen Beispiels sieht man nun gleich mehrere Dinge: 

1. In MATLAB wird die **Indexierung** (also das Ansprechen einzelner Zellen) über runde Klammern vorgenommen, in der Form (Zeile,Spalte). 

2. Matlab erlaubt nur reguläre n × m Matrizen und fügt deshalb bei der letzten Erweiterung automatisch eine 0 ein. Dies ist in unserem Beispiel für `a(2,2)` der Fall.

<br>

Wesentlich **komfortabler** lassen sich Matrizen folgendermaßen generieren, d.h. in eckigen Klammern mit einem Semikolon als Zeilentrenner.

```
b=[5 1 ; pi 0]
```

>b =    
>	5.0000 	1.0000    
>	3.1416 	0    

<br>

Auch **Strings** (also Zeichenketten) werden in MATLAB als Matrizen behandelt. Strings werden benötigt, um beispielsweise Dateien in einem Skript zu öffnen und abzuspeichern oder eine Grafik zu beschriften.

```
text = 'Hello world'
```

> text =    
>    
> ​	'Hello world'    

<br>

#### 2.2.2 Indexierung

In diesem Abschnitt wird noch etwas genauer auf die **Indexierung**, also das Ansprechen einzelner/mehrerer Zellen von Matrizen, eingegangen.

Hierbei leistet der Operator `:` gute Dienste. Mit diesem lassen sich auf einfache Weise Zahlenfolgen in der Form `Start : Schrittweite : Ende` erstellen. Im Folgenden sollen alle Werte zwischen 1 und 10 in der Schrittgröße 2 ausgegeben werden.

```
1:2:10
```

> ans =    
>    
> ​     1     3     5     7     9    

<br>

Gegeben sei nun die folgende 3x3-Matrix `M`:

```
M=[1:3 ; 4:6 ; 7:9]
```

> M =    
>    
> ​	 1     2     3    
> ​	 4     5     6    
> ​	 7     8     9    

<br>

Um nun alle Werte der ersten Spalte der Matrix `M`zu erhalten, könnte man die einfachste Form der Indexierung einer Matrix verwenden:

```
M(1),M(2),M(3)
```

> ans =    
>    
> ​	 1    
>    
>    
> ans =    
>    
>  	4    
>    
>    
> ans =    
>    
>  	7    

<br>

Aber das geht noch deutlich komfortabler. So ergibt auch die folgende Zeile die erste Spalte der Matrix `M`, da der Doppelpunkt für ”alle Elemente“ steht:

```
M(:,1)
```

> ans =    
>    
> ​	1    
> ​	4    
> ​	7    

<br>

Die erste und dritte Zeile lässt sich über folgende Indexierung ansprechen:

```
M([1 3],:)
```

> ans =    
>    
> ​	 1     2     3    
> ​	 7     8     9    

<br>

Der Begriff `end` steht für den maximalen Index:

```
M([1 3],end-1:end)
```

> ans =    
>    
>  	2     3    
>  	8     9    

<br>

#### 2.2.3 Grundlegende Matrix Operationen

Die **Dimensionalität** einer Matrix ermittelt man mit dem Befehl `size`, die Länge eines Vektors mit `length`.

```
size(M)
```

> ans =    
>    
> ​	 3     3    

<br>

Da in Matlab beinahe jedes Objekt eine Matrix darstellt, muss man sich keine Gedanken bei den elementaren Rechen-Operationen (wie +,-,*,/) machen. So muss man keine speziellen Funktionen für eine Matrix-Multiplikation aufrufen:

```
A=[1 2;3 4],B=[5 6; 7 8]

A * B
```

> A =    
>    
>  	1     2    
> 	 3     4    
>    
>    
> B =    
>    
>  	5     6    
> 	 7     8    
>    
>    
> ans =    
>    
> ​	19    22    
> ​	43    50    

<br>

Möchte man stattdessen die beiden Matrizen <u>elementweise</u> multiplizieren, so muss man `.` vor den Operator setzen:

```
A .* B
```

> ans =    
>    
> ​	 5     12    
> ​	21    32    

<br>

Um alle Werte einer Zeile aufzusummieren, benutzt man die Function `sum()`:

```
sum(A(1,: ))
```

> ans =    
>    
>  	3    

<br>

Die Transponierte der Matrix `A` erhält man über den Operator `'`:

```
A'
```

> ans =    
>    
>  	1     3    
>  	2     4    

<br>

_____



##### >>Aufgaben<<

- [ ] Addieren Sie alle Werte in der ersten Spalte der Matrix `A`.



_______

<br>

#### 2.2.4 Kontrollstrukturen

##### If-Bedingungen

Eine Bedingung lässt sich mit `if` prüfen. Im folgenden Beispiel wird geprüft, ob Variable `a` einen bestimmten Wert besitzt und entsprechend einen kleinen Text ausgeben. Dringend zu beachten sind dabei die **doppelten Gleichheitszeichen** zum Werteabgleich.

```matlab
a = 5; % hier gerne den Wert verändern und die folgende Kontrollstruktur neu durchlaufen lassen

if(a==5)
	disp(’a ist 5’)
elseif(a==6)
	disp(’a ist 6’)
else
	disp(’a ist weder 5 noch 6’)
end
```

<br>

##### for-Schleifen

Oftmals muss diesselbe Operation für alle Elemente einer Struktur mehrfach wiederholt werden. Anstatt nun aber denselben Code x-mal wiederholen zu müssen, lassen sich stattdessen Schleifen mittels `for` einsetzen. Die Schleife iteriert im folgenden Beispiel über den Inhalt einer Matrix. So kann sehr einfach eine Funktion nacheinander mit verschiedenen Parametern aufgerufen werden:

```matlab
for x = 1 : 8
    Y(x)= 3*x
end
```

<br>

__________

##### **>>Aufgaben<<**

- [ ] Generieren Sie zunächst die folgende Matrix `A`über folgende Zeile:

  ```
  A = magic (7)
  ```

- [ ] Ermitteln Sie die Summe der dritten und siebten Spalte sowie der vierten und fünften Reihe von `A`.

- [ ] Der letzte Wert der Matrix `A` soll 49 sein.

- [ ] Ersetzen Sie alle Werte kleiner 20 der Matrix `A `mit 0.

- [ ] Bauen Sie eine neue 3x3-Matrix , welche vollständig aus Nullen besteht.

- [ ] Erstellen sie die folgende Matrix `B`:

  > C =    
  > 	0 0 0 0 0 0 0    
  > 	0 1 1 1 1 1 0    
  > 	0 1 2 2 2 1 0    
  > 	0 1 2 3 2 1 0    
  > 	0 1 2 2 2 1 0    
  > 	0 1 1 1 1 1 0    
  > 	0 0 0 0 0 0 0    

  

_____________

​	
