# Computacion-en-la-Nube-con-AWS
Este repositorio contiene el trabajo realizado para la asignatura de Arquitectura de Sistemas y Software de Base del grado de Ingeniería de la Salud, centrado en la computación en la nube utilizando Amazon Web Services (AWS).

## 1. Descripción
Esta práctica se enfoca en el uso de Amazon Web Services (AWS) para implementar y gestionar instancias EC2, configurar balanceadores de carga, y asignar direcciones IP fijas. El objetivo es familiarizarse con la infraestructura en la nube y aprender a manejar diferentes servicios y configuraciones dentro de AWS.

## 2. Contenidos del Repositorio
El repositorio está organizado en varias secciones que corresponden a los pasos realizados durante la práctica.

### 2.1.  Código Fuente (src)
La carpeta /scripts contiene scripts y configuraciones utilizadas durante la práctica:

- **[index1.txt](src/index1.txt)** : Pequeña página web para la primera instancia EC2
- **[index2.txt](src/index2.txt)** : Pequeña página web para la segunda instancia EC2.
- **[comandos-AWS.txt](src/comandos-AWS.txt)** : Archivo con todos los comandos utilizados en la terminal para configurar la instancia y gestionar archivos.

### 2.2. Documentación (docs)
La carpeta /docs incluye la documentación detallada de cada paso:

- **[Computacion-nube-AWS-PPC.pdf](docs/Computacion-nube-AWS-PPC.pdf):** Documento que ofrece una explicación general del proyecto y sus componentes.

## 3. Instrucciones de Uso
### 3.1. Creación de Cuenta AWS
- Regístrate en AWS y completa el proceso de creación de cuenta.
- Agrega una tarjeta de crédito para servicios fuera de la capa gratuita.

### 3.2. Configuración de Alarmas de Facturación
- Accede a la Consola de administración de AWS.
- En "Preferencias de facturación", activa las alertas de uso y de facturación.
  
### 3.3. Configuración del Servicio EC2
- Lanza una instancia EC2 usando una AMI de Ubuntu y tipo de instancia t2.micro.
- Configura un grupo de seguridad para permitir el tráfico HTTP (puerto 80).
- Conéctate a la instancia usando SSH y configura un servidor Apache.
- Carga la página web desde tu máquina local a la instancia EC2.
  
### 3.4. Balanceador de Carga
- Crea un balanceador de carga en la consola de EC2.
- Configura el balanceador para distribuir el tráfico entre dos instancias EC2.
  
### 3.5. Direcciones IP Elásticas
- Asigna direcciones IP elásticas a tus instancias para mantener IPs fijas.
  
### 3.6. Eliminación de Recursos
- Detén y elimina todas las instancias y recursos utilizados al finalizar.
