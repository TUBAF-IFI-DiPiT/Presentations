<!--
author:   Sebastian Zug
email:    sebastian.zug@informatik.tu-freiberg.de
version:  0.0.1
language: en
narrator: none

icon:     https://www.dip-it.ovgu.de/dipit_media/Bilder/Marginalbereich/Logo_DiP_iT_wei%C3%9F-height-230-width-230-p-74.png
-->

[![LiaScript](https://raw.githubusercontent.com/LiaScript/LiaScript/master/badges/course.svg)](https://liascript.github.io/course/?https://raw.githubusercontent.com/TUBAF-IFI-DiPiT/Presentations/main/DELFI2022/presentation.md#1)

# Informatikstudierende als Team-player
<h2>Wie die Integration von Teamarbeit in die Lehre gelingen kann</h2>


<div style="width: 66%; float: left">

|                   | Autoren                                                                                                            |
| ------------------------ | ----------------------------------------------------------------------------------------------------------------------- |
| Otto von Guericke Universität Magdeburg | Anja Hawlitscheck  |    
| TU Bergakademie Freiberg | Galina Rudolf, Sebastian Zug                                                                             |

</div>

![Partners](https://github.com/TUBAF-IFI-DiPiT/Presentations/blob/main/DELFI2022/DipIt-Projektpartner.png?raw=true "Quelle Karte: [^1]")<!-- style="width: 30%; float: right" -->

<div style="width: 100%; float: left">
<h5>20. Fachtagung Bildungstechnologien der GI Fachgruppe Bildungstechnologien, Karlsruhe, 13.09.2022</h5>
</div>

--{{0}}--
Link auf die Materialien des Vortrages

--{{0}}--
![Partners](https://github.com/TUBAF-IFI-DiPiT/Presentations/blob/main/DELFI2022/frame.png?raw=true)

[^1]: By David Liuzzo - Based on Image:Karte Deutsche Bundesländer (nummeriert).svg, color scheme of Image:Karte Deutschland.png applied., CC BY-SA 2.0 de, https://commons.wikimedia.org/w/index.php?curid=2594472

## Ausgangspunkt ODER _Was ist Git?_

> __Ausgangspunkt: Informatik ist Teamarbeit!__

Beispiel: Github Screenshot des Entwicklungspfad des im Bumblebee Projekt

![Bumblebee_Developers](https://github.com/TUBAF-IFI-DiPiT/Presentations/blob/main/DELFI2022/Bumblebee_Developers_happy.jpeg?raw=true "Github Screenshot des Entwicklungspfad des im Bumblebee Projekt [^1]")
![Bumblebee_Developers](https://github.com/TUBAF-IFI-DiPiT/Presentations/blob/main/DELFI2022/Bumblebee_Developers_unhappy.jpeg?raw=true "Github Screenshot des Entwicklungspfad des im Bumblebee Projekt [^1]")

--{{0}}--
FÜr die Nicht-Linux Nutzer ein Eindruck, was die obige Zeile bewirken würde ... [Link]{https://www.youtube.com/watch?v=jaGDpWGdA3s}

[^1]: https://github.com/MrMEEE/bumblebee-Old-and-abbandoned/commit/a047be85247755cdbe0acce6f1dafc8beb84f2ac

> Erfolgreiche Softwareentwicklung ist ein absolut strukturierter Prozess!

+ explizite Verantwortlichkeiten 
+ Abbildung der gesamten Historie des kooperativ / kollaborativen Prozesses 
+ Automatismen in der Bearbeitungskette 
+ ... 

## Implementierung ODER _Wozu Learning Analytics?_ 

Relevante Lehrveranstaltung 
-------------------------------

| Parameter | Bemerkung |
|---|------|
| Lehrveranstaltung | Softwareentwicklung |
| Inhalt            | Einführung der Methoden und Werkzeuge des Softwareentwurfes / -implementierung [(Vorlesungen als OER)](https://github.com/TUBAF-IfI-LiaScript/VL_Softwareentwicklung)|
| Studiengänge      | Robotik / Angewandte Informatik |
| Konfiguration     | Vorlesungen und wöchentliche Übung |
| Umsetzung         | Github-Classrooms [(Git Templates der Aufgaben SoSe 2022)](https://github.com/ComputerScienceLecturesTUBAF)                 |

Die erfolgreiche Bearbeitung der Aufgaben keine zwingende Voraussetzung für die Teilnahme an der Abschlussprüfung.

### Ergebnisse 

Aggregierte Git-Aktivitäten der Studierendenteams über den 7 Aufgaben im Semester 

![Results2020](https://github.com/TUBAF-IFI-DiPiT/Presentations/blob/main/DELFI2022/dip-it_ergebnisse_2020.png?raw=true)<!-- style="width: 50%; float: left" -->

<div style="width: 46%; float: right">

> __Vorbefragung ($N=18$):__ Studierende haben wenig Erfahrung mit Teamarbeit und verbalisieren eher Nachteile von Teamarbeit, z.B. unproduktive Partner*innen, Ablenkung, Ineffizienz

> __Nachbefragung ($N=12$):__ negative Erfahrunge aufgrund fehlender Partizipation der Teampartner*in, Studierende wünschen sich didaktische Unterstützung/Anleitung bei der Teamarbeit

--{{0}}--
Das Diagramm fasst die Aktivitäten der Studierenden über 7 Aufgaben zusammen, die in zweierteams zu lösen waren (markiert durch die $2$) im Feld. Ein $x$ illustriert, dass die Aufgabe zwar in einer eigenen Kopie angelegt wurde, aber das keine Änderungen "auf dem Server" realisiert wurden. Eine 1 markiert Repositories in denen nur ein Studierender aktiv war. Offensicht wurde das Ziel, eine kollaborative Arbeit unter den Teilnehmerinnen und Teilnehmern umzusetzen, nicht erreicht.

</div>

### Anpassungen 

| Maßnahme | Beispiel |   |
|----------|-----------|---|
| Reorganisation der Aufgaben | ![Tasks](https://github.com/TUBAF-IFI-DiPiT/Presentations/blob/main/DELFI2022/TaskConfiguration.png?raw=true)<!-- style="width: 10%;--> | |
| Reflexion von studentischen Git-Aktivitäten in der Vorlesung    | ![NewsFromGithub](https://github.com/TUBAF-IFI-DiPiT/Presentations/blob/main/DELFI2022/NewsFromGithub.png?raw=true)<!-- style="width: 10%;-->  | [Link](https://liascript.github.io/course/?https://raw.githubusercontent.com/TUBAF-IfI-LiaScript/VL_Softwareentwicklung/master/17_Dokumentation_BuildTools.md#2) |
| Git-Monitore als Dashboards für die Tutoren der Veranstaltung | ![Monitor](https://github.com/TUBAF-IFI-DiPiT/Presentations/blob/main/DELFI2022/GitHubMonitor.png?raw=true)<!-- style="width: 10%;-->    | [Link](https://liascript.github.io/course/?https://raw.githubusercontent.com/SebastianZug/GitHubClassroomTutorFeedback/main/README.md#1) |

### Ergebnisse

![Results](https://github.com/TUBAF-IFI-DiPiT/Presentations/blob/main/DELFI2022/dip-it_ergebnisse.png?raw=true "Ergebnisse der kollaborativen/kooperativen Arbeit in den Aufgaben")

> Bestehende Herausforderungen:
> 
> + Abbildung der Prüfungskonfiguration 
> + Integration von realistischeren Szenarien 
> + Übertragung der Ansätze auf Veranstaltungen mit größeren Studierendengruppen

## Referenzen ODER _Wo ist die Software?_  

| Reference          | Link |
|--------------------|------|
| Projekt Website    | [https://www.dip-it.ovgu.de/](https://www.dip-it.ovgu.de/) |
| Aggregations und Analyseframework  | [github2pandas](https://github.com/TUBAF-IFI-DiPiT/github2pandas)|
|                                                   | [github2pandas_manager](https://github.com/TUBAF-IFI-DiPiT/github2pandas_manager) |
|  | | 
| Präsentationsinhalt auf Github | [Delfi2022](https://github.com/TUBAF-IFI-DiPiT/Presentations/tree/main/DELFI2022) |
| LiaScript Projekt | [https://liascript.github.io/](https://liascript.github.io/) |

> __DiP-iT__ wird durch das Bundesministerium für Bildung und Forschung gefördert. [Link](https://www.wihoforschung.de/wihoforschung/de/bmbf-projektfoerderung/foerderlinien/forschung-zur-digitalen-hochschulbildung/dritte-foerderlinie-zur-digitalen-hochschulbildung/dip-it/dip-it_node.html).
