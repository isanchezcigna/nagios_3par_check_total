# nagios_plugins: HP 3PAR CHECK TOTAL
Plugin SSH desarrollado para Nagios


**Check HP 3PAR Total (by Ignacio Sanchez rev. 1.0)**

Descripcion: El plugin fusiona el monitoreo de todos los puntos importantes para HP 3PAR.

Uso: $0 [ -M ip -U usuario -T tipo -h]

Sintaxis:
- M --> Direccion IP Storage
- U --> Usuario
- T --> Tipo (Capacidad, Bateria, Cages)
- O --> Opcion (ID Bateria, Tipo de Capacidad)
- h --> Muestra menu de ayuda.
    
[Nota: Este plugin utiliza el protocolo SSH y requiere una llave publica de autenticacion para correr.]
