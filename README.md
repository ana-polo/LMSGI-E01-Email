
# LMSGI-E02-Factura

Ejemplos de descripciones XML con DTD y XML-Schema

![Logo de Team](https://github.com/ana-polo/LMSGI-E02-Factura/blob/main/LMSGI.gif "Team logo")

## Table of Contents

[1. Información General.](#informacion-general)

[2. Tecnologías.](#tecnologias)

[3. Definition del problema.](#definicion-del-problema)

&nbsp;

<a name = "informacion-general"></a>

## 1. Información General

----

Ejemplo de código XML y DTD para el módulo de Lenguajes de Marcas y Sistemas de Gestión de Información (LMSGI) del grado superior de Administración de Sistemas Informáticos en Red.

&nbsp;

<a name = "tecnologias"></a>

## 2. Tecnologías

----

- **XML**

- **DTD**

- **XML Schema**

&nbsp;

<a name = "definicion-del-problema"></a>

## 3. Definición del problema

----

Consideremos que se pretende validar los ficheros XML que guardan la información de las cuentas de correo electrónico que están en un gestor de correo.
De cada una de esas cuentas, además de diferenciarlas entre si, se quiere guardar información de los mensajes que contienen sus bandejas de entrada (no incluir otros posibles contenedores). De cada mensaje queremos conocer, ademaán de los datos propios del mensaje en sí (código que lo identifica, fecha y hora de la recepción, remitente, destinatarios y su tipo, prioridad, asunto y mensaje), si está leído o no y, en el caso de que esté categorizado, la categoría.

### Apartado 1

    Analizar la estructura de datos.

[Solución propuesta](https://github.com/ana-polo/LMSGI-E01_Email/blob/main/Solucion/LMSGI-E01-Email-Arbol.pdf "Árbol de datos")

### Apartado 2

    Desarrollar el DTD por niveles que verifica los ficheros con la estructura de datos.

### Apartado 3

    Crear una instancia de un fichero XML validado con el vocabulario diseñado usando un DTD interno.

### Apartado 4

    Crear una instancia de un fichero XML validado con el vocabulario diseñado usando un DTD externo.

### Apartado 5

    Desarrollar el XML Schema que verifica los ficheros con la estructura de datos dada usando el método matriuska.

### Apartado 6

    Desarrollar el XML Schema que verifica los ficheros con la estructura de datos dada usando referencias.

&nbsp;
&nbsp;
&nbsp;

👀 ***¡Atención!***

    - En todos los casos los documentos XML han de estar bien formados.
    - Realizar las restricciones adecuadas para garantizar que los datos de cada elemento se ajusten a los requisitos.

&nbsp;
