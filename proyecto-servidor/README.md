# Configuración de servicios de red en Ubuntu

## Descripción
Proyecto académico de configuración y comprobación de servicios de correo electrónico y acceso remoto.

## Sistema operativo
Ubuntu 26.10 ejecutado en VirtualBox.

## Servicios implementados

### 1. Correo electrónico
- Postfix para SMTP.
- Dovecot para IMAP y POP3.
- Usuarios de prueba: correo1 y correo2.
- Envío y recepción comprobados mediante Thunderbird.

### 2. Telnet
- Instalación y habilitación temporal del servicio.
- Conexión local de prueba.
- Captura del tráfico con Wireshark.
- Desactivación posterior del servicio y comprobación del cierre del puerto 23.

### 3. SSH
- Puerto configurado: 2222.
- Acceso directo de root deshabilitado.
- Autenticación mediante claves públicas habilitada.
- Autenticación por contraseña deshabilitada.
- Transferencias comprobadas con SCP y SFTP.

## Configuración
Los archivos de configuración se encuentran en la carpeta `configuracion`.

## Observación
La práctica se realizó sobre Ubuntu 26.10. La consigna solicita Ubuntu Server 24.04 LTS o Debian, por lo que existe una diferencia entre el sistema solicitado y el utilizado.
