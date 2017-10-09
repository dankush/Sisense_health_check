# Sisense health check

Snapshot report of Sisense machine environment.


Steps:
1) Download this repository with zip option to your Sisense server.
2) Unzip the file.
3) Run "health_check.exe" as admin (wait 1-2 minutes till it finish to run).
4) Go to the desktop and open the snapshot report "health_check_<Date and time>.txt".


#### Report output:
```
Sisense version
System Information
Active cubes size information
ElastiCubeConfiguration.xml settings
Catalog folder size
Mongo folder size
EC folder size
Plugins list
JVM connectors list
CLR connectors list
defualt_yaml
Event viewer last 24 hours warnings and errors

```
