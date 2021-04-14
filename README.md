# Server-monitoring

## Metrix to be monitored :-
 1. CPU Utilization
 2. Memory Utilization
 3. Process/Services Monitoring
 4. Event Log Monitoring
 5. Disk size Monitoring
 6. Script Monitoring
 7. URL Monitoring
 8. iops
 9. Read and Write
 10. Network Throughput
 11. Port monitoring 443 and 80 ports
 12. Number of SSL requests
 13. NIC port status

## Monitoring tools :-

 Blow tools can be used to monitor the server metrix
 1. Nagios
 2. Grafana
 3. Dynatrace
 4. Cacti

* If the server is hosted on cloud then we can use the below monitoring tools

 5. Cloudwatch AWS
 6. Azure monitor


## Challenges :-

* Make sure the client and server agents are up and running (eg : xinetd or snmp for nagios) and restart incase if the service is down using Ansible
* SMTP issues -- alers are not sending as email, this also can be fixed by restarting the SMTP service using Ansible
* SMS and e-mail alerts for warning and critical alerts.
* Raise ticket with the concerned team automatically and set the priority
* Review threshold and monitoring regularly to optimize the alerts

* Spin-up a new server if the threshold is reaching 80 % if the server hosted on cloud
