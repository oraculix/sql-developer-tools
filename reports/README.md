Reports for Oracle SQL Developer
================================

See also: http://oraculix.com/2015/03/12/visualizing-statspack-performance-data-in-sql-developer/
Custom Reports should work from at least v3.0 of SQLDev.

Installation (English)
----------------------
- In the Navigator (usually on the left side) choose the tab "Reports".
- Right-click folder "User Defined Reports" and "Open Report".
- Open an XML file containing a report definition.


Directory
----------------------
- Autotasks: Display Autotasks with Detail (e.g., DBMS-Stats Gathering Tasks)
- AWR-Zeitreihe_Load_11g: "Average Active Sessions" visualization from AWR. With metric detail, AWR, and ADDM reports.
- DBMS_STATS_Report: HTML report on recent runs of DBMS_STATS
- Log_Switch_Heat_Map: Colored overview of log switches per hour.
- Longops_Gauge: Long running SQL from v$session_longops with drill-down into session waits, SQL plan and monitoring
- Scheduler_Jobs: Jobs, Run Log, Programs, Windows etc. All in one place, unlike the standard reports.
- Statspack_AAS: "Average Active Sessions" visualization from Statspack. With session, waits, top SQL and top segments.
- Statspack_AAS_3Level: "Average Active Sessions" visualization from Statspack. Adds a third level to the above report for historic and cached Explain Plan.
- Statspack_Host_CPU: CPU load visualization from Statspack (Host and DB CPU).
- Statspack_LIO: "Session Logical Reads" visualization from Statspack from Statspack with "consistent reads", "db block gets" and "db block changes".
- Statspack_PIO: "Session Physical Reads" and "Session Physical Writes" visualization from Statspack (read/write I/O to storage).
- Statspack_SysStat: Visualization of recent historic performance metrics from V$SYSSTAT.
- Storage_Overview: Quick and simple database size info.
- Wait_Class_History: DB-Load of the last 60 minutes, grouped by wait class.
- Wait_Class_History_RAC: DB-Load of the last 60 minutes, by RAC instance; Drill-Down grouped by wait class.