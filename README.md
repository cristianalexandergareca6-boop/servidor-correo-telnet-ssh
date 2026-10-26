# servidor-correo-telnet-ssh
onfiguración de Postfix, Dovecot, Telnet y OpenSSH en Ubuntu Server 24.04.5 LTS


# Configuración y Administración de Servidores de Correo Electrónico, TELNET y SSH

## Descripción

Proyecto académico de Tecnología Web I, desarrollado en Ubuntu Server 24.04.5 LTS mediante VMware Workstation.

## Objetivo

Documentar la configuración y administración de los servicios de correo electrónico y acceso remoto, así como las pruebas realizadas durante la práctica.

## Servicios

- **Postfix:** servicio SMTP para el envío de correo electrónico.
- **Dovecot:** servicios IMAP y POP3 para el acceso a los buzones.
- **Telnet:** pruebas de conectividad y análisis de los riesgos de autenticación sin cifrado.
- **OpenSSH:** acceso remoto seguro y transferencia de archivos.

## Archivos de configuración

- `main.cf`: configuración principal de Postfix.
- `dovecot.conf`: configuración principal de Dovecot.
- `sshd_config`: configuración del servidor OpenSSH.

## Entorno de laboratorio

- Sistema operativo: Ubuntu Server 24.04.5 LTS.
- Hostname: `mail.404.local`.
- Dirección IPv4: `192.168.188.132`.
- Interfaz de red: `ens33`.

## Autor

Cristian Alexander Gareca

## Nota

Los archivos incluidos deben corresponder a la configuración utilizada en el laboratorio. Las pruebas y resultados se documentan mediante capturas de pantalla en el informe académico.




















