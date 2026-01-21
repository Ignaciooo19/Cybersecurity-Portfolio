# CTF - Movimientos Laterales (Active Directory)

## Objetivo
Comprometer un entorno Active Directory hasta obtener control total del dominio y alcanzar el contexto NT AUTHORITY\SYSTEM.

## Técnicas utilizadas
- Descubrimiento de host y escaneo de servicios (Nmap)
- Enumeración de dominio (CrackMapExec)
- Enumeración Kerberos (Kerbrute)
- AS-REP Roasting + cracking (Hashcat)
- Kerberoasting (Impacket)
- Acceso remoto con WinRM / SMB (Evil-WinRM)
- Abuso de privilegios (SeBackupPrivilege / SeRestorePrivilege)
- Extracción de NTDS.dit y SYSTEM (diskshadow + robocopy)
- Volcado de usuarios/hashes (Impacket secretsdump)
- Escalada a SYSTEM y acceso final al DC

## Herramientas
- Nmap
- CrackMapExec
- Kerbrute
- Impacket
- Evil-WinRM
- Metasploit
- Hashcat

📄 Informe completo en PDF incluido en esta carpeta.

> Nota: Todo realizado en un laboratorio controlado (CTF).
