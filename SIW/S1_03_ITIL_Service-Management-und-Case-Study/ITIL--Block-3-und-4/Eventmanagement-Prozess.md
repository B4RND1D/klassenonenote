# Eventmanagement Prozess

Created: 2021-09-16 20:32:10 +0200

Modified: 2021-09-16 20:44:17 +0200

---

**Allgemein**

Der Zweck des Prozesses besteht darin, die Steuerung und das Management der Events über ihren gesamten Lifecycle hinweg zu gewährleisten. Dieser Lebenszyklus reicht von der Entdeckung eines Events über die entsprechenden Schlussfolgerungen bis zur Auswahl der angemessenen Aktion. Daher steht die Entdeckung der relevanten Statusänderungen (als Events) genauso im Fokus wie die Auswahl der Maßnahmen, die Festlegung der passenden Steuerungsaktionen (z.B.: »Wie werden welche Schwellenwerte in Abstimmung mit wem definiert?« und »Wie gelangen die Informationen aus dem Event Management wohin?«) und die dazugehörige Kommunikation. Zudem stellt das Event Management eine Basis für

das Service-Reporting dar. Die Ziele des Event Management lassen sich folgendermaßen darstellen:
-   Erkennen von relevanten Statusänderungen, die für das Management von Cis oder IT Services maßgeblich sind
-   Identifizieren und Definieren geeigneter Maßnahmen für Events sowie Gewährleisten, dass diese Maßnahmen den entsprechenden Teams oder Mitarbeitern bekannt sind
-   Anbieten von Ausgangs- und Ansatzpunkten für die Ausführung geeigneter Aktivitäten in den anderen Service-Operation-Prozessen. Sie sind durch den Anstoß über das Event Management in der Lage zu reagieren, um Servicebeeinträchtigungen zu beheben. Drei der fünf Prozesse in Service Operation sind diesbezüglich eng miteinander verzahnt: Event Management, Incident
-   Management und Problem Management. Alle drei Prozesse beschäftigen sich mit dem Verarbeiten von vorwiegend ungeplant eingetretenen Vorfällen oder deren Ursachenforschung.
-   Bereitstellen der Methoden und Verfahren zum Vergleich von Ist-Leistung und Soll-Leistung gemäß der SLA-Details. Daneben legt das Monitoring auch das unverzichtbare Faktenfundament für die Kapazitätsplanung und ermöglicht die professionelle Abrechnung von IT-Dienstleistungen auf der Grund lage von Service Level Agreements (SLA). Es spielt eine wichtige Rolle im Ressourcenmanagement und ist nicht wegzudenken beim Performance Tuning.
-   Bieten einer Basis für die Servicezusicherung, das Service-Reporting und die Serviceverbesserung







**Monitoring**

Events laufen typischerweise über Benachrichtigungen, die von einem IT Service, einer Komponente (CI) oder einem Monitoring-Tool erzeugt werden. Daher spielen die Tool-Auswahl und der Tool-Einsatz in Form von Monitoring- und Steuersystemen im Event Management eine wichtige Rolle. Dabei können zwei Arten von Tools Unterstützung leisten.

Zum einen sind es Tools für aktives Monitoring, mit denen die relevanten und definierten CIs abgefragt werden, um ihren Status und ihre Verfügbarkeit festzustellen. Alle Ausnahmen führen zu einem Alarm, der weitergeleitet und in adäquate Maßnahmen zu überführen ist.



Zum anderen gibt es Tools für das passive Monitoring. Sie ermitteln und mappen operative Alarme oder die von CIs erzeugten Benachrichtigungen. Das Event Management bietet die Möglichkeit, Incidents oder gar Probleme bzw. deren Ursachen frühzeitig zu entdecken. Es identifiziert Ansatzpunkte für Automatismen und zeigt so Optimierungspotenzial auf. Dies kann in eine Verringerung der Downtimes sowie Kosten- und Zeitersparnisse durch gezielte Hinweise

auf Abweichungen münden.





**Event**

Ein Event (Ereignis) ist eine Statusänderung, die für ein CI oder einen IT Service signifikant ist. Events sind üblicherweise Benachrichtigungen, die für das Management eines IT Service, Configuration Item oder eines Monitoring Tools von Bedeutung sind und dementsprechend vorab über Schwellenwerte oder andere Trigger berücksichtigt wurden.



Es existieren unterschiedliche Klassifizierungsmöglichkeiten für Events, die nach einer entsprechenden Definition verlangen, um z.B. Routing- und Eskalationswege festzulegen

**Information:**

Dies gilt für ein Event, das keine Aktion benötigt und keine Störung darstellt (z.B. Anwenderanmeldung an einem System, Abschluss einer Installationsroutine, Mail-Zustellung)

**Warnung**:

Wenn ein CI oder Service einen Grenzwert erreicht, zeugt dies von einem unüblichen, aber nicht außergewöhnlichen (fehlerhaften) Verhalten. Warnungen weisen darauf hin, dass die Situation der Beobachtung bedarf, um die angemessenen Maßnahmen zu ergreifen und eine Störung zu verhindern (z.B. wenn Transaktionszeiten oder Bereinigungsläufe für Datenbanken länger als

»üblich« dauern, Auffälligkeiten sich häufen). Es kann aber auch sein, dass sich der Fall von selbst erledigt. Die entsprechenden Regelungen sind in der Richtlinie zum Event Management zu finden.

**Ausnahme (Exception):**

Eine Ausnahme bedeutet, dass ein Service oder ein CI zurzeit nicht normal funktioniert. Beispiele für eine Exception sind z.B. ein ausgefallener Server oder zu lange Antwortzeiten einer Applikation. Derartige Ausnahme-Events werden ggf. zur Bearbeitung an das Incident Management weitergeleitet (siehe Abb. 15--5).

![Welche Art von (%ervvachung WWd benötigt (akti K/onitoring, Per%rrnance Ndonitoring etc Welche Kennzahlen sind abzudecken? Wann müssen Events erzeugt wer den ? Wer ist für das Erkennen, Kommunizieren Oder Weiterleiten sowie das Ergreifen von Maßnahrnen zuständig? Was muss überwacht wer den? Wer sind die Empfänger der Events? Welche CE•taiIs sind im Event zu übermitteln? ](../../media/S1_03_ITIL_Service-Management-und-Case-Study-Eventmanagement-Prozess-image1.png)



![Informierender Charakter Events, die einen normalen Betrieb anzeäen, z. B. dass eine Arbeitsabfolge beendet wurde, ein Anwender sich am System angemeldet hat oder eine E-Mail hren Empfänger erreicht hat Information Abb. 15---2 Event-Typen Eve nts Warnender Charakter: E'ÆNs, die unnormalen, aber keinen außergewöhnlilhn Betrieb ausweisem Sie sind ein Zeichen dafür, dass das Evert nähere Beobachtung oder Untersuchung benötät, z. B. geringfügige Überschrei- tungen von Schwellenwerten. Warnung AILsmhme-Chrakter: E'.æNs, die eine Ausnahme oder einen Sonde#ll identifizieren, z. B. bei sehr deutlichen Überschreitungen 'On Schwelknwetten Ausnahme O Besprechung ](../../media/S1_03_ITIL_Service-Management-und-Case-Study-Eventmanagement-Prozess-image2.png)


