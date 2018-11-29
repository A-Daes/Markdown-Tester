# VDMS Backup Files
This is a small guide we decided to make in case we have to restart the VDMS server and we lose our configuration files. 


##  <a name="index"></a>Index

[1. Index - Currently here](#index)

[2. Hosts](#hosts)

## <a name="hosts"></a>Hosts
This is our hosts file for the server. Please do not mess with this code unless really necessary.
```
127.0.0.1   localhost localhost.localdomain localhost4 localhost4.localdomain4
::1         localhost localhost.localdomain localhost6 localhost6.localdomain6
10.1.1.39 mldb
172.16.1.104 bi_us_reporting
192.168.170.54 bi_local
#216.58.192.100 vdms-aws.cemg3ebxdkdn.us-east-1.rds.amazonaws.com
```

The last line is commented since we use the whole connection in our pentaho processes.

