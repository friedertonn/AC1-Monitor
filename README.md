# AC1-Monitor
Assemblercode für den AC1-Monitor 10/88

Die Datei MONI1088.MAC enthält den Assemblercode für den AC1-Monitor 10/88.
Von diesem Monitor gibt es Anpassungen an den AC1-2010 mit COLOR-BWS-CPLD aus dem Jahr 2011.
In den Zeilen 36 bis 39 des Assemblercodes wird festgelegt, welcher Monitor gebildet werden soll.
Die Dokumentation des Monitors (Befehle, Unterprogramme, Speicherzellen, Steuercodes)
steht in der Datei MONI1088.DOK

Zum Assemblieren des Quellcodes kann der Macroassembler M80.COM verwendet werden.

M80 = MONI1088/L

Das Linken des Programmcodes erfolgt mit dem Linker LINKMT.COM

LINKMT MONI1088

Der Programmcode befindet sich dann in der Datei MONI1088.COM, die auf einen EPROM gebrannt werden kann.
Das Assemblerlisting steht in der Datei MONI1088.PRN

![](https://www.ftonn.de/GIT-Projekte/AC1-Monitor/Monitor_10-88.gif)

Volker Pohlers hat diesen und weitere AC1-Monitore disassembliert und auf
Github zur Verfügung gestellt: https://github.com/hcddr/ac1/tree/master/monitor 