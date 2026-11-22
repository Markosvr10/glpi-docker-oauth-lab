En esta practica se han realizado una serie de ejercicios introductorios acerca del despliegue y funcionamiento de glpi. Se ha usado una maquina virtual que actua como cliente y se han realizado distintas pruebas sobre la misma.

Las conclusiones que se han logrado sacar son:

A1: Comparativa de paquetes entre GLPI y dpkg -l.

A2: Explicación de por qué falta la RAM en Componentes (VirtualBox no emula módulos DIMM en las tablas SMBIOS que lee dmidecode).

A3: Contraste de interfaces (enp0s3 NAT y enp0s8 Solo Anfitrión) tanto en la web glpi como con ip -br a.

A4: Separación de privilegios en sshd (root escuchando en puerto 22 vs user en la sesión) y uso de --full para saltar la caché del agente.

A5: Registro en el histórico al instalar software nuevo y propuesta de reglas automáticas mediante tag.