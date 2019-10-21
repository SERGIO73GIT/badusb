PAYLOAD PREPARADOS PARA ATAQUES BADUSB

Scripts preparados para ser descargados en memoria desde powershell de un equipo víctima:
Funcionalidades:<br />
<dl>
  1- Tunel DNS<br />
        <dd>Herramienta DNSCAT2 cliente embebida en los scripts<br />
</dl>     
<dl>
  2- Invoke-mimikatz<br />
       <dd> Herramienta Invoke-mimikatz de powershell embebida con ciertas firmas limpiadas para esquivar a Windows Defender<br />
</dl>   
<dl>
  3- Persistencia HTTPS<br />
       <dd> Herramienta HTTP-RAT implementada con persistencia de tareas programadas de windows<br />
</dl>  
<dl>
  4- Horse.exe<br />
       <dd> Herramienta embebida en el script final para automatizar una escalada de privilegios, generado utilizazndo la herramient SneakyEXE<br />
</dl>  
<dl>
  5- PsExec.exe<br />
      <dd>  Herramienta SystemInternals, preparada para ejecutar cualquier comando con máximos privilegios. Se necesitan privilegios de administrador para ejecutarla<br />
</dl>     
<dl>
  6- Exfiltración de información<br />
       <dd> Mediante correo electrónico se exfiltra información de passwords WIFI y de la salida de mimikatz<br />
</dl>
<dl>
  7- final.sp1<br />
        <dd>Script definitivo, acondicionar el entorno<br />
</dl>
