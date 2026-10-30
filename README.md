# practica-1.4-daw-26-27

![Apache](images/apache.jpg)

### Paso 1: Configuración inicial del entorno
![Configuración del Paso 1](images/paso1.png)

### Paso 2: Creación de directorios y archivos necesarios
![Configuración del Paso 2](images/paso2.png)

### Paso 3: Configuración del Virtual Host en Apache
![Configuración del Paso 3](images/paso3.png)

### Pasos 4 y 5: Activación del módulo SSL y reinicio de Apache
![Activación del módulo y sitio seguro](images/paso4a5.png)

### Paso 6: Comprobación del protocolo HTTPS en el navegador

Al intentar acceder, el navegador detecta que el certificado es autofirmado y muestra la advertencia de seguridad de la entidad emisora:
![Error de Autoridad de Certificación Inválida](images/certificado.png)

A continuación, se detalla el proceso para omitir la advertencia paso a paso:

1. **Pantalla inicial del error:**
   ![Paso 6 - Error Inicial](images/paso6-1.png)

2. **Hacer clic en Opciones Avanzadas:**
   ![Paso 6 - Desplegar Avanzado](images/paso6-2.png)

3. **Confirmar el acceso al sitio no seguro:**
   ![Paso 6 - Enlace de acceso](images/paso6-3.png)

4. **Carga correcta del sitio web:**
   ![Paso 6 - Sitio cargado](images/paso6-4.png)

5. **Verificación final del cifrado en el navegador:**
   ![Paso 6 - Detalles del certificado](images/paso6-5a6-6.png)

Luego se añade la dirección IPv4 pública de la instancia al archivo "hosts":
![En la última línea](images/paso8.png)

Y por último, se accede a la ip elástica en el navegador:
![practica-despliegue1.local](images/dominio.png)