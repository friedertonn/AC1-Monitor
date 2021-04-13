# AC1-Monitor
Assemblercode für den AC1-Monitor 10/88

Die Datei MONI1088.MAC enthält den Assemblercode für den AC1-Monitor 10/88.
Von diesem Monitor gibt es Anpassungen an den AC1-2010 mit COLOR-BWS-CPLD aus dem Jahr 2011.
Am Anfang des Assemblercodes wird definiert, welcher Monitor gebildet werden soll.
Die Dokumentation ist in der Datei MONI1088.DOK

Zum Assemblieren kann der Macroassembler M80.COM verwendet werden.

M80 = MONI1088/L

Das Linken des Programmcodes erfolgt mit dem Linker LINKMT.COM

LINKMT MONI1088

Der Programmcode befindet sich dann in der Datei MONI1088.COM, die auf einen EPROM gebrannt werden kann.
Das Assemblerlisting steht in der Datei MONI1088.PRN

![](https://www.ftonn.de/GIT-Projekte/AC1-Monitor/Monitor_10-88.gif)
