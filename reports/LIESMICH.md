Berichte für Oracle SQL Developer
=================================

Derzeit hauptsächlich für
- DBAs
- Performance-Analysen

Siehe auch: http://oraculix.com/2015/03/12/visualizing-statspack-performance-data-in-sql-developer/ (Englisch)
Die Berichte setzen mindestens Oracle SQL Developer v3.0 voraus.

Installation (Deutsch)
----------------------
- Im Navigator links den Reiter "Berichte" auswählen
- Rechtsklick auf Ordner "Benutzerdefinierte Berichte" und "Bericht öffnen" anklicken
- Eine XML-Datei mit der Report-Definition im Filesystem auswählen.

Bedeutung der beiliegenden Reports:
-----------------------------------
- Autotasks: Anzeige der installierten Autotasks mit Details (z.B. DBMS-Stats)
- AWR-Zeitreihe_Load_11g: Visualisierung der Metrik "Average Active Sessions" aus AWR. Details zu Wait Classes, AWR- und ADDM Reports.
- DBMS_STATS_Report: Bericht über die letzten Aktivitäten von DBMS_STATS
- Longops_Gauge: Graphische Anzeige der v$session_longops mit Detailinfos zu Sessions, Wait Events und SQL
- Scheduler_Jobs: Jobs, Run Log, Programs, Windows etc.
  Die gibt es zwar größtenteils auch schon in den Standard-Reports, aber ein paar Details fehlen dort oder sind auf den Navigator und Berichte verteilt.
- Statspack_AAS: Visualisierung der Metrik "Average Active Sessions" aus Statspack.
- Statspack_AAS_3Level: Visualisierung der Metrik "Average Active Sessions" aus Statspack; mit einer dritten Ebene für historische und aktuelle Ausführungspläne zu Top SQL.
- Statspack_Host_CPU: Darstellung der CPU-Last des Servers (komplett, nicht nur Datenbank-Last).
- Statspack_LIO: Visualisierung der Metrik "Session Logical Reads" mit den Komponenten "consistent reads" und "db block gets" sowie separat "db block changes".
- Statspack_PIO: Visualisierung der Metriken "Session Physical Reads" und "Session Physical Writes" (Lese-/Schreibzugriffe auf die Festplatte)
- Statspack_SysStat: Visualisierung historisierter Metriken aus V$SYSSTAT.
- Storage_Overview: Einfacher Überblick über die DB-Größe
- Unindexed_FKs: Foreign Key Constraints ohne Index auf den entsprechenden Spalten.
- Wait_Class_History: DB-Last der letzten Stunde, nach Wait Classes gruppiert.
- Wait_Class_History_RAC: DB-Last der letzten Stunde, nach Cluster-Nodes; Drill-Down nach Wait Classes gruppiert.