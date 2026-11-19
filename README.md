# MSSQL-JobVisualiser
A Windows desktop app for people who watch Agent jobs every day.


See SQL Server Agent jobs on a timeline. Each job is a row, each run is a bar, and several servers stay open as tabs.

Job Visualiser is modelled on the trusty SQLjobvis 3.0 by SQLsoft: a small freeware viewer for Agent history, where failures, long-running jobs and overlapping runs show up in one picture, with rows and hours you can zoom. This app keeps that chart and runs as a current Windows desktop program.

History and jobs that are still running, read from msdb
Failed jobs and failed steps, each with its own alert
Filters, sort, date range, zoom, and colours you can keep
Windows or SQL login, with SQL passwords stored encrypted
A Windows desktop app for people who watch Agent jobs every day. 

Version 1.02.

Two shots from the running chart:

The day view: one server per tab, job names on the left, hours across the top.
<img width="1266" height="792" alt="image" src="https://github.com/user-attachments/assets/bb5c721f-187d-427c-87fb-e93b687b0885" />

The same chart zoomed in. Red is a failed job, green is a successful run, pink is a successful job with a failed step.
<img width="1266" height="793" alt="image" src="https://github.com/user-attachments/assets/b7b2d171-e596-4b66-86b6-3980bc852a6d" />
