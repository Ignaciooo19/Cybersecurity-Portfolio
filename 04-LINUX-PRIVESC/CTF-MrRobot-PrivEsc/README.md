# CTF - Mr.Robot (Elevación de Privilegios)

## Objetivo
Obtener acceso inicial a una máquina Linux vulnerable y realizar elevación horizontal y vertical hasta root, recopilando flags y credenciales del sistema/BBDD.

## Técnicas utilizadas
- Cracking de ZIP (password protegido)
- Descubrimiento de IP y escaneo (Nmap)
- Enumeración web (DIRB)
- Acceso inicial (SSH)
- Movimientos laterales (elevación horizontal)
- Decodificación Base64
- Enumeración de historial de comandos
- Escalada final a root (sudo / SUID)
- Acceso y enumeración de base de datos (MySQL)

## Herramientas
- Nmap
- DIRB / Gobuster
- SSH
- Base64 decode
- John the Ripper
- MySQL

## Evidencia
📄 Informe completo en PDF incluido en esta carpeta.

> Nota: Todo se realizó en un entorno de laboratorio/CTF controlado.
