Reports for Oracle SQL Developer
================================

See also: http://oraculix.com/2015/03/12/visualizing-statspack-performance-data-in-sql-developer/
Custom Reports should work from at least v3.0 of SQLDev.

Installation (English)
----------------------
- In the Navigator (usually on the left side) choose the tab "Reports".
- Right-click folder "User Defined Reports" and "Open Report".
- Open an XML file containing a report definition.


Installation (Deutsch)
----------------------
- Im Navigator links den Reiter "Berichte" auswählen
- Rechtsklick auf Ordner "Benutzerdefinierte Berichte" und "Bericht öffnen" anklicken
- Eine XML-Datei mit der Report-Definition im Filesystem auswählen.

Bedeutung der beiliegenden Reports:
- Autotasks: Anzeige der installierten Autotasks mit Details (z.B. DBMS-Stats)
- Longops_Gauge: Graphische Anzeige der v$session_longops mit Detailinfos zu Session und SQL
- Scheduler_Jobs: Jobs, Run Log, Programs, Windows etc.
- Statspack_AAS: Visualisierung der Metrik "Average Active Sessions" aus Statspack.
- Statspack_AAS_3Level: Visualisierung der Metrik "Average Active Sessions" aus Statspack; mit einer dritten Ebene für historische und aktuelle Ausführungspläne zu Top SQL.
- Statspack_Host_CPU: Darstellung der CPU-Last des Servers (komplett, nicht nur Datenbank-Last).
- Statspack_LIO: Visualisierung der Metrik "Session Logical Reads" mit den Komponenten "consistent reads" und "db block gets" sowie separat "db block changes".
- Statspack_PIO: Visualisierung der Metriken "Session Physical Reads" und "Session Physical Writes" (Lese-/Schreibzugriffe auf die Festplatte)
- Statspack_SysStat: Visualisierung historisierter Metriken aus V$SYSSTAT.
- Storage_Overview: Einfacher Überblick über die DB-Größe
