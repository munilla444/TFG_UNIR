# TFG_UNIR
Archivos necesarios para el TFG de UNIR (Universidad Internacional de la Rioja).
Los archivos deben de ser copiados en la ruta donde esté instalado el agente de Zabbix, por defecto C:\Program Files\Zabbix Agent.

Además, debemos insertar al final del documento llamado “zabbix_agentd.conf” las siguientes líneas.
	Include=C:\Program Files\Zabbix Agent\zabbix_agentd\os_windows_active.conf
	UnsafeUserParameters=1  
	Timeout=10
