# zabbix-template-openhardwaremonitor
A Zabbix Template and UserParameter scripts to get sensor information from OpenHardwareMonintor via WMI.

## Installation

 - Copy the folder`bin` to `c:\Program Files\Zabbix Agent 2\bin`, or `c:\Program Files\Zabbix Agent\bin` if you use zabbix1.
 - Copy the file `ohm.conf` to `c:\program Files\Zabbix Agent 2\zabbix_agent2.d\plugins.d\ohm.conf` or `c:\program Files\Zabbix Agent\zabbix_agentd.d\ohm.conf`if you use zabbix1.
 If you use zabbix-agent1, change the binary's location in `ohm.conf`
 - Import the template in `/template` to your Zabbix Server instance, and assign it to a host running OpenHardwareMonitor that has WMI accessible.

## Support

 - None. I will not help you troubleshoot WMI. I had issues with WMI, which required me to update OpenHardwareMonitor to v0.8.0.3, however that may just have been a case of Error: ID10T.
